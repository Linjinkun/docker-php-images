# Docker Images For PHP

## 仓库概述

基于官方镜像的 PHP 镜像，已安装常用扩展。

PHP 版本生命周期参考 [PHP 版本支持](https://www.php.net/supported-versions.php)

- 基于 [PHP Official Images](https://hub.docker.com/_/php)
- 基于 [docker-php-extension-installer](https://github.com/mlocati/docker-php-extension-installer)
- 基于 `GitHub Actions` 自动构建

## 使用镜像

```
docker pull jkobe824/php:8.3-fpm
```

镜像仓库 https://github.com/Linjinkun/docker-php-images

更多用法请参考 [PHP 官方镜像](https://hub.docker.com/_/php)

## 预装扩展

预装扩展请以对应镜像的 `Dockerfile` 文件为准。

```
docker run --rm suyar/php:8.2-cli php -m

[PHP Modules]
amqp
apcu
bcmath
bz2
calendar
Core
ctype
curl
date
decimal
dom
enchant
event
exif
fileinfo
filter
ftp
gd
gettext
gmp
hash
iconv
igbinary
imagick
intl
json
libxml
lzf
mbstring
memcached
mongodb
msgpack
mysqli
mysqlnd
openssl
pcntl
pcre
PDO
pdo_mysql
pdo_pgsql
pdo_sqlite
pgsql
Phar
posix
random
readline
redis
Reflection
session
SimpleXML
sockets
sodium
SPL
sqlite3
standard
swoole
tidy
timezonedb
tokenizer
uuid
xlswriter
xml
xmlreader
xmlwriter
xsl
yac
yaml
Zend OPcache
zip
zlib

[Zend Modules]
Zend OPcache
```
