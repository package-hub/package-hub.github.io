---
title: lion
categories: ['javascript', 'hacktoberfest', 'lion']
---
## [lion](https://github.com/ing-bank/lion)

### Fundamental white label web component features for your design system.


- Keep using `/docs` on the root level as we used it in the `master` branch. The documentation is copied into Astro related directories on `npm run start` and when when anything in `/docs` is updated.
- Replace manually all references to assets in all `md` files so that we imply that the path is produced from the directory where the md file is located. F.e. `new URL('../src/wa-combobox/assets/obama.jpeg', import.meta.url).href;` should `new URL('./src/wa-combobox/assets/obama.jpeg', import.meta.url).href;`. Note double dot is replaced with one dot. See [this PR](https://github.com/ing-bank/lion/pull/2125/files#diff-403b1e0ab54d51dcfe54248e847498e492da00383d8b33a4087994ab9035a22c) for the reference.
- Rename all `*.mjs` files to `*.js` ones if they are used by `mdjs` examples
