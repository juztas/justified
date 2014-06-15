# justify [![NPM version](https://badge.fury.io/js/justify.png)](http://badge.fury.io/js/justify)

> Wrap words to a specified length and justify the text.

## Install
Install with [npm](npmjs.org):

```bash
npm i justify --save-dev
```

## Usage

```js
var justify = require('justify');

var str = 'A project without documentation is like a project that doesn\'t exist. Verb solves this by making it dead simple to generate project documentation, using simple markdown templates, with zero configuration required.';

console.log(justify(str));
```

Results in:

```
  A project without documentation is like a project
  that doesn't exist. Verb solves this by making it
  dead  simple to generate  project documentation,
  using  simple  markdown   templates,   with  zero
  configuration required.
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on June 15, 2014._