## How to build on Ubuntu 22.04

Initialize workspace (everytime opening a new terminal):
```shell
source ./oe-init-build-env
```
Build RPi3 linux distro:
```shell
bitbake core-image-minimal
```
There may be missing dependencies that need to be installed.
