---
title: VIP-Coding-Standards
categories: ['php', 'vip', 'php-codesniffer']
---
## [VIP-Coding-Standards](https://github.com/Automattic/VIP-Coding-Standards)

### PHP_CodeSniffer ruleset to enforce WordPress.com VIP and VIP Go coding standards


This project contains [PHP_CodeSniffer (PHPCS) sniffs and rulesets](https://github.com/squizlabs/PHP_CodeSniffer) to validate code developed for [WordPress VIP](https://wpvip.com/).

This project contains two rulesets:

 - `WordPressVIPMinimum` - for use with projects on the (older) WordPress.com VIP platform.
 - `WordPress-VIP-Go` - for use with projects on the (newer) VIP Go platform.

These rulesets contain only the rules which are considered to be ["errors"](https://docs.wpvip.com/technical-references/code-review/vip-errors/) and ["warnings"](https://docs.wpvip.com/technical-references/code-review/vip-warnings/) according to the WordPress VIP Go documentation.

The rulesets use rules from the [WordPress Coding Standards](https://github.com/WordPress/WordPress-Coding-Standards) (WPCS) project, as well as the [VariableAnalysis](https://github.com/sirbrillig/phpcs-variable-analysis) standard.

Go to https://docs.wpvip.com/technical-references/code-review/phpcs-report/ to learn about why violations are flagged as errors vs warnings and what the levels mean.
