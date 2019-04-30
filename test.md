# 标题

## This is an H2

###### This is an H6



# 区块



> This is a blockquote with two paragraphs. This is first paragraph.
>
> This is second pragraph. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.



> This is another blockquote with one paragraph. There is three empty line to seperate two blockquote.



# 列表



## un-ordered list
*   Red
*   Green
*   Blue

## ordered list
1.  Red
2. 	Green
3.	Blue



# 任务



- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed



# 代码块

Here's an example:

```
function test() {
console.log("notice the blank line before this function?");
}
```

syntax highlighting:
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```



# 数学


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$




# 表格

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |



| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ | :-------------: | ------------: |
| col 3 is      | some wordy text |         $1600 |
| col 2 is      |    centered     |           $12 |
| zebra stripes |    are neat     |            $1 |





# 标注



You can create footnotes like this[^footnote].

[^footnote]: Here is the **text** of the ***\*footnote\****.





# 目录

[TOC]

# 分割线

***

---



# 连接

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.





# 内部连接



This is [an example][id] reference-style link.

Then, anywhere in the document, you define your link label on a line by itself like this:

[id]: http://example.com/  "Optional Title Here"





[Google][]
And then define the link:

[Google]: http://google.com/





# 网址

Typora允许您将URL作为链接插入，用`<`括号括起来`>`。

`<i@typora.io>`成为[i@typora.io](mailto:i@typora.io)。

Typora还会自动链接标准网址。例如：www.google.com。



# 图片

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg"Optional title")



# 重点

**single asterisks**

*_single underscores_*



\*this text is surrounded by literal asterisks\*



***\*double asterisks\****

**__double underscores__**



# 代码



Use the `printf()` function.



# 删除线

`~~Mistaken text.~~` 变 ~~错误的文字。~~



# 下划线

`<u>Underline</u>`成为下划线。



# 嵌入网页



```Markdown
<iframe height='265' scrolling='no' title='Fancy Animated SVG Menu' src='http://codepen.io/jeangontijo/embed/OxVywj/?height=265&theme-id=0&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'></iframe>
```



# 视频

```Markdown
<video src="xxx.mp4" />
```



# HTML

http://support.typora.io/HTML/

