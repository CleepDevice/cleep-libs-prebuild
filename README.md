# Cleep-libs-prebuild

This repo is used to store prebuilt version of some Cleep dependencies that kill installation duration due to the need to compile it for ARM env.

# Supported dependencies

* gevent https://www.gevent.org/ (about 50 mins to build on raspi3)
* pyzmq https://pyzmq.readthedocs.io/en/latest/ (about 25 mins to build on raspi3)

# Compiled versions

All compiled packages are stored directly on this repo.

Please check available versions on respective directories (gevent, pyzmq...)

# How to run

Simply tag version to build
> [lib-name]-[tag-name]

* lib-name must be the name of supported lib (gevent, pyzmq, ...)
* tab-name must the exact name of version to build (gevent is xx.xx.xx while pyzmq is vxx.xx.xx)

