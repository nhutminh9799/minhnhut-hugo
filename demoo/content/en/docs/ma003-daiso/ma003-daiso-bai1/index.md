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

## Ma Trận (Matrix)
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

- Ma trận thường được viết dưới dạng ngoặc hợp [] hoặc ngoặc đơn ()
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

- Ma trận vuông là ma trận có n = số hàng = số cột. Ký hiệu  $M_{n \times n}$( ${\Reals}$) hay $M_n$(${\Reals}$) hay là ma trận vuông cấp n.
- Dạng tổng quá của ma trận vuông cấp n
$$
\begin{pmatrix}
   a_{11} & a_{12} & \dots  & a_{1n} \cr
   a_{21} & a_{22} & \dots  & a_{2n} \cr
   \vdots & \vdots & \vdots  & \vdots \cr
   a_{n1} & a_{m2} & \dots  & a_{mn} 
\end{pmatrix}
$$
- Ví dụ về ma trận vuông cấp $3 \times 3 $

$$
\begin{pmatrix}
   5  & 9  & 2 \cr
   0 & 7  & 7 \cr
   0  & 0  & 2 
\end{pmatrix}
$$

- Ma trận vuông cấp n có các phần tử $a_{11}, a_{22}, a_{33}, ... a_{nn}$. Tập hợp những phần tử này gọi là là ***đường chéo chính*** hay ***đường chéo*** của 
dạng ma trận vuông.

$$
\begin{pmatrix}
   \color{red}\bold5  & 9  & 2 \cr
   -1 & \color{red}\bold7  & 7 \cr
   4  & 2  & \color{red}\bold2 
\end{pmatrix}
$$

- Vậy 5, 7, 2 là phần tử của đường chéo chính trong ma trận vuông.

- <span style="color:blue">**Trường hợp ma trận vuông Đặc biệt**</span><br>
-- Ma trận vuông có tất cả phần tử dưới đường chéo chính bằng 0, thì ma trận đó là <span style="color:#e9a374; font-style: italic;">ma trận tam giác trên.</span> <br>
○ Ví dụ <br>
$$
\begin{pmatrix}
   \color{red}\bold5  & 9  & 2 \cr
   0 & \color{red}\bold7  & 7 \cr
   0  & 0 & \color{red}\bold2 
\end{pmatrix}
$$
-- Ma trận vuông có tất cả phần tử trên đường chéo chính bằng 0, thì ma trận đó là <span style="color:#e9a374; font-style: italic;">ma trận tam giác dưới.</span> <br>
○ Ví dụ <br>
$$
\begin{pmatrix}
   \color{red}\bold5  & 0  & 0 \cr
   -1 & \color{red}\bold7  & 0 \cr
   4  & 2  & \color{red}\bold2 
\end{pmatrix}
$$
-- Ma trận vuông có tất cả phần tử ngoài đường chéo chính bằng 0, thì ma trận đó là <span style="color:#e9a374; font-style: italic;">ma trận đường chéo</span> <br>
○ Ví dụ <br>
$$
\begin{pmatrix}
   \color{red}\bold5  & 0  & 0 \cr
   0 & \color{red}\bold7  & 0 \cr
   0  & 0  & \color{red}\bold2 
\end{pmatrix}
$$
### 5. Ma trận đơn vị
- Ma trận đường chéo cấp n có tất cả phần tử đường chéo bằng 1 thì gọi là ma trận đơn vị cấp n kí hiệu là $I_{n}$ <br>
-- Ví dụ <br>
$$ I_{3} = 
\begin{pmatrix}
   \color{red}\bold1  & 0  & 0 \cr
   0 & \color{red}\bold1  & 0 \cr
   0  & 0  & \color{red}\bold1 
\end{pmatrix}
$$
## Vô Hướng (Scalar)

- Một số bất kỳ thuộc tập một số nào đó thì được gọi là Vô Hướng (Scalar).

- Ví dụ 5 thuộc số tự nhiên ký hiệu là $5 \isin \N$

- Ví dụ **5+i** thuộc trường số phức ký hiệu $5+i \isin \Complex$

## Véctơ (Vector)

- Véctơ trong ngôn ngữ lập trình còn có tên khác là mảng 1 chiều. Là một ma trận hàng hoặc ma trận cột (m = 1 hoặc n = 1).

## Tenxơ (Ternsor)

- Tenxơ là một mảng nhiều chiều. Như vậy định nghĩa thêm. <br>
-- Vectơ là một mảng 1 chiều. <br>
-- Matrix là một mảng 2 chiều. <br>
-- Ternsor là một mảng nhiều chiều. <br>

- Ứng dụng của Ternsor ứng dụng cũng rất nhiều trong nhiều nghành Khoa học Tự nhiên.
## Các phép tính trên ma trận

### 1. Phép toán so sánh hai ma trận
- <span style="color:blue">**Điều kiện so sánh hai ma trận:**</span> Để hai ma trận so sánh được với nhau thì hai ma trận đó phải cùng cấp (cùng số hàng và cùng số cột).

- <span style="color:blue">**Cách thức so sánh:**</span> Hai ma trận A, B cùng cấp với nhau, nếu $A_{ij} = B_{ij}, \forall i,j$ thì ta nói ma trận **A = B**.
- Ví dụ so sánh hai ma trận sau đây
*Cho hai ma trận cùng cấp A, B* $2 \times 2$:
$$
A=\begin{pmatrix}
   x+y  & 2+x  \cr
   2x+y & 2y
\end{pmatrix};
B= \begin{pmatrix}
   5 & 5  \cr
   10 - y & 2x - 2
\end{pmatrix}
$$
<br> *Tìm $x,y$ để A, B bằng nhau*
- **BÀI GIẢI**
*Để A và B bằng nhau thì*
$$\begin{cases}
   x + y = 5 \cr
   2 + x = 5 \cr
   2x +  y = 10 - y \cr
   2y = 2x - 2
\end{cases} \lrArr \begin{cases}
   y = 2 \cr
   x = 3 
\end{cases} $$

### 2. Phép chuyển vị hai ma trận
- <span style="color:blue">**Định nghĩa:**</span> *Ma trận chuyển vị* của ma trận  $A \in \ M_{m \times n}(\Reals)$ được ký hiệu là $A^T$,
là ma trận có được đổi thứ tự giữa hàng và cột tương ứng của ma trận A.

- Ta có ma trận $A$ và $A^T$ như sau:
$$
A = \begin{pmatrix}
   a_{11} & a_{12} & \dots  & a_{1n} \cr
   a_{21} & a_{22} & \dots  & a_{2n} \cr
   \vdots & \vdots & \vdots  & \vdots \cr
   a_{n1} & a_{m2} & \dots  & a_{mn} 
\end{pmatrix}; A^T = \begin{pmatrix}
   a_{11} & a_{21} & \dots  & a_{m1} \cr
   a_{12} & a_{22} & \dots  & a_{2n} \cr
   \vdots & \vdots & \vdots  & \vdots \cr
   a_{1n} & a_{2n} & \dots  & a_{msn} 
\end{pmatrix};
$$

- <span style="color:blue">**Các tính chất của ma trận chuyển vị:**</span> Cho $A, B$ là ma trận chuyển vị và thuộc $M_{m \times n}(\Reals)$
Thì ta được các tính chất sau đây: <br>
-- Tính chất 1: $(A^T)^T = A$ <br>
-- Tính chất 2: $A^T = B^T \lrArr A = B$

- <span style="color:blue">Định nghĩa *Ma trận đối xứng*: </span>Một ma trận được gọi là đối xứng khi và chỉ khi $A^T = A$
### 3. Phép cộng trừ hai ma trận cùng cấp
- <span style="color:blue">**Điều kiện cộng trừ, hai ma trận:**</span> Hai ma trận $A, B$ muốn cộng được thì $A, B$ phải cùng cấp với nhau.
- <span style="color:blue">**Cách tính tổng hai ma trận:**</span> Hai ma trận $A, B \isin M_{m \times n}(\Reals)$
### 4. Phép nhân hai ma trận, ma trận với 1 số
### 5. Phép lũy thừa ma trận


## Bài tập
## Tài liệu tham khảo
