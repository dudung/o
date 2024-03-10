+++
title = 'fourier decomposition example'
date = 2024-03-10T12:22:00+07:00
draft = false
tags = ['fi6004']
math = true
+++
Fourier decomposition example in 3 terms: Constant, cosine, sine.
<!--more-->

+ []()


## integral identities $x$
$$\tag{1}
\int_0^L \sin \left( m \frac{2\pi}{L} x \right) \sin \left( n \frac{2\pi}{L} x \right) \ dx = \left\\{
\begin{array}{rcl}
0, & m \ne n, \newline
\tfrac12 L, & m = n.
\end{array}
\right.
$$

&nbsp;

$$\tag{2}
\int_0^L \cos \left( m \frac{2\pi}{L} x \right) \cos \left( n \frac{2\pi}{L} x \right) \ dx = \left\\{
\begin{array}{rcl}
0, & m \ne n, \newline
\tfrac12 L, & m = n.
\end{array}
\right.
$$

&nbsp;

$$\tag{3}
\int_0^L \cos \left( m \frac{2\pi}{L} x \right) \sin \left( n \frac{2\pi}{L} x \right) \ dt = 0.
$$

&nbsp;

$$\tag{3b}
\int_0^L \cos \left( m \frac{2\pi}{L} x \right) \ dt = 0.
$$

&nbsp;

$$\tag{3c}
\int_0^L \sin \left( n \frac{2\pi}{L} x \right) \ dt = 0.
$$



## coefficients $x$
$$\tag{4}
f(x) = \sum_{m=1}^\infty a_m \cos \left[ m \left( \frac{2\pi}{L} \right) x \right] + \sum_{m=1}^\infty b_m \sin \left[ m \left( \frac{2\pi}{L} \right) x \right] + c_0
$$

$$\tag{5}
a_m = \frac{2}{L}\int_0^L f(x) \ \cos \left[ m \left( \frac{2\pi}{L} \right) x \right] \ dx
$$

$$\tag{6}
b_m = \frac{2}{L}\int_0^L f(x) \ \sin \left[ m \left( \frac{2\pi}{L} \right) x \right] \ dx
$$

$$\tag{7}
c_0 = \frac{1}{L} \int_0^L f(x) \ dx.
$$

$$\tag{8}
k_m = m \frac{2\pi}{L}, \ \ \ \ m = 1, 2, 3, ..
$$


## integral identities $t$
$$\tag{9}
\int_0^T \sin \left( m \frac{2\pi}{T} t \right) \sin \left( n \frac{2\pi}{T} t \right) \ dt = \left\\{
\begin{array}{rcl}
0, & m \ne n, \newline
\tfrac12 T, & m = n.
\end{array}
\right.
$$

&nbsp;

$$\tag{10}
\int_0^T \cos \left( m \frac{2\pi}{T} t \right) \cos \left( n \frac{2\pi}{T} t \right) \ dt = \left\\{
\begin{array}{rcl}
0, & m \ne n, \newline
\tfrac12 T, & m = n.
\end{array}
\right.
$$

&nbsp;

$$\tag{11}
\int_0^T \cos \left( m \frac{2\pi}{T} t \right) \sin \left( n \frac{2\pi}{T} t \right) \ dt = 0.
$$

&nbsp;

$$\tag{11b}
\int_0^T \cos \left( m \frac{2\pi}{T} t \right) \ dt = 0.
$$

&nbsp;

$$\tag{11c}
\int_0^T \sin \left( n \frac{2\pi}{T} t \right) \ dt = 0.
$$


## coefficients $t$
$$\tag{12}
f(t) = \sum_{m=1}^\infty a_m \cos \left[ m \left( \frac{2\pi}{L} \right) t \right] + \sum_{m=1}^\infty b_m \sin \left[ m \left( \frac{2\pi}{L} \right) t \right] + c_0
$$

$$\tag{13}
a_m = \frac{2}{T}\int_0^T f(t) \ \cos \left[ m \left( \frac{2\pi}{L} \right) t \right] \ dt
$$

$$\tag{14}
b_m = \frac{2}{T}\int_0^T f(t) \ \sin \left[ m \left( \frac{2\pi}{L} \right) t \right] \ dt
$$

$$\tag{15}
c_0 = \frac{1}{T} \int_0^T f(t) \ dt.
$$

&nbsp;

$$\tag{16}
\omega_m = m \frac{2\pi}{T}, \ \ \ \ m = 1, 2, 3, ..
$$


## example
$$\tag{17}
f(t) = 2 + 5 \cos 20 \pi t + 3 \sin 8 \pi t.
$$

&nbsp;

$$\tag{18}
\begin{array}{rcl}
f(t) & = & \displaystyle 2 + 5 \cos \left( \frac{2\pi}{0.1} t \right) + 3 \sin \left( \frac{2\pi}{0.25} t \right)
\newline \newline
& = & \displaystyle 2 + 5 \cos \left( 10 \frac{2\pi}{1} t \right) + 3 \sin \left( 4 \frac{2\pi}{1} t \right)
\end{array}
$$


## consine terms coefficients
+ Use Eqns (13), (10), (11).


## sine terms coefficients
+ Use Eqn (14), (9), (11).


## constant term
+ Use Eqn (15), (11b), (11c).


## refs
+ Michael Richmond, "Examples of Fourier decomposition", Phys283 Vibrations and Waves, Rochester Institute of Technology, Spring 2024, url http://spiff.rit.edu/classes/phys283/lectures/fourier_2/fourier_2.html [20240310].
