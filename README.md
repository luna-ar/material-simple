# [Material-simple][material-simple]

[![npm version](https://img.shields.io/npm/v/material-simple.svg)](https://www.npmjs.org/package/material-simple)

Material-simple is a **CSS framework** based on material design.

## Install

Material-simple is distributed with [npm][npm] and [yarn][yarn], you can install `material-simple` with this command.

### NPM

```sh
npm install material-simple
```

### Yarn

```sh
yarn add material-simple
```

### CDN

[https://unpkg.com/material-simple/][unpkg]
**or**
[https://cdn.jsdelivr.net/npm/material-simple/][jsdelivr]

Feel free to raise an issue or submit a pull request.

## Usage

### CSS

After [installation](#install), you can import the CSS file into your project using this snippet:

```js
import 'material-simple/css/mtrl.min.css';
```

Or if you want to include single module

```js
import "material-simple/css/elements/button.css";
```

### Sass

Some source files are writen in [Sass][sass]. After [installing](#install) with npm, you can add your project's `node_modules` directory to your Sass [include paths](https://github.com/sass/node-sass#includepaths) and import it with

```scss
@import "material-simple";
```

Or if you want to include single module

```scss
@import "material-simple/sass/elements/button.sass";
@import "material-simple/sass/elements/textfield.sass";
```

## Documentation

Docs in development

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[material-simple]: https://github.com/material-simple
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
[yarn]: https://yarnpkg.com/
[unpkg]: https://unpkg.com/material-simple@latest/css/mtrl.min.css
[jsdelivr]: https://cdn.jsdelivr.net/npm/material-simple@latest/css/mtrl.min.css