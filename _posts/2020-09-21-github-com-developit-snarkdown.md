---
title: snarkdown
categories: ['javascript', 'markdown', 'parser']
---
## [snarkdown](https://github.com/developit/snarkdown)

### :smirk_cat: A snarky 1kb Markdown parser written in JavaScript


- **Fast:** since it's basically one regex and a huge if statement
- **Tiny:** it's 1kb of gzipped ES3
- **Simple:** pass a Markdown string, get back an HTML string

> **Note:** Tables are not yet supported. If you love impossible to read regular expressions, submit a PR!
>
> **Note on XSS:** Snarkdown [doesn't sanitize HTML](https://github.com/developit/snarkdown/issues/70), since its primary target usage doesn't require it.
