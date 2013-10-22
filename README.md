android-buildenv-installer
==========================

Installer for Android build environment for Ubuntu.

Just do `vagrant up` and you'll have an Ubuntu box ready to build 
Android or run `install.sh` on your Ubuntu box to have it download 
and configure everything for you.


Proxy
=====

If you are behind proxy, for `install.sh` to work, you need to set
 
 * git proxy to clone it in the first place (`git config --global http.proxy http://<your proxy>/`)
 * apt proxy (in `/etc/apt/apt.conf.d/proxy` set `Acquire::http::proxy "http://<your proxy/";`)
 * python proxy (have `export http_proxy='http://<your proxy>/`)


