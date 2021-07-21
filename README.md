# Lesson1
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