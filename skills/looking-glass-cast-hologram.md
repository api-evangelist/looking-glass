---
name: Cast a hologram to a Looking Glass display
description: >-
  Connect to Looking Glass Bridge, find a connected display, build a playlist,
  add a Quilt or RGBD hologram, and play it on the Looking Glass.
api: openapi/looking-glass-bridge-openapi.yml
operations:
  - enter_orchestration
  - available_output_devices
  - instance_playlist
  - insert_playlist_entry
  - play_playlist
  - show_window
  - transport_control_seek_to_index
---

# Cast a hologram to a Looking Glass display

Use the Looking Glass Bridge HTTP REST API at `http://localhost:33334/`. Bridge
must be installed and running on the same machine as your app, with a Looking
Glass display connected. There is no authentication — the API is loopback-only.
Every call is an HTTP `POST` with a JSON body and returns
`{ "success": boolean, "response": object|null }`; treat `success:false` as a
failure and stop.

## Steps

1. **Start a session** — call `enter_orchestration` with a session keyword
   (e.g. `{ "name": "my-app" }`). Keep the returned orchestration token; pass it
   as `orchestration` on every following call.
2. **Find the display** — call `available_output_devices` with the token to
   confirm a Looking Glass is connected before casting.
3. **Show the player** — call `show_window` so the Bridge media player is
   visible on the display.
4. **Create a playlist** — call `instance_playlist` to get an empty playlist.
5. **Add the hologram** — call `insert_playlist_entry` with the playlist
   reference and the `uri` of your Quilt or RGBD media (JPG/PNG image or
   MP4/WebM video). Repeat to add more entries.
6. **Play it** — call `play_playlist` with the playlist reference to render the
   hologram(s) on the Looking Glass.
7. **Navigate (optional)** — use `transport_control_seek_to_index` with an
   `index` to jump to a specific hologram in the playlist.

## Notes

- The Bridge API has no idempotency-key contract; do not blind-retry writes —
  re-check state with `available_output_devices` first.
- Prefer the official typesafe client `@lookingglass/bridge` (bridge.js) over
  raw HTTP; it wraps every operation above.
