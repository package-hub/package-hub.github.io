---
title: objc-dependency-visualizer
categories: ['javascript', 'dependency', 'dependency-graph']
---
## [objc-dependency-visualizer](https://github.com/PaulTaykalo/objc-dependency-visualizer)

### Objective-C and Swift dependency visualizer. It's tool that helps to visualize current state of your project. It's really easy to see how tight your classes are coupled. 

This will clone project, and run it on the latest modified project
```
git clone https://github.com/PaulTaykalo/objc-dependency-visualizer.git ;
cd objc-dependency-visualizer ;
./generate-objc-dependencies-to-json.rb -d -s "" > origin.js ;
open index.html
```
