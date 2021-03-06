# Markdown 学习笔记


## 为什么使用 Markdown? 

- 纯文本. 极高的可读性. 可以用任何文本编辑器打开.
- 让你专注于内容而不是格式
- 轻松转换为html，电子书等各种格式
- 很高的可读性

</br>

## 标题

在 Markdown 中，有两种定义标题的格式

**1. Atx 格式**

    # 标题一
# 标题一
    ## 标题二
## 标题二
    ### 标题三
### 标题三
    #### 标题四
#### 标题四
    ##### 标题五
##### 标题五
    ###### 标题六
###### 标题六

</br>

**2. Setext 格式**

    标题一
    =======
标题一
=======

    标题二
    --------
标题二
--------

</br>

## 引用
**要建立区块引用时，在每一句前加上 >。**

	> 这是一段引用. 无意义凑字数的文字。
	> 无意义凑字数的文字。
	> 无意义凑字数的文字。无意义凑字数的文字。
	> 
	> 无意义凑字数的文字。无意义凑字数的文字。
	> 无意义凑字数的文字。

> 这是一段引用. 无意义凑字数的文字。
> 无意义凑字数的文字。
> 无意义凑字数的文字。无意义凑字数的文字。
> 
> 无意义凑字数的文字。无意义凑字数的文字。
> 无意义凑字数的文字。

</br>

**也可以只在段落前加上 >**

	> 这是一段包含两个段落的引用。 无意义凑字数的文字。无意义凑字数的文字。无	意义凑字数的文字。

	> 第二段。无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。无意	义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。

> 这是一段包含两个段落的引用。 无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。

> 第二段。无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。无意义凑字数的文字。

</br>

**引用可以嵌套使用.**

	> 这是第一层引用
	>
	> > 这是第二层引用
	>
	> 这又是第一层引用
	> 

> 这是第一层引用
>
> > 这是第二层引用
>
> 这又是第一层引用
> 

</br>

**你可以在引用的文段中使用其他Markdown语法.**

	> ### 这是一个标题
	> 
	> 1.   这是一个列表的第一行
	> 2.   这是这个列表的第二行
	> 
	> 代码:
	> 
	>     return hellow world！

> ### 这是一个标题
> 
> 1.   这是一个列表的第一行
> 2.   这是这个列表的第二行
> 
> 代码:
> 
>     return hellow world！

</br>

## 列表

	 * 红
	 * 蓝
	 * 黄
 * 红
 * 蓝
 * 黄

***

	 + 红	
	 + 蓝
	 + 黄
 + 红	
 + 蓝
 + 黄

***

	 1. 红
	 2. 蓝
	 3. 黄
 1. 红
 2. 蓝
 3. 黄

</br>

## 代码区块
要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，例如，下面的输入：

*(4 spaces or 1 tab)* Str = "hellow world!"</br>
*(4 spaces or 1 tab)* return Str

	Str = "hellow world!"
	return Str

</br>

## 分隔线

    * * *
 
 * * *

</br>

    ***
 
***

</br>

    *****
 
 *****

</br>

    - - -
 
 - - -

</br>

    ---------------------------------------
 
 ---------------------------------------


</br>

## 链接

**行内式链接**

    这是一个[行内式链接](http://example.com/ "Title") .

这是一个[行内式链接](http://example.com/ "Title") .

    这是[另一个行内式链接](http://another_example.com/ "Title") .

这是[另一个行内式链接](http://another_example.com/ "Title") .

</br>

**引用式链接**

	这是一个[引用式链接][id].

	[id]: http://example.com/


这是一个[引用式链接][id].

[id]: http://example.com/





</br></br></br></br>

##### 引用: 
1. [http://wow.kuapp.com/markdown/#header][r1]
2. [https://daringfireball.net/projects/markdown/syntax#p][r2]

[r1]:http://wow.kuapp.com/markdown/#header
[r2]:https://daringfireball.net/projects/markdown/syntax#p
