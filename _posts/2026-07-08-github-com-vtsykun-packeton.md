---
title: packeton
categories: ['php', 'packagist', 'private-packagist']
---
## [packeton](https://github.com/vtsykun/packeton)

### :package: Private, self-hosted Packagist/Composer/Satis repository with unlimited private repos.


- `APP_SECRET` - Must be static, used for encrypt SSH keys in database. The value is generated automatically, see `.env` in the data volume. 
- `APP_COMPOSER_HOME` - composer home, default /data/composer
- `DATABASE_URL` - Database DSN, default sqlite:////data/app.db. Example for postgres "postgresql://app:pass@127.0.0.1:5432/app?serverVersion=14&charset=utf8"
- `PACKAGIST_DIST_PATH` - Default /data/zipball, path to storage zipped versions
- `REDIS_URL` - Redis DB, default redis://localhost
- `PACKAGIST_DIST_HOST` - Hostname, (auto) default use the current host header in the request.
- `TRUSTED_PROXIES` - Ips for Reverse Proxy. See [Symfony docs](https://symfony.com/doc/current/deployment/proxies.html)
- `TRUSTED_HOSTS` - Trusted host, set if you've enabled public access and your nginx configuration uses without `server_name`. Otherwise, possible the DDoS attack with generated a big cache size for each host.
- `PUBLIC_ACCESS` - Allow anonymous users access to read packages metadata, default: `false`
- `MAILER_DSN` - Mailer for reset password, default disabled
- `MAILER_FROM` - Mailer from

Installation
------------
