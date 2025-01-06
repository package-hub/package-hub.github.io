---
title: gocd-yaml-config-plugin
categories: ['java', 'pipelines-as-code', 'gocd']
---
## [gocd-yaml-config-plugin](https://github.com/tomzo/gocd-yaml-config-plugin)

### Plugin to declare GoCD pipelines and environments configuration in YAML


[GoCD](https://www.gocd.org) plugin to keep **pipelines** and **environments**
configuration in source-control in [YAML](http://www.yaml.org/).
See [this document](https://docs.gocd.org/current/advanced_usage/pipelines_as_code.html)
to find out what are GoCD configuration repositories.

This is the second GoCD configuration plugin, which enhances some of shortcomings of
[JSON configuration plugin](https://github.com/tomzo/gocd-json-config-plugin)

* Format is **concise**. Unlike JSON, there are no unnecessary quotations `"`, brackets `{}` and commas `,`
* Tries to **enforce correctness** where possible. By using maps instead of lists and shorter object graphs.
* Allows to have multiple pipelines and environments in single file. But doesn't force it.
* **Comments in configuration files** - YAML supports comments,
so you can explain why pipeline/environment it is configured like this.
