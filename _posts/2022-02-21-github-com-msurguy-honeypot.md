---
title: Honeypot
categories: ['php']
---
## [Honeypot](https://github.com/msurguy/Honeypot)

### Simple spam prevention package for Laravel applications


"Honeypot" method of spam prevention is a simple and effective way to defer some of the spam bots that come to your site. This technique is based on creating an input field that should be left empty by the real users of the application but will most likely be filled out by spam bots. 

This package creates a hidden DIV with two fields in it, honeypot field (like "my_name") and a honeytime field - an encrypted timestamp that marks the moment when the page was served to the user. When the form containing these inputs invisible to the user is submitted to your application, a custom validator that comes with the package checks that the honeypot field is empty and also checks the time it took for the user to fill out the form. If the form was filled out too quickly (i.e. less than 5 seconds) or if there was a value put in the honeypot field, this submission is most likely from a spam bot.
