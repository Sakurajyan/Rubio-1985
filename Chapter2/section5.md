Calderon-Zygmund Theory
=======================

5. Singular Integral Operators
---------------------------

In this section we show how Calderon-Zygmund decomposition is used in
estimation of the convolution operator <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">, which defined on Schwartz
space <img src="https://www.zhihu.com/equation?tex=\mathscr{S}" alt="\mathscr{S}" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=T(f)=K*f(x)" alt="T(f)=K*f(x)" class="ee_img tr_noresize" eeimg="1">. The definition of singular integral
operator given in book is different from others like that in Stein's
*Singular Integrals and Differentiability Properties of Functions*.

Definition 5.0.1. Given a tempered distribution <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, the convolution operator

<img src="https://www.zhihu.com/equation?tex=T f(x)=K*f(x)\quad (f\in\mathscr{S}(\mathbb{R}^n))\\" alt="T f(x)=K*f(x)\quad (f\in\mathscr{S}(\mathbb{R}^n))\\" class="ee_img tr_noresize" eeimg="1">

 is called a
singular integral operator if the following two conditions are
satisfied:

1.  <img src="https://www.zhihu.com/equation?tex=\hat{K}\in L^\infty(\mathbb{R}^n)" alt="\hat{K}\in L^\infty(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> coincides in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n\setminus\{0\}" alt="\mathbb{R}^n\setminus\{0\}" class="ee_img tr_noresize" eeimg="1"> with a locally
    integrable function <img src="https://www.zhihu.com/equation?tex=K(x)" alt="K(x)" class="ee_img tr_noresize" eeimg="1"> satisfying Hormander's condition:
    
<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}\left\lvert K(x-y)-K(x)\right\rvert dx\leq B_k\\" alt="\int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}\left\lvert K(x-y)-K(x)\right\rvert dx\leq B_k\\" class="ee_img tr_noresize" eeimg="1">



Later we will see these two conditions guarantee the boundedness of
<img src="https://www.zhihu.com/equation?tex=T(f)" alt="T(f)" class="ee_img tr_noresize" eeimg="1">.

5.1 Hormander's condition

If a locally integrable function <img src="https://www.zhihu.com/equation?tex=k(x)" alt="k(x)" class="ee_img tr_noresize" eeimg="1"> satisfying Hormander's condition
and following two conditions:

<img src="https://www.zhihu.com/equation?tex=\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1\\" alt="\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\left\{
    \begin{aligned}
         & \left\lvert\int_{r<\left\lvert x\right\rvert<R}k(x)dx\right\rvert\leq C_2       \\
         & \lim_{r\to 0}\int_{r<\left\lvert x\right\rvert<1}k(x)dx~exists
    \end{aligned}
    \right.\\" alt="\left\{
    \begin{aligned}
         & \left\lvert\int_{r<\left\lvert x\right\rvert<R}k(x)dx\right\rvert\leq C_2       \\
         & \lim_{r\to 0}\int_{r<\left\lvert x\right\rvert<1}k(x)dx~exists
    \end{aligned}
    \right.\\" class="ee_img tr_noresize" eeimg="1">

 Then
<img src="https://www.zhihu.com/equation?tex=T f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}k(x-y)f(y)dy" alt="T f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}k(x-y)f(y)dy" class="ee_img tr_noresize" eeimg="1">
is a singular integrable operator (Proposition 5.5 in book). In other
words, <img src="https://www.zhihu.com/equation?tex=\lVert\hat{k}\rVert_\infty<\infty" alt="\lVert\hat{k}\rVert_\infty<\infty" class="ee_img tr_noresize" eeimg="1">

If we let a locally integrable function <img src="https://www.zhihu.com/equation?tex=k(x)" alt="k(x)" class="ee_img tr_noresize" eeimg="1"> be
<img src="https://www.zhihu.com/equation?tex=\Omega(x)\left\lvert x\right\rvert^{-n}" alt="\Omega(x)\left\lvert x\right\rvert^{-n}" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> homogeneous of
degree 0 (<img src="https://www.zhihu.com/equation?tex=\Omega(rx)=\Omega(x)" alt="\Omega(rx)=\Omega(x)" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=r\neq 0" alt="r\neq 0" class="ee_img tr_noresize" eeimg="1">). Then the following
continuity condition on <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> ensures Hormander condition holds:

<img src="https://www.zhihu.com/equation?tex=\int_0^1{w_1(\Omega;t)\frac{dt}{t}<\infty}\\" alt="\int_0^1{w_1(\Omega;t)\frac{dt}{t}<\infty}\\" class="ee_img tr_noresize" eeimg="1">

 where

<img src="https://www.zhihu.com/equation?tex=w_1(\Omega;t)=\sup_{h\in\mathbb{R}^n, \left\lvert h\right\rvert\leq t}\int_{\left\lvert x'\right\rvert=1}{\left\lvert\Omega(x'+h)-\Omega{(x')}\right\rvert d\sigma(x')}\\" alt="w_1(\Omega;t)=\sup_{h\in\mathbb{R}^n, \left\lvert h\right\rvert\leq t}\int_{\left\lvert x'\right\rvert=1}{\left\lvert\Omega(x'+h)-\Omega{(x')}\right\rvert d\sigma(x')}\\" class="ee_img tr_noresize" eeimg="1">


Then
<img src="https://www.zhihu.com/equation?tex=T f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}\Omega(y)\left\lvert y\right\rvert^{-n}f(x-y)d y" alt="T f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}\Omega(y)\left\lvert y\right\rvert^{-n}f(x-y)d y" class="ee_img tr_noresize" eeimg="1">
is a singular integrable operator. The condition
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{k}\rVert_\infty<\infty" alt="\lVert\hat{k}\rVert_\infty<\infty" class="ee_img tr_noresize" eeimg="1"> is ensured by explict formula for
<img src="https://www.zhihu.com/equation?tex=\hat{k}=m(\xi)" alt="\hat{k}=m(\xi)" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> is odd:

<img src="https://www.zhihu.com/equation?tex=m(\xi)=-\frac{\pi i}{2}\int_{\left\lvert x'\right\rvert=1}\Omega(x')\operatorname{sign}(x'\cdot\xi)d\sigma(x')\\" alt="m(\xi)=-\frac{\pi i}{2}\int_{\left\lvert x'\right\rvert=1}\Omega(x')\operatorname{sign}(x'\cdot\xi)d\sigma(x')\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=\operatorname{sign}x=\frac{x}{\left\lvert x\right\rvert}" alt="\operatorname{sign}x=\frac{x}{\left\lvert x\right\rvert}" class="ee_img tr_noresize" eeimg="1">
(Proposition 5.6 in book). If <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> is not necessarily odd then the
formula for <img src="https://www.zhihu.com/equation?tex=m(\xi)" alt="m(\xi)" class="ee_img tr_noresize" eeimg="1"> is (refer section 4.2 in chapter 2 in Stein's
*Singular Integrals and Differentiability Properties of Functions*):

<img src="https://www.zhihu.com/equation?tex=m(\xi)=\frac{\pi i}{2}\int_{\left\lvert x'\right\rvert=1}{(\operatorname{sign}(x'\cdot\xi)+\log{(\frac{1}{\left\lvert x'\cdot\xi\right\rvert})})\Omega(x')d\sigma(x')}\\" alt="m(\xi)=\frac{\pi i}{2}\int_{\left\lvert x'\right\rvert=1}{(\operatorname{sign}(x'\cdot\xi)+\log{(\frac{1}{\left\lvert x'\cdot\xi\right\rvert})})\Omega(x')d\sigma(x')}\\" class="ee_img tr_noresize" eeimg="1">



Remark 1.5.1.1. Equation

<img src="https://www.zhihu.com/equation?tex=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}(x'\cdot h)\operatorname{sign}(x'\cdot\xi)d\sigma(x')=\frac{\xi\cdot h}{\left\lvert\xi\right\rvert}\\" alt="\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}(x'\cdot h)\operatorname{sign}(x'\cdot\xi)d\sigma(x')=\frac{\xi\cdot h}{\left\lvert\xi\right\rvert}\\" class="ee_img tr_noresize" eeimg="1">


is by riesz representation for Hilbert space. If we fix <img src="https://www.zhihu.com/equation?tex=\xi" alt="\xi" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=\left\lvert\xi\right\rvert=1" alt="\left\lvert\xi\right\rvert=1" class="ee_img tr_noresize" eeimg="1">, then left hand side is a linear function
of <img src="https://www.zhihu.com/equation?tex=h" alt="h" class="ee_img tr_noresize" eeimg="1">, say <img src="https://www.zhihu.com/equation?tex=\ell(h)" alt="\ell(h)" class="ee_img tr_noresize" eeimg="1">. Since

<img src="https://www.zhihu.com/equation?tex=\left\lvert\ell(h)\right\rvert\leq\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert x'\right\rvert\left\lvert h\right\rvert d\sigma(x')=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert h\right\rvert d\sigma(x')=\left\lvert h\right\rvert\\" alt="\left\lvert\ell(h)\right\rvert\leq\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert x'\right\rvert\left\lvert h\right\rvert d\sigma(x')=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert h\right\rvert d\sigma(x')=\left\lvert h\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


, <img src="https://www.zhihu.com/equation?tex=\ell(h)" alt="\ell(h)" class="ee_img tr_noresize" eeimg="1"> is continuous linear functional with
<img src="https://www.zhihu.com/equation?tex=\lVert\ell\rVert\leq 1" alt="\lVert\ell\rVert\leq 1" class="ee_img tr_noresize" eeimg="1">. Thus <img src="https://www.zhihu.com/equation?tex=\ell(h)=(h,g)" alt="\ell(h)=(h,g)" class="ee_img tr_noresize" eeimg="1"> for some
<img src="https://www.zhihu.com/equation?tex=g\in\mathbb{R}^n" alt="g\in\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=\left\lvert g\right\rvert=\lVert\ell\rVert\leq 1" alt="\left\lvert g\right\rvert=\lVert\ell\rVert\leq 1" class="ee_img tr_noresize" eeimg="1">. Notice

<img src="https://www.zhihu.com/equation?tex=\ell(\xi)=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}(x'\cdot\xi)\operatorname{sign}(x'\cdot\xi)d\sigma(x')=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert x'\cdot\xi\right\rvert d\sigma(x')=1\\" alt="\ell(\xi)=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}(x'\cdot\xi)\operatorname{sign}(x'\cdot\xi)d\sigma(x')=\frac{\pi}{2}c_n\int_{\left\lvert x'\right\rvert=1}\left\lvert x'\cdot\xi\right\rvert d\sigma(x')=1\\" class="ee_img tr_noresize" eeimg="1">


Thus <img src="https://www.zhihu.com/equation?tex=\lVert\ell\rVert=1" alt="\lVert\ell\rVert=1" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=\left\lvert g\right\rvert=1" alt="\left\lvert g\right\rvert=1" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=1=\ell(\xi)=(\xi,g)\leq\left\lvert\xi\right\rvert\left\lvert g\right\rvert=1" alt="1=\ell(\xi)=(\xi,g)\leq\left\lvert\xi\right\rvert\left\lvert g\right\rvert=1" class="ee_img tr_noresize" eeimg="1">.
The inequality holds if and only if <img src="https://www.zhihu.com/equation?tex=g=k\xi" alt="g=k\xi" class="ee_img tr_noresize" eeimg="1"> for some <img src="https://www.zhihu.com/equation?tex=k\in\mathbb{R}" alt="k\in\mathbb{R}" class="ee_img tr_noresize" eeimg="1">.
Thus <img src="https://www.zhihu.com/equation?tex=g=\xi" alt="g=\xi" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\ell(h)=(h,\xi)" alt="\ell(h)=(h,\xi)" class="ee_img tr_noresize" eeimg="1">

5.2 Estimation of singular integral operator

The following theorem is the main result concerning singular integral
operators:

Theorem 5.2.1 (theorem 5.7 in book).Every singular integral operator satisfies the inequalities

<img src="https://www.zhihu.com/equation?tex=\lVert Tf\rVert_p\leq C_p\lVert f\rVert_p\quad (f\in L^2\cap L^p;1<p<\infty)\\" alt="\lVert Tf\rVert_p\leq C_p\lVert f\rVert_p\quad (f\in L^2\cap L^p;1<p<\infty)\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\label{ieq: case p=1}
        \left\lvert\{x:\left\lvert Tf(x)\right\rvert>t\}\right\rvert\leq \frac{C_1}{t}\lVert f\rVert_1\quad (f\in L^2\cap L^1)\\" alt="\label{ieq: case p=1}
        \left\lvert\{x:\left\lvert Tf(x)\right\rvert>t\}\right\rvert\leq \frac{C_1}{t}\lVert f\rVert_1\quad (f\in L^2\cap L^1)\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\label{ieq: case p=infty}
        \lVert Tf\rVert_{\operatorname{BMO}}\leq C_\infty\lVert f\rVert_\infty\quad (f\in L^2\cap L^\infty)\\" alt="\label{ieq: case p=infty}
        \lVert Tf\rVert_{\operatorname{BMO}}\leq C_\infty\lVert f\rVert_\infty\quad (f\in L^2\cap L^\infty)\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=C_p" alt="C_p" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=1\leq p\leq\infty" alt="1\leq p\leq\infty" class="ee_img tr_noresize" eeimg="1">, depends only on <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> and on the
constants <img src="https://www.zhihu.com/equation?tex=\lVert\hat{K}\rVert_\infty" alt="\lVert\hat{K}\rVert_\infty" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=B_K" alt="B_K" class="ee_img tr_noresize" eeimg="1"> of the kernel.

To prove this theorem, we only need to prove three case <img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=p=2" alt="p=2" class="ee_img tr_noresize" eeimg="1">,
and <img src="https://www.zhihu.com/equation?tex=p=\infty" alt="p=\infty" class="ee_img tr_noresize" eeimg="1"> and use Marcinkiewicz interpolation theorem in section 2
to derive <img src="https://www.zhihu.com/equation?tex=1< p<2" alt="1< p<2" class="ee_img tr_noresize" eeimg="1"> case. And use another interpolation theorem 3.7 in
section 3 to derive <img src="https://www.zhihu.com/equation?tex=2< p<\infty" alt="2< p<\infty" class="ee_img tr_noresize" eeimg="1"> case.

Remark 5.2.1 (notes on proof of inequality (1.2)). The key idea to prove the case <img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1"> is Calderon-Zygmund decomposition.
First we can split the space into a family of non-overlapping cubes
<img src="https://www.zhihu.com/equation?tex=C_t" alt="C_t" class="ee_img tr_noresize" eeimg="1"> and a set <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n\setminus\cup_{Q\in C_t}Q" alt="\mathbb{R}^n\setminus\cup_{Q\in C_t}Q" class="ee_img tr_noresize" eeimg="1">. These sets
satisfy:

1.  For every <img src="https://www.zhihu.com/equation?tex=Q\in C_t" alt="Q\in C_t" class="ee_img tr_noresize" eeimg="1">,
    <img src="https://www.zhihu.com/equation?tex=t<\frac{1}{\left\lvert Q\right\rvert}\int_{\left\lvert Q\right\rvert}{\left\lvert f(x)\right\rvert dx}\leq 2^nt" alt="t<\frac{1}{\left\lvert Q\right\rvert}\int_{\left\lvert Q\right\rvert}{\left\lvert f(x)\right\rvert dx}\leq 2^nt" class="ee_img tr_noresize" eeimg="1">

2.  For a.e. <img src="https://www.zhihu.com/equation?tex=X\notin \cup_{Q\in C_t}Q" alt="X\notin \cup_{Q\in C_t}Q" class="ee_img tr_noresize" eeimg="1">,
    <img src="https://www.zhihu.com/equation?tex=\left\lvert f(x)\right\rvert\leq t" alt="\left\lvert f(x)\right\rvert\leq t" class="ee_img tr_noresize" eeimg="1">

Let <img src="https://www.zhihu.com/equation?tex=\Omega=\cup_{Q\in C_t}Q" alt="\Omega=\cup_{Q\in C_t}Q" class="ee_img tr_noresize" eeimg="1">. For any function <img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">, the
Calderon-Zygmund decomposition of <img src="https://www.zhihu.com/equation?tex=f(x)=g(x)+b(x)" alt="f(x)=g(x)+b(x)" class="ee_img tr_noresize" eeimg="1"> is:

<img src="https://www.zhihu.com/equation?tex=g(x)=\sum_j{(\frac{1}{\left\lvert Q_j\right\rvert}\int_{Q_j}{f(t)dt})\chi_{Q_j}(x)+f(x)\chi_{\mathbb{R}^n\setminus\Omega}(x)}\\" alt="g(x)=\sum_j{(\frac{1}{\left\lvert Q_j\right\rvert}\int_{Q_j}{f(t)dt})\chi_{Q_j}(x)+f(x)\chi_{\mathbb{R}^n\setminus\Omega}(x)}\\" class="ee_img tr_noresize" eeimg="1">


and

<img src="https://www.zhihu.com/equation?tex=b(x)=f(x)-g(x)=\sum_jb_j(x)=\sum_j{(f(x)-\frac{1}{\left\lvert Q_j\right\rvert}\int_{Q_j}f(t)d t)}\chi_{Q_j}(x)\\" alt="b(x)=f(x)-g(x)=\sum_jb_j(x)=\sum_j{(f(x)-\frac{1}{\left\lvert Q_j\right\rvert}\int_{Q_j}f(t)d t)}\chi_{Q_j}(x)\\" class="ee_img tr_noresize" eeimg="1">


Generally, to estimate the size of the set
<img src="https://www.zhihu.com/equation?tex=\{x:\left\lvert f(x)\right\rvert>c\}" alt="\{x:\left\lvert f(x)\right\rvert>c\}" class="ee_img tr_noresize" eeimg="1">, we can use
<img src="https://www.zhihu.com/equation?tex=(\frac{\left\lvert f(x)\right\rvert}{c})^p>1" alt="(\frac{\left\lvert f(x)\right\rvert}{c})^p>1" class="ee_img tr_noresize" eeimg="1"> in that set and integral
the index function of that set on <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert=\int_{\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert}1dt\leq\int_{\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert}\left(\frac{\left\lvert f(x)\right\rvert}{c}\right)^p d t\leq\frac{1}{c^p}\int\left\lvert f(x)\right\rvert^p d t\\" alt="\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert=\int_{\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert}1dt\leq\int_{\left\lvert\{x:\left\lvert f(x)\right\rvert>c\}\right\rvert}\left(\frac{\left\lvert f(x)\right\rvert}{c}\right)^p d t\leq\frac{1}{c^p}\int\left\lvert f(x)\right\rvert^p d t\\" class="ee_img tr_noresize" eeimg="1">


This inequality sometimes called Markov inequality.

Remark 5.2.2 (notes on proof of lemma 5.11 in book). In proof of theorem 5.20 in book, it says <img src="https://www.zhihu.com/equation?tex=f\in L^\infty_c" alt="f\in L^\infty_c" class="ee_img tr_noresize" eeimg="1"> was only
imposed to ensure the
<img src="https://www.zhihu.com/equation?tex=I_\epsilon=\int_{\left\lvert y\right\rvert>\epsilon}{K(-y)f(y)dy}" alt="I_\epsilon=\int_{\left\lvert y\right\rvert>\epsilon}{K(-y)f(y)dy}" class="ee_img tr_noresize" eeimg="1">
exists. <img src="https://www.zhihu.com/equation?tex=M_pf(x)" alt="M_pf(x)" class="ee_img tr_noresize" eeimg="1"> increases as p increases by Holder inequality. let
<img src="https://www.zhihu.com/equation?tex=r<q" alt="r<q" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\frac{1}{r}=\frac{1}{p}+\frac{1}{q}" alt="\frac{1}{r}=\frac{1}{p}+\frac{1}{q}" class="ee_img tr_noresize" eeimg="1">, we have 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        (\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^r d t)^\frac{1}{r} & \leq \frac{1}{\left\lvert Q\right\rvert^\frac{1}{r}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p} (\int_{Q}1^q d t)^\frac{1}{q}=\frac{\left\lvert Q\right\rvert^\frac{1}{q}}{\left\lvert Q\right\rvert^\frac{1}{r}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p} \\
                                                                & =\frac{1}{\left\lvert Q\right\rvert^\frac{1}{p}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p}=(\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p}
    \end{aligned}\\" alt="\begin{aligned}
        (\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^r d t)^\frac{1}{r} & \leq \frac{1}{\left\lvert Q\right\rvert^\frac{1}{r}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p} (\int_{Q}1^q d t)^\frac{1}{q}=\frac{\left\lvert Q\right\rvert^\frac{1}{q}}{\left\lvert Q\right\rvert^\frac{1}{r}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p} \\
                                                                & =\frac{1}{\left\lvert Q\right\rvert^\frac{1}{p}}(\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p}=(\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^p d t)^\frac{1}{p}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">



Remark 1.5.2.3(notes on proof of inequality (1.3)). We have
<img src="https://www.zhihu.com/equation?tex=(Tf)^\#(0)=\sup_{0\in Q}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-(Tf)_Q\right\rvert dy}" alt="(Tf)^\#(0)=\sup_{0\in Q}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-(Tf)_Q\right\rvert dy}" class="ee_img tr_noresize" eeimg="1">
with <img src="https://www.zhihu.com/equation?tex=(Tf)_Q=\frac{1}{\left\lvert Q\right\rvert}\int_Q{Tf(x)dx}" alt="(Tf)_Q=\frac{1}{\left\lvert Q\right\rvert}\int_Q{Tf(x)dx}" class="ee_img tr_noresize" eeimg="1">

We know
<img src="https://www.zhihu.com/equation?tex=(T f)^\#(x)\cong\sup_{x\in Q}\inf_{a\in\mathbb{R}}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-a\right\rvert dy}" alt="(T f)^\#(x)\cong\sup_{x\in Q}\inf_{a\in\mathbb{R}}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-a\right\rvert dy}" class="ee_img tr_noresize" eeimg="1">,
where <img src="https://www.zhihu.com/equation?tex=\cong" alt="\cong" class="ee_img tr_noresize" eeimg="1"> is used to indicate that each side is bounded by the other
times an absolute constant (refer equation (3.1) in section 3, chapter 2
in book).

Observe that the cube <img src="https://www.zhihu.com/equation?tex=[-r,r]^n" alt="[-r,r]^n" class="ee_img tr_noresize" eeimg="1"> containing 0 is almost everywhere
contained in the open ball <img src="https://www.zhihu.com/equation?tex=B(0,n^\frac{1}{2}r)" alt="B(0,n^\frac{1}{2}r)" class="ee_img tr_noresize" eeimg="1">. Let <img src="https://www.zhihu.com/equation?tex=d" alt="d" class="ee_img tr_noresize" eeimg="1"> be the side
length of <img src="https://www.zhihu.com/equation?tex=Q" alt="Q" class="ee_img tr_noresize" eeimg="1">. Let <img src="https://www.zhihu.com/equation?tex=Q^2" alt="Q^2" class="ee_img tr_noresize" eeimg="1"> be the cube with origin as center and with side
length 2 times that of <img src="https://www.zhihu.com/equation?tex=Q" alt="Q" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=0\in Q" alt="0\in Q" class="ee_img tr_noresize" eeimg="1"> implies <img src="https://www.zhihu.com/equation?tex=Q\subset Q^2" alt="Q\subset Q^2" class="ee_img tr_noresize" eeimg="1">. Thus

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        (T f)^\#(0)&\leq C\sup_{0\in Q}\inf_{a\in\mathbb{R}}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-a\right\rvert dy}\\
                    &\leq C\sup_{r>0}\inf_{a\in\mathbb{R}}\frac{1}{2^nr^n}\int_{B(0,n^\frac{1}{2}r)}{\left\lvert Tf(y)-a\right\rvert dy}\\
                    &\leq C\sup_{r>0}\frac{1}{2^nr^n}\int_{\left\lvert y\right\rvert\leq n^\frac{1}{2}r}{\left\lvert Tf(y)-I_\epsilon\right\rvert dy}\\
                    & =C'\sup_{\epsilon>0}\epsilon^{-n}\int_{\left\lvert y\right\rvert\leq \frac{\epsilon}{2}}{\left\lvert Tf(y)-I_\epsilon\right\rvert dy}\\
    \end{aligned}\\" alt="\begin{aligned}
        (T f)^\#(0)&\leq C\sup_{0\in Q}\inf_{a\in\mathbb{R}}\frac{1}{\left\lvert Q\right\rvert}\int_Q{\left\lvert Tf(y)-a\right\rvert dy}\\
                    &\leq C\sup_{r>0}\inf_{a\in\mathbb{R}}\frac{1}{2^nr^n}\int_{B(0,n^\frac{1}{2}r)}{\left\lvert Tf(y)-a\right\rvert dy}\\
                    &\leq C\sup_{r>0}\frac{1}{2^nr^n}\int_{\left\lvert y\right\rvert\leq n^\frac{1}{2}r}{\left\lvert Tf(y)-I_\epsilon\right\rvert dy}\\
                    & =C'\sup_{\epsilon>0}\epsilon^{-n}\int_{\left\lvert y\right\rvert\leq \frac{\epsilon}{2}}{\left\lvert Tf(y)-I_\epsilon\right\rvert dy}\\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 .

To estimate
<img src="https://www.zhihu.com/equation?tex=\epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}" alt="\epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}" class="ee_img tr_noresize" eeimg="1">,
we use lemma 7.11 in book and Hormander's condition: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & \epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}                                                  \\
        \leq & C_pM_pf(0)+\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert\left\lvert f(y)\right\rvert dxd y}                              \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert dxdy}                  \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(x-y)-K(-y)\right\rvert d y)dx} \\
        =    & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(y-x)-K(y)\right\rvert d y)dx}  \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{B_kdx}                                            \\
        =    & C_p\lVert f\rVert_\infty+B_k\lVert f\rVert_\infty
    \end{aligned}\\" alt="\begin{aligned}
             & \epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}                                                  \\
        \leq & C_pM_pf(0)+\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert\left\lvert f(y)\right\rvert dxd y}                              \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert dxdy}                  \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(x-y)-K(-y)\right\rvert d y)dx} \\
        =    & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(y-x)-K(y)\right\rvert d y)dx}  \\
        \leq & C_p\lVert f\rVert_\infty+\lVert f\rVert_\infty\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{B_kdx}                                            \\
        =    & C_p\lVert f\rVert_\infty+B_k\lVert f\rVert_\infty
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 We can change the sign of <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1"> in fifth line
since the region is symmetric.

Remark 1.5.2.4. I don't know why
<img src="https://www.zhihu.com/equation?tex=\frac{1}{\pi}\log{\left\lvert\frac{x-a}{x-b}\right\rvert}" alt="\frac{1}{\pi}\log{\left\lvert\frac{x-a}{x-b}\right\rvert}" class="ee_img tr_noresize" eeimg="1">, with <img src="https://www.zhihu.com/equation?tex=a<b" alt="a<b" class="ee_img tr_noresize" eeimg="1">
is in <img src="https://www.zhihu.com/equation?tex=weak-L^1\cap\operatorname{BMO}" alt="weak-L^1\cap\operatorname{BMO}" class="ee_img tr_noresize" eeimg="1">.

5.3 Restriction and extension of singular integral operator

To understand the behavior of singular integral operators in <img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">, we ask if there is a subspace of <img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">, on which the
singular integral operator is strong type <img src="https://www.zhihu.com/equation?tex=(1,1)" alt="(1,1)" class="ee_img tr_noresize" eeimg="1">, and if the singular
integral operator can \"extend\" from <img src="https://www.zhihu.com/equation?tex=L^2\cap L^\infty" alt="L^2\cap L^\infty" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">.

For the first question, we introduce the Banach space <img src="https://www.zhihu.com/equation?tex=H^1_{at}" alt="H^1_{at}" class="ee_img tr_noresize" eeimg="1"> (atomic
<img src="https://www.zhihu.com/equation?tex=H^1" alt="H^1" class="ee_img tr_noresize" eeimg="1">). More study of <img src="https://www.zhihu.com/equation?tex=H^1_{at}" alt="H^1_{at}" class="ee_img tr_noresize" eeimg="1"> is in Chapter 3. You can also refer
section 5 and 6 in chapter 2 in Stein's *Functional Analysis*.

For the second question, notice <img src="https://www.zhihu.com/equation?tex=L^p\cap L^\infty" alt="L^p\cap L^\infty" class="ee_img tr_noresize" eeimg="1"> is not dense in
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">. The extension is not a trivial step. However, the function
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f+C" alt="f+C" class="ee_img tr_noresize" eeimg="1"> with constant <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> behavior the same in space
<img src="https://www.zhihu.com/equation?tex=\operatorname{BMO}" alt="\operatorname{BMO}" class="ee_img tr_noresize" eeimg="1">. Thus we introduce our definition of new <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> on
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">.

Proposition 5.3.1 (proposition 5.15 in book). Given a singular integral operator <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> with kernel <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, for each
<img src="https://www.zhihu.com/equation?tex=f\in L^\infty" alt="f\in L^\infty" class="ee_img tr_noresize" eeimg="1"> we define:

<img src="https://www.zhihu.com/equation?tex=T f(x)=\lim_{j\to\infty}{(T(f\chi_{B_j})(x)-\int_{1<\left\lvert y\right\rvert<j}K(-y)f(y)d y)}\\" alt="T f(x)=\lim_{j\to\infty}{(T(f\chi_{B_j})(x)-\int_{1<\left\lvert y\right\rvert<j}K(-y)f(y)d y)}\\" class="ee_img tr_noresize" eeimg="1">


The sequence to the right converges locally in <img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1"> and also pointwise
a.e., and the extended operator <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> satisfies:

<img src="https://www.zhihu.com/equation?tex=\lVert Tf\rVert_{\operatorname{BMO}}\leq C_\infty\lVert f\rVert_\infty\quad (f\in L^\infty)\\" alt="\lVert Tf\rVert_{\operatorname{BMO}}\leq C_\infty\lVert f\rVert_\infty\quad (f\in L^\infty)\\" class="ee_img tr_noresize" eeimg="1">



Remark 5.3.1 (notes on proof of proposition 5.15 in book). It is not clear that <img src="https://www.zhihu.com/equation?tex=g_j(x)" alt="g_j(x)" class="ee_img tr_noresize" eeimg="1"> converges pointwise. <img src="https://www.zhihu.com/equation?tex=g_j(x)" alt="g_j(x)" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=L^1(F)" alt="L^1(F)" class="ee_img tr_noresize" eeimg="1">
since <img src="https://www.zhihu.com/equation?tex=g_l(x)\in L^1(F)" alt="g_l(x)\in L^1(F)" class="ee_img tr_noresize" eeimg="1"> and the integral is bounded by
<img src="https://www.zhihu.com/equation?tex=B_K\lVert f\rVert_\infty" alt="B_K\lVert f\rVert_\infty" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is compact.

5.4 More precise estimation for more regular kernel

If the kernel is more regular, the estimation of operator <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> can be
replaced by maximal function. More precisely:

Definition 5.4.1 (definition 5.17 in book). A singular integral operator <img src="https://www.zhihu.com/equation?tex=Tf=K*f" alt="Tf=K*f" class="ee_img tr_noresize" eeimg="1"> is called regular if its kernel
satisfies the following two conditions:

1.  <img src="https://www.zhihu.com/equation?tex=\left\lvert K(x)\right\rvert\leq B\left\lvert x\right\rvert^{-n}" alt="\left\lvert K(x)\right\rvert\leq B\left\lvert x\right\rvert^{-n}" class="ee_img tr_noresize" eeimg="1">
    for <img src="https://www.zhihu.com/equation?tex=x\neq 0" alt="x\neq 0" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=\left\lvert K(x-y)-K(x)\right\rvert\leq B\left\lvert y\right\rvert\left\lvert x\right\rvert^{-n-1}" alt="\left\lvert K(x-y)-K(x)\right\rvert\leq B\left\lvert y\right\rvert\left\lvert x\right\rvert^{-n-1}" class="ee_img tr_noresize" eeimg="1">
    for <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert>2\left\lvert y\right\rvert>0" alt="\left\lvert x\right\rvert>2\left\lvert y\right\rvert>0" class="ee_img tr_noresize" eeimg="1">

Let
<img src="https://www.zhihu.com/equation?tex=T_\epsilon f(x)=\int_{\left\lvert y\right\rvert>\epsilon}{K(y)f(x-y)dy}" alt="T_\epsilon f(x)=\int_{\left\lvert y\right\rvert>\epsilon}{K(y)f(x-y)dy}" class="ee_img tr_noresize" eeimg="1">
and
<img src="https://www.zhihu.com/equation?tex=T^*f(x)=\sup_{\epsilon>0}{\left\lvert T_\epsilon f(x)\right\rvert}" alt="T^*f(x)=\sup_{\epsilon>0}{\left\lvert T_\epsilon f(x)\right\rvert}" class="ee_img tr_noresize" eeimg="1">.
The estimation is the following:

Theorem 5.4.2(theorem 5.20 in book). If <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> is a regular singular integral operator and <img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=1\leq p<\infty" alt="1\leq p<\infty" class="ee_img tr_noresize" eeimg="1">, then the following inequalities are verified:

1.  <img src="https://www.zhihu.com/equation?tex=(Tf)^\#(x)\leq C_qM_qf(x)\quad (q>1)" alt="(Tf)^\#(x)\leq C_qM_qf(x)\quad (q>1)" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=T^*f(x)\leq C_qM_qf(x)+CM(Tf)(x)\quad (q>1)" alt="T^*f(x)\leq C_qM_qf(x)+CM(Tf)(x)\quad (q>1)" class="ee_img tr_noresize" eeimg="1">

3.  <img src="https://www.zhihu.com/equation?tex=\lVert T^*f\rVert_p\leq C_p\lVert f\rVert_p\quad (1<p<\infty)" alt="\lVert T^*f\rVert_p\leq C_p\lVert f\rVert_p\quad (1<p<\infty)" class="ee_img tr_noresize" eeimg="1">

4.  <img src="https://www.zhihu.com/equation?tex=\left\lvert\{x:T^*f(x)>t\}\right\rvert\leq Ct^{-1}\lVert f\rVert_1\quad (t>0)" alt="\left\lvert\{x:T^*f(x)>t\}\right\rvert\leq Ct^{-1}\lVert f\rVert_1\quad (t>0)" class="ee_img tr_noresize" eeimg="1">

Remark 5.4.1 (notes on proof of theorem 5.20 in book). 3 is a trivial consequence of 2 and the <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> inequalities for the
operators <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">. The <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> inequality for operator <img src="https://www.zhihu.com/equation?tex=M_q" alt="M_q" class="ee_img tr_noresize" eeimg="1"> is
similar with operator <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1">. By 2,
<img src="https://www.zhihu.com/equation?tex=\lVert T^*f\rVert_p\leq \lVert C_qM_qf\rVert_p+\lVert CM(Tf)\rVert_p" alt="\lVert T^*f\rVert_p\leq \lVert C_qM_qf\rVert_p+\lVert CM(Tf)\rVert_p" class="ee_img tr_noresize" eeimg="1">,
and
<img src="https://www.zhihu.com/equation?tex=\lVert CM(Tf)\rVert_p\leq C'\lVert Tf\rVert_p\leq C''\lVert f\rVert_p" alt="\lVert CM(Tf)\rVert_p\leq C'\lVert Tf\rVert_p\leq C''\lVert f\rVert_p" class="ee_img tr_noresize" eeimg="1">.

Now we prove the <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> inequality for operator <img src="https://www.zhihu.com/equation?tex=M_q" alt="M_q" class="ee_img tr_noresize" eeimg="1">. We choose <img src="https://www.zhihu.com/equation?tex=q" alt="q" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=1<q<p" alt="1<q<p" class="ee_img tr_noresize" eeimg="1">: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
            \int_{\mathbb{R}^n}(M_q f(x))^p dx&=p\int_0^\infty  t^{p-1}\left\lvert\{x:M_qf(x)>t\}\right\rvert d t \\
            &=p\int_0^\infty  t^{p-1}\left\lvert\{x:\sup((\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^q d t)^\frac{1}{q})>t\}\right\rvert d t\\
            &=p\int_0^\infty t^{p-1}\left\lvert\{x:\sup((\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^q d t))>t^q\}\right\rvert d t\\
            &\leq C p\int_0^\infty t^{p-1}\int_{\{x:\left\lvert f(x)\right\rvert^q>\frac{t^q}{2}\}}\frac{\left\lvert f(x)\right\rvert^q}{t^q}d x d t\\
            &=C p\int_0^\infty \int_{\mathbb{R}^n}t^{p-1}\frac{\left\lvert f(x)\right\rvert^q}{t^q}\chi_{\{x:\left\lvert f(x)\right\rvert^q>\frac{t^q}{2}\}}dx d t\\
            &=C p\int_{\mathbb{R}^n}\int_0^{\left\lvert f(x)\right\rvert 2^{\frac{1}{q}}} t^{p-1-q}\left\lvert f(x)\right\rvert^q d x d t\\
            &=\frac{Cp}{p-q}\int_{\mathbb{R}^n} (\left\lvert f(x)\right\rvert 2^{\frac{1}{q}})^{p-q}\left\lvert f(x)\right\rvert^q d t\\
            &=\frac{Cp2^{\frac{p-q}{q}}}{p-q}\int_{\mathbb{R}^n}\left\lvert f(x)\right\rvert^p d t\\
        \end{aligned}\\" alt="\begin{aligned}
            \int_{\mathbb{R}^n}(M_q f(x))^p dx&=p\int_0^\infty  t^{p-1}\left\lvert\{x:M_qf(x)>t\}\right\rvert d t \\
            &=p\int_0^\infty  t^{p-1}\left\lvert\{x:\sup((\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^q d t)^\frac{1}{q})>t\}\right\rvert d t\\
            &=p\int_0^\infty t^{p-1}\left\lvert\{x:\sup((\frac{1}{\left\lvert Q\right\rvert}\int_{Q}\left\lvert f(t)\right\rvert^q d t))>t^q\}\right\rvert d t\\
            &\leq C p\int_0^\infty t^{p-1}\int_{\{x:\left\lvert f(x)\right\rvert^q>\frac{t^q}{2}\}}\frac{\left\lvert f(x)\right\rvert^q}{t^q}d x d t\\
            &=C p\int_0^\infty \int_{\mathbb{R}^n}t^{p-1}\frac{\left\lvert f(x)\right\rvert^q}{t^q}\chi_{\{x:\left\lvert f(x)\right\rvert^q>\frac{t^q}{2}\}}dx d t\\
            &=C p\int_{\mathbb{R}^n}\int_0^{\left\lvert f(x)\right\rvert 2^{\frac{1}{q}}} t^{p-1-q}\left\lvert f(x)\right\rvert^q d x d t\\
            &=\frac{Cp}{p-q}\int_{\mathbb{R}^n} (\left\lvert f(x)\right\rvert 2^{\frac{1}{q}})^{p-q}\left\lvert f(x)\right\rvert^q d t\\
            &=\frac{Cp2^{\frac{p-q}{q}}}{p-q}\int_{\mathbb{R}^n}\left\lvert f(x)\right\rvert^p d t\\
        \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">



Thus
<img src="https://www.zhihu.com/equation?tex=\lVert T^*f\rVert_p\leq \lVert C_qM_qf\rVert_p+\lVert CM(Tf)\rVert_p\leq C\lVert f\rVert_p" alt="\lVert T^*f\rVert_p\leq \lVert C_qM_qf\rVert_p+\lVert CM(Tf)\rVert_p\leq C\lVert f\rVert_p" class="ee_img tr_noresize" eeimg="1">

Remark 5.4.2 (notes on corollary 5.22 in book) Notice (5.19) implies (b) in
definition 5.1. By easy computation (5.18) implies (5.3). By proposition
5.5 in book, 5.1(b), (5.3) and (5.4) implies that <img src="https://www.zhihu.com/equation?tex=T=k*f" alt="T=k*f" class="ee_img tr_noresize" eeimg="1"> is a singular
integral operator. It is not clear how to pass
<img src="https://www.zhihu.com/equation?tex=\mathscr{S}(\mathbb{R}^n)" alt="\mathscr{S}(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=L^p(\mathbb{R}^n)" alt="L^p(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">.

5.5 Proof of proposition 5.5 and 5.6 in book

Remark 5.5.1 (notes on proof of proposition 5.5 in book). Let <img src="https://www.zhihu.com/equation?tex=A=\{x:\epsilon<\left\lvert x\right\rvert<R\}" alt="A=\{x:\epsilon<\left\lvert x\right\rvert<R\}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=B=\{x:\epsilon<\left\lvert x-y\right\rvert<R\}" alt="B=\{x:\epsilon<\left\lvert x-y\right\rvert<R\}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=C=\{x:\left\lvert x-y\right\rvert\leq\epsilon\}" alt="C=\{x:\left\lvert x-y\right\rvert\leq\epsilon\}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=B=\{x:\left\lvert x-y\right\rvert\geq R\}" alt="B=\{x:\left\lvert x-y\right\rvert\geq R\}" class="ee_img tr_noresize" eeimg="1"> 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & \int_{\mathbb{R}^n}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx                                                                            \\
        =    & \int_{A\cap B}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx+\int_{\mathbb{R}^n\setminus (A\cap B)}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx \\
        =    & \int_{A\cap B}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cup B^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx                                           \\
        \leq & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx  +\int_{B^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx   \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c}\left\lvert k_\epsilon^R(x-y)\right\rvert dx  +\int_{B^c}\left\lvert k_\epsilon^R(x)\right\rvert dx                                     \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx  +\int_{B^c\cap A}\left\lvert k(x)\right\rvert dx                                               \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx  +\int_{C\cap A}\left\lvert k(x)\right\rvert dx+\int_{D\cap A}\left\lvert k(x)\right\rvert dx
    \end{aligned}\\" alt="\begin{aligned}
             & \int_{\mathbb{R}^n}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx                                                                            \\
        =    & \int_{A\cap B}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx+\int_{\mathbb{R}^n\setminus (A\cap B)}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx \\
        =    & \int_{A\cap B}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cup B^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx                                           \\
        \leq & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx  +\int_{B^c}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx   \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c}\left\lvert k_\epsilon^R(x-y)\right\rvert dx  +\int_{B^c}\left\lvert k_\epsilon^R(x)\right\rvert dx                                     \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx  +\int_{B^c\cap A}\left\lvert k(x)\right\rvert dx                                               \\
        =    & \int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx+\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx  +\int_{C\cap A}\left\lvert k(x)\right\rvert dx+\int_{D\cap A}\left\lvert k(x)\right\rvert dx
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 If <img src="https://www.zhihu.com/equation?tex=x\in C" alt="x\in C" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert-\left\lvert y\right\rvert\leq\left\lvert x-y\right\rvert\leq\epsilon" alt="\left\lvert x\right\rvert-\left\lvert y\right\rvert\leq\left\lvert x-y\right\rvert\leq\epsilon" class="ee_img tr_noresize" eeimg="1">,
then
<img src="https://www.zhihu.com/equation?tex=C\subset \{x:\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert\}" alt="C\subset \{x:\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert\}" class="ee_img tr_noresize" eeimg="1">.
If <img src="https://www.zhihu.com/equation?tex=x\in D" alt="x\in D" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert+\left\lvert y\right\rvert\geq\left\lvert x-y\right\rvert\geq R" alt="\left\lvert x\right\rvert+\left\lvert y\right\rvert\geq\left\lvert x-y\right\rvert\geq R" class="ee_img tr_noresize" eeimg="1">,
then
<img src="https://www.zhihu.com/equation?tex=D\subset \{x:R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert\leq R\}" alt="D\subset \{x:R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert\leq R\}" class="ee_img tr_noresize" eeimg="1">.
Since <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> is large enough and <img src="https://www.zhihu.com/equation?tex=\epsilon" alt="\epsilon" class="ee_img tr_noresize" eeimg="1"> is small enough, we have
<img src="https://www.zhihu.com/equation?tex=C\cap A\subset \{x:\epsilon<\left\lvert x\right\rvert\leq\epsilon+\left\lvert y\right\rvert\}" alt="C\cap A\subset \{x:\epsilon<\left\lvert x\right\rvert\leq\epsilon+\left\lvert y\right\rvert\}" class="ee_img tr_noresize" eeimg="1">
and
<img src="https://www.zhihu.com/equation?tex=D\cap A\subset \{x:R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert\leq R\}" alt="D\cap A\subset \{x:R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert\leq R\}" class="ee_img tr_noresize" eeimg="1">.
Thus

<img src="https://www.zhihu.com/equation?tex=\int_{C\cap A}\left\lvert k(x)\right\rvert dx+\int_{D\cap A}\left\lvert k(x)\right\rvert dx\leq\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx\\" alt="\int_{C\cap A}\left\lvert k(x)\right\rvert dx+\int_{D\cap A}\left\lvert k(x)\right\rvert dx\leq\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx\\" class="ee_img tr_noresize" eeimg="1">


Let <img src="https://www.zhihu.com/equation?tex=x-y=t" alt="x-y=t" class="ee_img tr_noresize" eeimg="1">,

<img src="https://www.zhihu.com/equation?tex=\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx=\int_{\epsilon<\left\lvert t\right\rvert<R~and~\left\lvert t+y\right\rvert\leq\epsilon}\left\lvert k(t)\right\rvert d t+\int_{\epsilon<\left\lvert t\right\rvert<R~and~\left\lvert t+y\right\rvert\geq R}\left\lvert k(t)\right\rvert d t\\" alt="\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx=\int_{\epsilon<\left\lvert t\right\rvert<R~and~\left\lvert t+y\right\rvert\leq\epsilon}\left\lvert k(t)\right\rvert d t+\int_{\epsilon<\left\lvert t\right\rvert<R~and~\left\lvert t+y\right\rvert\geq R}\left\lvert k(t)\right\rvert d t\\" class="ee_img tr_noresize" eeimg="1">


Use almost the same argument, we can show:

<img src="https://www.zhihu.com/equation?tex=\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx\leq\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx\\" alt="\int_{A^c\cap B}\left\lvert k(x-y)\right\rvert dx\leq\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx\\" class="ee_img tr_noresize" eeimg="1">


Thus 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int_{\mathbb{R}^n}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx & \leq 2\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+2\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx \\
                                                                     & +\int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx
    \end{aligned}\\" alt="\begin{aligned}
        \int_{\mathbb{R}^n}\left\lvert k_\epsilon^R(x-y)-k_\epsilon^R(x)\right\rvert dx & \leq 2\int_{\epsilon<\left\lvert x\right\rvert\leq \epsilon+\left\lvert y\right\rvert}\left\lvert k(x)\right\rvert dx+2\int_{R-\left\lvert y\right\rvert\leq\left\lvert x\right\rvert< R}\left\lvert k(x)\right\rvert dx \\
                                                                     & +\int_{A}\left\lvert k(x-y)-k(x)\right\rvert dx
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" alt="\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" class="ee_img tr_noresize" eeimg="1">
implies
<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" alt="\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx= & \sum_{j=0}^\infty{\int_{\frac{r}{2^{j+1}}\left\lvert x\right\rvert<\frac{r}{2^j}}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx}\leq\sum_{j=0}^\infty{\int_{\frac{r}{2^{j+1}}\left\lvert x\right\rvert<\frac{r}{2^j}}\left\lvert k(x)\right\rvert\frac{r}{2^j}dx} \\
        =                                    & \sum_{j=0}^\infty{C_1\frac{r}{2^j}}=2C_1r
    \end{aligned}\\" alt="\begin{aligned}
        \int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx= & \sum_{j=0}^\infty{\int_{\frac{r}{2^{j+1}}\left\lvert x\right\rvert<\frac{r}{2^j}}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx}\leq\sum_{j=0}^\infty{\int_{\frac{r}{2^{j+1}}\left\lvert x\right\rvert<\frac{r}{2^j}}\left\lvert k(x)\right\rvert\frac{r}{2^j}dx} \\
        =                                    & \sum_{j=0}^\infty{C_1\frac{r}{2^j}}=2C_1r
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">


<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" alt="\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" class="ee_img tr_noresize" eeimg="1">
implies
<img src="https://www.zhihu.com/equation?tex=\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" alt="\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq & \int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\frac{\left\lvert x\right\rvert}{r}dx=\frac{1}{r}\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx \\
        \leq                                & \frac{1}{r}\int_{\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq\frac{1}{r}8C_1r=8C_1
    \end{aligned}\\" alt="\begin{aligned}
        \int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq & \int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\frac{\left\lvert x\right\rvert}{r}dx=\frac{1}{r}\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx \\
        \leq                                & \frac{1}{r}\int_{\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq\frac{1}{r}8C_1r=8C_1
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus
<img src="https://www.zhihu.com/equation?tex=\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" alt="\int_{r<\left\lvert x\right\rvert<2r}\left\lvert k(x)\right\rvert dx\leq C_1" class="ee_img tr_noresize" eeimg="1">
and
<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" alt="\int_{\left\lvert x\right\rvert<r}\left\lvert k(x)\right\rvert\left\lvert x\right\rvert dx\leq 4C_1r" class="ee_img tr_noresize" eeimg="1">
are equivalent.

Remark 5.5.2 (notes on proof of proposition 5.6 in book). Let <img src="https://www.zhihu.com/equation?tex=tx'=x-y" alt="tx'=x-y" class="ee_img tr_noresize" eeimg="1">, we have: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(x-y)-\Omega(x)\right\rvert}{\left\lvert x-y\right\rvert^n}dx}= & \int_{\left\lvert tx'+y\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}d(tx'+y)}            \\
        \leq                                                                        & \int_{\left\lvert tx'\right\rvert+\left\lvert y\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}d(tx')}        \\
        =                                                                           & \iint_{{t}>\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}t^{n-1}d t d\sigma(x')}        \\
        =                                                                           & \int_{{t}>\left\lvert y\right\rvert}\int_{\left\lvert x'\right\rvert=1}{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert d\sigma(x')\frac{dt}{t}}
    \end{aligned}\\" alt="\begin{aligned}
        \int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(x-y)-\Omega(x)\right\rvert}{\left\lvert x-y\right\rvert^n}dx}= & \int_{\left\lvert tx'+y\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}d(tx'+y)}            \\
        \leq                                                                        & \int_{\left\lvert tx'\right\rvert+\left\lvert y\right\rvert>2\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}d(tx')}        \\
        =                                                                           & \iint_{{t}>\left\lvert y\right\rvert}{\frac{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert}{t^n}t^{n-1}d t d\sigma(x')}        \\
        =                                                                           & \int_{{t}>\left\lvert y\right\rvert}\int_{\left\lvert x'\right\rvert=1}{\left\lvert\Omega(tx')-\Omega(tx'+y)\right\rvert d\sigma(x')\frac{dt}{t}}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 By mean value theorem, we have
<img src="https://www.zhihu.com/equation?tex=\left\lvert x-y\right\rvert^{-n}-\left\lvert x\right\rvert^{-n}=n\frac{y\cdot \xi}{\left\lvert\xi\right\rvert^{n+2}}" alt="\left\lvert x-y\right\rvert^{-n}-\left\lvert x\right\rvert^{-n}=n\frac{y\cdot \xi}{\left\lvert\xi\right\rvert^{n+2}}" class="ee_img tr_noresize" eeimg="1">
with <img src="https://www.zhihu.com/equation?tex=\xi=(1-c)(x-y)+cx=x-(1-c)y" alt="\xi=(1-c)(x-y)+cx=x-(1-c)y" class="ee_img tr_noresize" eeimg="1">. Notice
<img src="https://www.zhihu.com/equation?tex=\left\lvert\xi\right\rvert\geq \left\lvert x\right\rvert-(1-c)\left\lvert y\right\rvert\geq \left\lvert x\right\rvert-\left\lvert y\right\rvert" alt="\left\lvert\xi\right\rvert\geq \left\lvert x\right\rvert-(1-c)\left\lvert y\right\rvert\geq \left\lvert x\right\rvert-\left\lvert y\right\rvert" class="ee_img tr_noresize" eeimg="1">.
Since
<img src="https://www.zhihu.com/equation?tex=\left\lvert y\right\rvert\leq \frac{\left\lvert x\right\rvert}{2}" alt="\left\lvert y\right\rvert\leq \frac{\left\lvert x\right\rvert}{2}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\left\lvert\xi\right\rvert\geq \frac{\left\lvert x\right\rvert}{2}" alt="\left\lvert\xi\right\rvert\geq \frac{\left\lvert x\right\rvert}{2}" class="ee_img tr_noresize" eeimg="1">.
Thus

<img src="https://www.zhihu.com/equation?tex=\left\lvert\left\lvert x-y\right\rvert^{-n}-\left\lvert x\right\rvert^{-n}\right\rvert\leq n\frac{\left\lvert y\right\rvert\left\lvert \xi\right\rvert}{\left\lvert\xi\right\rvert^{n+2}}\leq n2^{n+1}\frac{\left\lvert y\right\rvert}{\left\lvert x\right\rvert^{n+1}}\\" alt="\left\lvert\left\lvert x-y\right\rvert^{-n}-\left\lvert x\right\rvert^{-n}\right\rvert\leq n\frac{\left\lvert y\right\rvert\left\lvert \xi\right\rvert}{\left\lvert\xi\right\rvert^{n+2}}\leq n2^{n+1}\frac{\left\lvert y\right\rvert}{\left\lvert x\right\rvert^{n+1}}\\" class="ee_img tr_noresize" eeimg="1">


