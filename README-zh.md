Mtl.css

中文|[English](README.md)

一个简单的css工具库。

![GitHub](https://img.shields.io/github/license/Srooter/Mtl-css)

## 特征

- 非常简单的css工具库。
- 只包含一些html标签的css重置。
- 封装的一些基础css工具类。
- 可以根据不同开发平台配置重置CSS。

## 环境支持

现代浏览器，Chrome,Firefox,Edge的最新两个版本。

## 使用

1. 配置需要重置的平台，在`src/utils/variables.scss`文件，设置`$platform`值。

2. `npm install node-sass -g`

3. `node-sass src/main.scss --output-style compressed dist/mtl.min.css`生成`mtl.min.css`文件

PS: class名说明请看 `src/*.scss` 文件.

## 参考

- [Normalize.css](https://necolas.github.io/normalize.css/).
- [Ant Design](https://ant.design/index-cn).
- [weui](https://weui.io/).
- [tailwindcss](https://tailwindcss.com/).

## License

The MIT License(http://opensource.org/licenses/MIT)
