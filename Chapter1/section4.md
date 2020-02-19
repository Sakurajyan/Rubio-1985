Some Classical Inequalities
===========================

In this section we study two classical Inequalities: Hardy's inequality
and Fejer-Riesz inequality. The first inequality is an example of why

<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is a natural replacement of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=p\leq 1" alt="p\leq 1" class="ee_img tr_noresize" eeimg="1">
. The second
inequality shows some geometry properties of conformal mappings.

4.1 Hardy's inequality
------------------

Theorem 1.4.1.1 (Hardy’s inequality) Let 
<img src="https://www.zhihu.com/equation?tex=F(z)=\sum_{j=0}^{\infty}{a_jz^j}" alt="F(z)=\sum_{j=0}^{\infty}{a_jz^j}" class="ee_img tr_noresize" eeimg="1">
 be in
<img src="https://www.zhihu.com/equation?tex=H^1" alt="H^1" class="ee_img tr_noresize" eeimg="1">
. Then:

<img src="https://www.zhihu.com/equation?tex=\sum_{j=0}^\infty{\frac{\left\lvert a_j\right\rvert}{j+1}}\leq C\left\lVert F\right\rVert_{H^1}\\" alt="\sum_{j=0}^\infty{\frac{\left\lvert a_j\right\rvert}{j+1}}\leq C\left\lVert F\right\rVert_{H^1}\\" class="ee_img tr_noresize" eeimg="1">

with a constant 
<img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1">
 independent of 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
.

We know the principal branch of the logarithm 
<img src="https://www.zhihu.com/equation?tex=\log{z}=\log{r}+i\theta" alt="\log{z}=\log{r}+i\theta" class="ee_img tr_noresize" eeimg="1">
where 
<img src="https://www.zhihu.com/equation?tex=z=re^{i\theta}" alt="z=re^{i\theta}" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=\left\lvert\theta\right\rvert<\pi" alt="\left\lvert\theta\right\rvert<\pi" class="ee_img tr_noresize" eeimg="1">
. Thus
<img src="https://www.zhihu.com/equation?tex=\operatorname{Im}{\log{1-z}}=\arg{1-z}" alt="\operatorname{Im}{\log{1-z}}=\arg{1-z}" class="ee_img tr_noresize" eeimg="1">
. It is easy to see
<img src="https://www.zhihu.com/equation?tex=-\frac{\pi}{2}<\arg{1-z}<\frac{\pi}{2}" alt="-\frac{\pi}{2}<\arg{1-z}<\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
.


<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    F(re^{it})u(re^{it})=&(\sum_{j=0}^{\infty}{a_j(re^{it})^j})(\frac{i}{2}\sum_{j\neq 0}{j^{-1}r^{\left\lvert j\right\rvert}e^{i j t}})\\
                        =&(\sum_{j=0}^{\infty}{a_j r^j e^{i j t}})(\frac{i}{2}\sum_{k\neq 0}{k^{-1}r^{\left\lvert k\right\rvert}e^{i k t}})\end{aligned}\\" alt="\begin{aligned}
    F(re^{it})u(re^{it})=&(\sum_{j=0}^{\infty}{a_j(re^{it})^j})(\frac{i}{2}\sum_{j\neq 0}{j^{-1}r^{\left\lvert j\right\rvert}e^{i j t}})\\
                        =&(\sum_{j=0}^{\infty}{a_j r^j e^{i j t}})(\frac{i}{2}\sum_{k\neq 0}{k^{-1}r^{\left\lvert k\right\rvert}e^{i k t}})\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

After taking integral, only 
<img src="https://www.zhihu.com/equation?tex=j+k=0" alt="j+k=0" class="ee_img tr_noresize" eeimg="1">
 term does not vanish, thus:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    \frac{1}{2\pi}\int_{-\pi}^{\pi}F(re^{it})u(re^{it})d t=&(\frac{i}{2}\sum_{j+k=0}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^j e^{i j t}k^{-1}r^{\left\lvert k\right\rvert}e^{i k t}}d t)\\
                        =&\frac{i}{2}\sum_{j+k=0}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^{j+\left\lvert k\right\rvert}e^{i(j+k)t}k^{-1}}d t\\
                        =&\frac{i}{2}\sum_{j=1}^{\infty}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^{2j}(-j)^{-1}}d t\\
                        =&\frac{i}{2}\sum_{j=1}^{\infty}{a_j r^{2j}(-j)^{-1}}\\
                        =&-\frac{i}{2}\sum_{j=1}^{\infty}{a_j j^{-1}{\color{red}r^{2j}}}\end{aligned}\\" alt="\begin{aligned}
    \frac{1}{2\pi}\int_{-\pi}^{\pi}F(re^{it})u(re^{it})d t=&(\frac{i}{2}\sum_{j+k=0}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^j e^{i j t}k^{-1}r^{\left\lvert k\right\rvert}e^{i k t}}d t)\\
                        =&\frac{i}{2}\sum_{j+k=0}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^{j+\left\lvert k\right\rvert}e^{i(j+k)t}k^{-1}}d t\\
                        =&\frac{i}{2}\sum_{j=1}^{\infty}\frac{1}{2\pi}\int_{-\pi}^{\pi}{a_j r^{2j}(-j)^{-1}}d t\\
                        =&\frac{i}{2}\sum_{j=1}^{\infty}{a_j r^{2j}(-j)^{-1}}\\
                        =&-\frac{i}{2}\sum_{j=1}^{\infty}{a_j j^{-1}{\color{red}r^{2j}}}\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

The corollary 4.2 in book shows that if 
<img src="https://www.zhihu.com/equation?tex=F(e^{it})" alt="F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 is absolutely
continuous (equivalent to 
<img src="https://www.zhihu.com/equation?tex=F'\in H^1" alt="F'\in H^1" class="ee_img tr_noresize" eeimg="1">
), then 
<img src="https://www.zhihu.com/equation?tex=(\hat{F}(n))_n\in\ell^1" alt="(\hat{F}(n))_n\in\ell^1" class="ee_img tr_noresize" eeimg="1">
.
But the converse is not true. 
<img src="https://www.zhihu.com/equation?tex=(\hat{F}(n))_n\in\ell^1" alt="(\hat{F}(n))_n\in\ell^1" class="ee_img tr_noresize" eeimg="1">
 only implies 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
extends to a continuous function on 
<img src="https://www.zhihu.com/equation?tex=\bar{D}" alt="\bar{D}" class="ee_img tr_noresize" eeimg="1">


Remark (Errata of Re H 1 ). Let 
<img src="https://www.zhihu.com/equation?tex=g(t)" alt="g(t)" class="ee_img tr_noresize" eeimg="1">
 be
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{F(e^{it})}=\sum_{j\geq 0}{a_je^{i j t}}" alt="\operatorname{Re}{F(e^{it})}=\sum_{j\geq 0}{a_je^{i j t}}" class="ee_img tr_noresize" eeimg="1">
. Then

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    g(t)=&\frac{F(e^{it})+\overline{F(e^{it})}}{2}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j\geq 0}{\frac{a_j}{2}e^{i j t}}+\sum_{j\geq 0}{\frac{\bar{a_j}}{2}e^{-i j t}}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j> 0}{\frac{a_j}{2} e^{i j t}}+\sum_{j< 0}{\frac{\overline{a_{-j}}}{2}e^{i j t}}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j\neq 0}{\hat{g}(j) e^{i j t}}\end{aligned}\\" alt="\begin{aligned}
    g(t)=&\frac{F(e^{it})+\overline{F(e^{it})}}{2}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j\geq 0}{\frac{a_j}{2}e^{i j t}}+\sum_{j\geq 0}{\frac{\bar{a_j}}{2}e^{-i j t}}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j> 0}{\frac{a_j}{2} e^{i j t}}+\sum_{j< 0}{\frac{\overline{a_{-j}}}{2}e^{i j t}}\\
        =&\frac{a_0+\bar{a_0}}{2}+\sum_{j\neq 0}{\hat{g}(j) e^{i j t}}\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

where 
<img src="https://www.zhihu.com/equation?tex=\hat{g}(j)=\frac{a_j}{2}" alt="\hat{g}(j)=\frac{a_j}{2}" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=j>0" alt="j>0" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=\hat{g}(j)=\frac{\overline{a_{-j}}}{2}" alt="\hat{g}(j)=\frac{\overline{a_{-j}}}{2}" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=j>0" alt="j>0" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=\hat{g}(j)=\operatorname{Re}{a_0}" alt="\hat{g}(j)=\operatorname{Re}{a_0}" class="ee_img tr_noresize" eeimg="1">
. Thus

<img src="https://www.zhihu.com/equation?tex=\left\lvert a_j\right\rvert=\left\lvert\hat{g}(j)\right\rvert+\left\lvert\hat{g}(-j)\right\rvert" alt="\left\lvert a_j\right\rvert=\left\lvert\hat{g}(j)\right\rvert+\left\lvert\hat{g}(-j)\right\rvert" class="ee_img tr_noresize" eeimg="1">
.
Substitute 
<img src="https://www.zhihu.com/equation?tex=\left\lvert a_j\right\rvert" alt="\left\lvert a_j\right\rvert" class="ee_img tr_noresize" eeimg="1">
 to

<img src="https://www.zhihu.com/equation?tex=\sum_{j=1}^\infty{\frac{\left\lvert a_j\right\rvert}{j}}\leq \pi\left\lVert F\right\rVert_{H^1}" alt="\sum_{j=1}^\infty{\frac{\left\lvert a_j\right\rvert}{j}}\leq \pi\left\lVert F\right\rVert_{H^1}" class="ee_img tr_noresize" eeimg="1">
.
We have

<img src="https://www.zhihu.com/equation?tex=\sum_{j\neq 0}{\left\lvert\frac{\hat{f}(j)}{j}\right\rvert}\leq \pi\left\lVert f\right\rVert_{\operatorname{Re}{H^1}}" alt="\sum_{j\neq 0}{\left\lvert\frac{\hat{f}(j)}{j}\right\rvert}\leq \pi\left\lVert f\right\rVert_{\operatorname{Re}{H^1}}" class="ee_img tr_noresize" eeimg="1">


We have 
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{H^1}" alt="\operatorname{Re}{H^1}" class="ee_img tr_noresize" eeimg="1">
 is a proper subspace of
<img src="https://www.zhihu.com/equation?tex=\operatorname{Re}{L^1}" alt="\operatorname{Re}{L^1}" class="ee_img tr_noresize" eeimg="1">
. And Hardy's inequality may be considered an
extension to 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
 of Paley's inequality which says that for 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">

with 
<img src="https://www.zhihu.com/equation?tex=1<p\leq 2" alt="1<p\leq 2" class="ee_img tr_noresize" eeimg="1">
:

<img src="https://www.zhihu.com/equation?tex=\sum_{j=-\infty}^\infty{\frac{\left\lvert\hat{f}(j)\right\rvert^p}{\left\lvert j\right\rvert^{p-2}}}\leq C_p\left\lVert F\right\rVert_p^p\\" alt="\sum_{j=-\infty}^\infty{\frac{\left\lvert\hat{f}(j)\right\rvert^p}{\left\lvert j\right\rvert^{p-2}}}\leq C_p\left\lVert F\right\rVert_p^p\\" class="ee_img tr_noresize" eeimg="1">

Later we will see in 
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">
 this inequality can be extended to
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=p<1" alt="p<1" class="ee_img tr_noresize" eeimg="1">
. And 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=p\leq 1" alt="p\leq 1" class="ee_img tr_noresize" eeimg="1">
 are natural substitutes of
Lebesgue spaces 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
.

4.2 Fejer-Riesz inequality
----------------------

Recall the final corollary in last section. Let 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 be a conformal map
from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 to interior domain bounded by a Jordan curve 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
. Then

<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
 is rectifiable if and only if 
<img src="https://www.zhihu.com/equation?tex=F'\in H^1" alt="F'\in H^1" class="ee_img tr_noresize" eeimg="1">
.

Theorem 1.4.2.1 (Fejer-Riesz inequality) Let 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=0<p<\infty" alt="0<p<\infty" class="ee_img tr_noresize" eeimg="1">
, then

<img src="https://www.zhihu.com/equation?tex=\int_{-1}^{1}{\left\lvert F(x)\right\rvert^p dx}\leq \frac{1}{2}\int_{-\pi}^{\pi}{\left\lvert F(e^{it})\right\rvert^p d t}\\" alt="\int_{-1}^{1}{\left\lvert F(x)\right\rvert^p dx}\leq \frac{1}{2}\int_{-\pi}^{\pi}{\left\lvert F(e^{it})\right\rvert^p d t}\\" class="ee_img tr_noresize" eeimg="1">


To prove this theorem, we first prove the 
<img src="https://www.zhihu.com/equation?tex=p=2" alt="p=2" class="ee_img tr_noresize" eeimg="1">
 case. Then for 
<img src="https://www.zhihu.com/equation?tex=p\neq 2" alt="p\neq 2" class="ee_img tr_noresize" eeimg="1">

case, we factorize 
<img src="https://www.zhihu.com/equation?tex=F(z)=B(z)H(z)" alt="F(z)=B(z)H(z)" class="ee_img tr_noresize" eeimg="1">
 and let
<img src="https://www.zhihu.com/equation?tex=\left\lvert G(z)\right\rvert^2=\left\lvert H(z)\right\rvert^p" alt="\left\lvert G(z)\right\rvert^2=\left\lvert H(z)\right\rvert^p" class="ee_img tr_noresize" eeimg="1">
 to
reduce this case to 
<img src="https://www.zhihu.com/equation?tex=p=2" alt="p=2" class="ee_img tr_noresize" eeimg="1">
.

Here is a direct application of this inequality. Let 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 be the
conformal map from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 to interior domain bounded by a Jordan curve
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
. Then image of diameter of 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 has length at most half of
length of <img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1"> (corollary 4.6 in book).

Remark (notes on proof of corollary 4.6 in book). To prove that 
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}" alt="\frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
 is the best constant in corollary 4.6 in
book, we only need to show there is a conformal map from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 to interior
domain bounded by a rectifiable Jordan curve 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
, the constant
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}" alt="\frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
 can not be smaller. Let 
<img src="https://www.zhihu.com/equation?tex=F(z)" alt="F(z)" class="ee_img tr_noresize" eeimg="1">
 is a conformal map from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
to rectangle <img src="https://www.zhihu.com/equation?tex=\{x+iy:\left\lvert x\right\rvert<1,\left\lvert y\right\rvert<\epsilon\}" alt="\{x+iy:\left\lvert x\right\rvert<1,\left\lvert y\right\rvert<\epsilon\}" class="ee_img tr_noresize" eeimg="1">
and 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 maps segment 
<img src="https://www.zhihu.com/equation?tex=(-1,1)" alt="(-1,1)" class="ee_img tr_noresize" eeimg="1">
 in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 to segment 
<img src="https://www.zhihu.com/equation?tex=(-1,1)" alt="(-1,1)" class="ee_img tr_noresize" eeimg="1">
 in rectangle.
It is easy to construct this map. The constant has to be at least
<img src="https://www.zhihu.com/equation?tex=\frac{2}{4+ 4\epsilon}" alt="\frac{2}{4+ 4\epsilon}" class="ee_img tr_noresize" eeimg="1">
. Let 
<img src="https://www.zhihu.com/equation?tex=\epsilon\to 0" alt="\epsilon\to 0" class="ee_img tr_noresize" eeimg="1">
 we conclude 
<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}" alt="\frac{1}{2}" class="ee_img tr_noresize" eeimg="1">
is the best constant.

Another usage of conformal mapping 
<img src="https://www.zhihu.com/equation?tex=F'\in H^1" alt="F'\in H^1" class="ee_img tr_noresize" eeimg="1">
 is following: 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 can be
extended on 
<img src="https://www.zhihu.com/equation?tex=\bar{D}" alt="\bar{D}" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is still conformal. More precisely, Let

<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 be a conformal mapping from 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 to interior domain bounded by a
rectifiable Jordan curve 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is also conformal at almost every
boundary point (corollary 4.7 in book).

Remark (notes on proof of corollary 4.7 in book). The step:

<img src="https://www.zhihu.com/equation?tex=\frac{F(e^{it_0})-F(z)}{e^{it_0}-z}-F'(e^{it_0})= \frac{1}{e^{it_0}-z}\int_z^{e^{it_0}}{(F'(\xi)-F'(e^{it_0}))d\xi}\to 0\\" alt="\frac{F(e^{it_0})-F(z)}{e^{it_0}-z}-F'(e^{it_0})= \frac{1}{e^{it_0}-z}\int_z^{e^{it_0}}{(F'(\xi)-F'(e^{it_0}))d\xi}\to 0\\" class="ee_img tr_noresize" eeimg="1">

as 
<img src="https://www.zhihu.com/equation?tex=z\to e^{it_0}" alt="z\to e^{it_0}" class="ee_img tr_noresize" eeimg="1">
 N.T. is by mean value theorem of integration.

I don't know why the tangent to 
<img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1">
 at the point 
<img src="https://www.zhihu.com/equation?tex=F(e^{it_0})" alt="F(e^{it_0})" class="ee_img tr_noresize" eeimg="1">
happens for a.e. boundary point 
<img src="https://www.zhihu.com/equation?tex=e^{it_0}" alt="e^{it_0}" class="ee_img tr_noresize" eeimg="1">
.

The angle between 
<img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">
 and boundary in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 is <img src="https://www.zhihu.com/equation?tex=\lim{\arg{z-e^{it_0}}}-t_0-\frac{\pi}{2}" alt="\lim{\arg{z-e^{it_0}}}-t_0-\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
 and The angle between
<img src="https://www.zhihu.com/equation?tex=F(\gamma)" alt="F(\gamma)" class="ee_img tr_noresize" eeimg="1">
 and boundary in 
<img src="https://www.zhihu.com/equation?tex=F(D)" alt="F(D)" class="ee_img tr_noresize" eeimg="1">
 is <img src="https://www.zhihu.com/equation?tex=\lim{\arg{F(z)-F(e^{it_0})}}-t_0-\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}" alt="\lim{\arg{F(z)-F(e^{it_0})}}-t_0-\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}" class="ee_img tr_noresize" eeimg="1">
.
Since 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is conformal in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
, to prove 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 is conformal in 
<img src="https://www.zhihu.com/equation?tex=\bar{D}" alt="\bar{D}" class="ee_img tr_noresize" eeimg="1">
,
we only need to prove the conformal map preserves angle on boundary.
That is:

<img src="https://www.zhihu.com/equation?tex=\lim_{z\to e^{it_0}}{\arg{(z-e^{it_0}})}-t_0-\frac{\pi}{2}=\lim_{z\to e^{it_0}}{\arg{(F(z)-F(e^{it_0}))}}-\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}\\" alt="\lim_{z\to e^{it_0}}{\arg{(z-e^{it_0}})}-t_0-\frac{\pi}{2}=\lim_{z\to e^{it_0}}{\arg{(F(z)-F(e^{it_0}))}}-\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}\\" class="ee_img tr_noresize" eeimg="1">

We have 
<img src="https://www.zhihu.com/equation?tex=\frac{d}{dt}F(e^{it})\vert_{t=t_0}=ie^{it_0}F'(e^{it_0})" alt="\frac{d}{dt}F(e^{it})\vert_{t=t_0}=ie^{it_0}F'(e^{it_0})" class="ee_img tr_noresize" eeimg="1">
. Thus <img src="https://www.zhihu.com/equation?tex=\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}=\frac{\pi}{2}+t_0+\arg{F'(e^{it_0})}" alt="\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}=\frac{\pi}{2}+t_0+\arg{F'(e^{it_0})}" class="ee_img tr_noresize" eeimg="1">
.
So the equality is the same as:

<img src="https://www.zhihu.com/equation?tex=\lim_{z\to e^{it_0}}{\arg{(z-e^{it_0}})}=\lim_{z\to e^{it_0}}{\arg{(F(z)-F(e^{it_0}))}}-\arg{F'(e^{it_0})}\\" alt="\lim_{z\to e^{it_0}}{\arg{(z-e^{it_0}})}=\lim_{z\to e^{it_0}}{\arg{(F(z)-F(e^{it_0}))}}-\arg{F'(e^{it_0})}\\" class="ee_img tr_noresize" eeimg="1">

which is clearly if we take 
<img src="https://www.zhihu.com/equation?tex=\arg" alt="\arg" class="ee_img tr_noresize" eeimg="1">
 in both sides in

<img src="https://www.zhihu.com/equation?tex=\lim_{z\to e^{it_0}}\frac{F(e^{it_0})-F(z)}{e^{it_0}-z}=F'(e^{it_0})" alt="\lim_{z\to e^{it_0}}\frac{F(e^{it_0})-F(z)}{e^{it_0}-z}=F'(e^{it_0})" class="ee_img tr_noresize" eeimg="1">
.
We use 
<img src="https://www.zhihu.com/equation?tex=t_0+\frac{\pi}{2}" alt="t_0+\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
 instead of 
<img src="https://www.zhihu.com/equation?tex=t_0-\frac{\pi}{2}" alt="t_0-\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">
 match to

<img src="https://www.zhihu.com/equation?tex=\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}" alt="\arg{(\frac{d}{dt}(F(e^{it}))\vert_{t=t_0})}" class="ee_img tr_noresize" eeimg="1">
 since they are in the
same direction.
