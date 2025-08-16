---
title: svelte-sitemap
categories: ['typescript', 'svelte', 'sveltejs']
---
## [svelte-sitemap](https://github.com/bartholomej/svelte-sitemap)

### Sitemap generator for SvelteKit. Small helper which scans your SvelteKit routes and generates static sitemap.xml


> Small helper which scans your Svelte routes and generates _sitemap.xml_
>
> - Designed for SvelteKit `adapter-static` with `prerender` option (SSG)
> - TypeScript, JavaScript, CLI version
> - Useful [options](#%EF%B8%8F-options) for customizing your sitemap
> - Support for [submiting sitemap](#ping-google-search-console) to Google Search Console
> - Support for Google [sitemap index](https://developers.google.com/search/docs/crawling-indexing/sitemaps/large-sitemaps). _Useful for large sites (more than 50K pages)_
> - Also compatible with [Vercel hosting](#vercel-apdatper)
> - Workaround for [this official SvelteKit issue](https://github.com/sveltejs/kit/issues/1142)
