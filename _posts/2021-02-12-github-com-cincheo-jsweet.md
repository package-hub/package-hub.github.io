---
title: jsweet
categories: ['java', 'jsweet', 'javascript-transpiler']
---
## [jsweet](https://github.com/cincheo/jsweet)

### A Java to JavaScript transpiler.


JSweet leverages TypeScript to write rich and responsive Web applications in Java through the use of JavaScript libraries and frameworks. With JSweet, Java programs are transpiled (source-to-source compiled) to TypeScript and JavaScript for being run in browsers, mobile Web views, or in Node.js. 

* JSweet is safe and reliable. It provides web applications with type-checking and generates fully type-checked JavaScript programs. It stands on Oracle's Java Compiler (javac) and on Microsoft's TypeScript (tsc). 
* JSweet allows you to use your favorite JS library ([JSweet+Angular2](https://github.com/cincheo/jsweet-angular2-quickstart), [JSweet+threejs](https://github.com/cincheo/jsweet-examples-threejs), [IONIC/Cordova](https://github.com/lgrignon/jsweet-cordova-ionic-example), ...).
* JSweet enables code sharing between server-side Java and client-side JavaScript. JSweet provides implementations for the core Java libraries for code sharing and legacy Java migration purpose.
* JSweet is fast, lightweight and fully JavaScript-interoperable. The generated code is regular JavaScript code, which implies no overhead compared to JavaScript, and can directly interoperate with existing JavaScript programs and libraries.

How does it work? JSweet depends on well-typed descriptions of JavaScript APIs, so-called "candies", most of them being automatically generated from TypeScript definition files. These API descriptions in Java can be seen as headers (similarly to *.h header files in C) to bridge JavaSript libraries from Java. There are several sources of candies for existing libraries and you can easily build a candy for any library out there (see [more details](http://www.jsweet.org/jsweet-candies/)). 

With JSweet, you take advantage of all the Java tooling (IDE's, Maven, ...) to program real JavaScript applications using the latest JavaScript libraries.
