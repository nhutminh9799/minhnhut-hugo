---
index: "1"
title: "BÀI 1. MA TRẬN VÀ CÁC PHÉP TOÁN CƠ BẢN TRÊN MA TRẬN"
description: "Introducing Doks, a Hugo theme helping you build modern documentation websites that are secure, fast, and SEO-ready — by default."
excerpt: "Introducing Doks, a Hugo theme helping you build modern documentation websites that are secure, fast, and SEO-ready — by default."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: []
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
katex: true
---

## Ma Trận
### 1. Định nghĩa ma trận

- Một ma trận cấp $m$x$n$ ($\begin{align} m \geq 1 \ ; \ n \geq 1 \end{align}$), với $m$ là số dòng của ma trận, $n$ là số cột của ma trận. <br>
- Các phần tử bên trong của ma trận thuộc trường số thực ${\Reals}$. Ma trận A cấp $m$x$n$ được định nghĩa như sau: <br>

$$
\begin{pmatrix}
   a_{11} & a_{12} & \dots  & a_{1n} \cr
   a_{21} & a_{22} & \dots  & a_{2n} \cr
   \vdots & \vdots & \vdots  & \vdots \cr
   a_{m1} & a_{m2} & \dots  & a_{mn} 
\end{pmatrix}
$$

- <span style="color:red">**Ký hiệu:**</span> $\def\foo{a_{ij}} \begin{align} A = (\foo)_{m \times n} \end{align}$ trong đó,  $\foo \isin {\Reals}$,
với  $\foo$ là phần tử hàng thứ $i$ và cột thứ $j$

- <span style="color:blue">**Chú ý:**</span> $M_{m \times n}$( ${\Reals}$) được gọi là tập hợp các ma trận cấp ${m \times n}$ trên trường số thực.

- **Ví dụ minh họa**:

&nbsp; &nbsp; &nbsp; a) Ma trận $
\begin{pmatrix}
   2 & 4 &  7 \cr
   6 & 5 &   2 \cr
   3 & 4 & 8
\end{pmatrix}
$ là ma trận **3 dòng** và **3 cột**, vị trí $a_{11} = 2$. <br>
&nbsp; &nbsp; &nbsp; Vị trí $a_{23} = ...$ , Vị trí  $a_{32} = ...$ <br>

&nbsp; &nbsp; &nbsp; b) Ma trận $
\begin{pmatrix}
   -2 & {\frac 4 7} &  {\frac 6 7} \cr
   7{\frac 2 3} & {\sqrt[3]{\smash[b]{7}}} &   2 
\end{pmatrix}
$ là ma trận **2 dòng** và **3 cột**, vị trí $a_{11} = -2$. <br>
&nbsp; &nbsp; &nbsp; Vị trí $a_{23} = ...$ , Vị trí  $a_{12} = ...$ <br>

### 2. Ma trận không

- Ma trận mà tất cả phần tử đều bằng 0 thì được gọi là ***ma trận không***.
- Ví dụ về ma trận ***ma trận không***:
 $
\begin{pmatrix}
   0 & 0 &  0 \cr
   0 & 0 &   0 \cr
   0 & 0 & 0
\end{pmatrix}
$ là ma trận không có **3 dòng** và **3 cột**. <br>

- Ký hiệu của ma trận không: $0_{m \times n}$
### 3. Ma trận hàng, ma trận cột

- Ma trận hàng là ma trận có số hàng là 1 và số cột thì tùy ý và $n > 1$ <br>
-- Dạng tổng quát của ma trận hàng
 $$
\begin{pmatrix}
   a_{11} & a_{12} & \dots  & a_{1n} \cr
\end{pmatrix}$$
--  Ví dụ về ***ma trận hàng***:
 $
\begin{pmatrix}
   1 & 2 &  4 \cr
\end{pmatrix}$

- Ma trận hàng là ma cột có số cột là 1 và số hàng thì tùy ý và $m > 1$ <br>
-- Dạng tổng quát của ma trận cột
 $$
\begin{pmatrix}
   a_{11} \cr
   a_{21} \cr
   \vdots \cr
   a_{m1}
\end{pmatrix}$$
-- Ví dụ về  ***ma trận cột***:
 $
\begin{pmatrix}
   5 \cr
   6 \cr
   7
\end{pmatrix}$
### 4. Ma trận vuông

## Các phép tính trên ma trận
### 1. Phép cộng trừ hai ma trận cùng cấp
### 2. Phép nhân hai ma trận, ma trận với 1 số
### 3. Phép lũy thừa ma trận

## Tài liệu tham khảo
