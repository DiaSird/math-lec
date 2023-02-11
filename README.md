---
title: Mathematics lecture
author: DiaSird
fontsize: 11pt
header-includes:
  - \lstset{numbers=left, frame=trlb, frameround=tttt, breaklines=true}
  - \renewcommand{\lstlistingname}{Source Code}
---

Initial version: 2022/06/17
Revised: 2022/

# Mathematics lecture

- 数学のまとめ記事
- これから自走するために必要な内容のみを記載している
- 独学で読んでも挫折しない記事を目指す

---

## 内容

- [Mathematics lecture](#mathematics-lecture)
  - [内容](#内容)
  - [1. 高校数学（docs/high_sch）](#1-高校数学docshigh_sch)
  - [2. 大学数学（docs/univ）](#2-大学数学docsuniv)

## 1. 高校数学（docs/high_sch）

理系の高校数学では、数 ⅠA(1 年次)、数 ⅡB(2 年次)、数 Ⅲ(3 年次)の順に学習する。これに沿って記述する。

数学 A:

- [順列・組合せ](https://github.com/DiaSird/math-lec/blob/main/docs/high_sch/1_%E9%A0%86%E5%88%97%E7%B5%84%E5%90%88%E3%81%9B.md)

数学 Ⅱ:

- 複素数
- 三角関数
- 図形と方程式
- 微分法と積分法

計算手法に重点をおく。ラプラス変換やフーリエ解析等、大学数学の土台はこの数学 Ⅱ の科目にある。

数学 B:

- ベクトル
- [数列](https://github.com/DiaSird/math-lec/blob/main/docs/high_sch/6_%E6%95%B0%E5%88%97.md)
- 確率統計

数学 B は、図形的な考え(幾何学)の面が強い。

数学 Ⅲ:

- 複素数平面
- 関数と極限
- 微積分法の応用

数学 Ⅲ は、高校数学の総合的な計算を主に行う。微積分が中心。

## 2. 大学数学（docs/univ）

- [はじめに](https://github.com/DiaSird/math-lec/blob/main/docs/univ/0_%E3%81%AF%E3%81%98%E3%82%81%E3%81%AB.md)

よく使われる記号について、前提知識を述べておく。

- [微積分学](https://github.com/DiaSird/math-lec/blob/main/docs/univ/1_%E5%BE%AE%E7%A9%8D%E5%88%86%E5%AD%A6.md)
- 線形代数

微積分と線形代数は基礎になるため、まずはこの 2 つの理解が最重要。数学 Ⅲ の内容を背景にして学習する。

- 確率統計学

統計理論は、機械学習の分野で多く使用されている。学部低学年 (1・2 年)で学習することが多い。微積分学で学んだガウス積分はここで用いられる。

- 常微分方程式
- ベクトル解析
- 複素解析

この 3 つは、学部低学年での学習カリキュラムが多い。

- フーリエ解析
- ラプラス変換
- 偏微分方程式

学部高学年(3・4 年)で学ぶ学習カリキュラムが多い科目。力学の問題を解く場合に、道具として使用される。

- 位相空間論
- 多様体論

発展的な内容。大学の理学部数学科では図形を調べる幾何学の分野としてこの科目がある。位相空間論が基礎になっており、専門書を読む際に必要となる場合がある。
