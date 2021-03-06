# 介绍

> 一个基于 Vue 的滚动插件，有 3 种模式用于适配 PC 和手机。

你可以通过更改配置来选择不同的模式:

- `native` 模式: 类似于原生的滚动条，但是可以自定义滚动条样式，使用于 PC 端用户。
- `slide` 模式: 允许你用手指或鼠标滑动内容， 可以滑动超出边界范围，适用于移动端端用户。
- `pure-native`模式: 滚动条使用原生的滚动条，适用于喜欢原生滚动条的用户。

你也可以通过更改配置滚动条的样式，包括：

- `透明度`
- `高度/宽度`
- `位置`
- `背景色`
- `是否保持显示`

## 特点

- 独创虚拟滚动条+滑动滚动，可以同时适配 PC 端和手机端！
- 拥有多个模式随时切换，每个模式都有不同的特点:
  - `native` 模式: 类似于原生的滚动条，但是可以自定义滚动条样式，使用于 PC 端用户。
  - `slide` 模式: 允许你用手指或鼠标滑动内容， 可以滑动超出边界范围，适用于移动端端用户。
  - `pure-native`模式: 滚动条使用原生的滚动条，适用于喜欢原生滚动条的用户。
- 检测滚动内容发生尺寸变化并自动更新滚动条。
- 通过使用 [不同的滚动动画](http://vuescrolljs.yvescoding.org/zh/guide/Configuration.html#scrollpanel)来平滑滚动。
- 下拉-刷新 (拉倒顶部并拉出边界开始刷新列表)
- 上推-加载 (推到底部并且退出边界开始加载列表)
- 能够放大或者缩小滚动的内容.
- 分页 (每次滑动整个页面)
- 截断 (每次滑动一个用户定义的距离)
- 能够禁止 X 或 Y 方向上的滚动。
- 能够设置滚动条是否保持显示。
- 能够设置滚动条，轨道的颜色和透明度。
- 能够设置滚动条，轨道的位置。
- 能够自定义内容的标签 (也就是说你能够设置内容的标签为一个组件)
