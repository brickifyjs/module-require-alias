# Module require alias
> Create CommonJS alias without any dependency \
Useful when used with [Module require for browser](https://github.com/brickifyjs/module-require) \
Useful when used with [Module bundler](https://github.com/brickifyjs/module-bundler)

## Usage

### .gitignore
Only ignore main node_modules
```
/node_modules
```

### Create your module index.js
```js
// Call the alias
var dummy = require('dummy');
module.exports = {}
```

### Create your alias in node_modules folder at same level or higher node_modules/dummy.js
```js
module.exports = require('PATH/MODULE');
```

