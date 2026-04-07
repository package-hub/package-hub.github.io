---
title: meteor-autoform
categories: ['javascript', 'meteor', 'blaze']
---
## [meteor-autoform](https://github.com/Meteor-Community-Packages/meteor-autoform)

### AutoForm is a Meteor package that adds UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation.


AutoForm 7.0 is now available and decouples from the default themes. **You will have to install themes manually!**

Be sure to check out the [change log](./CHANGELOG.md#700) for full details, first.
Note that if you use add-on packages that haven't been updated yet, you will not yet be able to update to version 6.

**Add-on Package Authors**: Please test your package against AutoForm 7.0, and then release a major version update in which you change your `api.use` to `api.use('aldeed:autoform@7.0.0');`.
We do NOT recommend using something like `api.use('aldeed:autoform@6.0.0 || 7.0.0');` to try to support multiple major versions of AutoForm because there is currently a known Meteor issue where trying to support too many dependency paths leads to running out of memory when trying to resolve dependencies.
