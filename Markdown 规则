# Markdown 规则
## CommonMark 标准
### 斜体
    *Italic斜体*  或者  _Italic斜体_

显示如下：\
*Italic斜体*

### 加粗
	**Bold加粗** 或者 __Bold加粗__
显示如下：\
**Bold加粗**
### 嵌套
	**格式*嵌套*，可多层**
显示如下：\
**格式*嵌套*，可多层**
### 转义
	显示星号\* 、显示\_
显示如下：(所有的字符都可以放在 \\ 后面转义)\
显示\*
### 标题
```
# Heading 1
## Heading 2
### Heading 3

Heading 1
=========

Heading 2
---------
```
显示如下：
# Heading 1
## Heading 2
### Heading 3

### 网址
	地址：<https://www.baidu.com>
显示如下：\
地址：https://www.baidu.com
### 链接
```
[Link](http://a.com)
或者
[Link][1]
⋮
[1]: http://b.org
```
显示如下：\
[Link](http://a.com)
### 图片
```
![Image](http://url/a.png)
或者
![Image][1]
⋮
[1]: http://url/b.jpg
```
显示如下：\
![Image](http://url/a.png)
### 引用文本
```
> Blockquote
>
> The second paragraph.
```
>Blockquote
>
>The second paragraph.
### 无序列表
```
* List
* List
* List
或者
- List
- List
- List
```
显示如下：
* List
* List
* List

### 有序列表
```
1. One
2. Two
3. Three
或者
1) One
2) Two
3) Three
```
1. One
2. Two
3. Three

### 列表嵌套
```
* Item
    1. First Subitem
    2. Second Subitem
* Item
    - Subitem
    - Subitem
```

显示如下：
* Item
    1. First Subitem
    2. Second Subitem
* Item
    - Subitem
    - Subitem

### 分割线
```
Horizontal Rule
---

Horizontal Rule
***
```
显示如下：\
Horizontal Rule
***

### 内嵌代码
用2个反引号 \` 将内嵌代码包起来
 ```
 `Inline code` with backticks
 ```
显示如下：\
`Inline code` with backticks
### 代码块
用前后两组由3个反引号 \` 组成的代码块标识，将代码包裹起来
```
    ```
    # code block
    print '3 backticks or'
    print 'indent 4 spaces'
    ```
```
或者，在每一行前面加4个空格
```
····# code block
····print '3 backticks or'
····print 'indent 4 spaces'
```
显示如下：
```
# code block
print '3 backticks or'
print 'indent 4 spaces'
```
### 段落
```
The first paragraph.

The second paragraph.
```
显示如下：\
The first paragraph.

The second paragraph.
### 换行
```
The first line\
The second line
```
The first line\
The second line

## GitHub Flavored Markdown扩展
### 删除
    ~~这是删除文本~~
显示如下：\
~~这是删除文本~~
### 锚点
    [回到第一部分](#Markdown)
显示如下：\
[回到第一部分](#Markdown)
### 高亮
代码语法高亮
```
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
\```
```
显示如下：
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
### 表格
```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | 姚明<br>易建联  |
```
显示如下：\
三行两列带表头的表格，表格内换行用HTML标签

表格	First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | 姚明<br>易建联

对齐方式，左对齐、居中对齐、右对齐

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


### 提醒
    Hey @kneath
显示如下：\
Hey @kneath
### 任务列表
```
- [x] This is a complete item
- [ ] This is an incomplete item
```
- [x] This is a complete item
- [ ] This is an incomplete item

以括号开头的例外处理
```
-[ ] \(Optional) 打开后续议题
```
显示如下：
- [x] This is a complete item
- [ ] \(Optional) 打开后续议题
