clubs-project.eu website
================

Sources for our project website.

## How to build?

This site is powered by [Spress](http://spress.yosymfony.com/). Dependencies are managed with [Composer](https://www.getcomposer.org).

Make sure you have a [working Composer installation](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

The commands create a static HTML website in the _build_ subdirectory.

```bash
$ git clone https://github.com/clubs-project/website.git

$ cd website/

# Install website dependencies, e.g. Spress
$ php composer.phar install

# Build static HTML with Spress
$ vendor/bin/spress site:build

```