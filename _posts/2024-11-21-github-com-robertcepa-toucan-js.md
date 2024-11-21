---
title: toucan-js
categories: ['typescript']
---
## [toucan-js](https://github.com/robertcepa/toucan-js)

### Cloudflare Workers client for Sentry


**Toucan** is a [Sentry](https://docs.sentry.io/) client for [Cloudflare Workers](https://developers.cloudflare.com/workers/) written in TypeScript.

- **Reliable**: In Cloudflare Workers isolate model, it is inadvisable to [set or mutate global state within the event handler](https://developers.cloudflare.com/workers/about/how-it-works). Toucan was created with Workers' concurrent model in mind. No race-conditions, no undelivered logs, no nonsense metadata in Sentry.
- **Flexible:** Supports `fetch` and `scheduled` Workers, their `.mjs` equivalents, and `Durable Objects`.
- **Familiar API:** Follows [Sentry unified API guidelines](https://develop.sentry.dev/sdk/unified-api/).
