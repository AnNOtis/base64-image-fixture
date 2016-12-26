# Base64 image fixtures [![npm](https://img.shields.io/npm/v/base64-image-fixture.svg?style=flat-square)](https://www.npmjs.com/package/base64-image-fixture)

> Collect base64 images for fixture usage

## Usage

Visit [here](https://annotis.github.io/base64-image-fixture/) to download images or copy base64 string

Alternatively, install `base64-image-fixture` package.

```sh
$ yarn add dev base64-image-fixture
```

And, read as utf-8 string.

```js
import fs from 'fs'

const base64PNGString =
  fs.readFileSync(
    './node_modules/base64-image-fixture/png/1x1-transparent',
    'utf8'
  )

console.log(base64PNGString)
// => data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAC0lEQVQYV2NgAAIAAAUAAarVyFEAAAAASUVORK5CYII=
```

## License

MIT
