Mtl.css

A simple css tool lib.

![GitHub](https://img.shields.io/github/license/Srooter/Mtl-css)

## Features

- very simple css tool lib.
- Only for common html tag reset css.
- According to the development platform configuration reset css.
- Encapsulation base tool class.

## Environment Support

Modern browser,like Chrome,Firefox,Edge last 2 versions

## Usage

1.congfig reset platform.
`build/utils/variables.scss`
// @param "pc","mobile"
\$platform: mobile;

2. `npm install node-sass -g`

3. `node-sass build/main.scss --output-style compressed dist/mtl.min.css`

4. `<link rel="stylesheet" href="mtl.min.css"/>`

PS: class name description see `build/*.scss` file.

## Reference

- [Normalize.css](https://necolas.github.io/normalize.css/).
- [Ant Design](https://ant.design/index-cn).
- [weui](https://weui.io/).
- [tailwindcss](https://tailwindcss.com/).

## License

The MIT License(http://opensource.org/licenses/MIT)
