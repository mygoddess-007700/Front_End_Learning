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
## 三、任务：个人社保计算软件界面
	为JS提供帮助，后面要写JS代码实现计算过程
	
# lesson6
## 一、JavaScript的作用
非常重要：前端、大数据、爬虫都需要掌握

## 二、不同的编程语言的应用场景（领域）
1. C语言
面向过程的。主要用于：智能硬件设备上的软件开发（嵌入式）、操作系统底层开发、算法等。
安卓手机的底层、Windows的底层也是用C开发的。偏底层应用。
2. C++语言
面向对象的。主要用于：图形界面软件开发（美图秀秀、PS、酷狗音乐等）、通信软件（QQ、钉钉）、算法
游戏（虚幻4）、控制软件（带有图形界面的控制软件）、STM32开发（嵌入式）
3. Java语言
面向对象的。主要用于：基于B/S结构的大型管理系统开发（12306、教务系统、四六级教务系统）
大数据开发（Hadoop）、安卓手机应用开发、智能电子设备软件开发（数字电视机顶盒）
4. Python语言
 Python2和Python3。胶水语言，什么都能干。主要用于：
 信息安全编程、爬虫、大数据分析、AI等。
5. JavaScript语言
面向对象的，脚本语言，运行在浏览器上。主要：
网页上的动态效果、网页和用户的交互
- 编程语言需要根据应用场景，选择不同的语言
- 公司里是精细化分工

## 三、JavaScript是什么？
脚本语言，运行在浏览器中，也就是运行在客户机中。各种浏览器都能执行JS，
但是不同的浏览器对JS的支持程度不尽相同。要进行浏览器的兼容性测试
JavaScript不是W3C的标准，由欧洲计算机制造商协会创立。
HTML、CSS、JavaScript都是由浏览器执行的

## 四、上网的过程，前端代码的执行过程
1. B/S结构：Browser/Server，浏览器/服务器结构。如：教务系统，有浏览器就能用
2. C/S结构：Client/Server，客户机/服务器结构。如：QQ，需要在自己电脑上安装客户端的
3. 单机软件：如：Word，在自己电脑上安，只能自己用。
4. 上网过程分析：上12306官网为例
- 输入网址，敲下回车：浏览器向12306的服务器发出请求
- 响应：服务器收到浏览器请求后，服务器会把保存在服务器上的网页源码发回给浏览器
- 浏览器在收到源码后，对源码执行，产生最终的执行效果

## 五、JavaScript学习方法
1. JS调试比较麻烦：JS程序的调试要利用Chrome或Firefox的控制台
2. 细心

## 六、Chrome调试（Chrome的控制台Console）
1. F12（有可能需要同时按下Fn+F12）
2. Ctrl + Shift + I
3. 打开控制台后，调试JS用Console；调试显示效果等：用Elements

## 七、JavaScript学习重点
1. 语法
2. 函数
3. 事件
4. 正则表达式和表单验证
5. DOM

## 八、JS输出
1. alert()
2. console.log()
- 补充：JS代码放在什么地方？
1. 网页内部：单独的.js文件内
2. title后的script里面
- JS输出便于调试代码

## 九、JS语法
1. JS是弱类型语言（没有类型）
2. JS中变量定义可以用var也可不用
3. JS语言严格区分大小写（和C语言一样）
4. 语句结尾分号可写可不写
5. JS函数用function，有函数名，函数形参，函数体，
 没有返回类型（因为JS是弱类型语言）
 
# lesson7
## 一、JS表单验证
 一般要使用正则表达式、JS函数、DOM
 在存款验证
 
# lesson8
## 任务：开发管理系统项目模型（界面）

# lessom9
## 总结：
 1. HTML表单（文本框、下拉列表、单选按钮、按钮）
 2. HTML表格
 3. HTML图片
 4. HTML超链接
 5. CSS选择器（id、class）
