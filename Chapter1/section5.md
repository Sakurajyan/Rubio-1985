The Conjugate Function
======================

In section 1, given a integrable function 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
, we know the
harmonic function 
<img src="https://www.zhihu.com/equation?tex=u=P(f)" alt="u=P(f)" class="ee_img tr_noresize" eeimg="1">
 determines a holomorphic function 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 up to a
constant 
<img src="https://www.zhihu.com/equation?tex=c" alt="c" class="ee_img tr_noresize" eeimg="1">
 if we consider 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 as the real part of 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
. Let
<img src="https://www.zhihu.com/equation?tex=v(re^{it})=F(re^{it})" alt="v(re^{it})=F(re^{it})" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=v(0)=0" alt="v(0)=0" class="ee_img tr_noresize" eeimg="1">
. Then we can define the conjugate
function of 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 to be: 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}(t)=\lim_{t\to 1}{v(re^{it})}\\" alt="\tilde{f}(t)=\lim_{t\to 1}{v(re^{it})}\\" class="ee_img tr_noresize" eeimg="1">
 
 The
next theorem ensures the above limit exists for a.e. t:

Theorem 5.0.1 (theorem 5.2 in book). Let 
<img src="https://www.zhihu.com/equation?tex=F\in H(D)" alt="F\in H(D)" class="ee_img tr_noresize" eeimg="1">
 be such that 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{F(z)}\geq 0" alt="\operatorname{Re}{F(z)}\geq 0" class="ee_img tr_noresize" eeimg="1">
 for every
<img src="https://www.zhihu.com/equation?tex=z\in D" alt="z\in D" class="ee_img tr_noresize" eeimg="1">
. Then 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 has N.T. limits at almost every boundary point.

Remark. I don't know why 
<img src="https://www.zhihu.com/equation?tex=\lim{G(z)}=\lim{\frac{1}{1+F(z)}}" alt="\lim{G(z)}=\lim{\frac{1}{1+F(z)}}" class="ee_img tr_noresize" eeimg="1">
 as 
<img src="https://www.zhihu.com/equation?tex=z\to e^{it}" alt="z\to e^{it}" class="ee_img tr_noresize" eeimg="1">
N.T. is different from 0 a.e. t.

5.1 Estimate conjugate function 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}" alt="\tilde{f}" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">

--------------------------------------------------------------------

The following theorem is key to estimate 
<img src="https://www.zhihu.com/equation?tex=\lVert\tilde{f}\rVert_p" alt="\lVert\tilde{f}\rVert_p" class="ee_img tr_noresize" eeimg="1">
 for
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
:

Theorem 5.1.1 ((theorem 5.3 in book)). For every 
<img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=1<p\leq 2" alt="1<p\leq 2" class="ee_img tr_noresize" eeimg="1">
, there is a
constant 
<img src="https://www.zhihu.com/equation?tex=C_p" alt="C_p" class="ee_img tr_noresize" eeimg="1">
, s.t. for every 
<img src="https://www.zhihu.com/equation?tex=F(z)=u(z)+iv(z)" alt="F(z)=u(z)+iv(z)" class="ee_img tr_noresize" eeimg="1">
, holomorphic in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
,
with 
<img src="https://www.zhihu.com/equation?tex=u(z)>0" alt="u(z)>0" class="ee_img tr_noresize" eeimg="1">
 on 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1">
 real valued and 
<img src="https://www.zhihu.com/equation?tex=v(0)=0" alt="v(0)=0" class="ee_img tr_noresize" eeimg="1">
, the inequality:

<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}{\left\lvert v(re^{it})\right\rvert^p d t}\leq C_p \int_{-\pi}^{\pi}{\left\lvert u(re^{it})\right\rvert^p d t}\\" alt="\int_{-\pi}^{\pi}{\left\lvert v(re^{it})\right\rvert^p d t}\leq C_p \int_{-\pi}^{\pi}{\left\lvert u(re^{it})\right\rvert^p d t}\\" class="ee_img tr_noresize" eeimg="1">

holds for every 
<img src="https://www.zhihu.com/equation?tex=0<r<1" alt="0<r<1" class="ee_img tr_noresize" eeimg="1">
.

Remark. We need inequality
<img src="https://www.zhihu.com/equation?tex=\left\lvert\sin{\theta}\right\rvert^p\leq C_p\left\lvert\cos{\theta}\right\rvert^p-D_p\cos{(p\theta)}" alt="\left\lvert\sin{\theta}\right\rvert^p\leq C_p\left\lvert\cos{\theta}\right\rvert^p-D_p\cos{(p\theta)}" class="ee_img tr_noresize" eeimg="1">
for 
<img src="https://www.zhihu.com/equation?tex=\left\lvert\theta\right\rvert<\frac{\pi}{2}" alt="\left\lvert\theta\right\rvert<\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
. To use this
inequality, we need 
<img src="https://www.zhihu.com/equation?tex=\psi(z)<\frac{\pi}{2}" alt="\psi(z)<\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
 where 
<img src="https://www.zhihu.com/equation?tex=\psi(z)=\arg{F(z)}" alt="\psi(z)=\arg{F(z)}" class="ee_img tr_noresize" eeimg="1">
.
<img src="https://www.zhihu.com/equation?tex=u(z)>0" alt="u(z)>0" class="ee_img tr_noresize" eeimg="1">
 ensures this inequality hold.

However, this inequality actually holds if 
<img src="https://www.zhihu.com/equation?tex=u\geq 0" alt="u\geq 0" class="ee_img tr_noresize" eeimg="1">
 since 
<img src="https://www.zhihu.com/equation?tex=u\geq 0" alt="u\geq 0" class="ee_img tr_noresize" eeimg="1">
implies 
<img src="https://www.zhihu.com/equation?tex=u>0" alt="u>0" class="ee_img tr_noresize" eeimg="1">
 by maximum principle.

Now we give the estimation of 
<img src="https://www.zhihu.com/equation?tex=\lVert\tilde{f}\rVert_p" alt="\lVert\tilde{f}\rVert_p" class="ee_img tr_noresize" eeimg="1">
 for
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
:

Corollary 5.1.2 (Marcel Riesz inequality (corollary 5.5 in book)). For every 
<img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
,
there is a constant 
<img src="https://www.zhihu.com/equation?tex=C_p" alt="C_p" class="ee_img tr_noresize" eeimg="1">
, s.t. for each 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
:

<img src="https://www.zhihu.com/equation?tex=\label{ieq: Marcel Riesz inequality}
        \int_{-\pi}^{\pi}{\lvert\tilde{f}(t)\rvert^p d t}\leq B_p \int_{-\pi}^{\pi}{\left\lvert f(t)\right\rvert^p d t}\\" alt="\label{ieq: Marcel Riesz inequality}
        \int_{-\pi}^{\pi}{\lvert\tilde{f}(t)\rvert^p d t}\leq B_p \int_{-\pi}^{\pi}{\left\lvert f(t)\right\rvert^p d t}\\" class="ee_img tr_noresize" eeimg="1">


Remark. First consider 
<img src="https://www.zhihu.com/equation?tex=1<p\leq 2" alt="1<p\leq 2" class="ee_img tr_noresize" eeimg="1">
 case. Let 
<img src="https://www.zhihu.com/equation?tex=f^+=\max{(f,0)}" alt="f^+=\max{(f,0)}" class="ee_img tr_noresize" eeimg="1">
,

<img src="https://www.zhihu.com/equation?tex=v_1=\tilde{f^+}" alt="v_1=\tilde{f^+}" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f^-=\max{(-f,0)}" alt="f^-=\max{(-f,0)}" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=v_2=\tilde{f^-}" alt="v_2=\tilde{f^-}" class="ee_img tr_noresize" eeimg="1">
. Notice
<img src="https://www.zhihu.com/equation?tex=u_1=P(f^+)=0" alt="u_1=P(f^+)=0" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=v_1=0" alt="v_1=0" class="ee_img tr_noresize" eeimg="1">
 if 
<img src="https://www.zhihu.com/equation?tex=f^+=0" alt="f^+=0" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=u_2=P(f^-)=0" alt="u_2=P(f^-)=0" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=v_2=0" alt="v_2=0" class="ee_img tr_noresize" eeimg="1">
 if
<img src="https://www.zhihu.com/equation?tex=f^-=0" alt="f^-=0" class="ee_img tr_noresize" eeimg="1">
. Thus we can write:

<img src="https://www.zhihu.com/equation?tex={\color{blue}\int_{-\pi}^{\pi}{\lvert v(re^{it})\rvert^p d t}=\int_{-\pi}^{\pi}{\left\lvert v_1(re^{it})\right\rvert^p+\left\lvert v_2(re^{it})\right\rvert^p d t}}\\" alt="{\color{blue}\int_{-\pi}^{\pi}{\lvert v(re^{it})\rvert^p d t}=\int_{-\pi}^{\pi}{\left\lvert v_1(re^{it})\right\rvert^p+\left\lvert v_2(re^{it})\right\rvert^p d t}}\\" class="ee_img tr_noresize" eeimg="1">


<img src="https://www.zhihu.com/equation?tex={\color{blue}\int_{-\pi}^{\pi}{\lvert u(re^{it})\rvert^p d t}=\int_{-\pi}^{\pi}{\left\lvert u_1(re^{it})\right\rvert^p+\left\lvert u_2(re^{it})\right\rvert^p d t}}\\" alt="{\color{blue}\int_{-\pi}^{\pi}{\lvert u(re^{it})\rvert^p d t}=\int_{-\pi}^{\pi}{\left\lvert u_1(re^{it})\right\rvert^p+\left\lvert u_2(re^{it})\right\rvert^p d t}}\\" class="ee_img tr_noresize" eeimg="1">

Since
<img src="https://www.zhihu.com/equation?tex=\int{\left\lvert v_1(re^{it})\right\rvert}\leq C_p\int{\left\lvert u_1(re^{it})\right\rvert}" alt="\int{\left\lvert v_1(re^{it})\right\rvert}\leq C_p\int{\left\lvert u_1(re^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
and
<img src="https://www.zhihu.com/equation?tex=\int{\left\lvert v_2(re^{it})\right\rvert}\leq C_p\int{\left\lvert u_2(re^{it})\right\rvert}" alt="\int{\left\lvert v_2(re^{it})\right\rvert}\leq C_p\int{\left\lvert u_2(re^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
by theorem 5.1.1, we have

<img src="https://www.zhihu.com/equation?tex=\int{\left\lvert v(re^{it})\right\rvert}\leq C_p\int{\left\lvert u(re^{it})\right\rvert}" alt="\int{\left\lvert v(re^{it})\right\rvert}\leq C_p\int{\left\lvert u(re^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
.
Fatou lemma yields inequality (5.1)

For 
<img src="https://www.zhihu.com/equation?tex=2<p<\infty" alt="2<p<\infty" class="ee_img tr_noresize" eeimg="1">
 case, we use
<img src="https://www.zhihu.com/equation?tex=\lVert v(re^{i\cdot})\rVert_p=\sup_{\lVert g\rVert_{p'}\leq 1}{\int{v(re^{it})g(t)d t}}" alt="\lVert v(re^{i\cdot})\rVert_p=\sup_{\lVert g\rVert_{p'}\leq 1}{\int{v(re^{it})g(t)d t}}" class="ee_img tr_noresize" eeimg="1">
by Hahn-Banach theorem.

Let 
<img src="https://www.zhihu.com/equation?tex=h=P(g)" alt="h=P(g)" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=w=\tilde{h}" alt="w=\tilde{h}" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=w(0)=0" alt="w(0)=0" class="ee_img tr_noresize" eeimg="1">
. Since 
<img src="https://www.zhihu.com/equation?tex=h+iw\in H^{p'}" alt="h+iw\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=h+iw" alt="h+iw" class="ee_img tr_noresize" eeimg="1">
 can be written as Poisson integral of boundary function,
<img src="https://www.zhihu.com/equation?tex=h(re^{it})+iw(re^{it})=P(g+i\tilde{g})" alt="h(re^{it})+iw(re^{it})=P(g+i\tilde{g})" class="ee_img tr_noresize" eeimg="1">
. Thus we have 
<img src="https://www.zhihu.com/equation?tex=w=P(\tilde{g})" alt="w=P(\tilde{g})" class="ee_img tr_noresize" eeimg="1">
.

By Holder inequality, We have: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
                 & \int{\left\lvert(u(rz)+iv(rz))(h(z)+iw(z))-(u(re^{it})+iv(re^{it})) (g(t)+i\tilde{g}(t))\right\rvert}                                     \\
            \leq & \int\vert (u(r z)+iv(r z))(h(z)+i w(z))-(u(r z)+iv(r z))(g(t)+i\tilde{g}(t))                                             \\
                 & +(u(r z)+iv(r z))(g(t)+i\tilde{g}(t))(u(re^{it})+iv(re^{it}))(g(t)+i\tilde{g}(t)) \vert                                  \\
            \leq & \int\left\lvert u(rz)+iv(rz)\right\rvert\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t))\right\rvert                                                           \\
                 & +\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert\left\lvert(g(t)+i\tilde{g}(t))\right\rvert                                           \\
            \leq & (\int\left\lvert u(rz)+iv(rz)\right\rvert^p)^\frac{1}{p}  (\int\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t)))\right\rvert^{p'})^\frac{1}{p'}                \\
                 & +(\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert^p)^\frac{1}{p}  (\int\left\lvert(g(t)+i\tilde{g}(t))\right\rvert^{p'})^\frac{1}{p'}
        \end{aligned}\\" alt="\begin{aligned}
                 & \int{\left\lvert(u(rz)+iv(rz))(h(z)+iw(z))-(u(re^{it})+iv(re^{it})) (g(t)+i\tilde{g}(t))\right\rvert}                                     \\
            \leq & \int\vert (u(r z)+iv(r z))(h(z)+i w(z))-(u(r z)+iv(r z))(g(t)+i\tilde{g}(t))                                             \\
                 & +(u(r z)+iv(r z))(g(t)+i\tilde{g}(t))(u(re^{it})+iv(re^{it}))(g(t)+i\tilde{g}(t)) \vert                                  \\
            \leq & \int\left\lvert u(rz)+iv(rz)\right\rvert\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t))\right\rvert                                                           \\
                 & +\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert\left\lvert(g(t)+i\tilde{g}(t))\right\rvert                                           \\
            \leq & (\int\left\lvert u(rz)+iv(rz)\right\rvert^p)^\frac{1}{p}  (\int\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t)))\right\rvert^{p'})^\frac{1}{p'}                \\
                 & +(\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert^p)^\frac{1}{p}  (\int\left\lvert(g(t)+i\tilde{g}(t))\right\rvert^{p'})^\frac{1}{p'}
        \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">


<img src="https://www.zhihu.com/equation?tex=(\int\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t)))\right\rvert^{p'})^\frac{1}{p'}\to 0" alt="(\int\left\lvert((h(z)+iw(z))-(g(t)+i\tilde{g}(t)))\right\rvert^{p'})^\frac{1}{p'}\to 0" class="ee_img tr_noresize" eeimg="1">

since 
<img src="https://www.zhihu.com/equation?tex=h+iw\in H^{p'}" alt="h+iw\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
.\

<img src="https://www.zhihu.com/equation?tex=(\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert^p)^\frac{1}{p}\to 0" alt="(\int\left\lvert((u(rz)+iv(rz))-(u(re^{it})+iv(re^{it})))\right\rvert^p)^\frac{1}{p}\to 0" class="ee_img tr_noresize" eeimg="1">

since 
<img src="https://www.zhihu.com/equation?tex=\left\lvert re^{it}\right\rvert<1" alt="\left\lvert re^{it}\right\rvert<1" class="ee_img tr_noresize" eeimg="1">
.

Thus
<img src="https://www.zhihu.com/equation?tex=(u(rz)+iv(rz))(h(z)+iw(z))\to (u(re^{it})+iv(re^{it})) (g(t)+i\tilde{g}(t))" alt="(u(rz)+iv(rz))(h(z)+iw(z))\to (u(re^{it})+iv(re^{it})) (g(t)+i\tilde{g}(t))" class="ee_img tr_noresize" eeimg="1">
in 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
.

Our final result is estimation of imaginary part of holomorphic
function:

Corollary 1.5.1.3 (corollary 5.8 in book). If 
<img src="https://www.zhihu.com/equation?tex=F\in H(D)" alt="F\in H(D)" class="ee_img tr_noresize" eeimg="1">
, then for every 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
 and every 
<img src="https://www.zhihu.com/equation?tex=0\leq r<1" alt="0\leq r<1" class="ee_img tr_noresize" eeimg="1">
:

<img src="https://www.zhihu.com/equation?tex=(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\operatorname{Im}{F(re^{it})}\right\rvert^p d t})^\frac{1}{p}\leq B_p^\frac{1}{p}(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\operatorname{Re}{F(re^{it})}\right\rvert^p d t})^\frac{1}{p}+\left\lvert\operatorname{Im}{F(0)}\right\rvert\\" alt="(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\operatorname{Im}{F(re^{it})}\right\rvert^p d t})^\frac{1}{p}\leq B_p^\frac{1}{p}(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\operatorname{Re}{F(re^{it})}\right\rvert^p d t})^\frac{1}{p}+\left\lvert\operatorname{Im}{F(0)}\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


5.2 Estimate conjugate function 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}" alt="\tilde{f}" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">

------------------------------------------------------

The corollary
5.1.2 does not hold for 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
. For
example, Poisson kernel 
<img src="https://www.zhihu.com/equation?tex=P_r(t)" alt="P_r(t)" class="ee_img tr_noresize" eeimg="1">
 is in 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=\lVert P_r(t)\rVert_1=2\pi" alt="\lVert P_r(t)\rVert_1=2\pi" class="ee_img tr_noresize" eeimg="1">
 but conjugate Poisson kernel 
<img src="https://www.zhihu.com/equation?tex=Q_r(t)" alt="Q_r(t)" class="ee_img tr_noresize" eeimg="1">
 is
not, 
<img src="https://www.zhihu.com/equation?tex=\int{\left\lvert Q_r(t)\right\rvert}=4\log{\frac{1+r}{1-r}}" alt="\int{\left\lvert Q_r(t)\right\rvert}=4\log{\frac{1+r}{1-r}}" class="ee_img tr_noresize" eeimg="1">
.

Remark. By Hahn-Banach theorem and duality of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
, for 
<img src="https://www.zhihu.com/equation?tex=v\in L^1" alt="v\in L^1" class="ee_img tr_noresize" eeimg="1">
,

<img src="https://www.zhihu.com/equation?tex=\int{\left\lvert v\right\rvert}=\sup_{\lVert g\rVert_\infty\leq 1}{\left\lvert\int{vg}\right\rvert}" alt="\int{\left\lvert v\right\rvert}=\sup_{\lVert g\rVert_\infty\leq 1}{\left\lvert\int{vg}\right\rvert}" class="ee_img tr_noresize" eeimg="1">
.
I don't know how the author concludes conjugate function operator is not
bounded in 
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">
.

For 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
, conjugate operator is of weak type 
<img src="https://www.zhihu.com/equation?tex=(1,1)" alt="(1,1)" class="ee_img tr_noresize" eeimg="1">
 (theorem 5.9
in book) and type 
<img src="https://www.zhihu.com/equation?tex=(1,p)" alt="(1,p)" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=0<p<1" alt="0<p<1" class="ee_img tr_noresize" eeimg="1">
 (corollary 5.10 in book).


Remark. <img src="https://www.zhihu.com/equation?tex=v(0)=0" alt="v(0)=0" class="ee_img tr_noresize" eeimg="1">
 is a necessary condition for conjugate operator is linear
operator.

The function
<img src="https://www.zhihu.com/equation?tex=f(z)=\frac{z-i\lambda}{z+i\lambda}=\frac{\left\lvert z\right\rvert^2-\lambda^2-2i\lambda\operatorname{Re}{z}}{\left\lvert z\right\rvert^2+\lambda^2+2\lambda\operatorname{Im}{z}}" alt="f(z)=\frac{z-i\lambda}{z+i\lambda}=\frac{\left\lvert z\right\rvert^2-\lambda^2-2i\lambda\operatorname{Re}{z}}{\left\lvert z\right\rvert^2+\lambda^2+2\lambda\operatorname{Im}{z}}" class="ee_img tr_noresize" eeimg="1">
maps 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{z}>0" alt="\operatorname{Re}{z}>0" class="ee_img tr_noresize" eeimg="1">
 to 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Im}{z}<0" alt="\operatorname{Im}{z}<0" class="ee_img tr_noresize" eeimg="1">
 since
<img src="https://www.zhihu.com/equation?tex=1\mapsto\frac{1-\lambda^2-2i\lambda}{1+\lambda^2}" alt="1\mapsto\frac{1-\lambda^2-2i\lambda}{1+\lambda^2}" class="ee_img tr_noresize" eeimg="1">
.

If 
<img src="https://www.zhihu.com/equation?tex=\left\lvert z\right\rvert=\lambda" alt="\left\lvert z\right\rvert=\lambda" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=f(z)=\frac{-i\operatorname{Re}{z}}{\lambda+\operatorname{Im}{z}}" alt="f(z)=\frac{-i\operatorname{Re}{z}}{\lambda+\operatorname{Im}{z}}" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=\arg{f(z)}=-\frac{\pi}{2}" alt="\arg{f(z)}=-\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=h_\lambda(z)=\frac{1}{2}" alt="h_\lambda(z)=\frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
. If
<img src="https://www.zhihu.com/equation?tex=k\neq \frac{1}{2}" alt="k\neq \frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
, the level lines 
<img src="https://www.zhihu.com/equation?tex=h_\lambda(z)=k" alt="h_\lambda(z)=k" class="ee_img tr_noresize" eeimg="1">
 when

<img src="https://www.zhihu.com/equation?tex=\tan\arg{f(z)}=\frac{-2\lambda\operatorname{Re}{z}}{\left\lvert z\right\rvert^2-\lambda^2}=\tan\pi(k-1)" alt="\tan\arg{f(z)}=\frac{-2\lambda\operatorname{Re}{z}}{\left\lvert z\right\rvert^2-\lambda^2}=\tan\pi(k-1)" class="ee_img tr_noresize" eeimg="1">
.
Which is 
<img src="https://www.zhihu.com/equation?tex=-2\lambda x=c(k)(x^2+y^2-\lambda^2)" alt="-2\lambda x=c(k)(x^2+y^2-\lambda^2)" class="ee_img tr_noresize" eeimg="1">
. This is a circle passing
through 
<img src="https://www.zhihu.com/equation?tex=i\lambda" alt="i\lambda" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=-i\lambda" alt="-i\lambda" class="ee_img tr_noresize" eeimg="1">
.

Let 
<img src="https://www.zhihu.com/equation?tex=f(x)=\frac{1}{x}+\arg{\tan{x}}-\frac{\pi}{2}" alt="f(x)=\frac{1}{x}+\arg{\tan{x}}-\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
.
<img src="https://www.zhihu.com/equation?tex=f'(x)=-\frac{1}{x^2}+\frac{1}{1+x^2}<0" alt="f'(x)=-\frac{1}{x^2}+\frac{1}{1+x^2}<0" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=\lim_{x\to\infty}f(x)=0" alt="\lim_{x\to\infty}f(x)=0" class="ee_img tr_noresize" eeimg="1">
.
Thus 
<img src="https://www.zhihu.com/equation?tex=f(x)>0" alt="f(x)>0" class="ee_img tr_noresize" eeimg="1">
. The inequality

<img src="https://www.zhihu.com/equation?tex=\frac{\pi}{2}-\arg{\tan{\lambda}}\leq\frac{1}{\lambda}" alt="\frac{\pi}{2}-\arg{\tan{\lambda}}\leq\frac{1}{\lambda}" class="ee_img tr_noresize" eeimg="1">
 holds.


<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is harmonic and 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is holomorphic, then 
<img src="https://www.zhihu.com/equation?tex=u\circ F" alt="u\circ F" class="ee_img tr_noresize" eeimg="1">
 is holomorphic.

<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{G}" alt="\operatorname{Re}{G}" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=G" alt="G" class="ee_img tr_noresize" eeimg="1">
 holomorphic. 
<img src="https://www.zhihu.com/equation?tex=G\circ F" alt="G\circ F" class="ee_img tr_noresize" eeimg="1">
 is
holomorphic. Thus 
<img src="https://www.zhihu.com/equation?tex=u\circ F=\operatorname{Re}{G\circ F}" alt="u\circ F=\operatorname{Re}{G\circ F}" class="ee_img tr_noresize" eeimg="1">
 is harmonic.

We should pay attention to this statement: *Since
<img src="https://www.zhihu.com/equation?tex=\tilde{f}(t)=\lim_{r\to 1}{v(re^{it})}" alt="\tilde{f}(t)=\lim_{r\to 1}{v(re^{it})}" class="ee_img tr_noresize" eeimg="1">
, then* 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \left\lvert E_\lambda\right\rvert & =\left\lvert\bigcup_{n=1}^{\infty}\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert \\
                        & =\left\lvert\lim_{n\to\infty}\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert      \\
                        & =\lim_{n\to\infty}\left\lvert\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert
    \end{aligned}\\" alt="\begin{aligned}
        \left\lvert E_\lambda\right\rvert & =\left\lvert\bigcup_{n=1}^{\infty}\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert \\
                        & =\left\lvert\lim_{n\to\infty}\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert      \\
                        & =\lim_{n\to\infty}\left\lvert\bigcap_{j=n}^{\infty}\{t:\left\lvert v(r_je^{it})\right\rvert>\lambda\}\right\rvert
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 The last equality is by continuity of measure.

I don't know why author choose 
<img src="https://www.zhihu.com/equation?tex=C=\frac{64}{\pi}" alt="C=\frac{64}{\pi}" class="ee_img tr_noresize" eeimg="1">
 finally.

5.3 Conjugate function and 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 space
----------------------------------

We now describe 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=1\leq q\leq \infty" alt="1\leq q\leq \infty" class="ee_img tr_noresize" eeimg="1">
. Suppose 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, we
know 
<img src="https://www.zhihu.com/equation?tex=F=P(f)" alt="F=P(f)" class="ee_img tr_noresize" eeimg="1">
 for some 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
 implies 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}" alt="\tilde{f}" class="ee_img tr_noresize" eeimg="1">
 is
well defined. We can write 
<img src="https://www.zhihu.com/equation?tex=F=f+\tilde{f}+i\operatorname{Im}{F(0)}" alt="F=f+\tilde{f}+i\operatorname{Im}{F(0)}" class="ee_img tr_noresize" eeimg="1">
 for
boundary 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=F(z)\in H^p" alt="F(z)\in H^p" class="ee_img tr_noresize" eeimg="1">
 implies 
<img src="https://www.zhihu.com/equation?tex=f\in\operatorname{Re}{L^p}" alt="f\in\operatorname{Re}{L^p}" class="ee_img tr_noresize" eeimg="1">

(theorem 3.6 in book). Thus:

<img src="https://www.zhihu.com/equation?tex=H^p\subset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}\\" alt="H^p\subset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}\\" class="ee_img tr_noresize" eeimg="1">

By writing 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}=F-f-\operatorname{Im}{F(0)}" alt="\tilde{f}=F-f-\operatorname{Im}{F(0)}" class="ee_img tr_noresize" eeimg="1">
, we know
<img src="https://www.zhihu.com/equation?tex=\tilde{f}\in L^p" alt="\tilde{f}\in L^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=1\leq p\leq\infty" alt="1\leq p\leq\infty" class="ee_img tr_noresize" eeimg="1">
 (conclusion in book).

When 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
 guarantees 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}\in L^p" alt="\tilde{f}\in L^p" class="ee_img tr_noresize" eeimg="1">
.
<img src="https://www.zhihu.com/equation?tex=(f+i\tilde{f}+ic)\in L^p" alt="(f+i\tilde{f}+ic)\in L^p" class="ee_img tr_noresize" eeimg="1">
 implies 
<img src="https://www.zhihu.com/equation?tex=P(f+i\tilde{f}+ic)\in H^p" alt="P(f+i\tilde{f}+ic)\in H^p" class="ee_img tr_noresize" eeimg="1">
. Thus for

<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
:

<img src="https://www.zhihu.com/equation?tex=H^p\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}\\" alt="H^p\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}\\" class="ee_img tr_noresize" eeimg="1">

Here we take 
<img src="https://www.zhihu.com/equation?tex=f\in\operatorname{Re}{L^p}" alt="f\in\operatorname{Re}{L^p}" class="ee_img tr_noresize" eeimg="1">
 to make 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}" alt="\tilde{f}" class="ee_img tr_noresize" eeimg="1">
meaningful. We also have 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{H^p}=\operatorname{Re}{L^p}" alt="\operatorname{Re}{H^p}=\operatorname{Re}{L^p}" class="ee_img tr_noresize" eeimg="1">
in this case.

For 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
 no longer guarantees 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}\in L^p" alt="\tilde{f}\in L^p" class="ee_img tr_noresize" eeimg="1">
. But we
know if 
<img src="https://www.zhihu.com/equation?tex=f,\tilde{f}\in L^1" alt="f,\tilde{f}\in L^1" class="ee_img tr_noresize" eeimg="1">
, then 
<img src="https://www.zhihu.com/equation?tex=F=P(f+i\tilde{f}+ic)\in H^1" alt="F=P(f+i\tilde{f}+ic)\in H^1" class="ee_img tr_noresize" eeimg="1">
. Thus:

<img src="https://www.zhihu.com/equation?tex=H^1\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^1},\tilde{f}\in{L^1}, c\in\mathbb{R}\}\\" alt="H^1\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^1},\tilde{f}\in{L^1}, c\in\mathbb{R}\}\\" class="ee_img tr_noresize" eeimg="1">

Here we take 
<img src="https://www.zhihu.com/equation?tex=f\in\operatorname{Re}{L^p}" alt="f\in\operatorname{Re}{L^p}" class="ee_img tr_noresize" eeimg="1">
 to make 
<img src="https://www.zhihu.com/equation?tex=\tilde{f}" alt="\tilde{f}" class="ee_img tr_noresize" eeimg="1">
meaningful. We also have
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{H^1}=\{f\in\operatorname{Re}{L^1}:\tilde{f}\in{L^1}\}\subsetneqq\operatorname{Re}{L^1}" alt="\operatorname{Re}{H^1}=\{f\in\operatorname{Re}{L^1}:\tilde{f}\in{L^1}\}\subsetneqq\operatorname{Re}{L^1}" class="ee_img tr_noresize" eeimg="1">

by counterexample Poisson kernel.

Similarly we have:

<img src="https://www.zhihu.com/equation?tex=H^\infty\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^\infty},\tilde{f}\in{L^\infty}, c\in\mathbb{R}\}\\" alt="H^\infty\supset\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^\infty},\tilde{f}\in{L^\infty}, c\in\mathbb{R}\}\\" class="ee_img tr_noresize" eeimg="1">

and

<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{H^\infty}=\{f\in\operatorname{Re}{L^\infty}:\tilde{f}\in{L^\infty}\}\subsetneqq\operatorname{Re}{L^\infty}\\" alt="\operatorname{Re}{H^\infty}=\{f\in\operatorname{Re}{L^\infty}:\tilde{f}\in{L^\infty}\}\subsetneqq\operatorname{Re}{L^\infty}\\" class="ee_img tr_noresize" eeimg="1">


Author suppose 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})\in H^p" alt="F(e^{it})\in H^p" class="ee_img tr_noresize" eeimg="1">
, but if 
<img src="https://www.zhihu.com/equation?tex=F(re^{it})\in H^p" alt="F(re^{it})\in H^p" class="ee_img tr_noresize" eeimg="1">
 we only
know 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})\in L^p" alt="F(e^{it})\in L^p" class="ee_img tr_noresize" eeimg="1">
. In other words, 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})\in H^p" alt="F(e^{it})\in H^p" class="ee_img tr_noresize" eeimg="1">
 is not
clear.

5.4 Conjugate operator
------------------


Remark
<img src="https://www.zhihu.com/equation?tex=\frac{r\sin{t}}{1+r^2-2r\cos{t}}\to\frac{1}{2\tan{\frac{t}{2}}}\\" alt="\frac{r\sin{t}}{1+r^2-2r\cos{t}}\to\frac{1}{2\tan{\frac{t}{2}}}\\" class="ee_img tr_noresize" eeimg="1">

 as
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
 fails if 
<img src="https://www.zhihu.com/equation?tex=t=0" alt="t=0" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \left\lvert\frac{r\sin{t}}{1+r^2-2r\cos{t}}\right\rvert & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{1+r^2-2r(2(\cos{\frac{t}{2}})^2-1)}\right\rvert \\
                                               & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{(1+r)^2-4r(\cos{\frac{t}{2}})^2}\right\rvert    \\
                                               & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{(1-r)^2+4r(\sin{\frac{t}{2}})^2}\right\rvert    \\
                                               & \leq\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{4r(\sin{\frac{t}{2}})^2}\right\rvert         \\
                                               & =\left\lvert\frac{1}{2\tan{\frac{t}{2}}}\right\rvert                                                    \\
                                               & {\color{red}=\frac{1}{2\tan{\left\lvert\frac{t}{2}\right\rvert}}}                                       \\
                                               & {\leq\frac{1}{\left\lvert t\right\rvert}}
    \end{aligned}\\" alt="\begin{aligned}
        \left\lvert\frac{r\sin{t}}{1+r^2-2r\cos{t}}\right\rvert & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{1+r^2-2r(2(\cos{\frac{t}{2}})^2-1)}\right\rvert \\
                                               & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{(1+r)^2-4r(\cos{\frac{t}{2}})^2}\right\rvert    \\
                                               & =\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{(1-r)^2+4r(\sin{\frac{t}{2}})^2}\right\rvert    \\
                                               & \leq\left\lvert\frac{2r\sin{\frac{t}{2}}\cos{\frac{t}{2}}}{4r(\sin{\frac{t}{2}})^2}\right\rvert         \\
                                               & =\left\lvert\frac{1}{2\tan{\frac{t}{2}}}\right\rvert                                                    \\
                                               & {\color{red}=\frac{1}{2\tan{\left\lvert\frac{t}{2}\right\rvert}}}                                       \\
                                               & {\leq\frac{1}{\left\lvert t\right\rvert}}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">


The following theorem shows we can define conjugate function without
getting inside the disk, by singular integral:

Theorem 5.4.1 (theorem 5.14 in book). If 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
, then

<img src="https://www.zhihu.com/equation?tex=\tilde{f}(\theta)=\lim_{\epsilon\to 0}\frac{1}{\pi}\int_{0<\epsilon<\left\lvert t\right\rvert<\pi}\frac{1}{2\tan{\frac{t}{2}}}f(\theta-t)d t\\" alt="\tilde{f}(\theta)=\lim_{\epsilon\to 0}\frac{1}{\pi}\int_{0<\epsilon<\left\lvert t\right\rvert<\pi}\frac{1}{2\tan{\frac{t}{2}}}f(\theta-t)d t\\" class="ee_img tr_noresize" eeimg="1">

for every 
<img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1">
 in the Lebesgue set of 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 and, consequently for a.e.
<img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1">
.

Remark. I don't know why

<img src="https://www.zhihu.com/equation?tex=\frac{1}{\pi}\int_{1-r<\left\lvert t\right\rvert<\pi}(\frac{r\sin{t}}{1+r^2-2r\cos{t}}-\frac{1}{2\tan{\frac{t}{2}}})f(\theta-t)d t\\" alt="\frac{1}{\pi}\int_{1-r<\left\lvert t\right\rvert<\pi}(\frac{r\sin{t}}{1+r^2-2r\cos{t}}-\frac{1}{2\tan{\frac{t}{2}}})f(\theta-t)d t\\" class="ee_img tr_noresize" eeimg="1">

is bounded by

<img src="https://www.zhihu.com/equation?tex=C(1-r)^2\int_{1-r<\left\lvert t\right\rvert<\pi}\frac{\left\lvert f(\theta-t)-f(\theta)\right\rvert}{\left\lvert t\right\rvert^3}d t\\" alt="C(1-r)^2\int_{1-r<\left\lvert t\right\rvert<\pi}\frac{\left\lvert f(\theta-t)-f(\theta)\right\rvert}{\left\lvert t\right\rvert^3}d t\\" class="ee_img tr_noresize" eeimg="1">

as 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
.

For upper half plane, we know 
<img src="https://www.zhihu.com/equation?tex=u(x,t)=P_t*f(x)" alt="u(x,t)=P_t*f(x)" class="ee_img tr_noresize" eeimg="1">
 is harmonic function. We
have Hilbert transform as counterpart of conjugate function:

<img src="https://www.zhihu.com/equation?tex=H f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}\frac{f(x-y)}{y}d y\\" alt="H f(x)=\lim_{\epsilon\to 0}\int_{\left\lvert y\right\rvert>\epsilon}\frac{f(x-y)}{y}d y\\" class="ee_img tr_noresize" eeimg="1">

for a.e. 
<img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">
.
