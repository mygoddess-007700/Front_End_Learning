# Lesson1
## 总结
	1. HTML只能做网页结构，大小写不区分，由浏览器执行
	2. 开发重点：表单、表格、超链接、图片、列表、iframe
	3. 用途：做项目的一个界面
## 一、 Markdown学习
1. Makedown是什么？
写软件文档用的

## 二、HTML介绍
1. What？
 叫做：超文本标记语言，由浏览器执行
2. Why？
 制作Web界面
3. Who？
 后端，前端，网页美工（UI）
4. When？
 。。。
5. Where？
用在网页上，搭建网页结构或元素
6. How？
 教程and项目
 
## 三、HTML标准
 由W3C：国际万维网组织（www.）
 
## 四、HTML表单制作
0. 表单怎么写？
```html
	<form action="receive.html">
```
1. 文本框怎么写？
```html
	<input type="text">
```
2. 密码框怎么写？
```html
	<input type="password">
```

3. 单选按钮怎么写？
```html
		<input type="radio" name="gender">男
		<input type="radio" name="gender">女
```
4. 下拉选择怎么写？
```html
	<select>
		<option>山西大同</option>
		<option>山西运城</option>
		<option>山西太原</option>
	</select>
```
5. 复选框怎么写？
```html
		爱好<input type="checkbox">玩电脑
		<input type="checkbox">打乒乓球
		<input type="checkbox">跑步
```
6. 文本域怎么写？
```html
		<textarea rows="5" cols="50">
		
		</textarea>
```
7. 文件上传怎么写？
```html
	<input type="file">
```
8. 提交按钮怎么写？
```html
	<input type="submit" value="提交">
```
9. 重置按钮怎么写？
```html
	<input type="reset" value="清空重填">
```
10. 如何跳转网页？
11. name、value和placeholder的区别
name就是给input起个名字，后台会把这个input和这个名字关联起来
value类似于初始化值的意思，例如在按钮上写字，在文本里面写东西
placehoulder和value类似，只起个提示作用

# Lesson2
## 一、注意事项
1. 网页变化、确认密码（JS）
2. 字体变红（CSS）
3. HTML语言不区分大小写
4. input是标记，type和name是属性

## 二、HTML表格
```html
	<table></table>表格标记
	<tr></tr>表格行
	<td></td>表格列
 在<table></table>里放<tr></tr>，在<tr></tr>里放<td></td>
 合并单元格使用：<td colspan="2"></td>
```

## 三、HTML超链接
1. 链接可以到自己的网站，也可以是外部网站
2. 语法
```html
	<a href=""></a>
```

## 四、HTML图片
1. 语法
```html
	<image src="" width="" height=""></image>
```

2. 图片带链接
在超链接标记<a>中放入<image src="" width="" height=""></image>

## 五、HTML列表
有序列表和无序列表
```html
	有序列表<ol></ol> 无序列表<ul></ul> 列表项<li></li>
```

## 六、标题
HTML共六级标题，从h1-h6

## 七、段落和DIV块
段落p：会自动换行
块div：会自动换行
span：不会自动换行
标签label：不会自动换行

## 八、HTML颜色
颜色表示两种：用颜色名，颜色的值：是16进制，以#开头
颜色是由3种色调配而成：RGB

## 九、字符实体
用的时候看菜鸟教程
HTML中的空格：&nbsp;

## 十、iframe框架

## 面试题：post和get有什么区别？
1. post方式提交表单，表单数据在地址栏不显示，比较安全
   get方式提交表单，数据会显示在地址栏上，不安全
2. post提交数据，数据量大小不限；get一般最大为2K
3. post比get慢 
4. post用于修改和写入数据
   get一般用于搜索排序和筛选之类的操作（淘宝，支付宝的搜索查询都是get提交），目的是资源的获取，读取数据 