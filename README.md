# is-directory [![NPM version](https://badge.fury.io/js/is-directory.png)](http://badge.fury.io/js/is-directory)

> Extends `stats.isDirectory()`, returns `true` if a filepath is a directory.

## Install
Install with [npm](npmjs.org):

```bash
npm i is-directory --save-dev
```

## Usage

```js
var isDir = require('is-directory');
console.log(isDir('README.md'));
//=> 'false'
console.log(isDir('test'));
//=> 'true'
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on July 19, 2014._