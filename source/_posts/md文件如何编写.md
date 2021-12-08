---
title: md文件如何编写
date: 2021-04-28 14:30:52
tags: [编程,博客,学习]
---
# 一、标签插件
## 1、引用块（quote）

``` bash
{% blockquote [author[, source]] [link] [source_link_title] %}
content
{% endblockquote %}
```

### 引用书上的句子

``` bash
{% blockquote 唐代 韩愈 , 古今贤文·劝学篇 %}
书山有路勤为径，学海无涯苦作舟。
{% endblockquote %}
```

{% blockquote 唐代 韩愈 , 古今贤文·劝学篇 %}
书山有路勤为径，学海无涯苦作舟。
{% endblockquote %}

### 引用网络上的文章

``` bash
{% blockquote 半虹  https://blog.csdn.net/wsmrzx/article/details/81478945 %}
Hexo系列(五) 撰写文章。
{% endblockquote %}
```

{% blockquote 半虹  https://blog.csdn.net/wsmrzx/article/details/81478945 %}
Hexo系列(五) 撰写文章。https://blog.csdn.net/wsmrzx/article/details/81478945
{% endblockquote %}

## 代码块（code）

``` bash
{% codeblock [title] [lang:language] [url] [link text] [additional options] %}
code snippet
{% endcodeblock %}
```

### 普通的代码块

``` bash
{% codeblock %}
alert('Hello World!');
{% endcodeblock %}
```

{% codeblock %}
alert('Hello World!');
{% endcodeblock %}

### 指定语言

``` bash
{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}
```

{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}



