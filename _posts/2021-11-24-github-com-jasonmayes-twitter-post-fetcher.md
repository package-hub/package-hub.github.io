---
title: Twitter-Post-Fetcher
categories: ['javascript', 'twitter', 'twitter-api']
---
## [Twitter-Post-Fetcher](https://github.com/jasonmayes/Twitter-Post-Fetcher)

### Fetch your twitter posts without using the new Twitter 1.1 API. Pure JavaScript! By Jason Mayes


Recently I was quite frustrated to find out that the old API on Twitter was depreciated and the overhead in setting up a system to perform OAUTH just to get my already publicly available tweets was too damn high (see https://dev.twitter.com/discussions/11564).

Even worse I couldn't find any simple solutions for JavaScript. All code examples were server side. So after much thinking I invented the following solution. It makes use of the over bloated widgets Twitter gives us to put on our sites, cuts out all the nonsense (and non semantic markup), and returns to you your raw tweet text so you can do with it as you please and style it how you want on your own website - like it should be. Instructions on how to get it working with your tweets are in the code comments, just do what it says! Enjoy!
