---
title: Generamba
categories: ['ruby']
---
## [Generamba](https://github.com/strongself/Generamba)

### This codegenerator is too brilliant to be real!


- Supports work with *.xcodeproj* files out of the box. All generated class files are automatically placed to specific folders and groups of Xcode project.
- Can generate both code itself and tests adding them to right targets.
- Based on work with [liquid-templates](https://github.com/Shopify/liquid) that have plain and readable syntax in comparison with templates for Xcode.
- It is very easy to create a new module: `generamba gen [MODULE_NAME] [TEMPLATE_NAME]`. You do not need to input a bunch of data each time because each project corresponds to only one configuration file that holds standard file system and Xcode-project pathes, names of targets, information about the author.
