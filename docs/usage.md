```js
var justify = require('justified');

var str = 'A project without documentation is like a project that doesn\'t exist. Verb solves this by making it dead simple to generate project documentation, using simple markdown templates, with zero configuration required.';

console.log(justify(str));
```

Resulting in:

```
  A project without documentation is like a project
  that doesn't exist. Verb solves this by making it
  dead simple to generate project documentation,
  using simple markdown templates, with zero
  configuration required.
```