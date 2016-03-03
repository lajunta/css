### 一、样式的添加有三种方法

1. 在当前文件 `<head>` 中添加
2. 引用外部的样式文件
3. 直接写在相应的标签中,加一个  `style` 属性

### 二、在当前网页中加入样式

在 `<head>` 中可以添加 `<style> </style>`

```
<head>
    <style>
        .atitle{各种声明}
        #abody{各种声明}
    </style>
</head>
```

### 三、引入外部的样式文件

在头部加入外部 css 样式文件

```
<head>
    <link rel="stylesheet" type="text/css" href="mystyle.css" />
</head>
```

### 四、内联样式
把样式直接写在标签内,给标签添加 `style` 属性

```
    <p style="width: 100px;height:200px;">
```
