---
title: scrapedin
categories: ['javascript', 'linkedin', 'scraper']
---
## [scrapedin](https://github.com/linkedtales/scrapedin)

### LinkedIn Scraper (currently working 2020)


```javascript
const scrapedin = require('scrapedin')

const profileScraper = await scrapedin({ email: 'login@mail.com', password: 'pass' })
const profile = await profileScraper('https://www.linkedin.com/in/some-profile/')
```

- If you are looking for a crawler to automatically extract multiple profiles see [scrapedin-crawler](https://github.com/linkedtales/scrapedin-linkedin-crawler)
