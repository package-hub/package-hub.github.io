---
title: openai-streams
categories: ['typescript', 'openai', 'streams']
---
## [openai-streams](https://github.com/SpellcraftAI/openai-streams)

### Tools for working with OpenAI streams in Node.js and TypeScript.


[**GitHub**](https://github.com/SpellcraftAI/openai-streams) |
[**NPM**](https://npmjs.com/package/openai-streams) |
[**Docs**](https://openai-streams.vercel.app)

> Now with ChatGPT API support! See [**Use with ChatGPT
> API**](#use-with-chatgpt-api). (Whisper coming soon!)

This library returns OpenAI API responses as streams only. Non-stream endpoints
like `edits` etc. are simply a stream with only one chunk update.

- Prioritizes streams, so you can display a completion as it arrives.
- Auto-loads `OPENAI_API_KEY` from `process.env`.
- One single function with inferred parameter type based on the endpoint you
  provide.

Uses `ReadableStream` by default for browser, Edge Runtime, and Node 18+, with
a `NodeJS.Readable` version available at `openai-streams/node`.
