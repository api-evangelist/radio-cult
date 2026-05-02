# Radio Cult (radio-cult)

Are you looking to power your online radio stations website with the Radio Cult API? If so, you're in the right place.

**APIs.yml URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/radio-cult/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Radio
- Streaming
- Audio
- Music
- Broadcasting

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-04-28

## APIs

### Radio Cult

Manage artists, schedules, media, playlists, recordings, and live streaming metadata for your online radio station.

- **Documentation:** https://www.radiocult.fm/docs/api
- **Base URL:** `https://api.radiocult.fm`
- **OpenAPI:** [openapi/radio-cult-openapi.yml](openapi/radio-cult-openapi.yml)
- **Authentication:** API key via `x-api-key` header (publishable `pk_*` or secret `sk_*`)
- **Rate limits:** 20 req/min burst, 2000 req/day

#### Resource Categories

- **Artists** — Retrieve, create, fetch by ID/slug, schedule lookup
- **Schedule** — Events by date range; live broadcast status (also via Socket.IO)
- **Media** — Track upload, signed download URLs, tagging, Soundcloud upload
- **Tags** — Retrieve all tags
- **Playlists** — List playlists, add entries, clear entries
- **Recordings** — List recordings, signed download URLs
- **Streaming** — Recent track playback history

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
