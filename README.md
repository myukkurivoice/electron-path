electron-path -- npm module to get electron path.
===========================================

## Description

get electron application path,
or get unpackedPath.

## Install

```bash
npm install --save git+https://github.com/taku-o/electron-path#master
````

## Usage

As a node module:

```js
const epath = require('electron-path');

const packagePath = epath.getAppPackageDir();
const unpackedPath = epath.getUnpackedPath();
```

