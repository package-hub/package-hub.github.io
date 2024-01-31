---
title: instagram-java-scraper
categories: ['java', 'instagram', 'instagram-client']
---
## [instagram-java-scraper](https://github.com/postaddictme/instagram-java-scraper)

###  Instagram Java Scraper. Get account information, photos, videos and comments.

```java
Instagram instagram = new Instagram(httpClient);
Account account = instagram.getAccountByUsername("kevin");
System.out.println(account.getMedia().getCount());
```
