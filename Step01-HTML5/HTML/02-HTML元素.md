HTML元素
===========

## 知识点

* 标题
* 段落
* 链接
* 图像

###标题
HTML 标题(Heading) 通过标签 h1--h6定义的
**使用例**

html4:
~~~html
    <h1>这是一个标题</h1>
    <h2>这是一个标题</h2>
    <h3>这是一个标题</h3> 
    在HTML4.01中 <h1>--</h6>的align属性已废弃 HTML中align属性不再支持使用css排列元素
~~~
设置标题排列方式
~~~
<h1 style="text-align:center">This is heading 1</h1>
<h2 style="text-align:left">This is heading 2</h2>
<h3 style="text-align:right">This is heading 3</h3>
<h4 style="text-align:justify">This is heading 4</h4>

~~~
###段落p
HTML中采用标签p来定义段落

**使用例**

~~~html
    <p>这是一个段落</p>
    <p>这是另一个段落</p>
~~~
###超链接a
~~~html
   <a href="http://www.baidu.com">这是一个链接</a>
~~~
###图像
图像标签img
~~~html
    <img src="" width="120" height="142"></img>
~~~
###HTML Element Syntax
HTML元素以开始标签起始,以结束标签终止,元素的内容是在开始标签与结束标签之间,某些HTML元素具有空内容,大多数HTML元素具有属性。
HTML元素可以嵌套,
###HTML元素属性
大多数HTML元素具有属性 class、id、style、title

class 为html元素定义一个或多个类名(classname)
id定义元素的唯一ID
style规定元素的行内样式
title描述元素的额外信息

###HTML标题
使用title属性描述网页标题
###HTML水平线
hr元素可以用于分隔内容
~~~html
<p>段落一</p>
<hr>
<p>段落二</p>
<hr>
~~~
###HTML注释
可以将注释插入HTML代码中,浏览器会忽略注释,也不会显示它们
~~~html
<!-- 用于注释HTML网页-->
~~~