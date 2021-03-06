# Nginx-EE

Compile and install the latest nginx releases from source with additional modules

![nginx-ee](https://raw.githubusercontent.com/VirtuBox/nginx-ee/master/nginx-ee.png)

## nginx-ee [Github page](https://virtubox.github.io/nginx-ee/) now available

---

## Features

* Compile the latest Nginx Mainline or Stable Release
* Replace previously installed Nginx package
* Support Additonal modules
* TLS v1.3 support (draft28)

---

## Additional modules

Nginx current mainline release : **v1.15.2**
Nginx current stable release : **v1.14.0**

* ngx_cache_purge
* memcached_nginx_module
* headers-more-nginx-module
* ngx_coolkit
* ngx_brotli
* redis2-nginx-module
* srcache-nginx-module
* ngx_http_substitutions_filter_module
* nginx-dynamic-tls-records-patch_1.13.0+
* Openssl 1.1.1 (OpenSSL_1_1_1-pre9)
* [ipscrub](http://www.ipscrub.org/)
* ngx_http_auth_pam_module
* [virtual-host-traffic-status](https://github.com/vozlt/nginx-module-vts)

optional modules :

* ngx_pagespeed
* naxsi WAF
* [nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module)

---

## Compatibility

* Ubuntu 16.04 LTS (Xenial)
* Ubuntu 18.04 LTS (Bionic)
* Debian 8 Jessie

---

## Requirements

* Nginx installed with **EasyEngine** or from **Ubuntu main APT repository**

---

## Usage

```bash
bash <(wget -O - https://raw.githubusercontent.com/VirtuBox/nginx-ee/master/nginx-build.sh)
```

---

## Nginx configurations

* [Ubuntu-nginx-web-server](https://github.com/VirtuBox/ubuntu-nginx-web-server/tree/master/etc/nginx)

---

## Roadmap

* [x] Add choice between stable & mainline release
* [x] Add Nginx configuration examples
* [ ] Add Cloudflare HPACK patch
* [ ] Add support for servers without EasyEngine
* [ ] Add non-interactive installation
* [ ] Add automated update detection



## Credits & Licence

* [ipscrub nginx module](http://ipscrub.org/)

Published & maintained by <a href="https://virtubox.net" title="VirtuBox">VirtuBox</a>