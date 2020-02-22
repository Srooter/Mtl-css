Mtl.css

English | [中文](README-zh.md)

A simple css tool lib.

![GitHub](https://img.shields.io/github/license/Srooter/Mtl-css)

## Features

- very simple css tool lib.
- Only for common html tag reset css.
- Encapsulation base tool class.
- CSS reset can be configured according to different development platforms.

## Environment Support

Modern browser,like Chrome,Firefox,Edge last 2 versions

## Usage

1. congfig reset platform. In the `src/utils/variables.scss` file

2. `npm install node-sass -g`

3. `node-sass src/main.scss --output-style compressed dist/mtl.min.css` dist `mtl.min.css` file.

PS: class name description see `src/*.scss` file.

## Reference

- [Normalize.css](https://necolas.github.io/normalize.css/).
- [Ant Design](https://ant.design/index-cn).
- [weui](https://weui.io/).
- [tailwindcss](https://tailwindcss.com/).

## License

The MIT License(http://opensource.org/licenses/MIT)
