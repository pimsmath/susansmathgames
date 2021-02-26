# Susan's Math Games

Welcome to Susan's Math Games. This repository contains a static version of
the [susansmathgames.ca](https://susansmathgames.ca) website built with the [hugo](https://gohugo.io). The
intention is that this site will soon replace the existing wordpress
installation and provide all of the same content.

## Building the site

The content of the website is (almost) pure markdown so it should build with
most versions of Hugo, but we recommend something above v0.64.0 (currently we
are using v0.80.0). This branch uses the
[anake theme](https://themes.gohugo.io/gohugo-theme-ananke) which has been installed
as a hugo module. 

### Clone and Build/Deploy
To deploy a copy of this site first clone this repository then initialize the
theme module

```bash
$ git clone git@github.com:pimsmath/susansmathgames.git
$ cd susansmathgames
$ hugo mod get
$ hugo serve
```

### Updating the Theme
We have attempted to keep local modifications of the theme to a minimum so that
updating the theme should be straightforward. That said, it is always worth
checking the [ananke github
page](https://github.com/theNewDynamic/gohugo-theme-ananke) for relevant issues
or breaking changes. In the simplest case, updating looks like
```bash
$ hugo mod get github.com/theNewDynamic/gohugo-theme-ananke@master
```
Where `@master` should be replaced with whatever tag you want to use.


susansmathgames.ca is a project of the [Pacific Institute for the Mathematical
Sciences](https://www.pims.math.ca).

