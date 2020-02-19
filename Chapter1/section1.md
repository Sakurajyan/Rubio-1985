Classical Theory of Hardy Space
===============================

Harmonic Functions, Poisson Representation
------------------------------------------

In plane case, we can rewrite harmonic condition: 
<img src="https://www.zhihu.com/equation?tex=\Delta F=0" alt="\Delta F=0" class="ee_img tr_noresize" eeimg="1">
 as

<img src="https://www.zhihu.com/equation?tex=\Delta F=(\frac{\partial}{\partial x}-i\frac{\partial}{\partial y})(\frac{\partial}{\partial x}+i\frac{\partial}{\partial y})F=0" alt="\Delta F=(\frac{\partial}{\partial x}-i\frac{\partial}{\partial y})(\frac{\partial}{\partial x}+i\frac{\partial}{\partial y})F=0" class="ee_img tr_noresize" eeimg="1">
.
Notices the equation

<img src="https://www.zhihu.com/equation?tex=\frac{\partial}{\partial x}+i\frac{\partial}{\partial y}=0" alt="\frac{\partial}{\partial x}+i\frac{\partial}{\partial y}=0" class="ee_img tr_noresize" eeimg="1">
 is
equivalent to the Cauchy-Riemann equations for function 
<img src="https://www.zhihu.com/equation?tex=F=u+iv" alt="F=u+iv" class="ee_img tr_noresize" eeimg="1">
.

If function F satisfies C-R equations, then F satisfies Laplace equation
for 
<img src="https://www.zhihu.com/equation?tex=\mathbb{C}" alt="\mathbb{C}" class="ee_img tr_noresize" eeimg="1">
. And if F satisfies 
<img src="https://www.zhihu.com/equation?tex=\Delta=0" alt="\Delta=0" class="ee_img tr_noresize" eeimg="1">
, so does 
<img src="https://www.zhihu.com/equation?tex=\bar{F}" alt="\bar{F}" class="ee_img tr_noresize" eeimg="1">
. Thus

<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=\bar{F}" alt="\bar{F}" class="ee_img tr_noresize" eeimg="1">
 are all harmonic functions. Besides, the real and
imaginary part of F, u and v also satisfy 
<img src="https://www.zhihu.com/equation?tex=\Delta=0" alt="\Delta=0" class="ee_img tr_noresize" eeimg="1">
, means u and v are
harmonic functions.

Assume that u satisfies 
<img src="https://www.zhihu.com/equation?tex=\Delta=0" alt="\Delta=0" class="ee_img tr_noresize" eeimg="1">
. If we let 
<img src="https://www.zhihu.com/equation?tex=v_x=-u_y" alt="v_x=-u_y" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=v_y=u_x" alt="v_y=u_x" class="ee_img tr_noresize" eeimg="1">
,
then we have 
<img src="https://www.zhihu.com/equation?tex=v_{xy}=v_{yx}" alt="v_{xy}=v_{yx}" class="ee_img tr_noresize" eeimg="1">
, which indicates exists of v (equivalent of
Fubini's Theorem and the equality of the mixed partial derivatives). And

<img src="https://www.zhihu.com/equation?tex=v_{xx}+v_{yy}=-u_{yx}+u_{xy}=0" alt="v_{xx}+v_{yy}=-u_{yx}+u_{xy}=0" class="ee_img tr_noresize" eeimg="1">
 indicates 
<img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1">
 is also harmonic. 
<img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1">
 is
determined up to an additive constant, and 
<img src="https://www.zhihu.com/equation?tex=F=u+iv" alt="F=u+iv" class="ee_img tr_noresize" eeimg="1">
 is holomorphic.

Later we will see holomorphic function is the special case of harmonic
function.

If 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is a real harmonic function, by above remark, we know

<img src="https://www.zhihu.com/equation?tex=u=\operatorname{Re}{F}" alt="u=\operatorname{Re}{F}" class="ee_img tr_noresize" eeimg="1">
 for some holomorphic function

<img src="https://www.zhihu.com/equation?tex=F(z)=\sum_{k=0}^{\infty}{c_k z^k}" alt="F(z)=\sum_{k=0}^{\infty}{c_k z^k}" class="ee_img tr_noresize" eeimg="1">
. Then we can derive the series
representation of 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
: 
<img src="https://www.zhihu.com/equation?tex=\label{series of harmonic function}
    u(re^{i\theta})=\sum_{k=-\infty}^\infty{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}\\" alt="\label{series of harmonic function}
    u(re^{i\theta})=\sum_{k=-\infty}^\infty{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}\\" class="ee_img tr_noresize" eeimg="1">

and it converges uniformly on compact subsets of 
<img src="https://www.zhihu.com/equation?tex=D(0,R)" alt="D(0,R)" class="ee_img tr_noresize" eeimg="1">
.

Using mean value property, sequence of holomorphic functions which
uniformly converge on compact subsets, the limit is a holomorphic
function.

The partial sum of

<img src="https://www.zhihu.com/equation?tex=u_n(re^{i\theta})=\sum_{k=-n}^n{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}" alt="u_n(re^{i\theta})=\sum_{k=-n}^n{a_kr^{\left\lvert k\right\rvert}e^{i k\theta}}" class="ee_img tr_noresize" eeimg="1">

is obviously harmonic, and it converges uniformly on compact subsets of

<img src="https://www.zhihu.com/equation?tex=D(0,R)" alt="D(0,R)" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})" alt="u(re^{i\theta})" class="ee_img tr_noresize" eeimg="1">
 is harmonic.

### Harmonic function to Poisson integral (or Poisson representation of harmonic function) {#harmonic function can be written as Poisson integral}

Assumed 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is harmonic in 
<img src="https://www.zhihu.com/equation?tex=D(0,R)." alt="D(0,R)." class="ee_img tr_noresize" eeimg="1">
If 
<img src="https://www.zhihu.com/equation?tex=R>1" alt="R>1" class="ee_img tr_noresize" eeimg="1">
, we can represent 
<img src="https://www.zhihu.com/equation?tex=a_k" alt="a_k" class="ee_img tr_noresize" eeimg="1">
 in
equation
[\[series of harmonic function\]](#series of harmonic function){reference-type="eqref"
reference="series of harmonic function"} by 
<img src="https://www.zhihu.com/equation?tex=u(e^{i t})" alt="u(e^{i t})" class="ee_img tr_noresize" eeimg="1">
 using Fourier
analysis. Finally we derive the Poisson kernel and the Poisson
representation:

<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=\frac{1}{2\pi}\int_{-\pi}^\pi{P_r(\theta-t)u(e^{i t})}d t\label{Poisson integral 1}\\" alt="u(re^{i\theta})=\frac{1}{2\pi}\int_{-\pi}^\pi{P_r(\theta-t)u(e^{i t})}d t\label{Poisson integral 1}\\" class="ee_img tr_noresize" eeimg="1">

If 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is only harmonic on 
<img src="https://www.zhihu.com/equation?tex=D(0,1)" alt="D(0,1)" class="ee_img tr_noresize" eeimg="1">
, the equation
[\[Poisson integral 1\]](#Poisson integral 1){reference-type="eqref"
reference="Poisson integral 1"} still can be valid in some sense once we
add some restriction on 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
.

[\[Poisson representation\]]{#Poisson representation
label="Poisson representation"} Let 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 be a harmonic function in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">

such that 
<img src="https://www.zhihu.com/equation?tex=\label{Poisson representation condition}
        \sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert^p d t}<\infty\\" alt="\label{Poisson representation condition}
        \sup_{0\leq r<1}{\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert^p d t}<\infty\\" class="ee_img tr_noresize" eeimg="1">

for some 
<img src="https://www.zhihu.com/equation?tex=p>1" alt="p>1" class="ee_img tr_noresize" eeimg="1">
. Then there is a function 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
 such that

<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=\frac{1}{2\pi}\int_{-\pi}^\pi{P_r(\theta-t)f(t)}d t\\" alt="u(re^{i\theta})=\frac{1}{2\pi}\int_{-\pi}^\pi{P_r(\theta-t)f(t)}d t\\" class="ee_img tr_noresize" eeimg="1">


In later section, we will see left side of inequality
[\[Poisson representation condition\]](#Poisson representation condition){reference-type="eqref"
reference="Poisson representation condition"} is 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 norm. The proof
of Theorem
[\[Poisson representation\]](#Poisson representation){reference-type="ref"
reference="Poisson representation"} shows that how dual space,
w\*-topology and Banach-Alaoglu theorem perform in integral
representation. The tricky part is using representation

<img src="https://www.zhihu.com/equation?tex=u(r_nre^{i\theta})" alt="u(r_nre^{i\theta})" class="ee_img tr_noresize" eeimg="1">
. In the proof we also need 
<img src="https://www.zhihu.com/equation?tex=P_r(\theta)\in L^{p'}" alt="P_r(\theta)\in L^{p'}" class="ee_img tr_noresize" eeimg="1">

which is easy since

<img src="https://www.zhihu.com/equation?tex=\left\lVert P_r(\theta)\right\rVert_\infty=\frac{1+r}{1-r}" alt="\left\lVert P_r(\theta)\right\rVert_\infty=\frac{1+r}{1-r}" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=L^\infty([-\pi,\pi]) \subset L^{p'}([-\pi,\pi])" alt="L^\infty([-\pi,\pi]) \subset L^{p'}([-\pi,\pi])" class="ee_img tr_noresize" eeimg="1">
.

In metrizable space, compact and sequentially compact are equivalent.

Let 
<img src="https://www.zhihu.com/equation?tex=f_n(t)=u(r_ne^{i t})" alt="f_n(t)=u(r_ne^{i t})" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=(f_n)\subset L^{p'*}" alt="(f_n)\subset L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is in a close ball
w.r.t p-norm and Banach-Alaoglu theorem indicates this ball is w\*
compact. Since w\*-compact is equivalent to w\*-sequentially compact if
this close ball is metrizable in w\*-topology, we need to prove this
close ball is metrizable in w\*-topology.

Here is a direct proof. Since 
<img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">
 is separable there is a countable
dense set 
<img src="https://www.zhihu.com/equation?tex=(g_n)\in L^{p'}" alt="(g_n)\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
. For every 
<img src="https://www.zhihu.com/equation?tex=g\in L^{p'}" alt="g\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
, let

<img src="https://www.zhihu.com/equation?tex=\hat{g}(f)=f(g)" alt="\hat{g}(f)=f(g)" class="ee_img tr_noresize" eeimg="1">
 where 
<img src="https://www.zhihu.com/equation?tex=f\in L^{p'*}" alt="f\in L^{p'*}" class="ee_img tr_noresize" eeimg="1">
. Any pair of points

<img src="https://www.zhihu.com/equation?tex=f_1,f_2\in L^{p'*}" alt="f_1,f_2\in L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 can be separate by some 
<img src="https://www.zhihu.com/equation?tex=g_i\in L^{p'}" alt="g_i\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
 (since
every 
<img src="https://www.zhihu.com/equation?tex=\hat{g_n}" alt="\hat{g_n}" class="ee_img tr_noresize" eeimg="1">
 is w\*-continuous, density of 
<img src="https://www.zhihu.com/equation?tex=(g_n)" alt="(g_n)" class="ee_img tr_noresize" eeimg="1">
 ensures

<img src="https://www.zhihu.com/equation?tex=f_1,f_2" alt="f_1,f_2" class="ee_img tr_noresize" eeimg="1">
 can be separate), Thus 
<img src="https://www.zhihu.com/equation?tex=(\hat{g_n})" alt="(\hat{g_n})" class="ee_img tr_noresize" eeimg="1">
 is a countable family of
continuous functions that separates points in 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
. Then we can use
metric:

<img src="https://www.zhihu.com/equation?tex=d(f_1,f_2)=\sum_{n=0}^\infty{2^{-n}\left\lvert f_1(g_n)-f_2(g_n)\right\rvert}" alt="d(f_1,f_2)=\sum_{n=0}^\infty{2^{-n}\left\lvert f_1(g_n)-f_2(g_n)\right\rvert}" class="ee_img tr_noresize" eeimg="1">
.

We have proved that 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is metrizable in w\*-topology. Here is a
topological thought. By Nagata-Smirnov metrization theorem, 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is
regular. we don't know how to shown this property directly. Also,

<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 a basis countably locally finite (by Nagata-Smirnov
metrization theorem), we also want to show this property directly.
Besides, consider Urysohn metrization theorem, if we have shown

<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is regular, 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is metrizable once we show there is a
countable basis for 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
. We don't know if it is possible.

Now 
<img src="https://www.zhihu.com/equation?tex=(f_n)" alt="(f_n)" class="ee_img tr_noresize" eeimg="1">
 is w\* sequentially compact in 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
. This means for any

<img src="https://www.zhihu.com/equation?tex=g\in L^{p'}" alt="g\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
, there is a subsequence 
<img src="https://www.zhihu.com/equation?tex=(f_{n_k})" alt="(f_{n_k})" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=f\in L^{p'*}" alt="f\in L^{p'*}" class="ee_img tr_noresize" eeimg="1">

such that 
<img src="https://www.zhihu.com/equation?tex=\int gf_{n_k}\to\int gf" alt="\int gf_{n_k}\to\int gf" class="ee_img tr_noresize" eeimg="1">
.


<img src="https://www.zhihu.com/equation?tex=L^{p'*}\cong L^p" alt="L^{p'*}\cong L^p" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is a normed space and 
<img src="https://www.zhihu.com/equation?tex=L^{p'*}" alt="L^{p'*}" class="ee_img tr_noresize" eeimg="1">
 is
metrizable.

The 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
 case is failed since we can not use w\*-topology. 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
 is not
a separate dual space of some space (Assume 
<img src="https://www.zhihu.com/equation?tex=L^1=X^*" alt="L^1=X^*" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
 is
separable in w\*-topology implies 
<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
 is separable). One method showing

<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
 is not a separate dual space of some space by showing 
<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
 does
not have the Radon-Nikodym property (Radon-Nikodym theorem is valid).

 If X is a Banach space, then 
<img src="https://www.zhihu.com/equation?tex=X^*" alt="X^*" class="ee_img tr_noresize" eeimg="1">
 has the Radon-Nikodym property (RNP)
if (and only if) every separable, linear subspace of X has a separable
dual (Charles Stegall: The Radon-Nikodym property in Conjugate Banach
Space. II).

Thus for 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
 case, we can not use same argument as Theorem
[\[Poisson representation\]](#Poisson representation){reference-type="ref"
reference="Poisson representation"}. However there is a relative result.

<img src="https://www.zhihu.com/equation?tex=L^1" alt="L^1" class="ee_img tr_noresize" eeimg="1">
 can be isometrically imbedded in to 
<img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1">
, the space of Borel
measures with bounded variation, which is dual of continuous function
with compact support space 
<img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1">
. Thus we can use same argument to 
<img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1">
 and introduce Poisson-Stieltjes integral.

When we use Borel measures case in Theorem
[\[Poisson representation\]](#Poisson representation){reference-type="ref"
reference="Poisson representation"}, we get *Poisson integral of
positive measure for harmonic functions*.

<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})=\frac{1}{2\pi}\int_\pi^\pi{P_r(\theta-t)d\mu(t)} \label{Poisson integral 2}\\" alt="u(re^{i\theta})=\frac{1}{2\pi}\int_\pi^\pi{P_r(\theta-t)d\mu(t)} \label{Poisson integral 2}\\" class="ee_img tr_noresize" eeimg="1">

Here 
<img src="https://www.zhihu.com/equation?tex=d\mu(t)" alt="d\mu(t)" class="ee_img tr_noresize" eeimg="1">
 is the w\*-limit of 
<img src="https://www.zhihu.com/equation?tex=u(r_ne^{it})d t" alt="u(r_ne^{it})d t" class="ee_img tr_noresize" eeimg="1">
. The difference
between
[\[Poisson integral 1\]](#Poisson integral 1){reference-type="eqref"
reference="Poisson integral 1"} and
[\[Poisson integral 2\]](#Poisson integral 2){reference-type="eqref"
reference="Poisson integral 2"} is that in
[\[Poisson integral 1\]](#Poisson integral 1){reference-type="eqref"
reference="Poisson integral 1"}, 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 needs to be harmonic in a little
larger disk 
<img src="https://www.zhihu.com/equation?tex=D(0,R),R>1" alt="D(0,R),R>1" class="ee_img tr_noresize" eeimg="1">
, but in
[\[Poisson integral 2\]](#Poisson integral 2){reference-type="eqref"
reference="Poisson integral 2"} 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 needs not. However, this is not hold
for all harmonic functions since we need constraints.

### Poisson integral indicates harmonic {#Poisson integral indicates harmonic}

Using Fourier series, we show that given a function 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
,

<img src="https://www.zhihu.com/equation?tex=1\leq p\leq \infty" alt="1\leq p\leq \infty" class="ee_img tr_noresize" eeimg="1">
 (or a complex Borel measure 
<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">
), Poisson
integral u=
<img src="https://www.zhihu.com/equation?tex=P(f)" alt="P(f)" class="ee_img tr_noresize" eeimg="1">
 (or u=
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">
) is real part of a holomorphic
function. Thus it is harmonic (Theorem 1.11 (or 1.14) in book). And we
give bound of norm of 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 by norm of 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 (or measure 
<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">
):

-   
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert^p d t \leq \int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^p d t~for~p<\infty" alt="\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert^p d t \leq \int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^p d t~for~p<\infty" class="ee_img tr_noresize" eeimg="1">


-   
<img src="https://www.zhihu.com/equation?tex=\left\lvert u(z)\right\rvert\leq \left\lVert f(t)\right\rVert_\infty~for~p=\infty" alt="\left\lvert u(z)\right\rvert\leq \left\lVert f(t)\right\rVert_\infty~for~p=\infty" class="ee_img tr_noresize" eeimg="1">


-   
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert d t \leq \int_{-\pi}^{\pi}d\left\lvert\mu\right\rvert(t)" alt="\int_{-\pi}^{\pi}\left\lvert u(re^{i t})\right\rvert d t \leq \int_{-\pi}^{\pi}d\left\lvert\mu\right\rvert(t)" class="ee_img tr_noresize" eeimg="1">


For 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=p\leq\infty" alt="p\leq\infty" class="ee_img tr_noresize" eeimg="1">
 case, the equality holds when 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
 or
take sup on right hand side. We prove this in section 3.

### Boundary behavior of Poisson integral (or norm convergence and pointwise convergence)

Given a continuous function 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 on 
<img src="https://www.zhihu.com/equation?tex=\partial D" alt="\partial D" class="ee_img tr_noresize" eeimg="1">
, we want to find a
continuous function on 
<img src="https://www.zhihu.com/equation?tex=\bar{D}" alt="\bar{D}" class="ee_img tr_noresize" eeimg="1">
, which is harmonic in 
<img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">
 and coincides
with 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 on 
<img src="https://www.zhihu.com/equation?tex=\partial D" alt="\partial D" class="ee_img tr_noresize" eeimg="1">
.

From section
[1.1.2](#Poisson integral indicates harmonic){reference-type="ref"
reference="Poisson integral indicates harmonic"}, we can see

<img src="https://www.zhihu.com/equation?tex=u(re^{i t})=P(f)" alt="u(re^{i t})=P(f)" class="ee_img tr_noresize" eeimg="1">
 is harmonic function. Roughly speaking, if

<img src="https://www.zhihu.com/equation?tex=u(e^{i t})=f" alt="u(e^{i t})=f" class="ee_img tr_noresize" eeimg="1">
 (Actually the domain of u is D, so 
<img src="https://www.zhihu.com/equation?tex=u(e^{i t})" alt="u(e^{i t})" class="ee_img tr_noresize" eeimg="1">
 is not
defined), the classical Dirichlet problem is solved. Thus we need to
study the boundary behavior of Poisson integral. *The key idea is
approximate identity*. Using this idea, we prove the following theorem.

[\[norm convergence\]]{#norm convergence label="norm convergence"} Let

<img src="https://www.zhihu.com/equation?tex=\phi_\alpha" alt="\phi_\alpha" class="ee_img tr_noresize" eeimg="1">
 be an approximate identity on the torus 
<img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">
. Then:

1.  If 
<img src="https://www.zhihu.com/equation?tex=f\in L^p([-\pi,\pi])" alt="f\in L^p([-\pi,\pi])" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=1\leq p<\infty" alt="1\leq p<\infty" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=f_\alpha" alt="f_\alpha" class="ee_img tr_noresize" eeimg="1">

    stands for convolution
    
<img src="https://www.zhihu.com/equation?tex=f_\alpha(\theta)=(f*\phi_\alpha)(\theta)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{f(\theta-t)\phi_\alpha(t)d t}\\" alt="f_\alpha(\theta)=(f*\phi_\alpha)(\theta)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{f(\theta-t)\phi_\alpha(t)d t}\\" class="ee_img tr_noresize" eeimg="1">

    it follows that 
<img src="https://www.zhihu.com/equation?tex=f_\alpha\to f" alt="f_\alpha\to f" class="ee_img tr_noresize" eeimg="1">
 in 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
, i.e.:
    
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}{\left\lvert f_\alpha(t)-f(t)\right\rvert^p d t}\to 0\\" alt="\int_{-\pi}^{\pi}{\left\lvert f_\alpha(t)-f(t)\right\rvert^p d t}\to 0\\" class="ee_img tr_noresize" eeimg="1">


2.  If f is a continuous 
<img src="https://www.zhihu.com/equation?tex=2\pi" alt="2\pi" class="ee_img tr_noresize" eeimg="1">
-periodic function, we have
    
<img src="https://www.zhihu.com/equation?tex=f_\alpha\to f" alt="f_\alpha\to f" class="ee_img tr_noresize" eeimg="1">
 uniformly on 
<img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">
.

Theorem [\[norm convergence\]](#norm convergence){reference-type="ref"
reference="norm convergence"} shows that for 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
,

<img src="https://www.zhihu.com/equation?tex=1\leq p<\infty" alt="1\leq p<\infty" class="ee_img tr_noresize" eeimg="1">
 or 
<img src="https://www.zhihu.com/equation?tex=f\in C" alt="f\in C" class="ee_img tr_noresize" eeimg="1">
, Poisson integral converges to boundary in
norm. Following the proof of theorem
[\[norm convergence\]](#norm convergence){reference-type="ref"
reference="norm convergence"}, we can show another two case: 
<img src="https://www.zhihu.com/equation?tex=p=\infty" alt="p=\infty" class="ee_img tr_noresize" eeimg="1">

and 
<img src="https://www.zhihu.com/equation?tex=f\in M" alt="f\in M" class="ee_img tr_noresize" eeimg="1">
. The convergence becomes w\* convergence (Corollary 1.19 in
book).

Here comes another topic: What about pointwise convergence for 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">

on boundary if 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">
 is Poisson-Stieltjes integral? We need a new
concept: non-tangentially converge. We show that

<img src="https://www.zhihu.com/equation?tex=P(\mu)(z)\to F'(\theta_1)" alt="P(\mu)(z)\to F'(\theta_1)" class="ee_img tr_noresize" eeimg="1">
 as 
<img src="https://www.zhihu.com/equation?tex=z\to e^{i\theta_1}" alt="z\to e^{i\theta_1}" class="ee_img tr_noresize" eeimg="1">
 N.T., where

<img src="https://www.zhihu.com/equation?tex=F(\theta)=\int_0^\theta{d\mu(t)}" alt="F(\theta)=\int_0^\theta{d\mu(t)}" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F'(\theta_1)" alt="F'(\theta_1)" class="ee_img tr_noresize" eeimg="1">
 exists and finite
(Theorem 1.20 in book).

You can omit the following remark if you choose not to check the proof
in book.

First we take 
<img src="https://www.zhihu.com/equation?tex=c>0" alt="c>0" class="ee_img tr_noresize" eeimg="1">
, since we need proof for any 
<img src="https://www.zhihu.com/equation?tex=c>0" alt="c>0" class="ee_img tr_noresize" eeimg="1">
. This 
<img src="https://www.zhihu.com/equation?tex=c" alt="c" class="ee_img tr_noresize" eeimg="1">
 decides
the approach region.\
Then given 
<img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1">
, we take 
<img src="https://www.zhihu.com/equation?tex=\delta" alt="\delta" class="ee_img tr_noresize" eeimg="1">
 small enough s.t.

<img src="https://www.zhihu.com/equation?tex=\left\lvert F(t)\right\rvert<\epsilon\left\lvert t\right\rvert" alt="\left\lvert F(t)\right\rvert<\epsilon\left\lvert t\right\rvert" class="ee_img tr_noresize" eeimg="1">
 when

<img src="https://www.zhihu.com/equation?tex=\left\lvert t\right\rvert<\delta" alt="\left\lvert t\right\rvert<\delta" class="ee_img tr_noresize" eeimg="1">
. This 
<img src="https://www.zhihu.com/equation?tex=\delta" alt="\delta" class="ee_img tr_noresize" eeimg="1">
 can be taken since

<img src="https://www.zhihu.com/equation?tex=F(0)=0" alt="F(0)=0" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F'(0)=0" alt="F'(0)=0" class="ee_img tr_noresize" eeimg="1">
.\
If we take 
<img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1">
 large enough and 
<img src="https://www.zhihu.com/equation?tex=re^{i\theta}" alt="re^{i\theta}" class="ee_img tr_noresize" eeimg="1">
 in the region. then

<img src="https://www.zhihu.com/equation?tex=\left\lvert\theta\right\rvert" alt="\left\lvert\theta\right\rvert" class="ee_img tr_noresize" eeimg="1">
 can be less than 
<img src="https://www.zhihu.com/equation?tex=\frac{\delta}{4}" alt="\frac{\delta}{4}" class="ee_img tr_noresize" eeimg="1">
.\
The estimation of 
<img src="https://www.zhihu.com/equation?tex=u(re^{i\theta})" alt="u(re^{i\theta})" class="ee_img tr_noresize" eeimg="1">
 is (we use

<img src="https://www.zhihu.com/equation?tex=F(t)=\int_{-\pi}^{\pi}{d\mu (t)}" alt="F(t)=\int_{-\pi}^{\pi}{d\mu (t)}" class="ee_img tr_noresize" eeimg="1">
 in the third line): 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \left\lvert u(re^{i\theta})\right\rvert= & \left\lvert\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{P_r(\theta-t)d\mu(t)}+\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r(\theta-t)d\mu(t)}\right\rvert                     \\
        \leq                   & \left\lvert\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{P_r(\theta-t)d\mu(t)}\right\rvert+\left\lvert\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r(\theta-t)d\mu(t)}\right\rvert               \\
        \leq                   & (\sup_{{\color{red}\left\lvert t\right\rvert>\delta}}{P_r(\theta-t)})\cdot\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{d\left\lvert\mu\right\rvert(t)}                                      \\
                               & +\left\lvert\left.(P_r(\theta-t)\cdot\frac{1}{2\pi}F(t))\right\rvert_{-\delta}^{\delta}
        +\int_{-\delta}^{\delta}{P_r'(\theta-t)\frac{1}{2\pi}F(t)d t}\right\rvert                                                                                                                  \\
        \leq                   & (\sup_{{\color{red}\frac{3\delta}{4}<\left\lvert t\right\rvert<\pi+\frac{\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\pi}^{\pi}{d\left\lvert\mu\right\rvert(t)}                        \\
                               & +\left\lvert\left.(P_r(\theta-t)\cdot\frac{1}{2\pi}F(t))\right\rvert_{-\delta}^{\delta}\right\rvert+\left\lvert\int_{-\delta}^{\delta}{(P_r'(\theta-t)\frac{1}{2\pi}F(t))dt}\right\rvert \\
        \leq                   & (\sup_{{\color{red}\left\lvert t\right\rvert>\frac{3\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\pi}^{\pi}{d\left\lvert\mu\right\rvert(t)}                                             \\
                               & +(\sup_{{\color{red}\left\lvert t\right\rvert>\frac{3\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\delta}^{\delta}{d\left\lvert\mu\right\rvert(t)}+
        \left\lvert\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r'(\theta-t)F(t)dt}\right\rvert
    \end{aligned}\\" alt="\begin{aligned}
        \left\lvert u(re^{i\theta})\right\rvert= & \left\lvert\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{P_r(\theta-t)d\mu(t)}+\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r(\theta-t)d\mu(t)}\right\rvert                     \\
        \leq                   & \left\lvert\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{P_r(\theta-t)d\mu(t)}\right\rvert+\left\lvert\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r(\theta-t)d\mu(t)}\right\rvert               \\
        \leq                   & (\sup_{{\color{red}\left\lvert t\right\rvert>\delta}}{P_r(\theta-t)})\cdot\frac{1}{2\pi}\int_{\delta<\left\lvert t\right\rvert\leq\pi}{d\left\lvert\mu\right\rvert(t)}                                      \\
                               & +\left\lvert\left.(P_r(\theta-t)\cdot\frac{1}{2\pi}F(t))\right\rvert_{-\delta}^{\delta}
        +\int_{-\delta}^{\delta}{P_r'(\theta-t)\frac{1}{2\pi}F(t)d t}\right\rvert                                                                                                                  \\
        \leq                   & (\sup_{{\color{red}\frac{3\delta}{4}<\left\lvert t\right\rvert<\pi+\frac{\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\pi}^{\pi}{d\left\lvert\mu\right\rvert(t)}                        \\
                               & +\left\lvert\left.(P_r(\theta-t)\cdot\frac{1}{2\pi}F(t))\right\rvert_{-\delta}^{\delta}\right\rvert+\left\lvert\int_{-\delta}^{\delta}{(P_r'(\theta-t)\frac{1}{2\pi}F(t))dt}\right\rvert \\
        \leq                   & (\sup_{{\color{red}\left\lvert t\right\rvert>\frac{3\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\pi}^{\pi}{d\left\lvert\mu\right\rvert(t)}                                             \\
                               & +(\sup_{{\color{red}\left\lvert t\right\rvert>\frac{3\delta}{4}}}{P_r(t)})\cdot\frac{1}{2\pi}\int_{-\delta}^{\delta}{d\left\lvert\mu\right\rvert(t)}+
        \left\lvert\frac{1}{2\pi}\int_{-\delta}^{\delta}{P_r'(\theta-t)F(t)dt}\right\rvert
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">


Lebesgue-Stieltjes integral is related to bounded increasing function.
The integral has decomposition 
<img src="https://www.zhihu.com/equation?tex=d\mu(t)=f(t)dt+d\sigma(t)" alt="d\mu(t)=f(t)dt+d\sigma(t)" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\in L^1" alt="f\in L^1" class="ee_img tr_noresize" eeimg="1">
.

<img src="https://www.zhihu.com/equation?tex=\int_0^\theta{d\sigma(t)}" alt="\int_0^\theta{d\sigma(t)}" class="ee_img tr_noresize" eeimg="1">
 is a jump function. Thus

<img src="https://www.zhihu.com/equation?tex=F'(\theta)=f(\theta)" alt="F'(\theta)=f(\theta)" class="ee_img tr_noresize" eeimg="1">
 a.e.. Considering 
<img src="https://www.zhihu.com/equation?tex=P(f)" alt="P(f)" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\in L^p" alt="f\in L^p" class="ee_img tr_noresize" eeimg="1">
,

<img src="https://www.zhihu.com/equation?tex=1\leq p\leq\infty" alt="1\leq p\leq\infty" class="ee_img tr_noresize" eeimg="1">
, or even 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">
, the integral 
<img src="https://www.zhihu.com/equation?tex=P(f)" alt="P(f)" class="ee_img tr_noresize" eeimg="1">
 or 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">

is L-S integral. Thus N.T. convergence holds a.e..

By section
[1.1.1](#harmonic function can be written as Poisson integral){reference-type="ref"
reference="harmonic function can be written as Poisson integral"},
Harmonic function with constraints (bounded in some sense) can be
written as Poisson integral 
<img src="https://www.zhihu.com/equation?tex=P(f)" alt="P(f)" class="ee_img tr_noresize" eeimg="1">
 or 
<img src="https://www.zhihu.com/equation?tex=P(\mu)" alt="P(\mu)" class="ee_img tr_noresize" eeimg="1">
 (Corollary 1.10 in book).
Thus the theorem of Fatou holds: *Any function holomorphic and bounded
in D has non-tangential boundary values a.e.*.

The difference between 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=p>1" alt="p>1" class="ee_img tr_noresize" eeimg="1">
 is the starting point of the
theory of Hardy spaces.

### Harmonic function in higher dimension

A continuous function is harmonic in region 
<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
 if and only if it
satisfies mean value property. For mean value property to harmonic, we
need an approximate identity.

You can omit the following remark if you choose not to check the proof
in book.

In converse part, we choose region 
<img src="https://www.zhihu.com/equation?tex=\Omega_\epsilon" alt="\Omega_\epsilon" class="ee_img tr_noresize" eeimg="1">
 is to make integral

<img src="https://www.zhihu.com/equation?tex=\int_{\mathbb{R}^n}{u(x_0+r\sigma-y)\phi_\epsilon(y)dy}" alt="\int_{\mathbb{R}^n}{u(x_0+r\sigma-y)\phi_\epsilon(y)dy}" class="ee_img tr_noresize" eeimg="1">
 and

<img src="https://www.zhihu.com/equation?tex=\int_{\mathbb{R}^n}{u(x_0-y)\phi_\epsilon(y)dy}" alt="\int_{\mathbb{R}^n}{u(x_0-y)\phi_\epsilon(y)dy}" class="ee_img tr_noresize" eeimg="1">
 defined. In other
words, if 
<img src="https://www.zhihu.com/equation?tex=x_0+r\sigma-y" alt="x_0+r\sigma-y" class="ee_img tr_noresize" eeimg="1">
 or 
<img src="https://www.zhihu.com/equation?tex=x_0-y" alt="x_0-y" class="ee_img tr_noresize" eeimg="1">
 out of 
<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
, then

<img src="https://www.zhihu.com/equation?tex=\phi_\epsilon(y)=0" alt="\phi_\epsilon(y)=0" class="ee_img tr_noresize" eeimg="1">
.

A consequence of mean value property is maximum principle. The proof can
be given by topological technic: Assumed 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 attains maximum value m in

<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
. Let 
<img src="https://www.zhihu.com/equation?tex=A=\{x:u(x)=m\}" alt="A=\{x:u(x)=m\}" class="ee_img tr_noresize" eeimg="1">
. Using mean value property, we show every

<img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">
 is interior point of 
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
 is open. However,

<img src="https://www.zhihu.com/equation?tex=\Omega\setminus A=\{x:u(x)<m\}" alt="\Omega\setminus A=\{x:u(x)<m\}" class="ee_img tr_noresize" eeimg="1">
 is open since 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is continuous.

<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
 is connected and 
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
 is not empty. 
<img src="https://www.zhihu.com/equation?tex=\Omega\setminus A" alt="\Omega\setminus A" class="ee_img tr_noresize" eeimg="1">
 is
empty. Thus u is constant.

By maximum principle and minimum principle, we can show 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is unique in

<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
 if 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is harmonic in 
<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is continuous on

<img src="https://www.zhihu.com/equation?tex=\partial\Omega" alt="\partial\Omega" class="ee_img tr_noresize" eeimg="1">
.

We introduce the Poisson kernel

<img src="https://www.zhihu.com/equation?tex=P(x,s)=\frac{1-\left\lvert x\right\rvert^2}{\left\lvert x-s\right\rvert^n}" alt="P(x,s)=\frac{1-\left\lvert x\right\rvert^2}{\left\lvert x-s\right\rvert^n}" class="ee_img tr_noresize" eeimg="1">

for Dirichlet problem in n dimension. The solution is

<img src="https://www.zhihu.com/equation?tex=\frac{1}{\left\lvert\Sigma_{n-1}\right\rvert}\int_{\Sigma_{n-1}}{P(x,s)f(s)ds}" alt="\frac{1}{\left\lvert\Sigma_{n-1}\right\rvert}\int_{\Sigma_{n-1}}{P(x,s)f(s)ds}" class="ee_img tr_noresize" eeimg="1">
.

There is a weaken form of mean value property (or called discrete mean
value property). 
<img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1">
 is harmonic if mean value property is satisfied
only on a sequence of 
<img src="https://www.zhihu.com/equation?tex=r_n\to 0" alt="r_n\to 0" class="ee_img tr_noresize" eeimg="1">
 (Theorem 1.30 in book).

You can omit the following remark if you choose not to check the proof
in book.

The proof here is not well understand. The set

<img src="https://www.zhihu.com/equation?tex=K=\{u(x)-v(x)=m:x\in\overline{B(x_0,R)}\}" alt="K=\{u(x)-v(x)=m:x\in\overline{B(x_0,R)}\}" class="ee_img tr_noresize" eeimg="1">
 is compact in

<img src="https://www.zhihu.com/equation?tex=\overline{B(x_0,R)}" alt="\overline{B(x_0,R)}" class="ee_img tr_noresize" eeimg="1">
 since K is closed in compact set

<img src="https://www.zhihu.com/equation?tex=\overline{B(x_0,R)}" alt="\overline{B(x_0,R)}" class="ee_img tr_noresize" eeimg="1">
. We can use finite open cover to prove K is also
compact in 
<img src="https://www.zhihu.com/equation?tex=B(x_0,R)" alt="B(x_0,R)" class="ee_img tr_noresize" eeimg="1">
. Let 
<img src="https://www.zhihu.com/equation?tex=f: K\to\mathbb{R}" alt="f: K\to\mathbb{R}" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f(x)=d(x,x_0)" alt="f(x)=d(x,x_0)" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 is
continuous function on compact set K thus it attains maximum value of

<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
. Let 
<img src="https://www.zhihu.com/equation?tex=x_1" alt="x_1" class="ee_img tr_noresize" eeimg="1">
 be a point of the maximum value. I just can image that
for sphere 
<img src="https://www.zhihu.com/equation?tex=\partial B(x_1,r)" alt="\partial B(x_1,r)" class="ee_img tr_noresize" eeimg="1">
, only half of the sphere is in K
otherwise 
<img src="https://www.zhihu.com/equation?tex=f(x_1)" alt="f(x_1)" class="ee_img tr_noresize" eeimg="1">
 is not the maximum value. Here 
<img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1">
 need to be small
enough to ensure 
<img src="https://www.zhihu.com/equation?tex=\partial B(x_1,r)\subset B(x_0,R)" alt="\partial B(x_1,r)\subset B(x_0,R)" class="ee_img tr_noresize" eeimg="1">
. But then

<img src="https://www.zhihu.com/equation?tex=u(x_1)-v(x_1)<m" alt="u(x_1)-v(x_1)<m" class="ee_img tr_noresize" eeimg="1">
 if we use integral with 
<img src="https://www.zhihu.com/equation?tex=r_j<r" alt="r_j<r" class="ee_img tr_noresize" eeimg="1">
. Thus it is a
contradiction.

 I don't know how the sequence 
<img src="https://www.zhihu.com/equation?tex=(r_n)" alt="(r_n)" class="ee_img tr_noresize" eeimg="1">
 plays in this proof.

Then we go to the reflection principle and Liouville theorem.

Finally we go to Dirichlet problem on unbounded domain, in particular

<img src="https://www.zhihu.com/equation?tex=\mathbb{R}_+^{n+1}" alt="\mathbb{R}_+^{n+1}" class="ee_img tr_noresize" eeimg="1">
. This problem cannot have a unique solution but can
have a unique bounded solution. And we give Poisson kernel for

<img src="https://www.zhihu.com/equation?tex=\mathbb{R}_+^{n+1}" alt="\mathbb{R}_+^{n+1}" class="ee_img tr_noresize" eeimg="1">
 by Fourier transform method.
