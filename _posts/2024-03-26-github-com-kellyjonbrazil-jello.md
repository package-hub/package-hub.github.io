---
title: jello
categories: ['python', 'json', 'json-lines']
---
## [jello](https://github.com/kellyjonbrazil/jello)

### CLI tool to filter JSON and JSON Lines data with Python syntax. (Similar to jq)

Filter JSON and JSON Lines data with Python syntax

`jello` is similar to `jq` in that it processes JSON and JSON Lines data except `jello` uses standard python dict and list syntax.

JSON or JSON Lines can be piped into `jello` via STDIN or can be loaded from a JSON file or JSON Lines files (JSON Lines are automatically slurped into a list of dictionaries). Once loaded, the data is available as a python list or dictionary object named '`_`'. Processed data can be output as JSON, JSON Lines, bash array lines, or a grep-able schema.

For more information on the motivations for this project, see my [blog post](https://blog.kellybrazil.com/2020/03/25/jello-the-jq-alternative-for-pythonistas/).
