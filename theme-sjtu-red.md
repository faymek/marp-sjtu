---
marp: true
size: 4:3
paginate: true
theme: gaia
backgroundImage: url('bg.png')
style: |
  section {
    color: black;
    padding: 91px 53px;
  }
  section.first h1 {
    text-align: center;
    font-size: 1.4em;
    font-weight: bold;
    padding: 355px 10px 10px 10px;
    color: white;
  }
  section.first p {
    text-align: center;
    font-size: 0.9em;
    color: white;
    margin: 20px 0 0 0;
    padding: 5px 0px 0px 5px;
  }
  section.second h1 {
    font-size: 1.4em;
    font-weight: normal;
    padding: 355px 10px 10px 10px;
    color: white;
  }
  section.second p {
    font-size: 0.9em;
    color: white;
    margin: 20px 0 0 0;
    padding: 5px 0px 0px 5px;
  }
  section::after {
    content: 'Page. ' attr(data-marpit-pagination);
    color: white;
    position: absolute;
    top: 12px;
    left: 820px;
    font-size: 0.5em;
  }
  h1 {
    font-size: 1.5em;
    color: #c8161e;
  }
  h2 {
    padding: 0px 0px 32px 0px;
    font-size: 1.2em;
    color: #c8161e;
  }
  p,ul,ol {
    font-size: 0.6em;
  }
  code, blockquote {
    font-size: 1em;
  }
  pre {
    font-size: 0.8em;
  }
  ul {
    list-style: none; /* Remove default bullets */
  }
  ul li::before {
    content: "\25aa";
    color: #c8161e;
    display: inline-block;
    width: 1.2em;
    margin-left: -2em;
  }
  ol {
    list-style: none;
    counter-reset: my-awesome-counter;
  }
  ol li {
    counter-increment: my-awesome-counter;
  }
  ol li::before {
    content: counter(my-awesome-counter) ". ";
    color: #c8161e;
    display: inline-block;
    width: 1.2em;
    margin-left: -2em;
  }
  p img {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

---

<!--
_paginate: false
_class: first
-->

![bg](bg-lead.png)

# 上海交通大学PPT模板

主讲人姓名

2019年11月

---
<!--
_paginate: false
_class: second
-->

![bg](bg-lead.png)

# 标题页第二版以及应用实例

主讲人姓名

2019年11月



---

## 急急流年，滔滔逝水

**波斯***诗人*`峨谟伽耶姆`的四行诗恰好说出了我们的感受：

> Into the Universe, and why not knowing, 
> Nor Whence, like water willy-nilly flowing: 
> And out of it, as wind along the waste, 
> I know not weither willy-nilly blowing.


- 来如流水兮逝如风，不知何处来兮何所终！

1. 到头这一身，难逃那一日。受用了一朝，一朝便宜。
2. 百岁光阴，七十者稀。急急流年，滔滔逝水。


```python
import timeflow as tf
print("了生死")
```

Powered By [Marp](https://marp.app/)

---

## 测试标题

**Marp**

交大学术等线幻灯模板

欢迎大佬调教

![bg right:60% 80%](bg-end.png)

---

<!--
_paginate: false
-->
![bg](bg-end.png)

