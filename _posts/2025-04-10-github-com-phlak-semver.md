---
title: SemVer
categories: ['php', 'semver', 'semantic-versioning']
---
## [SemVer](https://github.com/PHLAK/SemVer)

### Semantic versioning helper library for PHP


```php
$version = new SemVer\Version('v1.2.3-beta.4+007');

echo $version;             // '1.2.3-beta.4+007'
echo $version->major;      // 1
echo $version->minor;      // 2
echo $version->patch;      // 3
echo $version->preRelease; // 'beta.4'
echo $version->build;      // '007'
```
