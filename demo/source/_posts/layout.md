---
title: '写作基本语法'
date: 2026-04-02 23:00:49
tags:
thumbnail: "https://evan.beee.top/img/208184324-f2640ade-587a-4f46-8ad1-7b4c1b31394f.png"
---
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

> 区块引用
>> 嵌套引用

```Javascript
console.log('hello world');
```
*斜体*，_斜体_
**粗体**，__粗体__

* 第一项 
+ 第二项 
- 第三项

{% callout [type] [fa-style] [fa-icon] [extra-classes...]::我是标题 %}
内容写这里。内容写这里。内容写这里。内容写这里。内容写这里。内容写这里。
{% endcallout %}

段落内按钮：{% button text="文档" url="/" %}

{% button text="示例博客" url="https://www.ohevan.com" icon="fa-solid fa-play-circle" size="md" %}

{% button text="开始使用" url="https://redefine-docs.ohevan.com" icon="fa-solid fa-download" size="lg" align="center" %}

{% button text="新标签页打开" url="https://redefine.ohevan.com" target="_blank" %}

{% grid cols=3 gap=1rem class="my-grid" %}
...内容...
{% endgrid %}


{% folding title="Folding 折叠模块点击展开" class="green" %}

这里可以放普通文字，也可以嵌套其他模块。

{% callout type="danger" %}
danger 提示块标签
{% endcallout %}

{% callout type="info" %}
info 提示块标签
{% endcallout %}

{% endfolding %}

{% tabs %}

<!-- tab 分栏一 -->

分栏一内容

<!-- tab 分栏二 -->

分栏二内容

{% endtabs %}


