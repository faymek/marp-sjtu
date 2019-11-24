---
marp: true
size: 4:3
theme: gaia
paginate: true
backgroundImage: url('bg1.png')
---

<style gloabl>
section {
  color: black;
}
h1 {
  font-size: 1.5em;
  color: #c8161e;
}
h2 {
  padding: 0.5em 0em 0em 0em;
  font-size: 1.3em;
  color: #c8161e;
}
p,blockquote,ul,ol {
    font-size: 0.66em;
}
</style>

<style scoped>
h1 {padding: 6.5em 0em 0em 0em; color:white;}
p {font-size:0.9em; color:white;}
</style>

![bg](bg.png)
<!--
_paginate: false
_class: lead
-->

# 基于深度学习的编码优化工作
2019年11月
冯冬辉，朱  辰

---

## End-to-end编码
- G. Toderici, S. M. O’Malley, S. J. Hwang, D. Vincent, D. Minnen, S. Baluja, M. Covell, and R. Sukthankar. “Variable rate image compression with recurrent neural networks”. ICLR 2016.
- 首个可操作的端到端神经网络压缩方案，可变码率

![](img/toderici.png)

---

## End-to-end编码
- J. Ballé, V. Laparra, and E. P. Simoncelli, “End-to-end optimized image compression,” ICLR 2017.
- J. Ballé, D. Minnen, S. Singh, S. J. Hwang, and N. Johnston, “Variational image compression with a scale hyperprior,” ICLR 2018.
- D. Minnen, J. Ballé, and G. Toderici. “Joint Autoregressive and Hierarchical Priors for Learned Image Compression,” NeurIPS 2018.
“Integer Networks for Data Compression with Latent-Variable Models”, Ballé et al., 2019
- Y. Choi ..“Variable Rate Deep Image Compression With a Conditional Autoencoder”, ICCV 2019.
- 具有信息瓶颈的自编码器AE

