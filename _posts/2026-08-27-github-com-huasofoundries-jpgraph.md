---
title: jpgraph
categories: ['php', 'jpgraph', 'gd-library']
---
## [jpgraph](https://github.com/HuasoFoundries/jpgraph)

### Full blown refactor of JpGraph v3.5. Distant cousin of current official package


As can be seen in [their releases section](https://jpgraph.net/download/release.php), there was a six year pause in JPGraph release cycle, during which some of us had no choice but to code our way out of PHP 5.x. And thus "Community Edition" was born. From then on, this library evolved on its own and completely diverged from the official packages.

In general terms, JPGraph CE relies in PHP's thriving ecosystem. We aim to be a simple dependency you can seamlessly integrate in your app. JPGraph CE aligns with [PHP Standards Reccomendations](https://www.php-fig.org/psr/) as published by the [PHP Framework Interoperability Group](https://www.php-fig.org/), and when presented with the choice, will always pick an agnostic implementation over custom ones that reinvent the wheel. A lot of code has been trimmed and refactored with this purpose and a lot more is waiting to undergo such a change.

- Distrbution through PHP's popular [Packagist Registry](https://packagist.org/packages/amenadiel/jpgraph)
- Relies in [Composer](https://getcomposer.org/), so you don't need to manually download or copy anything, nor check for platform and dependency requirements yourself.
- [PSR-4: Autoloader](https://www.php-fig.org/psr/psr-4/) compliant structure. No need to resort to `require` or `include` in your code.
- Sensible fallbacks to handle missing fonts or particular GD version features availability.
- IDE friendly, allowing for autocompletion and go-to-definition where supported.
- [Integration pipelines](https://github.com/HuasoFoundries/jpgraph/actions/workflows/tests.yml) checking new releases compatibility against different PHP versions
- New or refactored code is expected to observe [PSR-1](https://www.php-fig.org/psr/psr-1/) and [PSR-2](https://www.php-fig.org/psr/psr-2/) coding standards (Eventually [PSR-12](https://www.php-fig.org/psr/psr-12/) as well).

Comparing against the original v3.5 codebase, we also stripped examples or incomplete implementation of graph types exclusive to v3.5 pro (e.g. Barcodes).
