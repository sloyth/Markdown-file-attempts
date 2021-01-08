`# 一级标题`

# 标题

`## 二级标题`

## 二级标题

以此类推

---

# 字体

`*斜体*`

*斜体*

`**粗体**`

**粗体**

`***粗体***`

***粗斜体***

---

`---`

分隔线

---

`~~删除线~~`

~~删除线~~

`<u>下划线</u>`

<u>下划线</u>

`[^脚注]：内容`

脚注[^A]

[^A]:示范脚注

---

# 列表

```无序列表
* 列表项一
* 列表项二
* 列表项三

- 列表项一
- 列表项二
- 列表项三

+ 列表项一
+ 列表项二
+ 列表项三
```

* 列表项一
* 列表项二
* 列表项三

---

```有序列表
1. 列表项一
2. 列表项一
3. 列表项一
```

1. 列表项一
2. 列表项一
3. 列表项一  

---

```列表嵌套
1. 列表项一
	* 列表项一
	* 列表项二
2. 列表项一
	* 列表项一
	* 列表项二
```

1. 列表项一
  * 列表项一

  * 列表项二
2. 列表项一
  * 列表项一

  * 列表项二

---

# 区块

```区块
> 区块（引用）
>> 区块可嵌套
```

> 区块（引用）
>
> > 区块可嵌套[^1]

---

# 代码

```代码
`code`
```

`code`

```代码块
​```这里是代码名称
这里是代码具体内容
可以换行
​```
```

```这里是代码名称
这里是代码具体内容
可以换行
```

---

#  网址链接

```链接
[链接名称](链接地址)
<链接地址>
```

[谷歌](www.baidu.com)[^2]

<https://www.baidu.com>

---

```网址变量
设置变量A：[Google][A]
设置变量B：[Baidu][B]

为变量赋值
[A]:https://www.baidu.com
[B]:https://www.google.com
```

设置变量A：[Google][A]
设置变量B：[Baidu][B]

---

#  图片

```图片
![alt 属性文本]（图片地址）
[![smJscF.jpg](https://s3.ax1x.com/2021/01/08/sKK3WD.jpg)](https://imgchr.com/i/sKK3WD)

不同格式：
![派蒙](https://s3.ax1x.com/2021/01/08/sKK3WD.jpg)

![派蒙][C] /通过定义网址变量/
```

[![smJscF.jpg](https://s3.ax1x.com/2021/01/08/sKK3WD.jpg)](https://imgchr.com/i/smJscF "这是一个派蒙")

Markdown暂时指定图片的大小，如果想指定大小，那就用`<img>`吧！

<img src="https://s3.ax1x.com/2021/01/08/sKK3WD.jpg" width="20%" height="20%">

---

# 表格

```表格
|表头（左对齐）|表头（居中）|表头（右对齐）|
|:-|:-------:|---------------------:|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
```

| 表头（左对齐） | 表头（居中） | 表头（右对齐） |
| :------------- | :----------: | -------------: |
| 单元格         |    单元格    |         单元格 |
| 单元格         |    单元格    |         单元格 |

---

# 折叠

```折叠
<details>
<summary>这是折叠标题</summary>
<pre>	这是折叠内容</pre>
</details>
```

<details>
<summary>这是折叠标题</summary>
<pre>	这是折叠内容</pre>
</details>

---

# 其它

Markdown支持部分html元素

```html
<kbd> <b> <i> <em> <sup> <sub> <br>
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
```

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

---

显示部分字符需要使用转义字符`/`

```
\   反斜线
`   反引号
*   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
#   井字号
+   加号
-   减号
.   英文句点
!   感叹号
```

---

Markdown支持在文中插入LaTeX格式的数学公式

```
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${Step1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
```

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${Step1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$

好吧[^3],这就是这个文档的全部了

-----

# 附录

[^1]:区块内可使用列表，列表中也可使用区块，区块中使用列表时需要在前面打四个空格或者一个制表符
[^2]:好吧，考虑到谷歌不一定打得开，我选择百度
[^3]:这个公式是我从隔壁Runoob抄的

[A]:https://www.baidu.com
[B]:https://www.google.com
[C]:https://s3.ax1x.com/2021/01/08/sKK3WD.jpg

