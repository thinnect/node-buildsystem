# Thinnect build system

GNU Make based build system for embedded projects.

## Installation and usage

```
$ git submodule add git@github.com:thinnect/node-buildsystem.git zoo/thinnect.node-buildsystem
$ cp zoo/thinnect.node-buildsystem/make/Makefile.sample Makefile
```

Edit Makefile and

* Add your own sources (.c files) to variable SOURCES
* Add your own include directories to variable INCLUDES
* Set your version in VERSION_xxx variables
* Set your application UUID in variable UUID_APPLICATION
* Update make targets to make sense for your application

Try to make your target. Fix errors or complain to author.
