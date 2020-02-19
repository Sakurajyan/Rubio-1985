F.Riesz Factorization Theorem
=============================

This section can be seen as a generalization of first section. In first
section, we talk about norm convergence and pointwise convergence when
boundary function 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 is in 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=1< p\leq \infty" alt="1< p\leq \infty" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 is a
measure. This conclusion is for harmonic function. Harmonic function has
series representation:

<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=\sum_{k=-\infty}^\infty{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}\\" alt="u(re^{i\theta})=\sum_{k=-\infty}^\infty{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}\\" class="ee_img tr_noresize" eeimg="1">

and we can derive Poisson representation 
<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=P_r(f)" alt="u(re^{i\theta})=P_r(f)" class="ee_img tr_noresize" eeimg="1">
. Since
holomorphic function also has series representation:

<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=\sum_{k=0}^\infty{a_kr^{k}e^{i k\theta}}\\" alt="u(re^{i\theta})=\sum_{k=0}^\infty{a_kr^{k}e^{i k\theta}}\\" class="ee_img tr_noresize" eeimg="1">
 
 , we can
consider this representation as special case of harmonic function with
<img src="https://www.zhihu.com/equation?tex=a_k=0" alt="a_k=0" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=k<0" alt="k<0" class="ee_img tr_noresize" eeimg="1">
. Poisson representation is also hold for holomorphic
function, thus the converge result is hold also for holomorphic
function. The following theorem is a summary of these results.

Theorem 3.1 Let 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 with
<img src="https://www.zhihu.com/equation?tex=1<p\leq \infty" alt="1<p\leq \infty" class="ee_img tr_noresize" eeimg="1">
. Then:

1.  For almost every 
<img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1">
. the limit
    
<img src="https://www.zhihu.com/equation?tex=F(e^{it})=\lim{F(z)} ~as ~z\to e^{it} ~N.T.\\" alt="F(e^{it})=\lim{F(z)} ~as ~z\to e^{it} ~N.T.\\" class="ee_img tr_noresize" eeimg="1">
 
 exists. The function 
<img src="https://www.zhihu.com/equation?tex=f(t)=F(e^{it})" alt="f(t)=F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 belongs to 
<img src="https://www.zhihu.com/equation?tex=L^p([-\pi,\pi])" alt="L^p([-\pi,\pi])" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F=P(f)" alt="F=P(f)" class="ee_img tr_noresize" eeimg="1">


2.  If 
<img src="https://www.zhihu.com/equation?tex=p<\infty" alt="p<\infty" class="ee_img tr_noresize" eeimg="1">
:
    
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^\pi{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t} \to 0~as~r\to 1\\" alt="\int_{-\pi}^\pi{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t} \to 0~as~r\to 1\\" class="ee_img tr_noresize" eeimg="1">

If 
<img src="https://www.zhihu.com/equation?tex=p=\infty" alt="p=\infty" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=F(re^{it})\to F(e^{it})" alt="F(re^{it})\to F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 in the w*-topology of
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">
 as 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
.

For each 
<img src="https://www.zhihu.com/equation?tex=1<p\leq\infty" alt="1<p\leq\infty" class="ee_img tr_noresize" eeimg="1">
:
<img src="https://www.zhihu.com/equation?tex=\left\lVert F\right\rVert_{H^p}=\left\lVert f\right\rVert_p" alt="\left\lVert F\right\rVert_{H^p}=\left\lVert f\right\rVert_p" class="ee_img tr_noresize" eeimg="1">
.

3. <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is the Cauchy integral of its boundary function, that is:
    
<img src="https://www.zhihu.com/equation?tex=F(z)=\frac{1}{2\pi i}\int_{\left\lvert\xi\right\rvert=1}{\frac{F(\xi)}{\xi-z}d\xi}=\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{F(e^{it})}{e^{it}-z}e^{it}d t}\\" alt="F(z)=\frac{1}{2\pi i}\int_{\left\lvert\xi\right\rvert=1}{\frac{F(\xi)}{\xi-z}d\xi}=\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{F(e^{it})}{e^{it}-z}e^{it}d t}\\" class="ee_img tr_noresize" eeimg="1">

Remark. For first statement in theorem 3.1, N.T. limit holds for 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
, but 
<img src="https://www.zhihu.com/equation?tex=P(f)" alt="P(f)" class="ee_img tr_noresize" eeimg="1">
 may not
be hold.

Remark. 
<img src="https://www.zhihu.com/equation?tex=u(re^{it})=P_r(t)" alt="u(re^{it})=P_r(t)" class="ee_img tr_noresize" eeimg="1">
 is neither in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 nor 
<img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=P_r(t)" alt="P_r(t)" class="ee_img tr_noresize" eeimg="1">
 is harmonic
but not holomorphic.

In this section we will extend this result to 
<img src="https://www.zhihu.com/equation?tex=p\leq 1" alt="p\leq 1" class="ee_img tr_noresize" eeimg="1">
. The main idea
is to factorize 
<img src="https://www.zhihu.com/equation?tex=F(z)" alt="F(z)" class="ee_img tr_noresize" eeimg="1">
 to a Blaschke product 
<img src="https://www.zhihu.com/equation?tex=B(z)" alt="B(z)" class="ee_img tr_noresize" eeimg="1">
 and a non-vanish
function 
<img src="https://www.zhihu.com/equation?tex=H(z)" alt="H(z)" class="ee_img tr_noresize" eeimg="1">
.

3.1 Result of non-vanish case
-------------------------

Suppose that 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}\leq p<1" alt="\frac{1}{2}\leq p<1" class="ee_img tr_noresize" eeimg="1">
. If 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 does not vanish
in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
. Then 
<img src="https://www.zhihu.com/equation?tex=F(z)=e^{f(z)}" alt="F(z)=e^{f(z)}" class="ee_img tr_noresize" eeimg="1">
 for some holomorphic function 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
. Let
<img src="https://www.zhihu.com/equation?tex=G(z)=e^{\frac{f(z)}{2}}" alt="G(z)=e^{\frac{f(z)}{2}}" class="ee_img tr_noresize" eeimg="1">
, we have 
<img src="https://www.zhihu.com/equation?tex=F(z)=G(z)^2" alt="F(z)=G(z)^2" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=G(z)\in H^{2p}" alt="G(z)\in H^{2p}" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=\left\lVert G\right\rVert^2_{H^{2p}}=\left\lVert F\right\rVert_{H^p}" alt="\left\lVert G\right\rVert^2_{H^{2p}}=\left\lVert F\right\rVert_{H^p}" class="ee_img tr_noresize" eeimg="1">
.
Since 
<img src="https://www.zhihu.com/equation?tex=2p\geq 1" alt="2p\geq 1" class="ee_img tr_noresize" eeimg="1">
, we have 
<img src="https://www.zhihu.com/equation?tex=G(e^{it})=\lim{G(z)}" alt="G(e^{it})=\lim{G(z)}" class="ee_img tr_noresize" eeimg="1">
 a.e. as 
<img src="https://www.zhihu.com/equation?tex=z\to e^{it}" alt="z\to e^{it}" class="ee_img tr_noresize" eeimg="1">
N.T.. It follows that 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})=\lim{F(z)}" alt="F(e^{it})=\lim{F(z)}" class="ee_img tr_noresize" eeimg="1">
 a.e. as 
<img src="https://www.zhihu.com/equation?tex=z\to e^{it}" alt="z\to e^{it}" class="ee_img tr_noresize" eeimg="1">
 N.T.

We know that
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t}\to 0" alt="\int_{-\pi}^{\pi}{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t}\to 0" class="ee_img tr_noresize" eeimg="1">
as 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
 if 
<img src="https://www.zhihu.com/equation?tex=p>1" alt="p>1" class="ee_img tr_noresize" eeimg="1">
. Suppose that 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}\leq p<1" alt="\frac{1}{2}\leq p<1" class="ee_img tr_noresize" eeimg="1">
 and
we have 
<img src="https://www.zhihu.com/equation?tex=F(z)=G(z)^2" alt="F(z)=G(z)^2" class="ee_img tr_noresize" eeimg="1">
 as before, then: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    &\int_{-\pi}^{\pi}{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t}\\
    =&\int_{-\pi}^{\pi}{\left\lvert G(re^{it})^2-G(e^{it})^2\right\rvert^p d t}\\
    =&\int_{-\pi}^{\pi}{\left\lvert G(re^{it})+G(e^{it})\right\rvert^p\left\lvert G(re^{it})-G(e^{it})\right\rvert^p d t}\\
    \leq&(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})+G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\\
    \leq&(\int_{-\pi}^{\pi}{(2\left\lvert G(e^{it})\right\rvert)^{2p}d t})^{\frac{1}{2}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\\
     \leq&2^p\left\lVert G\right\rVert^p_{H^{2p}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\to 0 ~as ~r\to 1\end{aligned}\\" alt="\begin{aligned}
    &\int_{-\pi}^{\pi}{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t}\\
    =&\int_{-\pi}^{\pi}{\left\lvert G(re^{it})^2-G(e^{it})^2\right\rvert^p d t}\\
    =&\int_{-\pi}^{\pi}{\left\lvert G(re^{it})+G(e^{it})\right\rvert^p\left\lvert G(re^{it})-G(e^{it})\right\rvert^p d t}\\
    \leq&(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})+G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\\
    \leq&(\int_{-\pi}^{\pi}{(2\left\lvert G(e^{it})\right\rvert)^{2p}d t})^{\frac{1}{2}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\\
     \leq&2^p\left\lVert G\right\rVert^p_{H^{2p}}(\int_{-\pi}^{\pi}{\left\lvert G(re^{it})-G(e^{it})\right\rvert^{2p}d t})^{\frac{1}{2}}\to 0 ~as ~r\to 1\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

We conclude that 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}\leq p<1" alt="\frac{1}{2}\leq p<1" class="ee_img tr_noresize" eeimg="1">
. If 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 does not
vanish in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
. Then there is a boundary function 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})" alt="F(e^{it})" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=F(z)" alt="F(z)" class="ee_img tr_noresize" eeimg="1">
converges to 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})" alt="F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 both in pointwise sense and norm sense.

Remark. There is a basic inequality, used also in proving Minkowski inequality:
<img src="https://www.zhihu.com/equation?tex=\left\lvert a+b\right\rvert^p\leq 2^p(\left\lvert a\right\rvert^p+\left\lvert b\right\rvert^p)" alt="\left\lvert a+b\right\rvert^p\leq 2^p(\left\lvert a\right\rvert^p+\left\lvert b\right\rvert^p)" class="ee_img tr_noresize" eeimg="1">

for 
<img src="https://www.zhihu.com/equation?tex=p>0" alt="p>0" class="ee_img tr_noresize" eeimg="1">
. To prove this we only need to consider two case:
<img src="https://www.zhihu.com/equation?tex=\left\lvert a\right\rvert\geq\left\lvert b\right\rvert" alt="\left\lvert a\right\rvert\geq\left\lvert b\right\rvert" class="ee_img tr_noresize" eeimg="1">
 or
<img src="https://www.zhihu.com/equation?tex=\left\lvert a\right\rvert\leq\left\lvert b\right\rvert" alt="\left\lvert a\right\rvert\leq\left\lvert b\right\rvert" class="ee_img tr_noresize" eeimg="1">
.

By induction, this conclusion can be extended to 
<img src="https://www.zhihu.com/equation?tex=0<p<1" alt="0<p<1" class="ee_img tr_noresize" eeimg="1">
. Thus two types
of convergence holds for all 
<img src="https://www.zhihu.com/equation?tex=0<p<\infty" alt="0<p<\infty" class="ee_img tr_noresize" eeimg="1">
.

Remark. Author uses Fatou's lemma when 
<img src="https://www.zhihu.com/equation?tex=F(z)" alt="F(z)" class="ee_img tr_noresize" eeimg="1">
 converges to 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})" alt="F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 N.T.. I
think we can use this lemma even if it converges radially.

3.2 Result of 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 case
--------------------

In the end of last section review, we state three theorems:

-   For 
<img src="https://www.zhihu.com/equation?tex=F\in N" alt="F\in N" class="ee_img tr_noresize" eeimg="1">
, the zeroes 
<img src="https://www.zhihu.com/equation?tex=(z_j)" alt="(z_j)" class="ee_img tr_noresize" eeimg="1">
 of 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 satisfies
<img src="https://www.zhihu.com/equation?tex=\sum_j{(1-\left\lvert z_j\right\rvert)<\infty}" alt="\sum_j{(1-\left\lvert z_j\right\rvert)<\infty}" class="ee_img tr_noresize" eeimg="1">
.

-   If 
<img src="https://www.zhihu.com/equation?tex=\sum_j{(1-\left\lvert z_j\right\rvert)<\infty}" alt="\sum_j{(1-\left\lvert z_j\right\rvert)<\infty}" class="ee_img tr_noresize" eeimg="1">
 holds, the
    Blaschke product converges uniformly on each compact subset to a
    function 
<img src="https://www.zhihu.com/equation?tex=B(z)\in H^\infty" alt="B(z)\in H^\infty" class="ee_img tr_noresize" eeimg="1">
 and they have zeroes 
<img src="https://www.zhihu.com/equation?tex=(z_j)" alt="(z_j)" class="ee_img tr_noresize" eeimg="1">
.

-  <img src="https://www.zhihu.com/equation?tex=\left\lvert B(e^{it})\right\rvert=1" alt="\left\lvert B(e^{it})\right\rvert=1" class="ee_img tr_noresize" eeimg="1"> a.e.

If we let 
<img src="https://www.zhihu.com/equation?tex=H=\frac{F}{B}" alt="H=\frac{F}{B}" class="ee_img tr_noresize" eeimg="1">
, where Blaschke product is formed by zeroes of
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
, then 
<img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1">
 does not have any zeroes. Besides, if 
<img src="https://www.zhihu.com/equation?tex=F\in N" alt="F\in N" class="ee_img tr_noresize" eeimg="1">
, then
<img src="https://www.zhihu.com/equation?tex=H\in N" alt="H\in N" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=\left\lVert H\right\rVert_N=\left\lVert F\right\rVert_N" alt="\left\lVert H\right\rVert_N=\left\lVert F\right\rVert_N" class="ee_img tr_noresize" eeimg="1">
.
If 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, then 
<img src="https://www.zhihu.com/equation?tex=H\in H^p" alt="H\in H^p" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=\left\lVert H\right\rVert_{H^p}=\left\lVert F\right\rVert_{H^p}" alt="\left\lVert H\right\rVert_{H^p}=\left\lVert F\right\rVert_{H^p}" class="ee_img tr_noresize" eeimg="1">
(theorem 3.3 in book). Notice now we can use method in section
3.1 on 
<img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1">
. We have following result:

Theorem 3.2.1. Let 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=0<p\leq \infty" alt="0<p\leq \infty" class="ee_img tr_noresize" eeimg="1">
. Then:

1.  For almost every 
<img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1">
. the limit
    
<img src="https://www.zhihu.com/equation?tex=F(e^{it})=\lim{F(z)}~as~z\to e^{it}~N.T.\\" alt="F(e^{it})=\lim{F(z)}~as~z\to e^{it}~N.T.\\" class="ee_img tr_noresize" eeimg="1">

 exists. The function 
<img src="https://www.zhihu.com/equation?tex=f(t)=F(e^{it})" alt="f(t)=F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 belongs to 
<img src="https://www.zhihu.com/equation?tex=L^p([-\pi,\pi])" alt="L^p([-\pi,\pi])" class="ee_img tr_noresize" eeimg="1">
.

2.  <img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^\pi{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t} \to 0" alt="\int_{-\pi}^\pi{\left\lvert F(re^{it})-F(e^{it})\right\rvert^p d t} \to 0" class="ee_img tr_noresize" eeimg="1"> as 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">


3.  <img src="https://www.zhihu.com/equation?tex=\left\lVert F\right\rVert_{H^p}=\lim_{r\to 1}{(\frac{1}{2\pi}\int_{-\pi}^\pi{\left\lvert F(re^{it})\right\rvert^p d t})^\frac{1}{p}}=(\frac{1}{2\pi}\int_{-\pi}^\pi{\left\lvert F(e^{it})\right\rvert^p d t})^\frac{1}{p}" alt="\left\lVert F\right\rVert_{H^p}=\lim_{r\to 1}{(\frac{1}{2\pi}\int_{-\pi}^\pi{\left\lvert F(re^{it})\right\rvert^p d t})^\frac{1}{p}}=(\frac{1}{2\pi}\int_{-\pi}^\pi{\left\lvert F(e^{it})\right\rvert^p d t})^\frac{1}{p}" class="ee_img tr_noresize" eeimg="1">


Another statement is that 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 can be improved to 
<img src="https://www.zhihu.com/equation?tex=F\in H^q" alt="F\in H^q" class="ee_img tr_noresize" eeimg="1">
 if
the boundary function 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})\in L^q" alt="F(e^{it})\in L^q" class="ee_img tr_noresize" eeimg="1">
 (Corollary 3.7). The hard part
of its proof is the case 
<img src="https://www.zhihu.com/equation?tex=p<q" alt="p<q" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=p\leq 1" alt="p\leq 1" class="ee_img tr_noresize" eeimg="1">
. We factorize 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 as
<img src="https://www.zhihu.com/equation?tex=F=BG^n" alt="F=BG^n" class="ee_img tr_noresize" eeimg="1">
, where 
<img src="https://www.zhihu.com/equation?tex=np>1" alt="np>1" class="ee_img tr_noresize" eeimg="1">
. Since 
<img src="https://www.zhihu.com/equation?tex=F(e^{it}) \in L^{q}" alt="F(e^{it}) \in L^{q}" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=\left\lvert G(e^{it})\right\rvert^n=\left\lvert F(e^{it})\right\rvert" alt="\left\lvert G(e^{it})\right\rvert^n=\left\lvert F(e^{it})\right\rvert" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=G(e^{it})\in L^{nq}" alt="G(e^{it})\in L^{nq}" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=G\in H^{nq}" alt="G\in H^{nq}" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F\in H^q" alt="F\in H^q" class="ee_img tr_noresize" eeimg="1">
.


<img src="https://www.zhihu.com/equation?tex=H^1" alt="H^1" class="ee_img tr_noresize" eeimg="1">
 function and its boundary
-------------------------------

Recall in section 1, when 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is a harmonic function in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty\\" alt="\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty\\" class="ee_img tr_noresize" eeimg="1">

,
we can only say 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">
 for some Borel measure and the result
can not be improved (consider Poisson kernel). However, if 
<img src="https://www.zhihu.com/equation?tex=F\in H^1" alt="F\in H^1" class="ee_img tr_noresize" eeimg="1">
,
in other words
<img src="https://www.zhihu.com/equation?tex=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty" alt="\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty" class="ee_img tr_noresize" eeimg="1">
and F is holomorphic, then by 
<img src="https://www.zhihu.com/equation?tex=F(re^{it})\to F(e^{it})" alt="F(re^{it})\to F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 in 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
. Thus

<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 can be written as the Poisson integral and the Cauchy integral of
its boundary function 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})" alt="F(e^{it})" class="ee_img tr_noresize" eeimg="1">
.

Remark (Proof of corollary 3.9 in book). I don't know why

<img src="https://www.zhihu.com/equation?tex=G(z)=\frac{1}{2\pi}\int_{-\pi}^\pi{\frac{e^{it}+z}{e^{it}-z}\operatorname{Re}{F(e^{it})}d t}\\" alt="G(z)=\frac{1}{2\pi}\int_{-\pi}^\pi{\frac{e^{it}+z}{e^{it}-z}\operatorname{Re}{F(e^{it})}d t}\\" class="ee_img tr_noresize" eeimg="1">

is holomorphic function.

An consequence of Poisson representation for 
<img src="https://www.zhihu.com/equation?tex=H^1" alt="H^1" class="ee_img tr_noresize" eeimg="1">
 functions is a famous
theorem due to F. and M. Riesz. It says given a Borel measure 
<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">
,
when negative frequencies of Fourier coefficients of 
<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">
 is zero, then

<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">
 is absolutely continuous w.r.t. Lebesgue measure, i.e.:

<img src="https://www.zhihu.com/equation?tex=d\mu(t)=f(t)d t" alt="d\mu(t)=f(t)d t" class="ee_img tr_noresize" eeimg="1">
 for some 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
. This theorem shows the difference
between bounded holomorphic function

<img src="https://www.zhihu.com/equation?tex=\sum_{k=0}^\infty{a_kr^{k}e^{i k\theta}}" alt="\sum_{k=0}^\infty{a_kr^{k}e^{i k\theta}}" class="ee_img tr_noresize" eeimg="1">
 and bounded harmonic function

<img src="https://www.zhihu.com/equation?tex=\sum_{k=-\infty}^\infty{a_kr^{k}e^{i k\theta}}" alt="\sum_{k=-\infty}^\infty{a_kr^{k}e^{i k\theta}}" class="ee_img tr_noresize" eeimg="1">
 (bounded as

<img src="https://www.zhihu.com/equation?tex=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty" alt="\sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert F(re^{i t})\right\rvert d t}<\infty" class="ee_img tr_noresize" eeimg="1">
).
The vanish of negative frequencies make bounded harmonic function (or
Poisson integral of complex Borel measure) to bounded holomorphic
function.


Remark (Proof of corollary 3.11 in book). <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 is bounded variation, then 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 can be written as difference of two
increasing bounded function. This is equivalent to 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 can be written as
difference of two Borel measure. Thus 
<img src="https://www.zhihu.com/equation?tex=f(t)=c+\int_{-\pi}^t{d\mu(s)}" alt="f(t)=c+\int_{-\pi}^t{d\mu(s)}" class="ee_img tr_noresize" eeimg="1">
where 
<img src="https://www.zhihu.com/equation?tex=c=f(-\pi)" alt="c=f(-\pi)" class="ee_img tr_noresize" eeimg="1">
.

The integration by parts: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    \int_{-\pi}^\pi{e^{ijt}d\mu(t)}=&\left.e^{i j t}\int_{-\pi}^t{d\mu(s)}\right\rvert_{-\pi}^{\pi}-i j\int_{-\pi}^\pi{g(t)e^{ijt}dt}\\
                                    =&\left(e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}-e^{-i j\pi}\int_{-\pi}^{-\pi}{d\mu(s)}\right)-i j\int_{-\pi}^\pi{g(t)e^{ijt}dt}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}-i j\int_{-\pi}^\pi{(F(e^{it})-c)e^{ijt}dt}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}-\lim_{r\to 1}{i j\int_{-\pi}^\pi{F(re^{it})e^{ijt}dt}}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}\end{aligned}\\" alt="\begin{aligned}
    \int_{-\pi}^\pi{e^{ijt}d\mu(t)}=&\left.e^{i j t}\int_{-\pi}^t{d\mu(s)}\right\rvert_{-\pi}^{\pi}-i j\int_{-\pi}^\pi{g(t)e^{ijt}dt}\\
                                    =&\left(e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}-e^{-i j\pi}\int_{-\pi}^{-\pi}{d\mu(s)}\right)-i j\int_{-\pi}^\pi{g(t)e^{ijt}dt}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}-i j\int_{-\pi}^\pi{(F(e^{it})-c)e^{ijt}dt}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}-\lim_{r\to 1}{i j\int_{-\pi}^\pi{F(re^{it})e^{ijt}dt}}\\
                                    =&{\color{blue}e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}}\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

The limit in fourth equality is by 
<img src="https://www.zhihu.com/equation?tex=F\in H^1" alt="F\in H^1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=F(re^{it})\to F(e^{it})" alt="F(re^{it})\to F(e^{it})" class="ee_img tr_noresize" eeimg="1">
in <img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
. This limit is 0 since 
<img src="https://www.zhihu.com/equation?tex=F\in H^1" alt="F\in H^1" class="ee_img tr_noresize" eeimg="1">
, the negative frequencies are
1. 
<img src="https://www.zhihu.com/equation?tex=e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}=e^{i j\pi}g(\pi)" alt="e^{i j\pi}\int_{-\pi}^\pi{d\mu(s)}=e^{i j\pi}g(\pi)" class="ee_img tr_noresize" eeimg="1">
 is 0 since

<img src="https://www.zhihu.com/equation?tex=f(\pi)=f(-\pi)+g(\pi)" alt="f(\pi)=f(-\pi)+g(\pi)" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=f(\pi)=f(-\pi)" alt="f(\pi)=f(-\pi)" class="ee_img tr_noresize" eeimg="1">
.

Corollary 3.11 in book shows a condition when bounded variation implies
absolutely continuity. This Corollary emphases again 'holomorphic
condition' or vanish of negative frequencies makes a Borel measure
absolutely continuous. Theorem 3.12 in book says that 
<img src="https://www.zhihu.com/equation?tex=F'\in H^1" alt="F'\in H^1" class="ee_img tr_noresize" eeimg="1">
 is the
necessary and sufficient condition of holomorphic 
<img src="https://www.zhihu.com/equation?tex=F\in H(D)" alt="F\in H(D)" class="ee_img tr_noresize" eeimg="1">
 is
absolutely continuous on boundary.


Remark (Proof of theorem 3.12). <img src="https://www.zhihu.com/equation?tex=F\in H^1" alt="F\in H^1" class="ee_img tr_noresize" eeimg="1">
 implies 
<img src="https://www.zhihu.com/equation?tex=F'\in H(D)" alt="F'\in H(D)" class="ee_img tr_noresize" eeimg="1">
. Since

<img src="https://www.zhihu.com/equation?tex=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}{\left\lvert F(re^{i t})\right\rvert d t}}=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}{\left\lvert ire^{it}F(re^{i t})\right\rvert d t}}\\" alt="\sup_{0\leq r<1}{\int_{-\pi}^{\pi}{\left\lvert F(re^{i t})\right\rvert d t}}=\sup_{0\leq r<1}{\int_{-\pi}^{\pi}{\left\lvert ire^{it}F(re^{i t})\right\rvert d t}}\\" class="ee_img tr_noresize" eeimg="1">

, 
<img src="https://www.zhihu.com/equation?tex=F'(z)\in H^1" alt="F'(z)\in H^1" class="ee_img tr_noresize" eeimg="1">
 if and only if 
<img src="https://www.zhihu.com/equation?tex=izF'(z)\in H^1" alt="izF'(z)\in H^1" class="ee_img tr_noresize" eeimg="1">
.

 I don't know why the difference is harmonic and continuous at the
origin, it has to be a constant c.

There is a corollary of Theorem 3.12 in book which is useful in next
section.

Corollary 1.3.3.1 (Corollary 3.13 in book). Let 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
 be a Jordan curve and let 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 be a conformal map from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">

to interior domain bounded by a Jordan curve 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
. Then 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
 is
rectifiable if and only if 
<img src="https://www.zhihu.com/equation?tex=F'\in H^1" alt="F'\in H^1" class="ee_img tr_noresize" eeimg="1">
.
