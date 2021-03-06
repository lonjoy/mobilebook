# MobileBook 结构模板与撰写指引

## 结构模板

全书的内容结构大概是这样的：

	#  1 章节标题
	##  1.1 章节一级栏目标题
	###  1.1.1	章节二级栏目标题
	####  章节三级栏目标题

* 章节标题

	每章节必须有且仅有一个标题，相当于页面标签结构的 `<h1>` ,全书有几个章节就有几个章节标题，在章节标题后应该有相应简短的文字对本章节内容进行描述和预告。
	
	章节标题使用一个 `#` （井号）来标注。

* 一极栏目标题

	章节一级栏目是每个章节里的直接子栏目，相当于页面标签结构的 `<h2>` ，章节一级栏目标题使用 `##` 来标注，并且在标题前加上 `章节序号 + "." + 章节一级栏目标题序号` 用以快速索引和定位内容，如 `3.1 CSS3属性` 。	
	
* 二级栏目标题

	章节二级栏目是每个章节二级栏目的直接子栏目，相当于页面标签结构的 `<h3>` ，章节二级栏目标题使用 `###` 来标注,并且在标题前加上 `章节序号 + "." + 章节一级栏目标题序号 + "." + 章节二级栏目标题序号` 用以快速索引和定位内容，如 `3.1.3 background-image的用法` 。

* 三级栏目标题

	章节三级栏目标题通常是最小的树形结构标题，相当于页面标签结构的 `<h4>`, 章节三级栏目标题使用 `####` 来标注。

三级栏目理论上是最小的树形结构，但了为了更语义和更清晰的层次，还可以使用有序列表和无序列表来补充和扩展。

例如：

	# 1 移动设备与响应式
	
	## 1.1 移动设备	
	### 1.1.1 操作系统
	#### iOS
	#### Android 
	#### Windows	
	### 1.1.2 设备尺寸	
	### 1.1.3 分辨率
	 
	## 1.2 响应式	
	### 1.2.1 viewport
	### 1.2.2 media-query
	
	# 2 常用的HTML5标签
	
	## 2.1 META
	### 2.1.1 viewport
	### 2.1.2 format-detection
	### 2.1.3 apple-mobile-web-app-capable
	### 2.1.4 apple-mobile-web-app-status-bar-style

	
	## 2.2 表单元素
	### 2.2.1 search
	### 2.2.2 number
	### 2.2.3 tel
	### 2.2.4 email
	### 2.2.5 range
	### 2.2.6 url

