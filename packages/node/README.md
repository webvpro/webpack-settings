Common webpack settings for node apps.

## Installation

```shell
npm install ctrine-webpack-settings-node
```

## Usage

The settings can be used directly in your `webpack.config.js` like so:

```Javascript
module.exports = require('ctrine-webpack-settings-node')
```

## Expected directory structure

```
build
src
  main.js
webpack.config.js
```
* **build:** Directory where the compiled files will reside.
* **src:** Project’s source.
* **main.js:** Entry point.
* **webpack.config.js:** Actual webpack config, the location of this file is
  used do determine the location of the `build` and `src` directories.
