---
title: linkedin2username
categories: ['python', 'hacking', 'pentesting']
---
## [linkedin2username](https://github.com/initstring/linkedin2username)

### OSINT Tool: Generate username lists for companies on LinkedIn

OSINT Tool: Generate username lists from companies on LinkedIn.

This is a pure web-scraper, no API key required. You use your valid LinkedIn username and password to login, it will create several lists of possible username formats for all employees of a company you point it at.

Use an account with a lot of connections, otherwise you'll get crappy results. Adding a couple connections at the target company should help - this tool will work up to third degree connections. Note that [LinkedIn will cap search results](https://www.linkedin.com/help/linkedin/answer/129/what-you-get-when-you-search-on-linkedin?lang=en) to 1000 employees max. You can use the features '--geoblast' or '--keywords' to bypass this limit. Look at help below for more details.

Here's what you get:
- first.last.txt: Usernames like Joe.Schmoe
- flast.txt:      Usernames like JSchmoe
- firstl.txt:     Usernames like JoeS
- first.txt       Usernames like Joe
- lastf.txt       Usernames like SchmoeJ
- rawnames.txt:   Full name like Joe Schmoe

Optionally, the tool will append @domain.xxx to the usernames.
