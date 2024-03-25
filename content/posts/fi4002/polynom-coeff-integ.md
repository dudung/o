+++
title = 'polynom coeff integ'
date = 2024-03-25T16:37:00+07:00
draft = false
tags = ['fi4002']
math = true
+++
Integration of polynomial: Coefficients operation
<!--more-->

+ []()


## polynomial as list
A polynomial in the form of

$$\tag{1}
y = \sum_{i=0}^n b_i t^i
$$

can be presented in a column matrix

$$\tag{2}
y \equiv [b_0 \ \ b_1 \ \ b_2 \ \ b_3 \ \ \dots \ \ b_{n-1} \ \ b_n]
$$

or simply a list in Python.


## differential
If $x = dy/dt$ the (1) will turn into

$$\tag{3}
x = \sum_{i=1}^n ib_i t^{i-1} = \sum_{j=0}^{n-1} a_j t^j
$$

with

$$\tag{4}
a_j = (j+1) b_{j+1}
$$

since

$$\tag{5}
\begin{array}{rcl}
x & = & [b_1 \ \ 2 b_2 \ \ 3b_3 \ \ \dots \ \ (n-1) b_{n-1} \ \  \ \ n b_n \ ] \newline
& = & [a_0 \ \ \ a_1 \ \ \ a_2 \ \ \ \dots \ \ \ \ \ \ \ \ a_{n-2} \ \ \ \  \ \ \ \ \ a_{n-1}].
\end{array}
$$


## integral
