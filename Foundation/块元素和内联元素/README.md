# 块级元素(block)和内联元素(inline)

> * 块级元素和内联元素区别
> * 常用的块级元素
> * 常用的内联元素


## 块级元素(block)
* 块级元素占据其父元素的整个行空间
* 通常浏览器会在块级元素前后另起一个新行.
* 块级元素只能出现在 `<body>` 元素内. 
* 块级元素可以包含内联元素和其它块级元素. 


## 内联元素(inline)
* 一个行内元素只占据它对应标签的边框所包含的空间


## 块级元素和内联元素的区别

* 格式
    * 块级元素会新起一行
    * 默认情况下，行内元素不会以新行开始
    
* 内容模型
    * 块级元素可以包含内联元素和其它块级元素
    * 行内元素只能包含数据和其他行内元素.
    
* `margin` `padding` 表现
    * 内联元素的 `margin` `padding` 水平方向占用空间, 垂直方向不占用空间.[详见Demo](inline元素的margin_padding特性/README.md)
    * 块级元素的 `margin` `padding` 水平和垂直方向都占用空间.  

* 默认内容区的 `width` 和 `height`值
    * 块元素的 `width` 默认为父元素的宽度.
    * inline元素的 `width` 是由内容"撑"开的.
    * 块元素的 `height` 是由内容"撑"开的.
    * inline元素的 `height` 是由内容"撑"开. 


## 常用的块级元素
* `<div>` `<h1>`~`<h6>` `<p>` `<ol>` `<ul>` `<form>` `<hr>` 


## 常用的内联元素
* `<b>` `<i>` `<small>`
* `<span>` `<a>` `<img>` `<q>`
* `<button>` `<input>` `<label>` `<select>` `<textarea>` 