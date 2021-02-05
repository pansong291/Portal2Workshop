# h1 标题
## h2 标题
### h3 标题
#### h4 标题
##### h5 标题
###### h6 标题


## 水平线

___

---

***


## 文本样式

**这是粗体文本**

__This is bold text__

*这是斜体文本*

_This is italic text_

~~Strikethrough 删除线~~

> 最外层
> > 第一层嵌套
> > > 第二层嵌套

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

使用 `<b>` 可以实现 <b>加粗</b> 的效果

使用 `<i>` 可以实现 <i>斜体</i> 的效果

使用 `<em>` 表示 <em>强调</em> 的效果

`<br>` 可以在同一段落内换行<br>使用 `<sup>` 做上标如 O<sup>2-</sup>。

使用 `<sub>` 做下标如 H<sub>2</sub>O。

链接：[Github 首页](https://github.com)

图片：![alt 文字](#)

| 左对齐的列 | 右对齐的列 | 居中对齐的列 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

## 列表

无序

+ 使用 `+`, `-` 和 `*` 符号开始新行来创建列表
+ 子列表需要缩进 2 个空格
  - 标记字符的改变迫使新的列表开始：
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

有序

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa  

另一个

1. 你可以用连续的数字...
1. ...或者全部都设置为 `1.`

以某个偏移开始

57. foo
1. bar


## 代码

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences" / 代码块 "围栏"

```
Sample text here...
```

Syntax highlighting / 语法高亮

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```
