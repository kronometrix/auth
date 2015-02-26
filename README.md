# Kronometrix Authentication #

This is the authentication binary package for **Kronometrix** software.

## Modules ##
* Openresty
* Redis

## Libs ##
* lua-resty-http-simple
* lua-resty-template
* router.lua
* inspect.lua (development mode)

### Required Libraries ###

FreeBSD
* openssl-1.0.1_13
* pcre-8.34_1

Linux
* libpcre3-dev
* libssl-dev


## Installation


### FreeBSD 10 amd64
```
# pkg install /var/tmp/kronometrix-auth-1.0.0b49-freebsd10.1-amd64.txz 
Updating FreeBSD repository catalogue...
FreeBSD repository is up-to-date.
All repositories are up-to-date.
Checking integrity... done (0 conflicting)
The following 1 packages will be affected (of 0 checked):

New packages to be INSTALLED:
	kronometrix-auth: 1.0.0b49

The process will require 29 MiB more space.

Proceed with this action? [y/N]: y
[1/1] Installing kronometrix-auth-1.0.0b49...
[1/1] Extracting kronometrix-auth-1.0.0b49: 100%
```
 
