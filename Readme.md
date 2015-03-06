
# metalsmith-highlight

A [Metalsmith](http://metalsmith.io) plugin to highlight code in Markdown files. Fork of [metalsmith-metallic](https://github.com/weswigham/metalsmith-metallic), to support minimatch and do not strip whitespace from beginning/ending of code.

## Installation

```shell
npm install metalsmith-metallic
```

## Setup

Include a [highlight.js](http://highlightjs.org/download/) theme somewhere in your templates.

Example:
```html
<link rel="stylesheet" href="http://yandex.st/highlightjs/8.0/styles/default.min.css">
```

## CLI Usage

Install via npm and then add the `metalsmith-highlight` key to your `metalsmith.json` plugin, like so:

```json
{
  "plugins": {
    "metalsmith-highlight": true
  } 
}
```

## Javascript Usage

```js
var highlight = require('metalsmith-highlight');

metalsmith.use(highlight());
```

## License
MIT
