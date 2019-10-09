# 进阶

### 支持 HTML 元素

不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有：`<kbd> <b> <i> <em> <sup> <sub> <br>`等 ，如：

```base
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
<b>b元素</b>
<i>i元素</i>
<em>em元素</em>
元素<sup>sup</sup>
元素<sub>sub</sub>
```

展示效果如下：

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

> <b>b元素</b>
> <i>i元素</i>
> <em>em元素</em>
> 元素<sup>sup</sup>
> 元素<sub>sub</sub>

---

## 转义

Markdown 支持使用**反斜杠+特殊字符**的形式表示转义特殊字符：

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