opal-rserver
=============

Opal R server Debian meta package


## Create the package

Depends on equivs-build: `sudo apt-get install equivs-build`

```
make all [sign=true]
```

Package is built to `build/opal-rserver-<version>_all.deb`


## Publish signed package

```
make publish dir=<destination> sign=true
```

Package will be copied to

* `<destination>/unstable` for SNAPSHOT version
* `<destination>/stable` for release version

