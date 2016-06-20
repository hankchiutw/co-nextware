# co-nextware

> co-nextware wraps an ES6 genderator as express.js middleware callback(having 'next' argument)

[![NPM Version][npm-image]][npm-url]

## Install

```bash
npm i co-nextware
```

## Usage

```javascript
var express = require('express');
var app = express();
var cn = require('co-nextware');

app.get('/', cn(fn));

function *fn(req, res, next){
....
}
```

## License

[MIT](http://vjpr.mit-license.org)

[npm-image]: https://img.shields.io/npm/v/co-nextware.svg
[npm-url]: https://npmjs.org/package/co-nextware
