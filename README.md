# TAR for Archiver v0.0.1 [![Build Status](https://travis-ci.org/archiverjs/archiver-tar.svg?branch=master)](https://travis-ci.org/archiverjs/archiver-tar)

> tar [archiver](https://github.com/archiverjs/node-archiver) plugin

[![NPM](https://nodei.co/npm/archiver-tar.png)](https://nodei.co/npm/archiver-tar/)

## Install

```bash
$ npm install --save imagemin-jpegoptim
```

## Usage

```js
var Archiver = require('archiver');
var ArchiverTar = require('archiver-tar');

new Archiver()
  .src('files/*.html')
  .dest('dest/archive.zip')
  .use(ArchiverTar())
  .run();
```

## API

### ArchiverTar(options)

#### TBA

## Things of Interest
- [Changelog](https://github.com/archiverjs/archiver-tar/releases)
- [Contributing](https://github.com/archiverjs/archiver-tar/blob/master/CONTRIBUTING.md)
- [MIT License](https://github.com/archiverjs/archiver-tar/blob/master/LICENSE)