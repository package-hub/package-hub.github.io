---
title: require-css
categories: ['javascript']
---
## [require-css](https://github.com/guybedford/require-css)

### A RequireJS CSS loader plugin to allow CSS requires and optimization


The use case for RequireCSS came out of a need to manage templates and their CSS together.
The idea being that a CSS require can be a dependency of the code that dynamically renders a template. 
When writing a large dynamic application, with templates being rendered on the client-side, it can be beneficial to inject the CSS as templates are required instead 
of dumping all the CSS together separately. The added benefit of this is then being able to build the CSS naturally with the RequireJS optimizer, 
which also supports [separate build layers](http://requirejs.org/docs/1.0/docs/faq-optimization.html#priority) as needed.
