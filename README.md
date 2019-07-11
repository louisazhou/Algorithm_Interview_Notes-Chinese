算法/深度学习/NLP面试笔记
===
**GitHub** 地址：https://github.com/

**说明**（2019-07-11）：准备项目和面试ing，在这里接着原作者https://github.com/imhuay/Algorithm_Interview_Notes-Chinese的工作，整理知识点之类的

RoadMap
---

<!-- | A | B | C | D | E | F | G | H | 
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | 
| 机器学习<br/>[:soccer:](./A-机器学习) | 深度学习<br/>[:basketball:](./A-深度学习) | 自然语言处理<br/>[:hamburger:](./C-自然语言处理) | 计算机视觉<br/>[:fries:](./D-计算机视觉) | 算法<br/>[:apple:](./E-算法) | 数学<br/>[:cherries:](./F-数学) | 编程语言<br/>[:strawberry:](./G-编程语言) | 笔试面经<br/>[:cookie:](./H-笔试面经) |  -->

<!-- <table style="width:100%; table-layout:fixed;">
  <tr>
    <td>A</td>
    <td>B</td>
    <td>C</td>
    <td>D</td>
    <td>E</td>
    <td>F</td>
    <td>G</td>
    <td>H</td>
  </tr>
  <tr>
    <td>机器学习<br/>[:soccer:](./A-机器学习)</td>
    <td>深度学习<br/>[:basketball:](./B-深度学习)</td>
    <td>自然语言处理<br/>[:hamburger:](./C-自然语言处理)</td>
    <td>计算机视觉<br/>[:fries:](./D-计算机视觉)</td>
    <td>算法<br/>[:apple:](./E-算法)</td>
    <td>数学<br/>[:cherries:](./F-数学)</td>
    <td>编程语言<br/>[:strawberry:](./G-编程语言)</td>
    <td>笔试面经<br/>[:cookie:](./H-笔试面经)</td>
  </tr>
</table> -->

- :soccer: [<font size=+1>机器学习</font>](./A-机器学习)
- :basketball: [<font size=+1>深度学习</font>](./A-深度学习)
- :hamburger: [<font size=+1>自然语言处理</font>](./B-自然语言处理)
- :fries: [<font size=+1>计算机视觉</font>](./B-计算机视觉)
- :cherries: [<font size=+1>数学</font>](./C-数学)
- :apple: [<font size=+1>算法</font>](./C-算法)
- :strawberry: [<font size=+1>编程语言</font>](./C-编程语言)
- :cookie: [<font size=+1>笔试面经</font>](./D-笔试面经)

<!--
算法/深度学习/机器学习面试问题整理，想法最初来源于这个[仓库](https://github.com/elviswf/DeepLearningBookQA_cn).
 - 该仓库整理了“花书”《深度学习》中的一些常见问题，其中部分偏理论的问题没有收录，如有需要可以浏览原仓库。 

此外，还包括我看到的所有机器学习/深度学习面经中的问题。
除了其中 DL/ML 相关的，其他与算法岗相关的计算机知识也会记录。
但是不会包括如前端/测试/JAVA/Android等岗位中有关的问题。
-->

<!--
## RoadMap
- [数学](./数学)
  - [微积分的本质](./数学/微积分的本质.md)
  - [深度学习的核心](./数学/深度学习的核心.md)
- [机器学习-深度学习-NLP](./机器学习-深度学习-NLP)
  - 深度学习
    - [深度学习基础](./机器学习-深度学习-NLP/DL-A-深度学习基础.md)
    - [《深度学习》整理](./机器学习-深度学习-NLP/DL-《深度学习》整理.md)
    - [专题-CNN](./机器学习-深度学习-NLP/DL-B-专题-CNN.md)
    - [专题-RNN](./机器学习-深度学习-NLP/DL-B-专题-RNN.md)
    - [专题-序列建模](./机器学习-深度学习-NLP/DL-C-专题-序列建模.md)
  - 机器学习
    - [机器学习算法](./机器学习-深度学习-NLP/ML-机器学习算法.md)
    - [机器学习实践](./机器学习-深度学习-NLP/ML-机器学习实践.md)
  - 自然语言处理
    - [NLP 基础](./机器学习-深度学习-NLP/NLP-A-自然语言处理基础.md)
    - [专题-词向量](./机器学习-深度学习-NLP/NLP-B-专题-词向量.md)
      - [Word2Vec](./机器学习-深度学习-NLP/NLP-B-专题-词向量.md#word2vec)
      - [GloVe](./机器学习-深度学习-NLP/NLP-B-专题-词向量.md#glove)
      - [FastText](./机器学习-深度学习-NLP/NLP-B-专题-词向量.md#fasttext)
- [算法](./算法)
  - [专题-动态规划](./算法/专题-动态规划.md)
  - [专题-洗牌、采样、随机数](./算法/专题-洗牌、采样、随机数.md)
  - [题解-剑指Offer](./算法/题解-剑指Offer.md)
  - [题解-LeetCode](./算法/题解-剑指Offer.md)
- [编程语言](./编程语言)
  - C/C++
    - [专题-基础知识](./编程语言/Cpp-基础知识.md)
    - [专题-左值与右值](./编程语言/Cpp-左值与右值.md)
    - [专题-面向对象编程](./编程语言/Cpp-面向对象编程.md)
  - Python TODO
- [笔试面经](./笔试面经)
- [project](./project)
- [code](./code)
  - [工具库](./code/工具库)
    - [gensim.FastText 的使用](./机器学习-深度学习-NLP/NLP-词向量.md#gensimmodelsfasttext-使用示例)
  - [倒排索引](./code/model/倒排索引)
- [招聘要求](./招聘要求.md)

-->

欢迎分享你在面试中遇见的问题！
---
- 你可以直接以你遇到的问题作为 issue 标题，然后分享你的回答或者其他参考资料。
- 我会经常修改文档的结构。如果文中有链接失效，请告诉我！

工具
---
- 在线 LaTeX 公式编辑器 http://www.codecogs.com/latex/eqneditor.php
