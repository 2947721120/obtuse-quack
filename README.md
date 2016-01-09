# 材料设计图标

材质设计图标是官方的 [icon set](http://www.google.com/design/spec/style/icons.html#icons-system-icons) 从谷歌设计的 [material design guidelines](http://www.google.com/design/spec).

### 2.1更新

2.1次更新增加了96个新的图标！

检查出什么是新的[material icons library](https://www.google.com/design/icons/).

## 开始

Read the [developer guide](http://google.github.io/material-design-icons/) 关于如何在项目中使用材质设计图标。

### 使用字体集合

The `iconfont` 文件夹中包含可包含在项目中的预生成的字体文件。这是特别方便的网络，但是，它通常是更好地链接到网络字体托管在谷歌字体：

```html
<link href="https://fonts.lug.ustc.edu.cn/icon?family=Material+Icons"
      rel="stylesheet">
```

多读 [font portion](http://google.github.io/material-design-icons/#icon-font-for-the-web) 我们的全面开发指南。

### 使用符号和精灵

The `css-sprite` and `svg-sprite` folders contain pre-generated sprite sheets, as well as svg symbols that can be `<use>`d more directly and with fewer constraints. Instructions for using them are in the [sprites documentation](https://github.com/google/material-design-icons/tree/master/sprites).

## Polymer icons

If you wish to use the icon set with Polymer, we recommend consuming them via the [`<iron-icons>`](https://github.com/polymerelements/iron-icons) element ([`<core-icons>`](https://github.com/Polymer/core-icons) in v0.5).

## License

We have made these icons available for you to incorporate them into your products under the [Creative Common Attribution 4.0 International License (CC-BY 4.0)](http://creativecommons.org/licenses/by/4.0/). Feel free to remix and re-share these icons and documentation in your products.
We'd love attribution in your app's *about* screen, but it's not required.
The only thing we ask is that you not re-sell the icons themselves.
