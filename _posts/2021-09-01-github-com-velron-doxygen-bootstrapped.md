---
title: doxygen-bootstrapped
categories: ['javascript']
---
## [doxygen-bootstrapped](https://github.com/Velron/doxygen-bootstrapped)

### Customize doxygen output to use the twitter bootstrap framework.

Doxygen provides a handful of ways to [customize the output](http://www.stack.nl/~dimitri/doxygen/manual/customize.html). The simplest way is to customize the HTML output.

Doxygen allows you to customize the HTML output by modifying a master HTML header, footer and stylesheet. You can then include additional stylesheets and javascript files. The following command will generate the default Doxygen files.

`doxygen -w html header.html footer.html customdoxygen.css`

Modifying these files alone is not enough to get good Twitter Bootstrap integration. Bootstrap requires that certain classes be applied within the HTML. For example, a Bootstrap “table” needs to have a class called “table” in order to apply the Bootstrap table formatting. We just need to augment the default HTML with these Bootstrap classes. To do this, we use the provided doxy-boot.js javascript file.

Also, you can augment doxygen’s default stylesheet with a customdoxygen.css stylesheet. This is where you would place any custom styling such as sticky footers.
