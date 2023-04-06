---
title: ObjectModel
categories: ['javascript', 'typing', 'strong']
---
## [ObjectModel](https://github.com/sylvainpolletvillard/ObjectModel)

### Strong Dynamically Typed Object Modeling for JavaScript

   
  ObjectModel intends to bring **strong dynamic type checking** to your web applications. Contrary to static type-checking solutions like [TypeScript] or [Flow], ObjectModel can also validate data at runtime: JSON from the server, form inputs, content from localStorage, external libraries...
  
  By leveraging **ES6 Proxies**, this library ensures that your variables always match the model definition and validation constraints you added to them. Thanks to the generated exceptions, it will help you spot potential bugs and save you time spent on debugging. ObjectModel is also very easy to master: *no new language to learn, no new tools, no compilation step, just a minimalist and intuitive API in a plain old JS micro-library*.
  
  Validating at runtime also brings many other benefits: you can define your own types, use them in complex model definitions with custom assertions that can even change depending on your application state. Actually it goes much further than just type safety. Go on and see for yourself.
