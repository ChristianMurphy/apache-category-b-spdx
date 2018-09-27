# apache-category-b-spdx

[![NPM Version](https://img.shields.io/npm/v/apache-category-b-spdx.svg)](https://www.npmjs.com/package/apache-category-b-spdx)

Apache Category B maybe include licenses in a machine readable format using [SPDX](https://spdx.org).

Adapted from <https://apache.org/legal/resolved.html#what-can-we-maybe-include-in-an-asf-project-category-b>

## Installation

```sh
# NPM
npm install apache-category-b-spdx

# Yarn
yarn add apache-category-b-spdx
```

## Usage

```js
var list = require("apache-category-b-spdx");

for (var i = 0; i < list.length; i++) {
  console.log(list[i]);
}
```
