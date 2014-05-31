# calculate-assets [![NPM version](https://badge.fury.io/js/calculate-assets.png)](http://badge.fury.io/js/calculate-assets)

> Calculate the path to an 'assets' or 'public' directory from dest files. Determines whether or not the path should have a trailing slash making it safe to use in templates.

## Install
Install with [npm](npmjs.org):

```bash
npm i calculate-assets --save-dev
```


## Usage

```
calculatePath(from, to);
```

Example:

```js
var calculatePath = require('calculate-assets');
console.log(calculatePath(dest, '_gh_pages/public'));
```

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

**Brian Woodward**

+ [github/doowb](https://github.com/doowb)
+ [twitter/doowb](http://twitter.com/jonschlinkert)

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on May 30, 2014._