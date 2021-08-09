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
   
# Lesson3
## 一、CSS是什么？
1. 层叠式样式表，简称为样式。（Cascading Style Sheets）
2. 由W3C组织制定的标准，最新版CSS3
3. CSS由浏览器执行
4. 作用：美化网页

## 二、CSS选择器
1. 标记选择器
2. id选择器
3. class选择器
注：重要！

## 三、CSS代码放置的位置
1. 页内样式：放在head之间，用style标记
2. 行内样式：放在style属性里，行内样式优先级最高
3. 外部样式：放在独立的.css文件中，在网页上用link标记引入

## 四、开发常用样式
1. 背景颜色（background-color）
2. 文本样式（color\text-align\text-decoration）
3. 字体样式（font-family\font-size）
 网页上的文字默认是16px；在工程上，网页上的文字一般是12px或14px
4. 链接样式（a:hover）
5. 表格样式（细线表格border-collapse:collapse）
6. 边框样式（边框变红border: 1px solid red）

## 五、CSS盒子模型
1. 与网页布局密切相关
2. 重要：外边距margin、内边距padding；内外边距是相对的，有四个方向

## 六、登录网页
1. 用到了盒子模型（内部外部边距等）
2. HTML表单元素（用户名，密码，登录按钮）

# lesson4
## lesson3简单总结：
1. CSS选择器（标记、id、class）
2. CSS代码放的位置
3. 边框样式（文本框变红）
4. 怎么样把自己做的网页让别人通过网址访问
	第一步：开发自己的网页
	第二步：购买Linux系统（阿里云主机），获得一个IP地址
	第三步：把自己做好的网页，远程上传到阿里云主机（此时就可以通过IP访问了）
	第四步：域名注册，备案，通过阿里云把域名和IP做绑定
	
## 一、CSS显示
1. display：隐藏后，释放区域
2. visibility：隐藏了，但区域不释放（好像不能隐藏块里面的内容）

## 二、CSS浮动
1. 主要用于：网页布局（CSS+div）
2. CSS+DIV做网页布局离不开浮动

## 三、Bootstrap技术
### 1. Bootstrap介绍
- Twitter公司发明的技术
- 用Bootstrap做的网页，能够自动适应屏幕大小（自适应、响应式）
- 移动端优先（Bootstrap伴随着智能手机而来）
- Bootstrap技术是基于：HTML、CSS、JavaScript
- Bootstrap本质：写好的CSS样式库（拿来就用）
- Bootstrap不是一种编程语言，是一种技术

### 2. Bootstrap如何来用
- 把Bootstrap文件从官网下载下来，复制到自己的项目里
- 直接使用CDN（内容发放网络，其实就是：放在公网上的文件）
	如果使用CDN方式，必须有网，否则不能用

### 3. 如何学Bootstrap
看官方文档

### 4. Bootstrap工作原理
- 网格系统（屏幕分成12列，使用者可以按自己的需要组合列）
- 使用Bootstrap后，CSS样式就不用自己写了，直接用即可

### 5. 如何在github上搭建静态网站
- 注册github账号
- 创建一个项目
- 把写好的网页上传到项目里
- 在设置中找到pages，点击main，点save

# lesson5
## lesson4反思
- 如果要使用Bootstrap样式，建议所有的地方都用Bootstrap样式
- Bootstrap追求的是自适应，不太讲究美观

## 一、Bootstrap表格
## 二、任务：个人存款计算器软件界面
