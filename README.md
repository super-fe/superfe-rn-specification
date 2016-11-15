# superfe-rn-specification

>Specification of super-fe's react-native apps

* [Development Environment](#development-environment)
    + [node&npm version](#nodenpm-version)
    + [react-native version](#react-native-version)
* [Project Files](#project-files)
    + [Directories](#directories)
    + [package.json](#packagejson)
    + [CHANGELOG.md](#changelogmd)
* [Code Style](#code-style)
    + [.editorconfig](#editorconfig)
    + [.fecs](#fecs)

## Development Environment

### node&npm version

`Node.js` requires latest of v6, which is a LTS version maintained until April 18, 2018. We suggest &gt;=6.9.1.

`NPM` requires latest of v3, whose tag is *3.x-latest*, *v3.x-latest* or *latest-3*. We suggest &gt;=3.10.9.

E.g.

```sh
npm i npm@3.x-latest -g
```

### react-native version

The [app](https://itunes.apple.com/cn/app/id382201985?mt=8&from=1000715p) carries v0.35.0 only until now(11/15/2016).

## Project Files

### Directories

1. `src` is for source files
1. `assets` is for assets
1. `bundle` is for outputed bundle
1. `__test__` is for jest test

### package.json

>TODO, that is a lot

### CHANGELOG.md

Follows <http://keepachangelog.com/zh-CN/0.3.0/>.

## Code Style

### .editorconfig

Follows <https://github.com/super-fe/superfe-npm-editorconfig>.

### .fecs

We are suggested to use [fecs](https://github.com/ecomfe/fecs).