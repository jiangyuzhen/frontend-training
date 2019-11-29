## HTML-CSS-Training

### 一、HTML

#### 0、学习内容：

- 宏观了解 `HTML`
- 掌握链接和文本常用元素
- 掌握标题与段落区别
- 掌握图片与可嵌入内容元素
- 掌握列表元素
- 掌握表格元素
- 掌握表单元素
- 掌握 `HTML5` 新增的常用语义化元素
- 掌握音频与视频元素及其属性
- 掌握新增表单类型
- 了解 `Web` 存储
- 了解 `Canvas` 画布 和 `SVG`



#### 1、学习资源

- [表单增强](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms)

- [MDN HTML5 介绍](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [w3c HTML5 基础教程](https://www.w3school.com.cn/html5/index.asp)

- [w3school HTML 基础教程](https://www.w3school.com.cn/html/index.asp)
- [MDN HTML 所有 Element](javascript:void(0))

- [慕课 HTML 练习1-5章](https://www.imooc.com/learn/9)
- [FCC 网站练习](https://learn.freecodecamp.one/responsive-web-design/basic-html-and-html5/)



### 二、CSS

#### 0、学习内容

- 掌握 `CSS` 选择器以及优先级
- 掌握 `CSS` 的文本样式
- 掌握 `CSS` 的背景样式
- 掌握 `CSS` 边框样式
- 掌握 `CSS` 的表格样式
- 了解 `CSS` 轮廓样式

#### 1、选择器

`CSS` 有 [权重或优先级](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Specificity) 概念，[如何计算](https://www.w3cplus.com/css/css-specificity-things-you-should-know.html)，建议把选择器了解后回头来看权重优先级怎么计算的。

选择器可以 [分组](https://www.w3school.com.cn/css/css_selector_grouping.asp)；

[选择器分类 - CSS/选择符](https://css.doyoe.com/)（`E` 为某元素）：

- 元素选择器
- `ID` 选择器
- 类选择器
- 属性选择器
- 后代选择器
- 子元素选择器
- 相邻兄弟选择器
- 伪类选择器，重点掌握：
  - `E:link`
  - `E:visited`
  - `E:hover`
  - `E:active`
  - `E:focus`
  - `E:not`
  - `E:first-child`
  - `E:last-child`
  - `E:nth-child(n)`
  - `E:nth-of-type(n)`
  - `E:checked`
  - `E:disabled`
- 伪元素选择器，重点掌握：
  - `E:before/E::before`
  - `E:after/E::after`
  - `E::placeholder`



#### 2、文本样式

文本样式包括：[基础文本和字体样式](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)、[列表样式](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)、[链接样式](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)、[网络字体](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts)

[**基础文本和字体样式**](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)，重点掌握：

- 字体/大小/样式：`font`
- 字体：`font-family`
- 字体大小：`font-size`
- 字体样式：`font-style`
- 字体样色：`color`
- 字体粗细：`font-weight`
- 字体缩进：`font-letter`
- 字符间距：`letter-spacing`
- 单词间距：`word-spacing`
- 行高：`line-height`
- 文本对齐：`text-align`
- 文字阴影：`text-shadow`
- 文本装饰：`text-decoration`

[**列表样式**](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)，重点掌握：

- 列表的项目符号的类型：`list-style-type`
- 项目符号位置：`list-style-position`
- 项目符号自定义图片：`list-style-image`
- 糅合前面三种属性的简写：`list-style`

[**链接样式**](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)，很多时候我们不太需要 `a` 元素本来有下划线的样式，用 `text-decoration: none;` 就可以解决这个问题



#### 3、背景样式

背景可以是纯颜色，也可以是图片作为背景，相关属性有：

- 背景颜色：[background-color](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-color)
- 插入背景图片：[background-image](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-image)
- 背景图片的起始位置：[background-position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-position)
- 背景图片是否重复：[background-repeat](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-repeat)
- 背景图片尺寸大小：[background-size](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-size)
- 糅合前几个属性的简写：[background](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background)



#### 4、边框样式

[边框样式](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders#Borders)，重要属性有：

- 边框宽度：`border-width`

- 边框样式：`border-style`

- 边框颜色：`border-color`

- 糅合前三种属性的简写：`border`

  边框样式可以指定**盒子的一边**，于是有了 `top/left/bottom/right` 属性：

- `border-top-width`
- `border-top-style`
- `border-top-color`
- `border-top`
- ......



#### 5、表格样式

[表格样式](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Styling_tables)，重要属性：

- 表格边框合并为单一的边框：`border-collapse`
- 显示单元、行和列的算法：`table-layout`



#### 6、轮廓样式

[轮廓样式](https://developer.mozilla.org/zh-CN/docs/Web/CSS/outline)，因为不常使用，所以不列所有属性，但是有一点需要大家重点掌握：前面我们已经学习了 **`input` 元素**，在没有给样式的情况下，如果我们鼠标点中 `input` 框，它会有一个**蓝色模糊框**，这个蓝色框就是轮廓实现的，建议大家动手看下效果。



#### 7、盒模型

盒模型中有几个需要大家掌握的知识点：**宽度(`width`)**、**高度(`height`)**、[**内边距(padding)**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/padding)、[**外边距(margin)**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/margin)、[**边框(border)**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/border)。

理解上面的几个知识点，我们再来看 [**盒模型**](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Building_blocks/The_box_model) 的解释。

浏览器的差异造成了盒子计算总高度和总宽度有所不同，但 [**box-sizing**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/box-sizing) 属性可以改变盒子的计算方式。

资源推荐：

- [极客学院 - 盒模型](http://www.jikexueyuan.com/course/164.html)



#### 8、定位

[定位属性(position)](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position) 让你对元素进行定位，我们必须掌握 `position` 几个重要的定位方式，以及在什么情况下使用：

- 相对定位：`relative`
- 绝对定位：`absolute`
- 固定定位：`fixed`
- 粘性定位：`sticky`

设置了定位方式后，再通过 **`top / left / bottom / right`** 来决定最终定位的位置。

**`position`** 用来设置定位后，常常会伴随着设置 [层叠显示(z-index)](https://developer.mozilla.org/zh-CN/docs/Web/CSS/z-index) 的问题。

资源推荐：

- [极客学院 - 定位&浮动](http://www.jikexueyuan.com/course/163.html)



#### 9、浮动

[**浮动(float)**](https://developer.mozilla.org/zh-CN/docs/CSS/float) 因为 **`flex` 布局** 的广泛使用现在已经不常使用了，但还是要掌握它，因为其兼容性更好。

由于设置了 **`float`** 后，其元素会被移出正常的文档流，这样会造成正常的后面的元素占据浮动的元素位置，但其实我们想要的效果是浮动后的元素依然在文档流中占据位置，所以我们需要使用 [**清除浮动(clear)**](https://developer.mozilla.org/en-US/docs/Web/CSS/clear) 来解决这个问题。



#### 10、显示类型

[**显示类型(display)**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/display) 一般包含两种特性，重点掌握以下属性：

- `block`
- `inline`
- `inline-block`
- `none`

布局相关的：

- [flex](https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
- `box`
- `grid`



#### 11、其它重要属性

- 设置元素显示的透明度：[**opacity**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/opacity)
- 设置鼠标移到元素上的显示样式：[**cursor**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/cursor)
- 设置元素是否可见：[**visibility**](https://developer.mozilla.org/zh-CN/docs/Web/CSS/visibility)
- 元素内容超过限定高度时：[**overflow**](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)



#### 12、尺寸

前面我们知道 `CSS` 可以给块级元素和行内块元素设置 `width` 和 `height`，这里需要大家掌握，除了 `width` 和 `height` 可以设置外，还有如下几个尺寸设置：

- 最大宽度：[max-width](https://developer.mozilla.org/en-US/docs/Web/CSS/max-width)
- 最大高度：[max-height](https://developer.mozilla.org/en-US/docs/Web/CSS/max-height)
- 最小宽度：[min-width](https://developer.mozilla.org/en-US/docs/Web/CSS/min-width)
- 最小高度：[min-height](https://developer.mozilla.org/en-US/docs/Web/CSS/min-height)



#### 13、单位

推荐资源：

- [MDN CSS units](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units#Numbers_lengths_and_percentages)



#### 14、媒体查询

推荐资源：

- [MDN CSS @media](https://developer.mozilla.org/zh-CN/docs/Web/CSS/@media)



#### 15、其他学习资源

- [慕课网 第6章-15章](https://www.imooc.com/learn/9)

- [CSS 速查表](https://css.doyoe.com/)