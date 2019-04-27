---
layout: post
title:  "Linear Algebra"
date:   2019-04-07 16:21:23 +0900
categories: linear algebra
---

https://twlab.tistory.com/3

선형 독립(Linear Independence)

1. 어떤 벡터가 다른 벡터들의 Linear Combination으로 정의되지 않을 때.
2. c1v1+...+cnvn(Linear Combination) 이 0 (영벡터)의 유일한 해(솔루션)가 c1=c2=...=cn = 0 일때.
어떤 조합에 의해서 linearly dependent하면 그 조합으로 colinear한 벡터를 생성할 수 있다. 이를 통해서 상쇄시키는 식을 0벡터가 생성됨.
3. 개인적으로 정의해본 것이지만, n개의 벡터를 따지면 그 벡터의 span(v1, ... , vn)이 n차원의 공간을 만들 때.(2개 - 평면, 3개 - 입체, 4개 - 4차원 공간 ...)

남아도는 벡터(redundant vector)가 있으면 linearly dependent.

3 tuple [X X X] : 엘리먼트가 3개일때

span은 벡터들을 linear combination한 것.

subspace는 영벡터를 포함하고 스칼라곱셈과 덧셈에 대하여 closure. 
그래서 span은 자동적으로 subspace.

basis는 그 subspace를 span하는 최소한의 집합을 의미.