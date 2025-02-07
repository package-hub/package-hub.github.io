---
title: cli
categories: ['javascript']
---
## [cli](https://github.com/NodeSecure/cli)

### JavaScript security CLI that allow you to deeply analyze the dependency tree of a given package or local Node.js project.


- Run a static scan on every JavaScript files and sort out warnings (unsafe-regex, unsafe-import etc) and the complete list of required expr and statements (files, node.js module, etc.).
- Return complete composition for each packages (extensions, files, tarball size, etc).
- Packages metadata from the npm registry API (number of releases, last publish date, maintainers etc).
- Search for licenses files in the tarball and return the [SPDX](https://spdx.org/licenses/) expression conformance of each detected licenses.
- Link vulnerabilities from the multiple sources like GitHub Advisory, Sonatype or Snyk using [Vulnera](https://github.com/NodeSecure/vulnera). 
- Add flags (emojis) to each packages versions to identify well known patterns and potential security threats easily.
- First-class support of open source security initiatives like [OpenSSF Scorecard](https://github.com/ossf/scorecard).
- Generate security report (PDF).
