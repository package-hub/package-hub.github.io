---
title: psiTurk
categories: ['python', 'hacktoberfest']
---
## [psiTurk](https://github.com/NYUCCL/psiTurk)

### An open platform for science on Amazon Mechanical Turk.


psiTurk v3 has been released! See the migration guide [here](https://psiturk.readthedocs.io/en/latest/migrating.html).

psiTurk v3 does not support the psiturk ad server. If you still need
the psiTurk ad server, use psiTurk v2.3.12, and remove all HTML comments
from your `ad.html` file. Versions less than v2.3.12 will not be able to post
HITs due to a change implemented by the psiturk ad server's hosting provider. You can upgrade to psiturk v2.3.12 by running `pip install --upgrade psiturk=2.3.12`.
