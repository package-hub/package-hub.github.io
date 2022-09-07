---
title: npq
categories: ['javascript', 'npm', 'package-manager']
---
## [npq](https://github.com/lirantal/npq)

### 🎖safely* install packages with npm or yarn by auditing them as part of your install process


Once npq is installed, you can safely* install packages:

```bash
npq install express
```

`npq` will perform the following steps to sanity check that the package is safe by employing syntactic heuristics and querying a CVE database:

* Consult the [snyk.io database of publicly disclosed vulnerabilities](https://snyk.io/vuln) to check if a security vulnerability exists for this package and its version.
* Package age on npm
* Package download count as a popularity metric
* Package has a README file
* Package has a LICENSE file
* Package has pre/post install scripts

If npq is prompted to continue with the install, it simply hands over the actual package install job to the package manager (npm by default).

safely* - there's no guaranteed safety; a malicious or vulnerable package could still exist that has no security vulnerabilities publicly disclosed and passes npq's checks.
