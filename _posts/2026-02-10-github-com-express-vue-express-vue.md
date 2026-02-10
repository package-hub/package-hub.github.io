---
title: express-vue
categories: ['javascript', 'expressjs', 'express']
---
## [express-vue](https://github.com/express-vue/express-vue)

### Vue rendering engine for Express.js. Use .Vue files as templates using streams


A Simple way of using Server Side rendered Vue.js 2.0+ natively in Express using streams

If you want to use vue.js and setup a large scale web application that is server side rendered, using Node+Express, but you want to use all the fantastic tools given to you by Vue.js. Then this is the library for you.

The idea is simple use Node+Express for your Controller and Models, and Vue.js for your Views.. you can have a secure server side rendered website without all the hassle. Your Controller will pass in the data to your View through

`res.renderVue('view', {data}, [{vueOptions}])`.
