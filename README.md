# Looking Glass

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Looking Glass Factory builds light field (holographic) displays — group-viewable 3D screens ranging from the pocket-sized Looking Glass Go to 16", 27", 32" and 65" panels — plus the software that drives them. For developers, the core surface is Looking Glass Bridge: a local runtime that exposes an HTTP REST API on http://localhost:33334/ for enumerating connected displays, opening the media player, building playlists of Quilt and RGBD holograms, and controlling playback. Around it Looking Glass ships official client libraries — the typesafe bridge.js (@lookingglass/bridge), a WebXR polyfill (@lookingglass/webxr) that targets the displays from any WebXR framework, a Python Bridge SDK, the legacy HoloPlay Core C/C++/C# SDK, and engine plugins for Unity, Unreal and Blender. Looking Glass Blocks (blocks.glass) hosts holograms on the internet. The company is backed by Uncork Capital and headquartered in Brooklyn, New York.

**Areas:** Company · Holographic Displays · Light Field · 3D · Developer Tools · WebXR · Hardware · Holograms · Media Player

## Looking Glass on APIs.io

Everything profiled for Looking Glass is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/looking-glass/](https://apis.io/providers/looking-glass/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Looking Glass Autostart API](https://apis.io/apis/looking-glass/looking-glass-autostart-api/) — Playlists that auto-play when Bridge starts
- [Looking Glass Devices API](https://apis.io/apis/looking-glass/looking-glass-devices-api/) — Enumerate connected Looking Glass displays
- [Looking Glass Orchestration API](https://apis.io/apis/looking-glass/looking-glass-orchestration-api/) — Multi-user Bridge sessions (orchestrations)
- [Looking Glass Playback API](https://apis.io/apis/looking-glass/looking-glass-playback-api/) — Transport controls for the Bridge media player
- [Looking Glass Playlist API](https://apis.io/apis/looking-glass/looking-glass-playlist-api/) — Create, edit and delete hologram playlists
- [Looking Glass Version API](https://apis.io/apis/looking-glass/looking-glass-version-api/) — Bridge and API version information

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [looking-glass-bridge](https://apis.io/servers/looking-glass/looking-glass-bridge/)

#### Collections (6)

Postman and Open Collection request collections.

- [Looking Glass Bridge Autostart API](https://apis.io/collections/looking-glass/open-looking-glass-autostart-api/)
- [Looking Glass Bridge Autostart Devices API](https://apis.io/collections/looking-glass/open-looking-glass-devices-api/)
- [Looking Glass Bridge Autostart Orchestration API](https://apis.io/collections/looking-glass/open-looking-glass-orchestration-api/)
- [Looking Glass Bridge Autostart Playback API](https://apis.io/collections/looking-glass/open-looking-glass-playback-api/)
- [Looking Glass Bridge Autostart Playlist API](https://apis.io/collections/looking-glass/open-looking-glass-playlist-api/)
- [Looking Glass Bridge Autostart Version API](https://apis.io/collections/looking-glass/open-looking-glass-version-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Looking Glass Bridge Overlay](https://apis.io/overlays/looking-glass/looking-glass-bridge-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Looking Glass Authentication](https://apis.io/security/looking-glass/looking-glass-authentication/)
- [Looking Glass Domain Security](https://apis.io/security/looking-glass/looking-glass-domain-security/)
- [Looking Glass Vulnerability Disclosure](https://apis.io/security/looking-glass/looking-glass-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lookingglassfactory.com)
- [Documentation](https://docs.lookingglassfactory.com)
- [API reference](https://docs.lookingglassfactory.com/software/looking-glass-bridge-sdk/web-application-integration)
- [Pricing](https://checkout.lookingglassfactory.com)
- [Sign up](https://blocks.glass)
- [Blog](https://blog.lookingglassfactory.com)
- [Security](https://lookingglassfactory.com/product-security-policy)
- [Terms of service](https://lookingglassfactory.com/terms-and-conditions)
- [Privacy policy](https://lookingglassfactory.com/privacy-policy)
- [GitHub](https://github.com/Looking-Glass)

## API Evangelist rating

**Kin Score 38.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 36.1 |
| Contract governance | 4.5 |
| Operational transparency | 13.2 |
| Developer ergonomics | 49.4 |
| Access clarity | 44.7 |

**Agent readiness 16.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/looking-glass/](https://apis.io/providers/looking-glass/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Looking Glass: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/looking-glass/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
