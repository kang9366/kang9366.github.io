---
layout: post
title: "R 함수 정리"
date: 2020-11-17
excerpt: "r functions"
tags: [R, function]
category: [R]
comments: true
---

### apply
```
apply(data, margin = n, function)
```
data : 적용할 데이터  
margin  : margin = 1 이면 행방향으로 적용, margin = 2이면 열 방향으로 적용  
function : 적용할 함수  

```
lapply(
```
벡터나 리스트(데이터프레임도 가능)를 입력받아서 리스트로 반환한다.  

```
sapply
```
lapply와 비슷하지만 결과를 행렬이나 벡터로 반환한다.

```

