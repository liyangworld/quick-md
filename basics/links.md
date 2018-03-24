# 链接和图片

#### 1\.链接

```markdown
[百度](http://www.baidu.com)
[百度](http://www.baidu.com "鼠标悬浮时显示的文字")
```

解释为：

```markdown
<a href="http://www.baidu.com">百度</a>
<a href="http://www.baidu.com" title="鼠标悬浮时显示的文字">百度</a>
```

注：如果链接的地址和名字重复，可以用尖括号语法将其简化。以下三个等价：

```markdown
<http://www.baidu.com>
[http://www.baidu.com](http://www.baidu.com)
[http://www.baidu.com]()
```

#### 2\.图片

```markdown
![加载失败显示的文字](/path/to/img.jpg)
![加载失败显示的文字](/path/to/img.jpg "鼠标悬浮时显示的文字")
```

解释为：

```markdown
<img src="/path/to/img.jpg" alt="加载失败显示的文字" />
<img src="/path/to/img.jpg" alt="加载失败显示的文字" title="鼠标悬浮时显示的文字" />
```

