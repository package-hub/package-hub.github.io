---
title: tracy
categories: ['javascript', 'xss', 'xss-detection']
---
## [tracy](https://github.com/nccgroup/tracy)

### A tool designed to assist with finding all sinks and sources of a web application and display these results in a digestible manner.

A pentesting tool designed to assist with finding all sinks and sources of a web
application and display these results in a digestible manner. `tracy` should be used
during the mapping-the-application phase of the pentest to identify sources of input
and their corresponding outputs. `tracy` can use this data to intelligently find
vulnerable instances of XSS, especially with web applications that use lots of JavaScript.

`tracy` is a browser extension that records all user input 
to a web application and monitors any time those inputs are output, for example in a
DOM write, server response, or call to `eval`.

For guides and reference materials about `tracy`, see [the documentation](https://github.com/nccgroup/tracy/wiki).
