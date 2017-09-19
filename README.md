# minify-js
It minifies JavaScript

# Installation
`npm i -D minify-js`

# Usage
```
const minifier = require('minify-js')
const fileName = `${__dirname}/src/src.js`

const minifiedSourceFile = minifier(fileName)

// => Do things w/ minified source...
```
