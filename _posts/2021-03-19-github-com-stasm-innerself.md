---
title: innerself
categories: ['javascript']
---
## [innerself](https://github.com/stasm/innerself)

### ◘ A tiny view + state management solution using innerHTML


You need to know a few things before you jump right in.  _innerself_ is
a less-than-serious pet project and I don't recommend using it in production.

It's a poor choice for form-heavy UIs.  It tries to avoid unnecessary
re-renders, but they still happen if the DOM needs even a tiniest update.  Your
form elements will keep losing focus because every re-render is essentially
a new assignment to the root element's `innerHTML`.

When dealing with user input in serious scenarios, any use of `innerHTML`
requires sanitization.  _innerself_ doesn't do anything to protect you or your
users from XSS attacks.  If you allow keyboard input or display data fetched
from a database, please take special care to secure your app.  The
`innerself/sanitize` module provides a rudimentary sanitization function.

Perhaps the best use-case for _innerself_ are simple mouse-only UIs with no
keyboard input at all :)

