Canonical Factorization Theorem
===============================

In section 3, we show a holomorphic function 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=0<p\leq\infty" alt="0<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
can be written as 
<img src="https://www.zhihu.com/equation?tex=F=BH" alt="F=BH" class="ee_img tr_noresize" eeimg="1">
, where 
<img src="https://www.zhihu.com/equation?tex=B" alt="B" class="ee_img tr_noresize" eeimg="1">
 is the Blaschke product, 
<img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1">
 is
never zero and 
<img src="https://www.zhihu.com/equation?tex=\lVert H\rVert_{H^p}=\lVert F\rVert_{H^p}" alt="\lVert H\rVert_{H^p}=\lVert F\rVert_{H^p}" class="ee_img tr_noresize" eeimg="1">
. We will get
a finer factorization: canonical factorization. We can factorize 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 as
product of inner and outer function: 
<img src="https://www.zhihu.com/equation?tex=F(z)=I_F(z)E_F(z)\\" alt="F(z)=I_F(z)E_F(z)\\" class="ee_img tr_noresize" eeimg="1">

 where:

<img src="https://www.zhihu.com/equation?tex=I_F(z)=e^{i c}B(z)\exp{(-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\sigma(t)})}\\" alt="I_F(z)=e^{i c}B(z)\exp{(-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\sigma(t)})}\\" class="ee_img tr_noresize" eeimg="1">

and

<img src="https://www.zhihu.com/equation?tex=E_F(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t})}\\" alt="E_F(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t})}\\" class="ee_img tr_noresize" eeimg="1">


Canonical factorization
-----------------------

For 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=0<p\leq\infty" alt="0<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
, we use Riesz factorization 
<img src="https://www.zhihu.com/equation?tex=F=BH" alt="F=BH" class="ee_img tr_noresize" eeimg="1">
. We
want to keep factorizing non zero function 
<img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1">
. Write
<img src="https://www.zhihu.com/equation?tex=\log{\left\lvert H(r_je^{it})\right\rvert}=\log^+{\left\lvert H(r_je^{it})\right\rvert}-\log^-{\left\lvert H(r_je^{it})\right\rvert}" alt="\log{\left\lvert H(r_je^{it})\right\rvert}=\log^+{\left\lvert H(r_je^{it})\right\rvert}-\log^-{\left\lvert H(r_je^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
.
We know 
<img src="https://www.zhihu.com/equation?tex=\log^-{\left\lvert H(r_je^{it})\right\rvert}" alt="\log^-{\left\lvert H(r_je^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
 converges to a
positive measure 
<img src="https://www.zhihu.com/equation?tex=\mu_2" alt="\mu_2" class="ee_img tr_noresize" eeimg="1">
. And we observe
<img src="https://www.zhihu.com/equation?tex=\log^+{\left\lvert H(r_je^{it})\right\rvert}\to \log^+{\left\lvert H(e^{it})\right\rvert}" alt="\log^+{\left\lvert H(r_je^{it})\right\rvert}\to \log^+{\left\lvert H(e^{it})\right\rvert}" class="ee_img tr_noresize" eeimg="1">
in 
<img src="https://www.zhihu.com/equation?tex=H^1" alt="H^1" class="ee_img tr_noresize" eeimg="1">
 norm.

Since 
<img src="https://www.zhihu.com/equation?tex=\log{H(r_jz)}=\log{\left\lvert H(r_jz)\right\rvert}+i\theta" alt="\log{H(r_jz)}=\log{\left\lvert H(r_jz)\right\rvert}+i\theta" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=\left\lvert\log{H(r_jz)}\right\rvert\leq \left\lvert\log{\left\lvert H(r_jz)\right\rvert}\right\rvert+\left\lvert\theta\right\rvert" alt="\left\lvert\log{H(r_jz)}\right\rvert\leq \left\lvert\log{\left\lvert H(r_jz)\right\rvert}\right\rvert+\left\lvert\theta\right\rvert" class="ee_img tr_noresize" eeimg="1">
.
By theorem 3.2 in book, we show that
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\log{\left\lvert H(re^{it})\right\rvert}\right\rvert d t}" alt="\frac{1}{2\pi}\int_{-\pi}^{\pi}{\left\lvert\log{\left\lvert H(re^{it})\right\rvert}\right\rvert d t}" class="ee_img tr_noresize" eeimg="1">
is finite. Thus 
<img src="https://www.zhihu.com/equation?tex=\log{H(r_jz)}\in H^1" alt="\log{H(r_jz)}\in H^1" class="ee_img tr_noresize" eeimg="1">
.

Now we factorize the non zero function 
<img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1">
. by corollary 3.9 in book:

<img src="https://www.zhihu.com/equation?tex=\log{H(r_jz)}=i\arg{H(0)}+\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert H(r_je^{it})\right\rvert}d t}\\" alt="\log{H(r_jz)}=i\arg{H(0)}+\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert H(r_je^{it})\right\rvert}d t}\\" class="ee_img tr_noresize" eeimg="1">

Using 
<img src="https://www.zhihu.com/equation?tex=\log=\log^+-\log^-" alt="\log=\log^+-\log^-" class="ee_img tr_noresize" eeimg="1">
, and let 
<img src="https://www.zhihu.com/equation?tex=r_j\to 1" alt="r_j\to 1" class="ee_img tr_noresize" eeimg="1">
, We have:

<img src="https://www.zhihu.com/equation?tex=\log{H(z)}=i c+\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log^+{\left\lvert H(e^{it})\right\rvert}d t}-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\mu_2(t)}\\" alt="\log{H(z)}=i c+\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log^+{\left\lvert H(e^{it})\right\rvert}d t}-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\mu_2(t)}\\" class="ee_img tr_noresize" eeimg="1">

Write 
<img src="https://www.zhihu.com/equation?tex=d\mu_2(t)=g(t)d t+d\sigma(t)" alt="d\mu_2(t)=g(t)d t+d\sigma(t)" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=k(t)=\log^+{\left\lvert H(e^{it})\right\rvert}-g(t)" alt="k(t)=\log^+{\left\lvert H(e^{it})\right\rvert}-g(t)" class="ee_img tr_noresize" eeimg="1">
. We finally get
canonical theorem: 
<img src="https://www.zhihu.com/equation?tex=F(z)=I_F(z)E_F(z)\\" alt="F(z)=I_F(z)E_F(z)\\" class="ee_img tr_noresize" eeimg="1">
 where:

<img src="https://www.zhihu.com/equation?tex=I_F(z)=e^{i c}B(z)\exp{(-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\sigma(t)})}\\" alt="I_F(z)=e^{i c}B(z)\exp{(-\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}d\sigma(t)})}\\" class="ee_img tr_noresize" eeimg="1">

and

<img src="https://www.zhihu.com/equation?tex=E_F(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t})}\\" alt="E_F(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t})}\\" class="ee_img tr_noresize" eeimg="1">


Remark 7.1.1 If 
<img src="https://www.zhihu.com/equation?tex=p<\infty" alt="p<\infty" class="ee_img tr_noresize" eeimg="1">
, we have
<img src="https://www.zhihu.com/equation?tex=\left\lvert E_F(z)\right\rvert^p\leq P(\left\lvert F(e^{it})\right\rvert^p)" alt="\left\lvert E_F(z)\right\rvert^p\leq P(\left\lvert F(e^{it})\right\rvert^p)" class="ee_img tr_noresize" eeimg="1">
,
or
<img src="https://www.zhihu.com/equation?tex=\left\lvert E_F(re^{i\theta})\right\rvert^p\leq \frac{1}{2\pi}\int_{-\pi}^{\pi}P_r(\theta-t)\left\lvert F(e^{it})\right\rvert^p dt" alt="\left\lvert E_F(re^{i\theta})\right\rvert^p\leq \frac{1}{2\pi}\int_{-\pi}^{\pi}P_r(\theta-t)\left\lvert F(e^{it})\right\rvert^p dt" class="ee_img tr_noresize" eeimg="1">
.
Integrate both side by 
<img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1">
 we have 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert E_F(re^{i\theta})\right\rvert^p d\theta & \leq \frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{1}{2\pi}\int_{-\pi}^{\pi}P_r(\theta-t)\left\lvert F(e^{it})\right\rvert^p dt d\theta \\
                                                                         & \leq\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert F(e^{it})\right\rvert^p dt
    \end{aligned}\\" alt="\begin{aligned}
        \frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert E_F(re^{i\theta})\right\rvert^p d\theta & \leq \frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{1}{2\pi}\int_{-\pi}^{\pi}P_r(\theta-t)\left\lvert F(e^{it})\right\rvert^p dt d\theta \\
                                                                         & \leq\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert F(e^{it})\right\rvert^p dt
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 Thus 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 implies 
<img src="https://www.zhihu.com/equation?tex=E_F\in H^p" alt="E_F\in H^p" class="ee_img tr_noresize" eeimg="1">
. The 
<img src="https://www.zhihu.com/equation?tex=p=\infty" alt="p=\infty" class="ee_img tr_noresize" eeimg="1">

case is trivial.

<img src="https://www.zhihu.com/equation?tex=\left\lvert E_F(e^{it})\right\rvert=\left\lvert F(E^{it})\right\rvert" alt="\left\lvert E_F(e^{it})\right\rvert=\left\lvert F(E^{it})\right\rvert" class="ee_img tr_noresize" eeimg="1">
a.e.t since 
<img src="https://www.zhihu.com/equation?tex=I_F(e^it)" alt="I_F(e^it)" class="ee_img tr_noresize" eeimg="1">
 has finite non zero point.

We say 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 is an inner function if and only if 
<img src="https://www.zhihu.com/equation?tex=E_F=1" alt="E_F=1" class="ee_img tr_noresize" eeimg="1">
, and say
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 is an outer function if and only if 
<img src="https://www.zhihu.com/equation?tex=I_F" alt="I_F" class="ee_img tr_noresize" eeimg="1">
 is constant.

Outer function
--------------

We list some conclusions about outer functions. Most of them are
criterions of outer function.

Corollary 7.2.1 If 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=0<p\leq\infty" alt="0<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
, and is not identically zero, then:

<img src="https://www.zhihu.com/equation?tex=\log\left\lvert F(0)\right\rvert\leq \frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t}\\" alt="\log\left\lvert F(0)\right\rvert\leq \frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}\log{\left\lvert F(e^{it})\right\rvert}d t}\\" class="ee_img tr_noresize" eeimg="1">

and equality holds if and only if 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is an outer functions.

The following theorem is an easy consequence of the above corollary.

Theorem 1.7.2.2 (criterion of outer function. theorem 7.5 in book). Suppose that 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F^{-1}\in H^p" alt="F^{-1}\in H^p" class="ee_img tr_noresize" eeimg="1">
 for some 
<img src="https://www.zhihu.com/equation?tex=0<p\leq\infty" alt="0<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
.
Then 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is an outer function.

The next theorem states that the limit of sequence of decreasing outer
functions is outer function.

Theorem 7.2.3. Let 
<img src="https://www.zhihu.com/equation?tex=F_j\in H^p" alt="F_j\in H^p" class="ee_img tr_noresize" eeimg="1">
 be outer functions for 
<img src="https://www.zhihu.com/equation?tex=j=1,2,\cdots" alt="j=1,2,\cdots" class="ee_img tr_noresize" eeimg="1">
. Suppose that
<img src="https://www.zhihu.com/equation?tex=\left\lvert F_1(z)\right\rvert\geq\left\lvert F_2(z)\right\rvert\geq\cdots" alt="\left\lvert F_1(z)\right\rvert\geq\left\lvert F_2(z)\right\rvert\geq\cdots" class="ee_img tr_noresize" eeimg="1">
for every 
<img src="https://www.zhihu.com/equation?tex=z\in D" alt="z\in D" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F_j(z)\to F(z)" alt="F_j(z)\to F(z)" class="ee_img tr_noresize" eeimg="1">
 uniformly over compact subsets
of 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
, as 
<img src="https://www.zhihu.com/equation?tex=j\to\infty" alt="j\to\infty" class="ee_img tr_noresize" eeimg="1">
. Then, if 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is not identically zero, 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is an
outer function.

Remark 1.7.2.1 (notes on proof of theorem 7.6 in book).
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2\pi}\int_{-\pi}^{\pi}{\log^-{\left\lvert F_j(e^{it})\right\rvert}d t}\to \frac{1}{2\pi}\int_{-\pi}^{\pi}{\log^-{\left\lvert F(e^{it})\right\rvert}d t}\\" alt="\frac{1}{2\pi}\int_{-\pi}^{\pi}{\log^-{\left\lvert F_j(e^{it})\right\rvert}d t}\to \frac{1}{2\pi}\int_{-\pi}^{\pi}{\log^-{\left\lvert F(e^{it})\right\rvert}d t}\\" class="ee_img tr_noresize" eeimg="1">

by monotone convergence. But monotone convergence does not ensure limit
is finite. I wonder if it can be infinite.

The following theorem is an easy consequence of the above theorem.

Theorem 7.2.4 (theorem 7.7 in book).
Let 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=0<p\leq\infty" alt="0<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
, not identically zero, and such that

<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{F(z)}\geq 0" alt="\operatorname{Re}{F(z)}\geq 0" class="ee_img tr_noresize" eeimg="1">
 for every 
<img src="https://www.zhihu.com/equation?tex=z\in D" alt="z\in D" class="ee_img tr_noresize" eeimg="1">
. Then 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is an outer
function.

Remark 7.2.2 (notes on proof of theorem 7.8 in book).
Proof of
<img src="https://www.zhihu.com/equation?tex=\left\lvert K(z)\right\rvert^p=\exp{P(\log(\left\lvert K(e^{it})\right\rvert^p))}\leq P(\left\lvert K(e^{it})\right\rvert^p)" alt="\left\lvert K(z)\right\rvert^p=\exp{P(\log(\left\lvert K(e^{it})\right\rvert^p))}\leq P(\left\lvert K(e^{it})\right\rvert^p)" class="ee_img tr_noresize" eeimg="1">
implies 
<img src="https://www.zhihu.com/equation?tex=K\in H^p" alt="K\in H^p" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=p=\infty" alt="p=\infty" class="ee_img tr_noresize" eeimg="1">
 case is similar with remark
7.1.1.

Inner function
--------------

We can prove the following corollary, although sometimes it is
considered as definition of inner functions.

Corollary 7.3.1 (corollary 7.2 in book).The inner functions are precisely those functions 
<img src="https://www.zhihu.com/equation?tex=F\in H^\infty" alt="F\in H^\infty" class="ee_img tr_noresize" eeimg="1">
 for
which 
<img src="https://www.zhihu.com/equation?tex=\left\lvert F(e^{it})\right\rvert=1" alt="\left\lvert F(e^{it})\right\rvert=1" class="ee_img tr_noresize" eeimg="1">
 almost everywhere.

Remark 7.3.1 (notes on proof of corollary 7.2 in book).Since
<img src="https://www.zhihu.com/equation?tex=\left\lvert E_F(z)\right\rvert=\exp{P(\log\left\lvert F(e^{it})\right\rvert)}" alt="\left\lvert E_F(z)\right\rvert=\exp{P(\log\left\lvert F(e^{it})\right\rvert)}" class="ee_img tr_noresize" eeimg="1">
.
One direction is

<img src="https://www.zhihu.com/equation?tex=E_F=1\implies\left\lvert E_F\right\rvert=1\implies\log{\left\lvert F(e^{it})\right\rvert}=0\implies\left\lvert F(e^{it})\right\rvert=1\\" alt="E_F=1\implies\left\lvert E_F\right\rvert=1\implies\log{\left\lvert F(e^{it})\right\rvert}=0\implies\left\lvert F(e^{it})\right\rvert=1\\" class="ee_img tr_noresize" eeimg="1">

Another direction is

<img src="https://www.zhihu.com/equation?tex=\left\lvert F(e^{it})\right\rvert=1  \implies\log{\left\lvert F(e^{it})\right\rvert}=0\implies E_F=1\\" alt="\left\lvert F(e^{it})\right\rvert=1  \implies\log{\left\lvert F(e^{it})\right\rvert}=0\implies E_F=1\\" class="ee_img tr_noresize" eeimg="1">


Consider space 
<img src="https://www.zhihu.com/equation?tex=F\cdot\mathscr{P}" alt="F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
, where 
<img src="https://www.zhihu.com/equation?tex=\mathscr{P}" alt="\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is the space of
polynomials. Theorem 7.9 shows if 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is an outer function, then

<img src="https://www.zhihu.com/equation?tex=F\cdot\mathscr{P}" alt="F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is dense in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
. Corollary 7.11 shows if 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is
just in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
, then closure of 
<img src="https://www.zhihu.com/equation?tex=F\cdot\mathscr{P}" alt="F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is 
<img src="https://www.zhihu.com/equation?tex=I_F\cdot H^p" alt="I_F\cdot H^p" class="ee_img tr_noresize" eeimg="1">
.
These conclusions show how the inner factor plays in some approximation
problems.

Remark 7.3.2 (notes on theorem 7.9 in book). Even if 
<img src="https://www.zhihu.com/equation?tex=\mathscr{P}" alt="\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is dense in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=F\cdot\mathscr{P}" alt="F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 may not be
dense in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
. For example if 
<img src="https://www.zhihu.com/equation?tex=F(0)=0" alt="F(0)=0" class="ee_img tr_noresize" eeimg="1">
 in a positive measure set.

By Hahn-Banach theorem, if 
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
 is locally convex and 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is subspace of
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
, then 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is dense in 
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
 if and only if for any 
<img src="https://www.zhihu.com/equation?tex=f\in E^*" alt="f\in E^*" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=f\vert_F=0 \implies f=0" alt="f\vert_F=0 \implies f=0" class="ee_img tr_noresize" eeimg="1">
. Thus for 
<img src="https://www.zhihu.com/equation?tex=p\geq 1" alt="p\geq 1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=E_F\cdot\mathscr{P}" alt="E_F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is
dense in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is equivalent to for any 
<img src="https://www.zhihu.com/equation?tex=k(e^{it})\in L^{p'}" alt="k(e^{it})\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}E_F(e^{it})e^{ijt}k(e^{it})dt=0\implies\int_{-\pi}^{\pi}G(e^{it})k(e^{it})dt=0" alt="\int_{-\pi}^{\pi}E_F(e^{it})e^{ijt}k(e^{it})dt=0\implies\int_{-\pi}^{\pi}G(e^{it})k(e^{it})dt=0" class="ee_img tr_noresize" eeimg="1">
for each 
<img src="https://www.zhihu.com/equation?tex=G\in H^p" alt="G\in H^p" class="ee_img tr_noresize" eeimg="1">
. But
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}E_F(e^{it})e^{ijt}k(e^{it})dt=0" alt="\int_{-\pi}^{\pi}E_F(e^{it})e^{ijt}k(e^{it})dt=0" class="ee_img tr_noresize" eeimg="1">
 also implies the non
positive frequencies of 
<img src="https://www.zhihu.com/equation?tex=E_F(e^{it})k(e^{it})" alt="E_F(e^{it})k(e^{it})" class="ee_img tr_noresize" eeimg="1">
 is 0. This means
<img src="https://www.zhihu.com/equation?tex=E_F(e^{it})k(e^{it})=\sum_{j=1}^\infty{a_ne^{ijt}}" alt="E_F(e^{it})k(e^{it})=\sum_{j=1}^\infty{a_ne^{ijt}}" class="ee_img tr_noresize" eeimg="1">
. Thus
<img src="https://www.zhihu.com/equation?tex=E_F(e^{it})k(e^{it})=e^{it}H(e^{it})" alt="E_F(e^{it})k(e^{it})=e^{it}H(e^{it})" class="ee_img tr_noresize" eeimg="1">
. By Holder inequality, we see

<img src="https://www.zhihu.com/equation?tex=H\in H^1" alt="H\in H^1" class="ee_img tr_noresize" eeimg="1">
.

I wonder in which sense 
<img src="https://www.zhihu.com/equation?tex=E_F\cdot\mathscr{P}" alt="E_F\cdot\mathscr{P}" class="ee_img tr_noresize" eeimg="1">
 is not dense in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 and
how the proof excludes this case.

By Holder inequality,
<img src="https://www.zhihu.com/equation?tex=\int\left\lvert R-E_K\cdot Q\right\rvert^p\leq(\int\left\lvert R-E_K\cdot Q\right\rvert^{2p})^\frac{1}{2}(\int 1)^\frac{1}{2}" alt="\int\left\lvert R-E_K\cdot Q\right\rvert^p\leq(\int\left\lvert R-E_K\cdot Q\right\rvert^{2p})^\frac{1}{2}(\int 1)^\frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
.
Thus 
<img src="https://www.zhihu.com/equation?tex=\lVert R-E_K\cdot Q\rVert_{H^{2p}}<\epsilon" alt="\lVert R-E_K\cdot Q\rVert_{H^{2p}}<\epsilon" class="ee_img tr_noresize" eeimg="1">
 implies
<img src="https://www.zhihu.com/equation?tex=\lVert R-E_K\cdot Q\rVert_{H^{p}}<\epsilon" alt="\lVert R-E_K\cdot Q\rVert_{H^{p}}<\epsilon" class="ee_img tr_noresize" eeimg="1">

