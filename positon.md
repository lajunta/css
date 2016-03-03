### css 定位机制

css 有三种定位机制: 普通流 浮动和定位

所有元素默认都晨普通流中定位,它们的位置由它在HTML文件中的位置顺序来美如美如决定


### 一、position 属性 

使用position属性可以选择4 种不同类型的定位

static: 元素正常显示

relative: 元素偏移某个距离，它原来所占的空间保留

absolute: 元素从文档流中删除，并相对于其包含的元素进行定位，元素原先在正常文档中的空间会关闭。

fixed: 元素定位类似 absolute,不过它的父级元素为视窗本身

### 二、float 浮动

如果一个盒子浮动，其它同一级别的盒子也要看情况进行浮动，否则就会把其它的盒子给盖住。

详细见 [float 浮动](http://www.w3school.com.cn/css/css_positioning_floating.asp)