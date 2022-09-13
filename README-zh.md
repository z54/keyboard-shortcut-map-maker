![Website](https://img.shields.io/website?url=https%3A%2F%2Farchie-adams.github.io%2Fkeyboard-shortcut-map-maker%2F)
![GitHub](https://img.shields.io/github/license/archie-adams/keyboard-shortcut-map-maker)

# 键盘快捷键地图制作工具

这是一个网站工具，用于创建键盘快捷键或键绑定的可视化地图/图像。

它最初是作为为我的ahk-scripts [ahk-scripts](https://github.com/Archie-Adams/ahk-scripts) 项目生成帮助页面的工具。

注意：可以在[releases](https://github.com/Archie-Adams/keyboard-shortcut-map-maker/releases)页面中找到该网站的单个文件版本，以便于本地使用。

---

### 特性

- 使用 html 文件保存和加载。
- 保存为 png 文件。
- 用于打印的样式。
- 添加无限键盘。
- 添加无限节。
- 重命名键盘和节。
- 重新排序键盘和节的列表。
- 多种颜色选择。
- 支持色盘左侧固定。

### 计划特点

- 添加键和弦表/节。
- 每个键盘的可折叠笔记部分。
- 自定义颜色。
- 完全控制按键文本。
- 不同的键盘布局。
- 单 HTML 文件版本。
- 更好的样式+更多的动效。
- 代码重构和清理。
- 可折叠节。
- 键盘控制。
- 优化保存文件名默认值改为"文件名+时间", 并弹出提示窗口用于自定义
- 颜色区可增加提示文字

### 已知的问题

- 如果不加载另一个中间文件，则无法重新加载相同的文件。
	- 由在输入文件更改时调用加载函数引起。

&nbsp;

# [演示页面 ↪](https://archie-adams.github.io/keyboard-shortcut-map-maker/)

# 演示图片

![A keyboard with the key text being its keyboard shortcut function.](images/readmeimage.png "")  

# 依赖项

[dom-to-image](https://github.com/tsayen/dom-to-image)  
[file-saver](https://github.com/eligrey/FileSaver.js/)  

# 贡献

如果您想改进这个项目并欢迎提交拉取请求。

# 致谢

[Keyboard](https://github.com/guido732/mechanical-keyboard) 灵感: [Guido Torres](https://github.com/guido732)  
