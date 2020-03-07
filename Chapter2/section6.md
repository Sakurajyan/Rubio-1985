6. Multipliers
===========

In this section, we keep talk about the convergence property and norm
estimate of convolution operator. In last section, we know some
convolution operator can not be defined as usual Lebesgue integral but a
limit process called singular integral. The stimulation of studying the
convolution operator is that the convolution operator is equivalent to
translation invariant operator.

Suppose <img src="https://www.zhihu.com/equation?tex=Tg=\int f(x-y)g(y)dy" alt="Tg=\int f(x-y)g(y)dy" class="ee_img tr_noresize" eeimg="1"> is a convolution operator. Then by
Fourier transform, we have <img src="https://www.zhihu.com/equation?tex=(Tf)^\wedge=\hat{f}\hat{g}" alt="(Tf)^\wedge=\hat{f}\hat{g}" class="ee_img tr_noresize" eeimg="1">. The concept of
multipliers give us another approach to study the convolution operator
<img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">:

Definition 6.0.1. Let <img src="https://www.zhihu.com/equation?tex=1\leq p<\infty" alt="1\leq p<\infty" class="ee_img tr_noresize" eeimg="1">. Given <img src="https://www.zhihu.com/equation?tex=m\in L^\infty" alt="m\in L^\infty" class="ee_img tr_noresize" eeimg="1">, we say that <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a
(Fourier) multiplier for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> if the operator <img src="https://www.zhihu.com/equation?tex=T_m" alt="T_m" class="ee_img tr_noresize" eeimg="1">, initially defined
in <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> by the relation: 
<img src="https://www.zhihu.com/equation?tex=(T_mf)^\wedge(\xi)=m(\xi)\hat{f}(\xi)\\" alt="(T_mf)^\wedge(\xi)=m(\xi)\hat{f}(\xi)\\" class="ee_img tr_noresize" eeimg="1">


satisfies the inequality

<img src="https://www.zhihu.com/equation?tex=\lVert T_mf\rVert_p\leq C\lVert f\rVert_p  \quad (f\in L^2\cap L^p)\\" alt="\lVert T_mf\rVert_p\leq C\lVert f\rVert_p  \quad (f\in L^2\cap L^p)\\" class="ee_img tr_noresize" eeimg="1">



 Remark 6.0.1. Given a sequence of kernels <img src="https://www.zhihu.com/equation?tex=(k_N)_N" alt="(k_N)_N" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">, if <img src="https://www.zhihu.com/equation?tex=T_Nf=k_N*f" alt="T_Nf=k_N*f" class="ee_img tr_noresize" eeimg="1"> are
uniformly bounded from <img src="https://www.zhihu.com/equation?tex=\mathscr{S}" alt="\mathscr{S}" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">, it is easy to see
<img src="https://www.zhihu.com/equation?tex=(T_N)_N" alt="(T_N)_N" class="ee_img tr_noresize" eeimg="1"> is a Cauchy sequence of in bounded linear functional space
<img src="https://www.zhihu.com/equation?tex=\mathscr{B}(\mathscr{S},L^p)" alt="\mathscr{B}(\mathscr{S},L^p)" class="ee_img tr_noresize" eeimg="1"> (<img src="https://www.zhihu.com/equation?tex=\mathscr{B}(\mathscr{S},L^p)" alt="\mathscr{B}(\mathscr{S},L^p)" class="ee_img tr_noresize" eeimg="1"> is
complete by assigning <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> norm on <img src="https://www.zhihu.com/equation?tex=\mathscr{S}" alt="\mathscr{S}" class="ee_img tr_noresize" eeimg="1"> and completeness of
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">), then the limit of <img src="https://www.zhihu.com/equation?tex=T_N" alt="T_N" class="ee_img tr_noresize" eeimg="1"> exists. Indeed, under hypothesis,
proposition 5.5 in book gives <img src="https://www.zhihu.com/equation?tex=T_Nf" alt="T_Nf" class="ee_img tr_noresize" eeimg="1"> is a singular integral for
<img src="https://www.zhihu.com/equation?tex=f\in \mathscr{S}(\mathbb{R}^n)" alt="f\in \mathscr{S}(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=T_N" alt="T_N" class="ee_img tr_noresize" eeimg="1"> is uniformly bounded. Since
<img src="https://www.zhihu.com/equation?tex=\mathscr{S}(\mathbb{R}^n)" alt="\mathscr{S}(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1"> is dense in <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> can be uniquely
extends to <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">.

Notice that the limit process agrees the definition of singular
integral.

6.1 Hormander-Mihlin multiplier theorem
-----------------------------------

We know every <img src="https://www.zhihu.com/equation?tex=m\in L^\infty" alt="m\in L^\infty" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> by Plancherel's
theorem. The Hormander-Mihlin multiplier theorem gives a sufficient
condition for <img src="https://www.zhihu.com/equation?tex=m\in L^\infty" alt="m\in L^\infty" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">.

Theorem 6.1.1 (Hormander-Mihlin multiplier theorem). Let <img src="https://www.zhihu.com/equation?tex=a=[\frac{n}{2}]+1" alt="a=[\frac{n}{2}]+1" class="ee_img tr_noresize" eeimg="1"> be the first integer greater than <img src="https://www.zhihu.com/equation?tex=\frac{n}{2}" alt="\frac{n}{2}" class="ee_img tr_noresize" eeimg="1">.
If <img src="https://www.zhihu.com/equation?tex=m\in L^\infty(\mathbb{R}^n)" alt="m\in L^\infty(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1"> is of class <img src="https://www.zhihu.com/equation?tex=C^a" alt="C^a" class="ee_img tr_noresize" eeimg="1"> outside the origin
and satisfies: 
<img src="https://www.zhihu.com/equation?tex=\label{hypothesis of H-M multiplier theorem}
        (R^{-n}\int_{R<\left\lvert x\right\rvert<2R}\left\lvert D^\alpha m(\xi)\right\rvert^2d\xi)^{\frac{1}{2}}\leq CR^{-\left\lvert\alpha\right\rvert}\quad (0<R<\infty)\\" alt="\label{hypothesis of H-M multiplier theorem}
        (R^{-n}\int_{R<\left\lvert x\right\rvert<2R}\left\lvert D^\alpha m(\xi)\right\rvert^2d\xi)^{\frac{1}{2}}\leq CR^{-\left\lvert\alpha\right\rvert}\quad (0<R<\infty)\\" class="ee_img tr_noresize" eeimg="1">


for every multi-index <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> such that
<img src="https://www.zhihu.com/equation?tex=\left\lvert\alpha\right\rvert\leq a" alt="\left\lvert\alpha\right\rvert\leq a" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a multiplier for
<img src="https://www.zhihu.com/equation?tex=L^{p}" alt="L^{p}" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">.

This theorem is an improvement of Mihlin multiplier theorem. Mihlin
multiplier theorem supposes a stronger condition:

<img src="https://www.zhihu.com/equation?tex=\label{ieq: Mihlin condition}
    \left\lvert D^\alpha m(\xi)\right\rvert\leq CR^{-\left\lvert\alpha\right\rvert}\quad (\left\lvert\alpha\right\rvert\leq a)\\" alt="\label{ieq: Mihlin condition}
    \left\lvert D^\alpha m(\xi)\right\rvert\leq CR^{-\left\lvert\alpha\right\rvert}\quad (\left\lvert\alpha\right\rvert\leq a)\\" class="ee_img tr_noresize" eeimg="1">


In other words, Hormander weaken the decreasing speed as <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1">
increasing. The decreasing of uniform boundedness of
<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\alpha m(\xi)\right\rvert" alt="\left\lvert D^\alpha m(\xi)\right\rvert" class="ee_img tr_noresize" eeimg="1"> is weakened to the decreasing
of <img src="https://www.zhihu.com/equation?tex=L^{2}" alt="L^{2}" class="ee_img tr_noresize" eeimg="1"> norm of <img src="https://www.zhihu.com/equation?tex=\left\lvert D^\alpha m(\xi)\right\rvert" alt="\left\lvert D^\alpha m(\xi)\right\rvert" class="ee_img tr_noresize" eeimg="1">.

Inequality (6.2.2) is satisfied by every function
<img src="https://www.zhihu.com/equation?tex=m(\xi)" alt="m(\xi)" class="ee_img tr_noresize" eeimg="1"> of class <img src="https://www.zhihu.com/equation?tex=C^{a}" alt="C^{a}" class="ee_img tr_noresize" eeimg="1"> outside the origin of degree <img src="https://www.zhihu.com/equation?tex=ib" alt="ib" class="ee_img tr_noresize" eeimg="1">. Indeed by
chain rule: <img src="https://www.zhihu.com/equation?tex=\frac{\partial}{\partial x_i}(f_i(tx))=f_i(tx)t" alt="\frac{\partial}{\partial x_i}(f_i(tx))=f_i(tx)t" class="ee_img tr_noresize" eeimg="1">. And
<img src="https://www.zhihu.com/equation?tex=\frac{\partial}{\partial x_i}(t^pf_i(x))=t^pf_i(x)\leq C\left\lvert\xi\right\rvert^{-1}" alt="\frac{\partial}{\partial x_i}(t^pf_i(x))=t^pf_i(x)\leq C\left\lvert\xi\right\rvert^{-1}" class="ee_img tr_noresize" eeimg="1">.
We have <img src="https://www.zhihu.com/equation?tex=f_i(tx)t=t^pf_i(x)" alt="f_i(tx)t=t^pf_i(x)" class="ee_img tr_noresize" eeimg="1">. Thus
<img src="https://www.zhihu.com/equation?tex=\left\lvert m_i(\xi)\right\rvert=\left\lvert\left\lvert\xi\right\rvert^{ib-1}m_i(x')\right\rvert=\frac{\left\lvert m_i(x')\right\rvert}{\left\lvert\xi\right\rvert}" alt="\left\lvert m_i(\xi)\right\rvert=\left\lvert\left\lvert\xi\right\rvert^{ib-1}m_i(x')\right\rvert=\frac{\left\lvert m_i(x')\right\rvert}{\left\lvert\xi\right\rvert}" class="ee_img tr_noresize" eeimg="1">
with <img src="https://www.zhihu.com/equation?tex=\left\lvert x'\right\rvert=1" alt="\left\lvert x'\right\rvert=1" class="ee_img tr_noresize" eeimg="1">. By induction,
<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\alpha m(\xi)\right\rvert\leq \frac{\left\lvert D^\alpha m(x')\right\rvert}{\xi^{-\alpha}}" alt="\left\lvert D^\alpha m(\xi)\right\rvert\leq \frac{\left\lvert D^\alpha m(x')\right\rvert}{\xi^{-\alpha}}" class="ee_img tr_noresize" eeimg="1">.
Let

<img src="https://www.zhihu.com/equation?tex=C=\max_{\left\lvert\alpha\right\rvert\leq a}\sup_{\left\lvert x'\right\rvert=1}\left\lvert D^\alpha m(x')\right\rvert\\" alt="C=\max_{\left\lvert\alpha\right\rvert\leq a}\sup_{\left\lvert x'\right\rvert=1}\left\lvert D^\alpha m(x')\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


. We have
<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\alpha m(\xi)\right\rvert\leq C\left\lvert\xi\right\rvert^{-\alpha}" alt="\left\lvert D^\alpha m(\xi)\right\rvert\leq C\left\lvert\xi\right\rvert^{-\alpha}" class="ee_img tr_noresize" eeimg="1">

There are two standard techniques in proof of the Hormander-Mihlin
multiplier theorem. The first one is the smooth cutting of the
multiplier into dyadic pieces.

Lemma 6.1.2 (Lemma 6.5 in book). There is a non negative function <img src="https://www.zhihu.com/equation?tex=\phi\in C^\infty" alt="\phi\in C^\infty" class="ee_img tr_noresize" eeimg="1"> supported in the
spherical shell <img src="https://www.zhihu.com/equation?tex=\{\xi: \frac{1}{2}\left\lvert\xi\right\rvert<2\}" alt="\{\xi: \frac{1}{2}\left\lvert\xi\right\rvert<2\}" class="ee_img tr_noresize" eeimg="1"> such
that 
<img src="https://www.zhihu.com/equation?tex=\sum_{j\in\mathbb{Z}}\phi(2^{-j}\xi)=1\quad (\xi\neq 0)\\" alt="\sum_{j\in\mathbb{Z}}\phi(2^{-j}\xi)=1\quad (\xi\neq 0)\\" class="ee_img tr_noresize" eeimg="1">



The second is an explicit formulation of the well known fact that the
regularity of the multiplier is translated into control of the size of
kernel.

Lemma 6.1.3 (Lemma 6.6 in book). Let <img src="https://www.zhihu.com/equation?tex=a=[\frac{n}{2}]+1" alt="a=[\frac{n}{2}]+1" class="ee_img tr_noresize" eeimg="1">, and let <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1"> be such that
<img src="https://www.zhihu.com/equation?tex=a=\frac{n}{s}+\frac{1}{2}" alt="a=\frac{n}{s}+\frac{1}{2}" class="ee_img tr_noresize" eeimg="1"> (so that <img src="https://www.zhihu.com/equation?tex=s\leq 2" alt="s\leq 2" class="ee_img tr_noresize" eeimg="1">). If <img src="https://www.zhihu.com/equation?tex=k\in L^2" alt="k\in L^2" class="ee_img tr_noresize" eeimg="1"> is such
that <img src="https://www.zhihu.com/equation?tex=\hat{k}" alt="\hat{k}" class="ee_img tr_noresize" eeimg="1"> is of class <img src="https://www.zhihu.com/equation?tex=C^a" alt="C^a" class="ee_img tr_noresize" eeimg="1">, then,

<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert dx\leq C_n t^{-\frac{1}{2}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^{\alpha}\hat{k}\rVert_s}\quad (0<t<\infty)\\" alt="\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert dx\leq C_n t^{-\frac{1}{2}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^{\alpha}\hat{k}\rVert_s}\quad (0<t<\infty)\\" class="ee_img tr_noresize" eeimg="1">



The details of proof of two lemmas and Hormander-Mihlin multiplier
theorem is in book and the subsection 6.4

6.2 More precise estimation for more regular multiplier
---------------------------------------------------

If we consider Mihlin multiplier theorem, the stronger condition
(6.2.2) gives the smoothness of multipliers.
And we have more precise estimation like Theorem 5.20 (i) in book.

Theorem 6.2.1 (theorem 6.10 in book). Let <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1"> be an integer such that <img src="https://www.zhihu.com/equation?tex=\frac{n}{2}<a\leq n" alt="\frac{n}{2}<a\leq n" class="ee_img tr_noresize" eeimg="1">, and suppose that
the multiplier <img src="https://www.zhihu.com/equation?tex=m(\xi)" alt="m(\xi)" class="ee_img tr_noresize" eeimg="1"> satisfies
(6.2.2) for all
<img src="https://www.zhihu.com/equation?tex=\left\lvert\alpha\right\rvert\leq a" alt="\left\lvert\alpha\right\rvert\leq a" class="ee_img tr_noresize" eeimg="1">. Then, for every <img src="https://www.zhihu.com/equation?tex=q>\frac{n}{a}" alt="q>\frac{n}{a}" class="ee_img tr_noresize" eeimg="1">,
the operator <img src="https://www.zhihu.com/equation?tex=T_m" alt="T_m" class="ee_img tr_noresize" eeimg="1"> satisfies

<img src="https://www.zhihu.com/equation?tex=(T_mf)^\#(x)\leq C_qM_qf(x)\quad (f\in\cup_{1<p<\infty}L^p)\\" alt="(T_mf)^\#(x)\leq C_qM_qf(x)\quad (f\in\cup_{1<p<\infty}L^p)\\" class="ee_img tr_noresize" eeimg="1">



6.3 Some properties of multipliers
------------------------------
Theorem 6.3.1. <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> if and only if it is a multiplier for
<img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">. And the norm of operator are identical.

I want to use: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int T_mf(x)\overline{g(x)}dx & =\int (\int m(y)\hat{f}(y) e^{2\pi i x\cdot y}d y)\overline{g(x)}dx                      \\
                                      & =\iint m(y)\hat{f}(y) e^{2\pi i x\cdot y}\overline{g(x)}d y d x                          \\
                                      & =\iint m(y)(\int f(z)e^{-2\pi i y\cdot z}d z) e^{2\pi i x\cdot y}\overline{g(x)}d y d x  \\
                                      & =\iiint m(y)f(z)e^{-2\pi i y\cdot z}e^{2\pi i x\cdot y}\overline{g(x)}d z d y d x        \\
                                      & =\iint m(y)f(z)e^{-2\pi i y\cdot z}\overline{(\int e^{-2\pi i x\cdot y}{g(x)}dx)}d z d y \\
                                      & =\iint m(y)f(z)e^{-2\pi i y\cdot z}\overline{\hat{g}(y)}d z d y                          \\
                                      & =\int f(z)\overline{(\int \overline{m(y)}\hat{g}(y)e^{2\pi i y\cdot z}d y)}d z           \\
                                      & =\int f(z)\overline{T_{\bar{m}}g(z)}d z                                                  \\
    \end{aligned}\\" alt="\begin{aligned}
        \int T_mf(x)\overline{g(x)}dx & =\int (\int m(y)\hat{f}(y) e^{2\pi i x\cdot y}d y)\overline{g(x)}dx                      \\
                                      & =\iint m(y)\hat{f}(y) e^{2\pi i x\cdot y}\overline{g(x)}d y d x                          \\
                                      & =\iint m(y)(\int f(z)e^{-2\pi i y\cdot z}d z) e^{2\pi i x\cdot y}\overline{g(x)}d y d x  \\
                                      & =\iiint m(y)f(z)e^{-2\pi i y\cdot z}e^{2\pi i x\cdot y}\overline{g(x)}d z d y d x        \\
                                      & =\iint m(y)f(z)e^{-2\pi i y\cdot z}\overline{(\int e^{-2\pi i x\cdot y}{g(x)}dx)}d z d y \\
                                      & =\iint m(y)f(z)e^{-2\pi i y\cdot z}\overline{\hat{g}(y)}d z d y                          \\
                                      & =\int f(z)\overline{(\int \overline{m(y)}\hat{g}(y)e^{2\pi i y\cdot z}d y)}d z           \\
                                      & =\int f(z)\overline{T_{\bar{m}}g(z)}d z                                                  \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 By dual of <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> and Hahn-Banach theorem,

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \lVert T_m\rVert= & \sup_{\lVert f\rVert_p\leq 1}\lVert T_mf\rVert_p                                                                                                                          \\
        =           & \sup_{\lVert f\rVert_p\leq 1}\sup_{\lVert g\rVert_q\leq 1}\int T_mf\bar{g}=\sup_{\lVert f\rVert_p\leq 1}\sup_{\lVert g\rVert_q\leq 1}\int f\overline{T_{\bar{m}}g}=\lVert T_{\bar{m}}\rVert
    \end{aligned}\\" alt="\begin{aligned}
        \lVert T_m\rVert= & \sup_{\lVert f\rVert_p\leq 1}\lVert T_mf\rVert_p                                                                                                                          \\
        =           & \sup_{\lVert f\rVert_p\leq 1}\sup_{\lVert g\rVert_q\leq 1}\int T_mf\bar{g}=\sup_{\lVert f\rVert_p\leq 1}\sup_{\lVert g\rVert_q\leq 1}\int f\overline{T_{\bar{m}}g}=\lVert T_{\bar{m}}\rVert
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> if and only if
<img src="https://www.zhihu.com/equation?tex=\bar{m}" alt="\bar{m}" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">. And the norm of operator are
identical. And <img src="https://www.zhihu.com/equation?tex=\bar{m}" alt="\bar{m}" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1"> implies <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a
multiplier for <img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">. And their norms are equal.

Theorem 6.3.2. If <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> is a multiplier for <img src="https://www.zhihu.com/equation?tex=L^q" alt="L^q" class="ee_img tr_noresize" eeimg="1">
with <img src="https://www.zhihu.com/equation?tex=p'<q<p" alt="p'<q<p" class="ee_img tr_noresize" eeimg="1"> or <img src="https://www.zhihu.com/equation?tex=p<q<p'" alt="p<q<p'" class="ee_img tr_noresize" eeimg="1">.

This theorem is by theorem
6.3.1 and Marcinkiewicz' interpolation
theorem. If we use Riesz-Thorin interpolation theorem, we can get
estimation <img src="https://www.zhihu.com/equation?tex=\lVert T_m\rVert_{p,p}\geq\lVert m\rVert_\infty" alt="\lVert T_m\rVert_{p,p}\geq\lVert m\rVert_\infty" class="ee_img tr_noresize" eeimg="1">.

Theorem 6.3.3. The multipliers for <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> form a subalgebra of <img src="https://www.zhihu.com/equation?tex=L^\infty(\mathbb{R}^n)" alt="L^\infty(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">
which is invariant under translations, rotations and dilations.

2.2.4 Details of proof and errata {#details}
---------------------------

Note 1 (proof of lemma 6.1). Since the constant <img src="https://www.zhihu.com/equation?tex=C_p" alt="C_p" class="ee_img tr_noresize" eeimg="1"> depends only on <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> and on the constants
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{K}\rVert_{\infty}" alt="\lVert\hat{K}\rVert_{\infty}" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=B_K" alt="B_K" class="ee_img tr_noresize" eeimg="1"> of the kernel, and
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{K}\rVert_\infty" alt="\lVert\hat{K}\rVert_\infty" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=B_K" alt="B_K" class="ee_img tr_noresize" eeimg="1"> is bounded by hypothesis a) and
b), <img src="https://www.zhihu.com/equation?tex=T_Nf=k_N*f" alt="T_Nf=k_N*f" class="ee_img tr_noresize" eeimg="1"> are uniformly bounded.

<img src="https://www.zhihu.com/equation?tex=k_N=k\chi_{\{x:\frac{1}{N}\leq \left\lvert x\right\rvert\leq N\}}" alt="k_N=k\chi_{\{x:\frac{1}{N}\leq \left\lvert x\right\rvert\leq N\}}" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=T_m\leq\lVert m\rVert_\infty" alt="T_m\leq\lVert m\rVert_\infty" class="ee_img tr_noresize" eeimg="1"> is easy. To prove
<img src="https://www.zhihu.com/equation?tex=T_m\geq\lVert m\rVert_\infty" alt="T_m\geq\lVert m\rVert_\infty" class="ee_img tr_noresize" eeimg="1">, by Plancherel's theorem, this is
equivalent to
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{Tf}\rVert_2\geq\lVert m\rVert_\infty\lVert\hat{f}\rVert_2" alt="\lVert\hat{Tf}\rVert_2\geq\lVert m\rVert_\infty\lVert\hat{f}\rVert_2" class="ee_img tr_noresize" eeimg="1">
for some <img src="https://www.zhihu.com/equation?tex=\hat{f}" alt="\hat{f}" class="ee_img tr_noresize" eeimg="1">. For any <img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1">, let
<img src="https://www.zhihu.com/equation?tex=A_\epsilon=\{x\in [0,1]:m(x)>\lVert m\rVert_\infty-\epsilon\}" alt="A_\epsilon=\{x\in [0,1]:m(x)>\lVert m\rVert_\infty-\epsilon\}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\hat{f}(\xi)=\chi_{A_\epsilon}" alt="\hat{f}(\xi)=\chi_{A_\epsilon}" class="ee_img tr_noresize" eeimg="1">.
<img src="https://www.zhihu.com/equation?tex=\hat{Tf}=m\hat{f}>(\lVert m\rVert_\infty-\epsilon)\hat{f}" alt="\hat{Tf}=m\hat{f}>(\lVert m\rVert_\infty-\epsilon)\hat{f}" class="ee_img tr_noresize" eeimg="1"> hence
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{Tf}\rVert_2>(\lVert m\rVert_\infty-\epsilon)\lVert\hat{f}\rVert_2" alt="\lVert\hat{Tf}\rVert_2>(\lVert m\rVert_\infty-\epsilon)\lVert\hat{f}\rVert_2" class="ee_img tr_noresize" eeimg="1">.
Thus
<img src="https://www.zhihu.com/equation?tex=\lVert\hat{Tf}\rVert_2\geq\lVert m\rVert_\infty\lVert\hat{f}\rVert_2" alt="\lVert\hat{Tf}\rVert_2\geq\lVert m\rVert_\infty\lVert\hat{f}\rVert_2" class="ee_img tr_noresize" eeimg="1">.

The proof of lemma 6.6 is bad formatted. We give the complete proof of
lemma 6.6.

First we have
<img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert^a\leq (\sqrt{n\max_i{x_i}^2})^a\leq n^{\frac{a}{2}}max_i \left\lvert x_i\right\rvert^a\leq n^{\frac{a}{2}}(\sum_i \left\lvert x_i\right\rvert^a)" alt="\left\lvert x\right\rvert^a\leq (\sqrt{n\max_i{x_i}^2})^a\leq n^{\frac{a}{2}}max_i \left\lvert x_i\right\rvert^a\leq n^{\frac{a}{2}}(\sum_i \left\lvert x_i\right\rvert^a)" class="ee_img tr_noresize" eeimg="1">.

By
<img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert^a\leq n^{\frac{a}{2}}(\sum_i \left\lvert x_i\right\rvert^a)" alt="\left\lvert x\right\rvert^a\leq n^{\frac{a}{2}}(\sum_i \left\lvert x_i\right\rvert^a)" class="ee_img tr_noresize" eeimg="1">,
Holder inequality and Minkowski inequality for <img src="https://www.zhihu.com/equation?tex=s'\geq 2" alt="s'\geq 2" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx} & = \int_{\left\lvert x\right\rvert>t}^{}{\frac{\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)\left\lvert k(x)\right\rvert}{\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)}dx}                                     \\
                                          & \leq \int_{\left\lvert x\right\rvert>t}^{}{\frac{C\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)\left\lvert k(x)\right\rvert}{\left\lvert x\right\rvert^a}dx}                                                 \\
                                          & \leq C(\int_{}(\sum_{j=1}^n(\left\lvert x_j^ak(x)\right\rvert)^{s'})dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}} \\
                                          & \leq C\sum_{j=1}^n(\int_{}\left\lvert x_j^ak(x)\right\rvert^{s'}dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}}     \\
    \end{aligned}\\" alt="\begin{aligned}
        \int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx} & = \int_{\left\lvert x\right\rvert>t}^{}{\frac{\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)\left\lvert k(x)\right\rvert}{\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)}dx}                                     \\
                                          & \leq \int_{\left\lvert x\right\rvert>t}^{}{\frac{C\sum_{j=1}^n(\left\lvert x_j\right\rvert^a)\left\lvert k(x)\right\rvert}{\left\lvert x\right\rvert^a}dx}                                                 \\
                                          & \leq C(\int_{}(\sum_{j=1}^n(\left\lvert x_j^ak(x)\right\rvert)^{s'})dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}} \\
                                          & \leq C\sum_{j=1}^n(\int_{}\left\lvert x_j^ak(x)\right\rvert^{s'}dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}}     \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Notice <img src="https://www.zhihu.com/equation?tex=\frac{2}{3}\leq s\leq 2" alt="\frac{2}{3}\leq s\leq 2" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=n+\frac{1}{3}\leq as\leq n+1" alt="n+\frac{1}{3}\leq as\leq n+1" class="ee_img tr_noresize" eeimg="1">. Thus
<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx" alt="\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx" class="ee_img tr_noresize" eeimg="1">
converges and
<img src="https://www.zhihu.com/equation?tex=(\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}}=Ct^{-\frac{1}{2}}" alt="(\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{as}}dx)^{\frac{1}{s}}=Ct^{-\frac{1}{2}}" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=1\leq p\leq 2" alt="1\leq p\leq 2" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=q" alt="q" class="ee_img tr_noresize" eeimg="1"> is the dual exponent if <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">, the
Hausdorff-Young inequality is:

<img src="https://www.zhihu.com/equation?tex=(\sum\left\lvert a_n\right\rvert^q)^\frac{1}{q} \leq(\frac{1}{2\pi}\int_{0}^{2\pi}\left\lvert f(\theta)\right\rvert^p d\theta)^\frac{1}{p}\\" alt="(\sum\left\lvert a_n\right\rvert^q)^\frac{1}{q} \leq(\frac{1}{2\pi}\int_{0}^{2\pi}\left\lvert f(\theta)\right\rvert^p d\theta)^\frac{1}{p}\\" class="ee_img tr_noresize" eeimg="1">


and its dual:

<img src="https://www.zhihu.com/equation?tex=(\frac{1}{2\pi}\int_{0}^{2\pi}\left\lvert f(\theta)\right\rvert^q d\theta)^\frac{1}{q}\leq(\sum\left\lvert a_n\right\rvert^p)^\frac{1}{p}\\" alt="(\frac{1}{2\pi}\int_{0}^{2\pi}\left\lvert f(\theta)\right\rvert^q d\theta)^\frac{1}{q}\leq(\sum\left\lvert a_n\right\rvert^p)^\frac{1}{p}\\" class="ee_img tr_noresize" eeimg="1">


But here it uses the analog for the Fourier transform (Corollary 2.6 in
Chapter 2 in stein's *Functional Analysis*):

Theorem 6.4.1. If <img src="https://www.zhihu.com/equation?tex=1\leq p\leq 2" alt="1\leq p\leq 2" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\frac{1}{p}+\frac{1}{q}=1" alt="\frac{1}{p}+\frac{1}{q}=1" class="ee_img tr_noresize" eeimg="1">, then the Fourier transform <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> has a unique
extension to a bounded map from <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=L^q" alt="L^q" class="ee_img tr_noresize" eeimg="1">, with
<img src="https://www.zhihu.com/equation?tex=\lVert T(f)\rVert_q\leq\lVert f\rVert_p" alt="\lVert T(f)\rVert_q\leq\lVert f\rVert_p" class="ee_img tr_noresize" eeimg="1">

By Theorem
6.4.1 and property of Fourier
transform. 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        (\int_{}\left\lvert(x_j^ak(x))\right\rvert^{s'}dx)^{\frac{1}{s'}} & \leq (\int_{}\left\lvert(x_j^ak(x))^\wedge\right\rvert^{s}dx)^{\frac{1}{s}}                                 \\
                                                         & =(\int_{}\left\lvert(-2\pi i)^{-a}D_j^a\hat{k}(\xi)\right\rvert^{s}dx)^{\frac{1}{s}}=C\lVert D_j^a\hat{k}\rVert_s
    \end{aligned}\\" alt="\begin{aligned}
        (\int_{}\left\lvert(x_j^ak(x))\right\rvert^{s'}dx)^{\frac{1}{s'}} & \leq (\int_{}\left\lvert(x_j^ak(x))^\wedge\right\rvert^{s}dx)^{\frac{1}{s}}                                 \\
                                                         & =(\int_{}\left\lvert(-2\pi i)^{-a}D_j^a\hat{k}(\xi)\right\rvert^{s}dx)^{\frac{1}{s}}=C\lVert D_j^a\hat{k}\rVert_s
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus

<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx}\leq Ct^{-\frac{1}{2}}\sum_{j=1}^n{\lVert D_j^a\hat{k}\rVert_s}\\" alt="\int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx}\leq Ct^{-\frac{1}{2}}\sum_{j=1}^n{\lVert D_j^a\hat{k}\rVert_s}\\" class="ee_img tr_noresize" eeimg="1">


Observe that
<img src="https://www.zhihu.com/equation?tex=\sum_{j=1}^n{\lVert D_j^a\hat{k}\rVert_s}\leq n\max_j{\lVert D_j^a\hat{k}\rVert_s}\leq n\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}" alt="\sum_{j=1}^n{\lVert D_j^a\hat{k}\rVert_s}\leq n\max_j{\lVert D_j^a\hat{k}\rVert_s}\leq n\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}" class="ee_img tr_noresize" eeimg="1">.
We finally prove that:

<img src="https://www.zhihu.com/equation?tex=\int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx}\leq Ct^{-\frac{1}{2}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}\\" alt="\int_{\left\lvert x\right\rvert>t}^{}{\left\lvert k(x)\right\rvert dx}\leq Ct^{-\frac{1}{2}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}\\" class="ee_img tr_noresize" eeimg="1">



By Leibnitz rule

<img src="https://www.zhihu.com/equation?tex=D^\alpha m_j(\xi)=\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}D^\gamma\phi(2^{-j}\xi)\\" alt="D^\alpha m_j(\xi)=\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}D^\gamma\phi(2^{-j}\xi)\\" class="ee_img tr_noresize" eeimg="1">


with <img src="https://www.zhihu.com/equation?tex=\left\lvert\alpha\right\rvert=\alpha_1+\alpha_2+\cdots+\alpha_n" alt="\left\lvert\alpha\right\rvert=\alpha_1+\alpha_2+\cdots+\alpha_n" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=m=\sum_j m_j" alt="m=\sum_j m_j" class="ee_img tr_noresize" eeimg="1"> and at most two <img src="https://www.zhihu.com/equation?tex=m_j" alt="m_j" class="ee_img tr_noresize" eeimg="1"> can be non zero at any point. We
have
<img src="https://www.zhihu.com/equation?tex=\sum_j\left\lvert\hat{k_j}(\xi)\right\rvert=\sum_j\left\lvert m_j(\xi)\right\rvert\leq 2\lVert m\rVert_\infty" alt="\sum_j\left\lvert\hat{k_j}(\xi)\right\rvert=\sum_j\left\lvert m_j(\xi)\right\rvert\leq 2\lVert m\rVert_\infty" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=\left\lvert(2\pi y)^\gamma\right\rvert\leq C\left\lvert y\right\rvert^{\left\lvert\gamma\right\rvert}" alt="\left\lvert(2\pi y)^\gamma\right\rvert\leq C\left\lvert y\right\rvert^{\left\lvert\gamma\right\rvert}" class="ee_img tr_noresize" eeimg="1">

Note 4 (proof of theorem 6.3 in book). By Leibnitz rule we have

<img src="https://www.zhihu.com/equation?tex=D^\alpha m_j(\xi)=\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}D^\gamma\phi(2^{-j}\xi)\\" alt="D^\alpha m_j(\xi)=\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}D^\gamma\phi(2^{-j}\xi)\\" class="ee_img tr_noresize" eeimg="1">


Since for each <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\gamma\phi(2^{-j}\xi)\right\rvert" alt="\left\lvert D^\gamma\phi(2^{-j}\xi)\right\rvert" class="ee_img tr_noresize" eeimg="1"> is uniformly bounded
and there are finite choice of <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">, there is a constant <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\gamma\phi(2^{-j}\xi)\right\rvert\leq C" alt="\left\lvert D^\gamma\phi(2^{-j}\xi)\right\rvert\leq C" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=\xi" alt="\xi" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">. Notice
<img src="https://www.zhihu.com/equation?tex=\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert}" alt="\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert}" class="ee_img tr_noresize" eeimg="1"> is
also bounded. Thus

<img src="https://www.zhihu.com/equation?tex=\left\lvert D^\alpha m_j(\xi)\right\rvert\leq C'\sum_{\left\lvert\beta\right\rvert\leq \left\lvert\alpha\right\rvert}\left\lvert D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}\right\rvert=C'2^{-j\left\lvert\alpha\right\rvert}\sum_{\left\lvert\beta\right\rvert\leq \left\lvert\alpha\right\rvert}\left\lvert D^\beta m(\xi)2^{j\left\lvert\beta\right\rvert}\right\rvert\\" alt="\left\lvert D^\alpha m_j(\xi)\right\rvert\leq C'\sum_{\left\lvert\beta\right\rvert\leq \left\lvert\alpha\right\rvert}\left\lvert D^\beta m(\xi)2^{-j\left\lvert\gamma\right\rvert}\right\rvert=C'2^{-j\left\lvert\alpha\right\rvert}\sum_{\left\lvert\beta\right\rvert\leq \left\lvert\alpha\right\rvert}\left\lvert D^\beta m(\xi)2^{j\left\lvert\beta\right\rvert}\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


Now we estimate the norm of <img src="https://www.zhihu.com/equation?tex=D^\alpha m_j(\xi)" alt="D^\alpha m_j(\xi)" class="ee_img tr_noresize" eeimg="1">. Notice
<img src="https://www.zhihu.com/equation?tex=\operatorname{supp}(m_j)\subset\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" alt="\operatorname{supp}(m_j)\subset\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" class="ee_img tr_noresize" eeimg="1">.
Thus the support of <img src="https://www.zhihu.com/equation?tex=D^\alpha m_j(\xi)" alt="D^\alpha m_j(\xi)" class="ee_img tr_noresize" eeimg="1"> is also in
<img src="https://www.zhihu.com/equation?tex=\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" alt="\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" class="ee_img tr_noresize" eeimg="1">. Thus only
need to integrate each <img src="https://www.zhihu.com/equation?tex=D^\beta m(\xi)" alt="D^\beta m(\xi)" class="ee_img tr_noresize" eeimg="1"> on
<img src="https://www.zhihu.com/equation?tex=\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" alt="\{\xi:2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}\}" class="ee_img tr_noresize" eeimg="1">. By
separate the region of integral: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}                                                                                   \\
        \leq & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}+  (\int_{2^{j}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}
    \end{aligned}\\" alt="\begin{aligned}
             & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}                                                                                   \\
        \leq & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}+  (\int_{2^{j}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 By Holder inequality and hypothesis
(6.2.1), the first integral on
right hand side is: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}                                                                          \\
        \leq & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^2 d\xi)^{\frac{1}{2}}(\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}} 1 d\xi)^{\frac{1}{s}-\frac{1}{2}} \\
        \leq & C_1 (2^{j-1})^{-\left\lvert\beta\right\rvert}(2^{j-1})^\frac{n}{2} C_2(2^{j n}-2^{(j-1)n})^{\frac{1}{s}-\frac{1}{2}}                                                        \\
        =    & C_1C_2 (2^{j-1})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n}(1-2^{-n}))^{\frac{1}{s}-\frac{1}{2}}                                                                    \\
        =    & C (1-2^{-n})^{\frac{1}{s}-\frac{1}{2}}(2^{-1})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}               \\
        \leq & C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}
    \end{aligned}\\" alt="\begin{aligned}
             & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}}                                                                          \\
        \leq & (\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}}\left\lvert D^\beta m(\xi)\right\rvert^2 d\xi)^{\frac{1}{2}}(\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j}} 1 d\xi)^{\frac{1}{s}-\frac{1}{2}} \\
        \leq & C_1 (2^{j-1})^{-\left\lvert\beta\right\rvert}(2^{j-1})^\frac{n}{2} C_2(2^{j n}-2^{(j-1)n})^{\frac{1}{s}-\frac{1}{2}}                                                        \\
        =    & C_1C_2 (2^{j-1})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n}(1-2^{-n}))^{\frac{1}{s}-\frac{1}{2}}                                                                    \\
        =    & C (1-2^{-n})^{\frac{1}{s}-\frac{1}{2}}(2^{-1})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}               \\
        \leq & C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Using the same argument for the second integral on
right hand side: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        (\int_{2^{j}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}} & \leq  C_1 (2^{j})^{-\left\lvert\beta\right\rvert}(2^{j})^\frac{n}{2} C_2(2^{(j+1)n}-2^{j n})^{\frac{1}{s}-\frac{1}{2}}      \\
                                                                                          & =C (2^{n}-1)^{\frac{1}{s}-\frac{1}{2}}(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}} \\
                                                                                          & \leq C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}
    \end{aligned}\\" alt="\begin{aligned}
        (\int_{2^{j}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}} & \leq  C_1 (2^{j})^{-\left\lvert\beta\right\rvert}(2^{j})^\frac{n}{2} C_2(2^{(j+1)n}-2^{j n})^{\frac{1}{s}-\frac{1}{2}}      \\
                                                                                          & =C (2^{n}-1)^{\frac{1}{s}-\frac{1}{2}}(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}} \\
                                                                                          & \leq C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus

<img src="https://www.zhihu.com/equation?tex=(\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}} \leq  C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}=C'(2^{j})^{-\left\lvert\beta\right\rvert+\frac{n}{s}}\\" alt="(\int_{2^{j-1}\leq \left\lvert\xi\right\rvert\leq 2^{j+1}}\left\lvert D^\beta m(\xi)\right\rvert^s d\xi)^{\frac{1}{s}} \leq  C'(2^{j})^{\frac{n}{2}-\left\lvert\beta\right\rvert}(2^{j n})^{\frac{1}{s}-\frac{1}{2}}=C'(2^{j})^{-\left\lvert\beta\right\rvert+\frac{n}{s}}\\" class="ee_img tr_noresize" eeimg="1">



Note 5 (proof of theorem 6.3 in book) By Plancherel's theorem:

<img src="https://www.zhihu.com/equation?tex=\lVert T^Nf-T_mf\rVert_2=\lVert(m-m^N)\hat{f}\rVert_2=\lVert(m-m^N)\rVert_2\lVert\hat{f}\rVert_2\\" alt="\lVert T^Nf-T_mf\rVert_2=\lVert(m-m^N)\hat{f}\rVert_2=\lVert(m-m^N)\rVert_2\lVert\hat{f}\rVert_2\\" class="ee_img tr_noresize" eeimg="1">



Thus <img src="https://www.zhihu.com/equation?tex=T^Nf\to T_mf" alt="T^Nf\to T_mf" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> for every <img src="https://www.zhihu.com/equation?tex=f\in L^2" alt="f\in L^2" class="ee_img tr_noresize" eeimg="1">.

Generally, <img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1"> convergence does not implies pointwise convergence. But
there is a subsequence converges pointwise. Thus we have:

<img src="https://www.zhihu.com/equation?tex=\liminf_{N\to \infty}\left\lvert T^Nf(x)-T_mf(x)\right\rvert=0\quad a.e.\\" alt="\liminf_{N\to \infty}\left\lvert T^Nf(x)-T_mf(x)\right\rvert=0\quad a.e.\\" class="ee_img tr_noresize" eeimg="1">


By triangular inequality: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    (\int\left\lvert T_m f(x)\right\rvert^p)^\frac{1}{p} \leq & (\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+\int\left\lvert T^N f(x)\right\rvert^p \\
    \leq                                    & (\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p\end{aligned}\\" alt="\begin{aligned}
    (\int\left\lvert T_m f(x)\right\rvert^p)^\frac{1}{p} \leq & (\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+\int\left\lvert T^N f(x)\right\rvert^p \\
    \leq                                    & (\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">


Take <img src="https://www.zhihu.com/equation?tex=\liminf" alt="\liminf" class="ee_img tr_noresize" eeimg="1"> on both side and use Fatou's Lemma: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    (\int\left\lvert T_m f(x)\right\rvert^p)^\frac{1}{p}\leq & \liminf(\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p \\
    \leq                                   & (\int\liminf\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p \\
    =                                      & C_p\lVert f\rVert_p\end{aligned}\\" alt="\begin{aligned}
    (\int\left\lvert T_m f(x)\right\rvert^p)^\frac{1}{p}\leq & \liminf(\int\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p \\
    \leq                                   & (\int\liminf\left\lvert T^N f(x)-T_mf(x)\right\rvert^p)^\frac{1}{p}+C_p\lVert f\rVert_p \\
    =                                      & C_p\lVert f\rVert_p\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">



Note 6 (proof of theorem 6.3 in book). By Leibnitz rule:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \left\lvert D^\alpha\tilde{m_j}(\xi)\right\rvert & =\left\lvert\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m_j(\xi)D^\gamma(e^{-2\pi i y\cdot\xi}-1)\right\rvert                                            \\
                                       & \leq C\sum_{\alpha=\beta+\gamma}\left\lvert D^\beta m_j(\xi)\right\rvert\left\lvert D^\gamma(e^{-2\pi iy\cdot\xi}-1)\right\rvert                                                                    \\
                                       & \leq C'\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\gamma\right\rvert)}\left\lvert D^\beta m_j(\xi)\right\rvert                                                                             \\
                                       & \leq C'\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\gamma\right\rvert)}   C''2^{-j\left\lvert\beta\right\rvert}\sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert \\
                                       & \leq C\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\alpha\right\rvert)} \sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                        \\
                                       & \leq C\sum_{\left\lvert\beta\right\rvert\leq a}\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                     \\
                                       & \leq C\sum_{\left\lvert\beta\right\rvert\leq a}\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                             \\
                                       & = Ca\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                                                       \\
    \end{aligned}\\" alt="\begin{aligned}
        \left\lvert D^\alpha\tilde{m_j}(\xi)\right\rvert & =\left\lvert\sum_{\alpha=\beta+\gamma}\binom{\left\lvert\alpha\right\rvert}{\left\lvert\beta\right\rvert} D^\beta m_j(\xi)D^\gamma(e^{-2\pi i y\cdot\xi}-1)\right\rvert                                            \\
                                       & \leq C\sum_{\alpha=\beta+\gamma}\left\lvert D^\beta m_j(\xi)\right\rvert\left\lvert D^\gamma(e^{-2\pi iy\cdot\xi}-1)\right\rvert                                                                    \\
                                       & \leq C'\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\gamma\right\rvert)}\left\lvert D^\beta m_j(\xi)\right\rvert                                                                             \\
                                       & \leq C'\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\gamma\right\rvert)}   C''2^{-j\left\lvert\beta\right\rvert}\sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert \\
                                       & \leq C\sum_{\alpha=\beta+\gamma}\left\lvert y\right\rvert 2^{j(1-\left\lvert\alpha\right\rvert)} \sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                        \\
                                       & \leq C\sum_{\left\lvert\beta\right\rvert\leq a}\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq \left\lvert\beta\right\rvert}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                     \\
                                       & \leq C\sum_{\left\lvert\beta\right\rvert\leq a}\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                             \\
                                       & = Ca\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}\left\lvert D^{\beta'} m(\xi)2^{j\left\lvert\beta'\right\rvert}\right\rvert                                                                       \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \sup_{\left\lvert\alpha\right\rvert=a}\lVert D^\alpha\tilde{m_j}\rVert_s & \leq C\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\left\lvert\beta'\right\rvert}\lVert D^{\beta'} m(\xi)\rVert_s        \\
                                                          & \leq C\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\left\lvert\beta'\right\rvert}C2^{j(-\left\lvert\beta'\right\rvert+\frac{n}{s})} \\
                                                          & \leq C'\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\frac{n}{s}}                                  \\
                                                          & \leq C' a\left\lvert y\right\rvert 2^{j(1-a+\frac{n}{s})}                                                                \\
    \end{aligned}\\" alt="\begin{aligned}
        \sup_{\left\lvert\alpha\right\rvert=a}\lVert D^\alpha\tilde{m_j}\rVert_s & \leq C\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\left\lvert\beta'\right\rvert}\lVert D^{\beta'} m(\xi)\rVert_s        \\
                                                          & \leq C\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\left\lvert\beta'\right\rvert}C2^{j(-\left\lvert\beta'\right\rvert+\frac{n}{s})} \\
                                                          & \leq C'\left\lvert y\right\rvert 2^{j(1-a)} \sum_{\left\lvert\beta'\right\rvert\leq {a}}2^{j\frac{n}{s}}                                  \\
                                                          & \leq C' a\left\lvert y\right\rvert 2^{j(1-a+\frac{n}{s})}                                                                \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">



We denote <img src="https://www.zhihu.com/equation?tex=t_j=2^j\left\lvert y\right\rvert" alt="t_j=2^j\left\lvert y\right\rvert" class="ee_img tr_noresize" eeimg="1"> 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & \int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}{\left\lvert k^N(x-y)-k^N(x)\right\rvert\left\lvert f(x)\right\rvert dx}                                                                                                                                \\
        =    & \sum_{j=1}^{\infty}\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert k^N(x-y)-k^N(x)\right\rvert\left\lvert f(x)\right\rvert dx}                                                                                                         \\
        \leq & \sum_{j=1}^{\infty}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert k^N(x-y)-k^N(x)\right\rvert^{q'}dx})^\frac{1}{q'}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}                                     \\
        \leq & \sum_{j=1}^{\infty}(\int_{t_j<\left\lvert x\right\rvert}{\left\lvert k^N(x-y)-k^N(x)\right\rvert^{q'}dx})^\frac{1}{q'}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}                                              \\
        \leq & (\sum_{j=1}^{\infty}Ct_{j}^{-\epsilon-\frac{n}{q}}\left\lvert y\right\rvert^{\epsilon}\left\lvert B(0,2t_j)\right\rvert^{\frac{1}{q}})\sup_j{(\frac{1}{\left\lvert B(0,2t_j)\right\rvert}\int_{\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}} \\
        \leq & C(\sum_{j=1}^{\infty}t_{j}^{-\epsilon-\frac{n}{q}}\left\lvert y\right\rvert^{\epsilon}{t_j}^{\frac{n}{q}})M_q f(0)                                                                                          \\
        =    & C\left\lvert y\right\rvert^{\epsilon}(\sum_{j=1}^{\infty}t_{j}^{-\epsilon})M_q f(0)                                                                                                                         \\
        =    & C\left\lvert y\right\rvert^{\epsilon}\left\lvert y\right\rvert^{-\epsilon}(\sum_{j=1}^{\infty}2^{-j\epsilon})M_q f(0)                                                                                                         \\
        =    & C'M_q f(0)                                                                                                                                                                                \\
    \end{aligned}\\" alt="\begin{aligned}
             & \int_{\left\lvert x\right\rvert>2\left\lvert y\right\rvert}{\left\lvert k^N(x-y)-k^N(x)\right\rvert\left\lvert f(x)\right\rvert dx}                                                                                                                                \\
        =    & \sum_{j=1}^{\infty}\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert k^N(x-y)-k^N(x)\right\rvert\left\lvert f(x)\right\rvert dx}                                                                                                         \\
        \leq & \sum_{j=1}^{\infty}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert k^N(x-y)-k^N(x)\right\rvert^{q'}dx})^\frac{1}{q'}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}                                     \\
        \leq & \sum_{j=1}^{\infty}(\int_{t_j<\left\lvert x\right\rvert}{\left\lvert k^N(x-y)-k^N(x)\right\rvert^{q'}dx})^\frac{1}{q'}(\int_{t_j<\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}                                              \\
        \leq & (\sum_{j=1}^{\infty}Ct_{j}^{-\epsilon-\frac{n}{q}}\left\lvert y\right\rvert^{\epsilon}\left\lvert B(0,2t_j)\right\rvert^{\frac{1}{q}})\sup_j{(\frac{1}{\left\lvert B(0,2t_j)\right\rvert}\int_{\left\lvert x\right\rvert\leq 2t_j}{\left\lvert f(x)\right\rvert^q dx})^\frac{1}{q}} \\
        \leq & C(\sum_{j=1}^{\infty}t_{j}^{-\epsilon-\frac{n}{q}}\left\lvert y\right\rvert^{\epsilon}{t_j}^{\frac{n}{q}})M_q f(0)                                                                                          \\
        =    & C\left\lvert y\right\rvert^{\epsilon}(\sum_{j=1}^{\infty}t_{j}^{-\epsilon})M_q f(0)                                                                                                                         \\
        =    & C\left\lvert y\right\rvert^{\epsilon}\left\lvert y\right\rvert^{-\epsilon}(\sum_{j=1}^{\infty}2^{-j\epsilon})M_q f(0)                                                                                                         \\
        =    & C'M_q f(0)                                                                                                                                                                                \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Since we prove that
<img src="https://www.zhihu.com/equation?tex=(T_mf)^\#(0)\leq A_n\sup_{\epsilon>0}\epsilon^{-n}\int_{\left\lvert x\right\rvert\leq\frac{\epsilon}{2}}\left\lvert f(y)-I_\epsilon\right\rvert dy" alt="(T_mf)^\#(0)\leq A_n\sup_{\epsilon>0}\epsilon^{-n}\int_{\left\lvert x\right\rvert\leq\frac{\epsilon}{2}}\left\lvert f(y)-I_\epsilon\right\rvert dy" class="ee_img tr_noresize" eeimg="1">
and using lemma 5.11 in book: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
             & \epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}                                    \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert\left\lvert f(y)\right\rvert dxd y}                \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(y-x)-K(y)\right\rvert\left\lvert f(y)\right\rvert d y)dx} \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(C'M_q f(0))dx}                                            \\
        \leq & C_qM_qf(0)+C''M_q f(0)                                                                                      \\
        \leq & CM_q f(0)
    \end{aligned}\\" alt="\begin{aligned}
             & \epsilon^{-n}\int_{\left\lvert x\right\rvert<\frac{\epsilon}{2}}{\left\lvert Tf(x)-I_\epsilon\right\rvert dx}                                    \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\iint_{2\left\lvert x\right\rvert<\epsilon<\left\lvert y\right\rvert}{\left\lvert K(x-y)-K(-y)\right\rvert\left\lvert f(y)\right\rvert dxd y}                \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(\int_{2\left\lvert x\right\rvert<\left\lvert y\right\rvert}\left\lvert K(y-x)-K(y)\right\rvert\left\lvert f(y)\right\rvert d y)dx} \\
        \leq & C_qM_qf(0)+\epsilon^{-n}\int_{2\left\lvert x\right\rvert<\epsilon}{(C'M_q f(0))dx}                                            \\
        \leq & C_qM_qf(0)+C''M_q f(0)                                                                                      \\
        \leq & CM_q f(0)
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Thus <img src="https://www.zhihu.com/equation?tex=(T^Nf)^\#(0)\leq CM_qf(0)" alt="(T^Nf)^\#(0)\leq CM_qf(0)" class="ee_img tr_noresize" eeimg="1">.

Note 8 (proof of (6.11) in book). First we prove a variant of Lemma 6.6: 
<img src="https://www.zhihu.com/equation?tex=\label{variant of lemma 6.6}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert^{q'}dx)^\frac{1}{q'}\leq C t^{\epsilon-\frac{n}{q}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^{\alpha}\hat{k}\rVert_s}\quad (0<t<\infty)\\" alt="\label{variant of lemma 6.6}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert^{q'}dx)^\frac{1}{q'}\leq C t^{\epsilon-\frac{n}{q}}\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^{\alpha}\hat{k}\rVert_s}\quad (0<t<\infty)\\" class="ee_img tr_noresize" eeimg="1">


The proof is entirely similar with lemma 6.6, but Holder's inequality is
applied in the form:
<img src="https://www.zhihu.com/equation?tex=\lVert\cdot\rVert_{q'}\leq \lVert\cdot\rVert_{r}\lVert\cdot\rVert_{s'}" alt="\lVert\cdot\rVert_{q'}\leq \lVert\cdot\rVert_{r}\lVert\cdot\rVert_{s'}" class="ee_img tr_noresize" eeimg="1">,
with <img src="https://www.zhihu.com/equation?tex=\frac{1}{r}=\frac{1}{s}-\frac{1}{q}" alt="\frac{1}{r}=\frac{1}{s}-\frac{1}{q}" class="ee_img tr_noresize" eeimg="1">. Notice <img src="https://www.zhihu.com/equation?tex=-ar+n-1<-1" alt="-ar+n-1<-1" class="ee_img tr_noresize" eeimg="1"> by
<img src="https://www.zhihu.com/equation?tex=a-\frac{n}{s}=\epsilon>-\frac{1}{q}" alt="a-\frac{n}{s}=\epsilon>-\frac{1}{q}" class="ee_img tr_noresize" eeimg="1">, the second integral on right hand
side converges. 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert^{q'}dx)^\frac{1}{q'} & \leq C(\int_{}(\sum_{j=1}^n(\left\lvert x_j^ak(x)\right\rvert)^{s'})dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{ar}}dx)^{\frac{1}{r}} \\
                                                         & \leq C\sum_{j=1}^n(\int_{}\left\lvert x_j^ak(x)\right\rvert^{s'}dx)^{\frac{1}{s'}}  (t^{n-a r})^{\frac{1}{r}}                                        \\
                                                         & \leq C\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}  (t^{\frac{n}{r}-a})                                                         \\
    \end{aligned}\\" alt="\begin{aligned}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k(x)\right\rvert^{q'}dx)^\frac{1}{q'} & \leq C(\int_{}(\sum_{j=1}^n(\left\lvert x_j^ak(x)\right\rvert)^{s'})dx)^{\frac{1}{s'}}  (\int_{\left\lvert x\right\rvert>t}^{} \frac{1}{\left\lvert x\right\rvert^{ar}}dx)^{\frac{1}{r}} \\
                                                         & \leq C\sum_{j=1}^n(\int_{}\left\lvert x_j^ak(x)\right\rvert^{s'}dx)^{\frac{1}{s'}}  (t^{n-a r})^{\frac{1}{r}}                                        \\
                                                         & \leq C\max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{k}\rVert_s}  (t^{\frac{n}{r}-a})                                                         \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 By
<img src="https://www.zhihu.com/equation?tex=\frac{n}{r}-a=\frac{n}{s}-\frac{n}{q}-a=-\epsilon-\frac{n}{q}" alt="\frac{n}{r}-a=\frac{n}{s}-\frac{n}{q}-a=-\epsilon-\frac{n}{q}" class="ee_img tr_noresize" eeimg="1">, we have
proof inequality
(6.2.3).

Now we prove:

<img src="https://www.zhihu.com/equation?tex=(\int_{\left\lvert x\right\rvert>2t}\lvert k_j(x-y)-k_j(x)\rvert^{q'}dx)^\frac{1}{q'}\leq\left\{
        \begin{array}{ll}
            Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\quad (2^j\left\lvert y\right\rvert\geq 1) \\
            C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (2^j\left\lvert y\right\rvert<1)
        \end{array}
        \right.\\" alt="(\int_{\left\lvert x\right\rvert>2t}\lvert k_j(x-y)-k_j(x)\rvert^{q'}dx)^\frac{1}{q'}\leq\left\{
        \begin{array}{ll}
            Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\quad (2^j\left\lvert y\right\rvert\geq 1) \\
            C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (2^j\left\lvert y\right\rvert<1)
        \end{array}
        \right.\\" class="ee_img tr_noresize" eeimg="1">



The first inequality is by inequality
(6.2.3) and inequality (6.7) in book:

<img src="https://www.zhihu.com/equation?tex=\lVert D^{\alpha}m_j\rVert_s\leq C 2^{j(-\left\lvert\alpha\right\rvert+\frac{n}{s})}\quad (\left\lvert\alpha\right\rvert\leq a; 1\leq s\leq 2)\\" alt="\lVert D^{\alpha}m_j\rVert_s\leq C 2^{j(-\left\lvert\alpha\right\rvert+\frac{n}{s})}\quad (\left\lvert\alpha\right\rvert\leq a; 1\leq s\leq 2)\\" class="ee_img tr_noresize" eeimg="1">


we have 
<img src="https://www.zhihu.com/equation?tex=\label{variant 2 of lemma 6.6}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k_j(x)\right\rvert^{q'}dx)^\frac{1}{q'}\leq Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\\" alt="\label{variant 2 of lemma 6.6}
        (\int_{\left\lvert x\right\rvert>t}\left\lvert k_j(x)\right\rvert^{q'}dx)^\frac{1}{q'}\leq Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\\" class="ee_img tr_noresize" eeimg="1">



The proof of the second inequality is similar with (6.9). By the same
argument as above, we have

<img src="https://www.zhihu.com/equation?tex=(\int_{\left\lvert x\right\rvert>t}\lvert\tilde{k_j}(x)\rvert^{q'}dx)^\frac{1}{q'} \leq C t^{-\epsilon-\frac{n}{q}} \max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{\tilde{k_j}}\rVert_s}\\" alt="(\int_{\left\lvert x\right\rvert>t}\lvert\tilde{k_j}(x)\rvert^{q'}dx)^\frac{1}{q'} \leq C t^{-\epsilon-\frac{n}{q}} \max_{\left\lvert\alpha\right\rvert=a}{\lVert D^\alpha\hat{\tilde{k_j}}\rVert_s}\\" class="ee_img tr_noresize" eeimg="1">


By <img src="https://www.zhihu.com/equation?tex=\hat{\tilde{k}}=\tilde{m}" alt="\hat{\tilde{k}}=\tilde{m}" class="ee_img tr_noresize" eeimg="1"> and inequality (6.9) in book

<img src="https://www.zhihu.com/equation?tex=\sup_{\left\lvert\alpha\right\rvert=a}\lVert D^{\alpha}\tilde{m_j}\rVert_s\leq C \left\lvert y\right\rvert 2^{j(1-a+\frac{n}{s})}=C \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (1\leq s\leq 2; 2^j\left\lvert y\right\rvert<1)\\" alt="\sup_{\left\lvert\alpha\right\rvert=a}\lVert D^{\alpha}\tilde{m_j}\rVert_s\leq C \left\lvert y\right\rvert 2^{j(1-a+\frac{n}{s})}=C \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (1\leq s\leq 2; 2^j\left\lvert y\right\rvert<1)\\" class="ee_img tr_noresize" eeimg="1">


, we have: 
<img src="https://www.zhihu.com/equation?tex=\label{variant of 6.9}
        (\int_{\left\lvert x\right\rvert>t}\lvert\tilde{k_j}(x)\rvert^{q'}dx)^\frac{1}{q'} \leq C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (1\leq s\leq 2; 2^j\left\lvert y\right\rvert<1)\\" alt="\label{variant of 6.9}
        (\int_{\left\lvert x\right\rvert>t}\lvert\tilde{k_j}(x)\rvert^{q'}dx)^\frac{1}{q'} \leq C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (1\leq s\leq 2; 2^j\left\lvert y\right\rvert<1)\\" class="ee_img tr_noresize" eeimg="1">



Now by inequality
(6.2.4) and inequality
(8) we have:

<img src="https://www.zhihu.com/equation?tex=(\int_{\left\lvert x\right\rvert>2t}\lvert k_j(x-y)-k_j(x)\rvert^{q'}dx)^\frac{1}{q'}\leq\left\{
        \begin{array}{ll}
            Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\quad (2^j\left\lvert y\right\rvert\geq 1) \\
            C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (2^j\left\lvert y\right\rvert<1)
        \end{array}
        \right.\\" alt="(\int_{\left\lvert x\right\rvert>2t}\lvert k_j(x-y)-k_j(x)\rvert^{q'}dx)^\frac{1}{q'}\leq\left\{
        \begin{array}{ll}
            Ct^{-\epsilon-\frac{n}{q}}2^{-j\epsilon}\quad (2^j\left\lvert y\right\rvert\geq 1) \\
            C t^{-\epsilon-\frac{n}{q}} \left\lvert y\right\rvert 2^{j(1-\epsilon)}\quad (2^j\left\lvert y\right\rvert<1)
        \end{array}
        \right.\\" class="ee_img tr_noresize" eeimg="1">

 Finally, by summing with different part of index,
(6.11) is an easy consequence of above inequality.

By definition of subalgebra, we only need to check that <img src="https://www.zhihu.com/equation?tex=T_{am_1+bm_2}" alt="T_{am_1+bm_2}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=T_{m_1m_2}" alt="T_{m_1m_2}" class="ee_img tr_noresize" eeimg="1"> are bounded. These are easy since <img src="https://www.zhihu.com/equation?tex=T_m" alt="T_m" class="ee_img tr_noresize" eeimg="1"> is linear on <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=T_{m_1m_2}=T_{m_1}T_{m_2}" alt="T_{m_1m_2}=T_{m_1}T_{m_2}" class="ee_img tr_noresize" eeimg="1">. Suppose the affine transformations
<img src="https://www.zhihu.com/equation?tex=A(x)=h+L(x)" alt="A(x)=h+L(x)" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=L" alt="L" class="ee_img tr_noresize" eeimg="1"> is linear transformation. I don't know why the
following holds:

<img src="https://www.zhihu.com/equation?tex=(f\circ A)^\wedge(\xi)=e^{2\pi i h\cdot\tilde{L}(\xi)}\left\lvert\det{L}\right\rvert^{-1}\hat{f}(\tilde{L}(\xi))\\" alt="(f\circ A)^\wedge(\xi)=e^{2\pi i h\cdot\tilde{L}(\xi)}\left\lvert\det{L}\right\rvert^{-1}\hat{f}(\tilde{L}(\xi))\\" class="ee_img tr_noresize" eeimg="1">


with <img src="https://www.zhihu.com/equation?tex=\tilde{L}=(L^*)^{-1}" alt="\tilde{L}=(L^*)^{-1}" class="ee_img tr_noresize" eeimg="1"> and how this implies multipliers are
invariant under transformation <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">.
