# 链接及图片

---

## 链接

markdown有两种方式使用链接。

```base
[链接名称](链接地址)

或者

<链接地址>
```

代码如下：

```
[百度一下](www.baidu.com)

或者直接使用链接地址

<www.baidu.com>
```

展示效果如下：

> [ 百度一下](www.baidu.com)
> <www.baidu.com>

也可以使用html语言的a标签代替。

```xml
<a href="https://baidu.com" target="_blank">baidu</a>
```

---

## 变量链接

链接也可以用变量来代替，文档末尾附带变量地址：

```
这个链接用 1 作为网址变量 [Baidu][1]

在文档的结尾为变量赋值（网址）
[1]: http://www.baidu.com/
  
```

展示效果如下：

这个链接用 1 作为网址变量 [Baidu][1]

[1]: http://www.baidu.com/

---

## 图片

Markdown 图片语法格式如下：

```base
![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")
```

```
![点赞图标](.\img\likered.png)

![点赞图标](.\img\likered.png "赞")
```

正常图片：  

![点赞图标](.\img\likered.png)

有title属性的图片：  

![点赞图标](.\img\likered.png "赞")

Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 `<img>` 标签。

```
<img src=".\img\likered.png" width="10%">
```

