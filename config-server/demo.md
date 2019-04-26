语法指南
以下是Markdown语法的概述，您可以在GitHub.com或您自己的文本文件中的任何位置使用它。

头
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
重点
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
清单
无序
* Item 1
* Item 2
  * Item 2a
  * Item 2b
有序
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
图片
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
链接
http://github.com - automatic!
[GitHub](http://github.com)
引用文字
As Kanye West said:

> We're living the future so
> the present is our past.
内联代码
I think you should use an
`<addr>` element here instead.

GitHub调味降价
GitHub.com使用自己版本的Markdown语法，该语法提供了一组额外的有用功能，其中许多功能可以更轻松地使用GitHub.com上的内容。

请注意，GitHub Flavored Markdown的某些功能仅在“问题和请求”的说明和注释中提供。这些包括@mentions以及对SHA-1哈希，问题和请求的引用。任务列表也可以在Gist注释和Gist Markdown文件中找到。

语法突出显示
以下是如何使用GitHub Flavored Markdown进行语法高亮显示的示例：

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
您还可以简单地将代码缩进四个空格：

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
以下是没有语法突出显示的Python代码示例：

def foo():
    if not bar:
        return True
任务列表
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
如果您在问题的第一条评论中包含任务列表，您将在问题列表中获得一个方便的进度指示器。它也适用于Pull Requests！

表
您可以通过组合单词列表​​并用连字符-（对于第一行）分隔它们，然后用管道分隔每个列来创建表格|：

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
会成为：

第一个标题	第二个标题
来自单元格1的内容	来自单元格2的内容
第一列中的内容	第二列中的内容
SHA引用
对提交的SHA-1哈希的任何引用都将自动转换为GitHub上该提交的链接。

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
在存储库中发出引用
任何引用Issue或Pull Request的数字都将自动转换为链接。

#1
mojombo#1
mojombo/github-flavored-markdown#1
用户名@mentions
键入@符号，后跟用户名，将通知该人来查看评论。这被称为“@mention”，因为你提到的是个人。您还可以在组织内@mention团队。

自动链接URL
任何URL（如http://www.github.com/）都将自动转换为可点击的链接。

删除线
任何包含两个波浪形（如~~this~~）的单词都会显示为划掉。

表情符号
GitHub支持表情符号！

要查看我们支持的每张图片的列表，请查看表情符号备忘单。