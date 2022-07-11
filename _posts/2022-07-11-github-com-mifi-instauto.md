---
title: instauto
categories: ['javascript', 'instagram-bot', 'instagram']
---
## [instauto](https://github.com/mifi/instauto)

###  Instagram bot / automation library written in Javascript for Node.js


- First install [Node.js](https://nodejs.org/en/) 8 or newer.
  - On MacOS, it's recommended to use [homebrew](https://brew.sh/): `brew install node`

- Create a new directory with a file like [example.js](https://github.com/mifi/instauto/blob/master/example.js)

- Adjust your `example.js` to your needs. If you want to see how it would work without doing any invasive actions, use the `dryRun: true` option. Toggle `headless` to see it in action.

- Open a terminal in the directory

- Run `npm i -g yarn`

- Run `yarn add puppeteer instauto`

- Run `node example`

You can run this code for example once every day using cron or pm2 or similar

See [index.js](https://github.com/mifi/instauto/blob/master/src/index.js) for available options.
