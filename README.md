## 一.subline使用必备技巧
### 1.显示比例放大：Ctrl+“+”；显示比例减小：Ctrl+“-”
### 2.分屏：同时按下Alt+Ctrl+分屏数字键2分屏，按下Alt+Ctrl+分屏数字键1恢复单屏
同时显示html和css文件：单屏Alt + Shift + 2 将视图设置成两列；
打开一个css文件，Ctrl + Shift + 2，将其“赶”到右边那列。
### 3.折叠与展开代码：光标靠近行号右下角，点击出现的三角形。
### 4.Ctrl+D:选择一个单词；Ctrl+L:选择一行；Ctrl+A:全选；
### 5.同时多处输入文本：按下Ctrl键的同时用光标多处选择输入文本处，选完松开Ctrl键，输入文本即可。
### 6.代码缩进：Ctrl+]将所选代码向右缩进；Ctrl+[将所选代码向左缩进；
### 7.调试（注意调试前先Ctrl+保存才能看到g改动的效果，否则浏览器仍打开上次保存时的文件）：空白处右键单击选择“在浏览器中打开”
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
#### ①.生成含3列表项的无序列表的扩展：输入ul>li* 3(扩展)，效果如下($个数代表强制输出数字位数）：
```javascript
	<ul>
		<li></li>
		<li></li>
		<li></li>
	</ul>
```
### 8.带有从1开头的有序数字的多个对象的快速生成：举例如下
#### ①.快速生成10个有序数字的标题扩展：输入`h1{$$$}*10`(扩展)，效果如下：
```javascript
	<h1>001</h1>
	<h1>002</h1>
	<h1>003</h1>
	<h1>004</h1>
	<h1>005</h1>
	<h1>006</h1>
	<h1>007</h1>
	<h1>008</h1>
	<h1>009</h1>
	<h1>010</h1>
```

### 9.文本的快速生成：举例如下
#### ①.快速生成一段文本：输入lorem(扩展)，效果如下（（）内的同区域即同组，p和img位于不同区域因此被分组）：
```javascript
	Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque aspernatur inventore maiores aut, fugit blanditiis tempora, ipsam incidunt impedit sequi quisquam vero quis eum quia quos voluptas fugiat ab deserunt!
```
#### ②.快速生成一段指定单词数的文本：输入lorem+（指定单词数，此处为4）(扩展)，效果如下：
```javascript
	Lorem ipsum dolor sit.
```
