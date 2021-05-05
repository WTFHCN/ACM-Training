# ACM-Training

---
title: 训练记录
date: 2021-12-31 10:47:00
tags: 
mathjax: true
---

## 训练日程

+ √  代表赛中AC

+ · 代表赛中尝试但未AC

+ O 代表赛后AC

+ \-  代表题目不存在

+ ?  代表对题目/标程存疑

+ × 代表题目/标程有问题

### 团队摸鱼

| date       | contest   | rank    | A   | B   | C   | D   | E   | F   | G   | H   | I   | J   | K   | L   | M   | N   | O   |
| ---------- | --------- | ------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2021/05/02 | gym103049 | 143/307 | √   |     | √   | √   | O   | √   | O   | √   | O   |     | √   | -   | -   | -   | -   |
| 2021/05/01 | gym103055 | 148/644 | √   | O   | √   | O   |     | √   | √   |     | O   | √   |     | √   | √   | -   | -   |




<!--more-->


<details>
  <summary>脑瘫问题首发</summary>

+ $s.earse(地址)$
+ 递归是用全局$vetor$
+ 线段树$if(!tag[pos])$
+ 可撤销并查集可以采用**保持合并前所有信息**
+ 多项式 $如果 while(ML<n+m-1)$ ,$n,m为项数$，如果$ML\leq n+m$
$n,m$为最高项系数，$sqrt,Inv....$等倒入的是项数（有多少项）。
+ 多项式合并时注意限制项数。
+ 线段树注意$lazy$的初始化
+ 公式化的离散化线段变成左开右闭  
+ 直径看清楚是否需要$-1$
+ 虚树注意清空该清空的
+ 多维$dp$转移注意边界
+ 后缀树上$lcp(i,j)=len(lca(i,j))$
+ 全排列二项式定理，也要考虑单独概率考虑
+ 随机化使用$std::mt19937 rnd(std::chrono::steady_clock::now().time_since_epoch().count());$
+ 树链剖分注意$top[rt]$，注意$w[dfn[x]]$
+ $KruskalTree重构树$开两倍空间。
+ 负数向下取整$>>1$
+ $KruskalTree重构树$是特胖叶子节点$g[x].size()\leq 1$!!,可以减少特胖
+ 字典序表示先字母大小再长度
+ 二分图的最大团=补图的最大独立集。，最大独立集=所有顶点数-最小顶点覆盖，最小顶点覆盖等于二分图的最大匹配。
+ Boruvka算法快。
+ 李超线段树$\max,\min$ 里面都要仔细改
+ 点分治的时候记住情况应该清空的数据结构，要记住有$a[rt]$这个点也要加入。
+ map.count!!!!!


<details>




<!-- ### 牛客多校
+ [2020牛客暑期多校训练营（第一场）](https://ac.nowcoder.com/acm/contest/5666)  $solve(2/10)$,$upsolve(2/10)$
+ [2020牛客暑期多校训练营（第二场）](https://ac.nowcoder.com/acm/contest/5667) $solve(1/11)$,$upsolve(9/11)$
+ [2020牛客暑期多校训练营（第三场）](https://ac.nowcoder.com/acm/contest/5668) $solve(5/12)$,$upsolve(9/12)$
+ [2020牛客暑期多校训练营（第四场）](https://ac.nowcoder.com/acm/contest/5669) $solve(3/10)$,$upsolve(4/10)$
+ [2020牛客暑期多校训练营（第五场）](https://ac.nowcoder.com/acm/contest/5670) $solve(4/11)$,$upsolve(8/10)$
+ [2020牛客暑期多校训练营（第六场）](https://ac.nowcoder.com/acm/contest/5671) $solve(2/11)$,$upsolve(6/11)$
+ [2020牛客暑期多校训练营（第七场）](https://ac.nowcoder.com/acm/contest/5672) 
+ [2020牛客暑期多校训练营（第八场）](https://ac.nowcoder.com/acm/contest/5673) $solve(3/11)$,$upsolve(5/11)$
+ [2020牛客暑期多校训练营（第九场）](https://ac.nowcoder.com/acm/contest/5673) $solve(3/11)$,$upsolve(10/12)$ -->



