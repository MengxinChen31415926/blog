## 一.subline使用必备技巧
## 二.安装emmet插件的subline使用必备技巧
	### 1.html5框架扩展：首先新建文件，将文件保存为HTML文件，输入半角的！+tab键或Ctrl+E键（进行扩展），效果如下：
	```javascript
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>Document</title>
	</head>
	<body>
	```
### 2.各种标签简化输入(不需原始参数）扩展，通常输入标签名按tab键扩展即可。举两例如下：
#### ①.段落扩展：输入p(扩展)，效果如下：
```javascript
	<p></p>
```
#### ②.图像扩展：输入img(扩展)，效果如下：
```javascript
	<img src="" alt="">
```
### 3.各种标签简化输入扩展，通常输入标签名及所需参数按tab键扩展即可。举两例如下：
#### ①.连同段落内容的段落扩展：输入p+段落内容(扩展)，效果如下：
```javascript
	<p>段落内容</p>
```
#### ②.带有初始主图地址的图像扩展：输入 `img[src=logo.jpg] `(扩展)，效果如下：
```javascript
	<img src="logo.jpg" alt="">
```
### 4.标签的嵌套扩展：举例如下
#### ①.输入p>span(扩展)，效果如下（p>span所以p是span的上级）：
```javascript
	<p><span></span></p>
```
### 5.添加同级标签扩展：举例如下
#### ①.img和a同级的扩展：输入p>img+a(扩展)，效果如下（img和a同级）：
```javascript
	<p><img src="" alt=""><a href=""></a></p>
```
### 6.标签的分组扩展：举例如下
#### ①.p和img的分组扩展：输入(div>p)+(div>img)(扩展)，效果如下（（）内的同区域即同组，p和img位于不同区域因此被分组）：
```javascript
	<div>
		<p></p>
	</div>
	<div>
		<img src="" alt="">
	</div>
```
### 7.多个对象的快速生成：举例如下
#### ①.生成含3列表项的无序列表的扩展：输入ul>li* 3(扩展)，效果如下：
```javascript
	<ul>
		<li></li>
		<li></li>
		<li></li>
	</ul>
```
### 8.文本的快速生成：举例如下
#### ①.快速生成一段文本：输入lorem(扩展)，效果如下（（）内的同区域即同组，p和img位于不同区域因此被分组）：
```
	Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque aspernatur inventore maiores aut, fugit blanditiis tempora, ipsam incidunt impedit sequi quisquam vero quis eum quia quos voluptas fugiat ab deserunt!
```
#### ②.快速生成一段指定单词数的文本：输入lorem+（指定单词数，此处为4）(扩展)，效果如下：
```javascript
	Lorem ipsum dolor sit.
	
```


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MengxinChen31415926/blog/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
