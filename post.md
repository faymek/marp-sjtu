---
marp: true
size: 4:3
theme: gaia
paginate: true
backgroundImage: url('bg.png')

---

<style gloabl>
section {
  color: black;
  padding: 91px 53px;
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

</style>

<!-- Note: Leading Page -->
<!--
_paginate: false
_class: lead
-->
<style scoped>
h1 {padding: 6.5em 0em 0em 0em; color:white;}
p {font-size:0.9em; color:white;}
</style>

![bg](bg-lead.png)


# 基于Marp的幻灯展示模板
2019年11月
古秋

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


<!-- Note: Ending Page -->
<!--
_paginate: false
_class: lead
-->
![bg](bg-end.png)

