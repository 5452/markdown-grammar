**Markdown** 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。  
#语法示例
##1. 图片
`![Foo](http://www.baidu.com/aaa.png)` 将生成类似html的效果：`<img src="http://www.baidu.com/aaa.png" alt="Foo">` 效果如下：  
![测试图片](http://b.hiphotos.baidu.com/image/pic/item/55e736d12f2eb938aa921ffcd7628535e4dd6fc4.jpg)  
##2. 换行
在文本中输入的换行会从最终生成的结果中删除，浏览器会根据可用空间自动换行。如果想强迫换行，可以在行尾插入至少两个空格。  
##3. 强调  
`*强调* 或者 _强调_`  示例 *斜体*  
`**加重强调** 或者 __加重强调__` (示例 **粗体**)  
`***特别强调*** 或者 ___特别强调___` (示例 ***粗斜体***)   
##4. 代码  
要在Markdown中插入代码，你有两种选择。 一种是把代码用反引号(\`)(键盘上Esc键下面的键)包起，例如：夹杂着`一些代码`的文字内容  
又或者以制表符或至少四个空格缩进的行，例如  
    `第一行代码`  
    `第二行代码`  
    `第三行代码`  
后面一种用法会让Markdown保留所有的空白字符——而与之相反，一般情况下，Markdown会删除所有换行和空格，打乱原有的缩进和排版。  
##5.标题  
可以在标题内容前输入特定数量的井号('#')来实现对应级别的HTML样式的标题(HTML提供六级标题)。例如：  

`# 一级标题`  
# 一级标题
`#### 四级标题`  
#### 四级标题
一级和二级标题还有一种写法：

`一级标题`  
`===================`  

一级标题
===================

`二级标题`  
`--------------------`
二级标题
--------------------
##6.列表
###无序列表
* 无序(没有编号的)列表中的一项
    * 一个子项，要以一个制表符或者4个空格缩进
* 无序列表中的另一个项
###有序列表
1. 有序(排好序，有编号的)列表中的一项
    - 1.1 一个子项,与起始处保持1个空格缩进
2. 有序列表中的另一个项  

##7.换行
如果你真的想在Markdown中插入换行标签`<br/>`，你可以在行尾输入两个或以上的空格，然后回车。 这样插入换行十分麻烦，但是“每个换行都转换为`<br/>`”在 Markdown中并不合适，所以只在你确定你需要时手动添加。
##8.引用
引用只需要在被引用的内容段落开头加上右尖括号('>')即可。你可以选择只在开头加一个。也可以在每行前面都加一个，效果是一样的。  
> 这一整段的内容都会作为一个HTML的引用元素。引用元素是会自动优化排版的（reflowable，可回流）。你可以任意地将引用的内容包含进来，然后所有这些都会被解析成为单独一个引用元素。  

引用可以嵌套。如果要在一个引用里插入一个引用，可以用两个('>')开头。依此类推，根据嵌套层次加相应数量的符号。  
> 这是一个引用。这是第一行  
这是第二行。
>> 这是一个嵌套的引用。这是第一行。  
这是第二行
> 
> 外层引用的第三行。前面需要一个视觉上的空行表示内层嵌套的结束，空行前面的('>')可以有可以没有。  

##9.链接
链接可以在行内插入：  
`[链接文字](链接地址)`  
例子： [Markdown](http://zh.wikipedia.com/wiki/Markdown)  
##10.水平分割线
要生成水平分割线，可以在单独一行里输入3个或以上的短横线、星号或者下划线实现。短横线和星号之间可以输入任意空格。以下每一行都产生一条水平分割线。  
* * *  
***  
*****  
- - -  
---------------------------------------  

