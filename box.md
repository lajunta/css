### 一、盒子概念

在网页中的标签，可以认为是一个独立的盒子，有自己的边界，边框，填充。

和其它的盒子彼此分开，每个网页可以认为是由一个个盒子组成。

每个块级标签都可以认为是盒子，行内标签转化为块级标签后也可认为是一个盒子

### 二、盒子模型

盒子是指在网页中有宽度和高度，有边界，有边框，有填充的正方形，它在网页中占有自己的空间

边界(margin) 指元素与其它元素之间的距离

边框(border) 指元素四条边或者某一条边的宽度

填充(padding) 指标签内容与边框之间的距离

无论是边界 边框 还是填充都有四个方向 上 下 左 右 (top bottom left right)

我们在设置一个元素的高度和宽度时一定要考虑它的边界 边框 填充 

![盒子模型](images/boxmodel.gif)

盒子的宽度 = 左边界 + 左边框 + 左填充 + 宽度 + 右填充 + 右边框 + 右边界

盒子的高度 = 上边界 + 上边框 + 上填充 + 高度 + 下填充 + 下边框 + 下边界

***

边界: top-margin right-margin bottom-margin left-margin

边框：top-border right-border bottom-border left-border

填充：top-padding right-padding bottom-padding left-padding
