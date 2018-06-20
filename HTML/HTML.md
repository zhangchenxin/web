# HTML概述

## 1.什么是HTML
- HTML是用来描述网页的语言

>- 超文本标记语言是一种用于创建网页的标准标记语言
>- HTML是一种标记语言,不是编程语言
>- 标记语言是一套标记标签(markup tag)
>- HTML文档包含HTML标签和文本内容
>- HTML文档也叫web页面

## 2.HTML是用来干嘛的?

- 可以使用HTML来建立自己的web站点,由浏览器来解析

## 3.建立一个HTML文件
- 可以再编译器中创建
- 可以直接新建一个文本文档,之后将后缀改为.html或者.htm

## 4.HTML的注释
- 注释是用来解释代码,是用来给人看的
- \<!--注释-->

## 5.HTML网页的基本结构
- \<!DOCTYPE html> :声明为HTML文档
- \<html>: 元素是HTML页面的根元素
- \<head>: 元素包括了文档的元数据
- \<body>: 元素包括了可见页面内容
## 6. HTML标签结构
HTML标签通常被叫做 : HTML标签(HTML tag)
- HTML标签是由尖括号包围的关键词
- HTML标签通常是成对出现的
- 标签中第一个标签是开始标签,第二个标签是结束标签

      <开始标签>内容</结束内容>

- 标签一般用小写字母
## 7.HTML元素
"HTML标签"和"HTML元素"通常是描述的同样的意思.一个HTML元素包含了开始标签和结束标签

## 8.HTML属性
- HTML元素可以设置属性,HTML属性一定要加双引号
- 属性一般设置在开始标签当中
- 属性一般以名称加值来组成

# 常用HTML标签

## HTML常用的有意义块级标签
- HTML块级标签一般独占一行
- 常用的有语义的块级标签,是有格式的
- \<h1></h1>: 这个表示的是一级标题,HTML中有六级标题
- \<p></p>: 段落标签
- \<br></br>: 强制换行
- 列表
   - 无序列表
   
      
      <ul>
      <li>列表项1</li>
      <li>列表项2</li>
      <li>列表项3</li>
      </ul>
         
   - 有序列表,有属性,type可以改变标识符类型,start设置列表项从第几项开始        
   
        
        <ol>
        <li>这是有序列表1</li>
        <li>这是有序列表2</li>
        </ol>
     
   - 自定义列表
   
   
        <dl>
        <dt>这是自定义列表</dt>
        <dd>这是自定义列表</dd>
        </dl>
   
- 表格: 

   
    <table>                         
    <tr>                        
          <td>这是第一行第一列</td>       
          <td>这是第二行第二列</td>       
    </tr>                       
    <tr>                        
        <td>这是第二行第一列</td>       
        <td>这是第二行第二列</td>       
    </tr>                       
    </table>                        

    
- 表格的属性:
   - border: 边框
   - cellpadding: 内容离表框的距离
   - cellspacing: 单元格和单元格之间的距离
   - rowspan: 垂直合并
   - coispan: 水平合并
   - anglin: 内容水平对齐方式
   - valign: 内容垂直对齐方式
   - width: 设置单元格总体宽度
   - high: 设置单元格总体高度
   - colspan: 表头(不是属性,是一个标签),默认水平居中,将字体加粗.
## HTML常用的无意义的块级标签(没有默认的语义,独占一行)
- \<hr>:多了一道下划线(分界线)
- \<div></div>
    - 一般用来划分一块区域,配合css来使用.
    - 文档布局,取代使用表格布局的老式方法.
# HTML常用的行级元素
行级元素不独占一行

## 有语义的行级元素
### HTML链接标签 
- HTML链接 a标签


    <a href="链接,要跳转的网址">网站描述</a>
    
- 跳转到本地的文件
   - 在实际开发当中建议使用相对路径, ./ 为当前目录  ../上目录
   
   
    <a href="./02.html">上节课的内容</a>
- 标签属性:
   - href属性:后跟要跳转的链接
   - target :_blank 属性: 在新窗口打开要跳转的页面 
   - html锚点: <a href="https://www.cnblogs.com/mfmdaoyou/p/7105358.html">锚点的一些说明</a>

### HTML图像标签
- HTML格式

    
    <img src="http://imgsrc.baidu.com/forum/w%3D580/sign=1540629246c2d562f208d0e5d71
    090f3/6e52224e251f95ca7db05e44c0177f3e66095250.jpg" 
    width="500px"  alt="这是图片标签" title="这是我老婆">
- HTML属性
   - src: 图片的地址(网络资源或者本地资源)\
   - alt: 用于图片加载失败后的替代文字
   - title: 当鼠标放在图片上时显示的文字
   - width: 设置图片的宽度
   - height:  设置图片的高度
   - 注意: 我们一般只对高度或宽度设置,如果全部设置的话,会导致图片拉长
   
### HTML文档标签
- 文本标签
   - 加粗
    
    
    <b>我也不知道写什么,但我想让这句话加粗</b><br>
    <strong>这句话也是加粗,但有强调意义</strong><br>
   - 斜体


    <i>我也不知道写什么,但我想让这句话斜体</i><br>
    <em>这句话也是斜体,但是它也有强调意义</em><br>
## 无语义的行级标签
- \<span>\</span>
    - 一般是配合css来使用,用来设置一些文本格式


     <span style="color: deepskyblue">  我想让这句话变为蓝色</span>

## HTML的当中的实体字符
- &gt; : 大于号
- &lt: 小于号
- 还有很多 <a href="http://www.w3school.com.cn/html/html_entities.asp">全部的实体字符</a>

## 表单列表
表单是一个包含表单元素的区域,通过from来定义表单区域
>通过type属性定义不同类型的表单控件

- 表单控件
   - 必须要有name属性
   - type: 指定我们的表单类型(普通文本,密码框,单选框, 多选框)
   - radio: 表示的是单选框,name的值必须相同,必须有name和value
   - checkbox: 表示的是多选框,必须有name和value且name的值必须相同
   - select: 下拉选项框,必须有那么和valu,必须配合option使用
   - file: 一般用于文件上传
   - textarea; 用于输入说明
   - submit: 按钮,用于提交等
   - \<input type="reset">: 重置
   - hidden: 隐藏域,不需要用户去填写或查看
- 表单的属性
   - action :提交地址
   - method: 提交方式 get post
   - entype: 指定属性值为 multipart/form-data 用于进行文件转码
   - name: 表单名项,用于储存内容值
   - value: 输入的值
   - disabled: 禁用
   - readonly: 只读
   - placeholder: 提示
- 表单提交默认是以get形式进行数据的提交
- get: 通过URL地址传输数据,数据会显示在URL地址栏当中,所以传输数据大小有限制根据浏览器的不同
数据大小不同,相对来说不安全
- post: 没有大小限制,比较安全












