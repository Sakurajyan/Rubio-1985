
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 as a Linear Space
=======================

In this section we look at 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 as a topological vector space. By
considering distance 
<img src="https://www.zhihu.com/equation?tex=d(F,G)=\lVert F-G\rVert_{H^p}" alt="d(F,G)=\lVert F-G\rVert_{H^p}" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=p\geq 1" alt="p\geq 1" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=d(F,G)=\lVert F-G\rVert_{H^p}^p" alt="d(F,G)=\lVert F-G\rVert_{H^p}^p" class="ee_img tr_noresize" eeimg="1">
 for 
<img src="https://www.zhihu.com/equation?tex=p<1" alt="p<1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is a metric space. By
considering mapping 
<img src="https://www.zhihu.com/equation?tex=F(z)\mapsto F(e^{it})" alt="F(z)\mapsto F(e^{it})" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is isometric to
subspace of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
. The main topic in this section is dual of 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
.


6.1 <img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is not Locally convex for 
<img src="https://www.zhihu.com/equation?tex=0<p<1" alt="0<p<1" class="ee_img tr_noresize" eeimg="1">
---------------------------------------

If a space is locally convex, there is a convex neighborhood 
<img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">

contained in ball 
<img src="https://www.zhihu.com/equation?tex=B(0,1)" alt="B(0,1)" class="ee_img tr_noresize" eeimg="1">
. Since 
<img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">
 is a neighborhood, there is a ball
<img src="https://www.zhihu.com/equation?tex=B(0,\epsilon)" alt="B(0,\epsilon)" class="ee_img tr_noresize" eeimg="1">
 contained in 
<img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">
. Thus by contrapositive, If for all
<img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1">
, there is a convex combination of 
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">
 in ball
<img src="https://www.zhihu.com/equation?tex=B(0,\epsilon)" alt="B(0,\epsilon)" class="ee_img tr_noresize" eeimg="1">
 is out of 
<img src="https://www.zhihu.com/equation?tex=B(0,1)" alt="B(0,1)" class="ee_img tr_noresize" eeimg="1">
, then the space is not locally
convex.

It is easy to prove for 
<img src="https://www.zhihu.com/equation?tex=0<p<1" alt="0<p<1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
 is not locally convex by using
triangle wave function. To prove the same fact for 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
, we use
trigonometric polynomials to approximate triangle wave function. And
conclude these polynomials are in ball 
<img src="https://www.zhihu.com/equation?tex=B(0,\epsilon)" alt="B(0,\epsilon)" class="ee_img tr_noresize" eeimg="1">
 and their convex
combination is out of ball 
<img src="https://www.zhihu.com/equation?tex=B(0,1)" alt="B(0,1)" class="ee_img tr_noresize" eeimg="1">
.

Remark. For 
<img src="https://www.zhihu.com/equation?tex=1<p<1" alt="1<p<1" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=(a+b)^p\leq a^p+b^p" alt="(a+b)^p\leq a^p+b^p" class="ee_img tr_noresize" eeimg="1">
 by
<img src="https://www.zhihu.com/equation?tex=(a+b)^p\leq\frac{(2a)^p+(2b)^p}{2}=2^{p-1}a^p+2^{p-1}b^p\leq a^p+b^p" alt="(a+b)^p\leq\frac{(2a)^p+(2b)^p}{2}=2^{p-1}a^p+2^{p-1}b^p\leq a^p+b^p" class="ee_img tr_noresize" eeimg="1">


Given any vector space 
<img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">
 over a field 
<img src="https://www.zhihu.com/equation?tex=\mathbb{F}" alt="\mathbb{F}" class="ee_img tr_noresize" eeimg="1">
, the algebraic dual
space 
<img src="https://www.zhihu.com/equation?tex=V^*" alt="V^*" class="ee_img tr_noresize" eeimg="1">
 is defined as the set of all linear functionals
<img src="https://www.zhihu.com/equation?tex=\phi:V\to \mathbb{F}" alt="\phi:V\to \mathbb{F}" class="ee_img tr_noresize" eeimg="1">
.

When dealing with topological vector spaces, one is typically only
interested in the continuous linear functionals 
<img src="https://www.zhihu.com/equation?tex=\phi:V\to \mathbb{F}" alt="\phi:V\to \mathbb{F}" class="ee_img tr_noresize" eeimg="1">
.
This gives rise to the notion of the \"continuous dual space\" or
\"topological dual\" which is a linear subspace of the algebraic dual
space. For any finite-dimensional normed vector space or topological
vector space, such as Euclidean n-space, the continuous dual and the
algebraic dual coincide. This is however false for any
infinite-dimensional normed space.

Being non locally convex has a great deal of continuous linear
functionals. The topological dual or continuous linear functional on
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is zero. First we prove the only convex neighborhood of 0 is the
whole space. By using the proof of non locally convex reversely, Given a
convex and open set 
<img src="https://www.zhihu.com/equation?tex=V\subset H^p" alt="V\subset H^p" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=0\in V" alt="0\in V" class="ee_img tr_noresize" eeimg="1">
, we can show for any

<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, there is a combination 
<img src="https://www.zhihu.com/equation?tex=\sum_j{\lambda_jF_j}=F" alt="\sum_j{\lambda_jF_j}=F" class="ee_img tr_noresize" eeimg="1">
, s.t.

<img src="https://www.zhihu.com/equation?tex=\sum_j{\lambda_j}=1" alt="\sum_j{\lambda_j}=1" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=F_j\in V" alt="F_j\in V" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=F\in V" alt="F\in V" class="ee_img tr_noresize" eeimg="1">
 by 
<img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">
 convex and we
have 
<img src="https://www.zhihu.com/equation?tex=V=H^p" alt="V=H^p" class="ee_img tr_noresize" eeimg="1">
.

Then we consider the continuous linear functionals on 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
. Assume
<img src="https://www.zhihu.com/equation?tex=\phi:H^p\to \mathbb{F}" alt="\phi:H^p\to \mathbb{F}" class="ee_img tr_noresize" eeimg="1">
 is a continuous linear functional. Let

<img src="https://www.zhihu.com/equation?tex=\mathscr{B}" alt="\mathscr{B}" class="ee_img tr_noresize" eeimg="1">
 be a locally convex base for 
<img src="https://www.zhihu.com/equation?tex=\mathbb{F}" alt="\mathbb{F}" class="ee_img tr_noresize" eeimg="1">
. For any

<img src="https://www.zhihu.com/equation?tex=W\in \mathscr{B}" alt="W\in \mathscr{B}" class="ee_img tr_noresize" eeimg="1">
, we have 
<img src="https://www.zhihu.com/equation?tex=\phi^{-1}(W)" alt="\phi^{-1}(W)" class="ee_img tr_noresize" eeimg="1">
 is convex and open hence is

<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=\phi(H^p)\subset W" alt="\phi(H^p)\subset W" class="ee_img tr_noresize" eeimg="1">
 for all 
<img src="https://www.zhihu.com/equation?tex=W\in \mathscr{B}" alt="W\in \mathscr{B}" class="ee_img tr_noresize" eeimg="1">
. We conclude that

<img src="https://www.zhihu.com/equation?tex=\phi(F)=0" alt="\phi(F)=0" class="ee_img tr_noresize" eeimg="1">
 for all 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
. Thus all continuous linear functionals
on 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 are zero (This part is following the section 1.47 in Rudin,
1991).

Using inequality:

<img src="https://www.zhihu.com/equation?tex=\left\lvert F(z)\right\rvert\leq\frac{1}{(1-\left\lvert z\right\rvert)^{\frac{1}{p}}}\lVert F\rVert_{H^p}\\" alt="\left\lvert F(z)\right\rvert\leq\frac{1}{(1-\left\lvert z\right\rvert)^{\frac{1}{p}}}\lVert F\rVert_{H^p}\\" class="ee_img tr_noresize" eeimg="1">

for 
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=0<p<\infty" alt="0<p<\infty" class="ee_img tr_noresize" eeimg="1">
, we can prove 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is a complete
space. Thus 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is closed subspace of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
 in isometry sense.

Remark. I don't know why 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is the minimal closed subspace which contains
<img src="https://www.zhihu.com/equation?tex=\{e^{ijt}:j=0,1,\cdots\}" alt="\{e^{ijt}:j=0,1,\cdots\}" class="ee_img tr_noresize" eeimg="1">
. The author give the reason as follows: If
<img src="https://www.zhihu.com/equation?tex=F(z)=\sum_0^\infty{a_jz^j}" alt="F(z)=\sum_0^\infty{a_jz^j}" class="ee_img tr_noresize" eeimg="1">
 is in 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=F(re^{it})\to F(e^{it})" alt="F(re^{it})\to F(e^{it})" class="ee_img tr_noresize" eeimg="1">
 in
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
 as 
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1">
. And for 
<img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1">
 fixed,

<img src="https://www.zhihu.com/equation?tex=\sum_0^n{a_jr^je^{ijt}}\to F(re^{it})" alt="\sum_0^n{a_jr^je^{ijt}}\to F(re^{it})" class="ee_img tr_noresize" eeimg="1">
 uniformly as 
<img src="https://www.zhihu.com/equation?tex=n\to\infty" alt="n\to\infty" class="ee_img tr_noresize" eeimg="1">
.

6.2 Dual of 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">

-------------

In subsection [1.1](#sec: locally convex){reference-type="ref"
reference="sec: locally convex"}, we show for 
<img src="https://www.zhihu.com/equation?tex=0<p<1" alt="0<p<1" class="ee_img tr_noresize" eeimg="1">
, the dual of 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
is zero. We investigate case 
<img src="https://www.zhihu.com/equation?tex=1\leq p\leq \infty" alt="1\leq p\leq \infty" class="ee_img tr_noresize" eeimg="1">
 in this subsection.

In section 5, we show for 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=H^p=\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}" alt="H^p=\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^p}, c\in\mathbb{R}\}" class="ee_img tr_noresize" eeimg="1">
and for 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=H^1=\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^1},\tilde{f}\in{L^1}, c\in\mathbb{R}\}" alt="H^1=\{f+i\tilde{f}+i c:f\in\operatorname{Re}{L^1},\tilde{f}\in{L^1}, c\in\mathbb{R}\}" class="ee_img tr_noresize" eeimg="1">
.
Thus 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 is a proper subspace of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
.

By dual of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
, any continuous linear functional 
<img src="https://www.zhihu.com/equation?tex=\phi(g)" alt="\phi(g)" class="ee_img tr_noresize" eeimg="1">
 for
<img src="https://www.zhihu.com/equation?tex=g\in L^p" alt="g\in L^p" class="ee_img tr_noresize" eeimg="1">
 can be written as 
<img src="https://www.zhihu.com/equation?tex=\phi_f(g)=\int{gf}" alt="\phi_f(g)=\int{gf}" class="ee_img tr_noresize" eeimg="1">
 with 
<img src="https://www.zhihu.com/equation?tex=f\in L^{p'}" alt="f\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
. We
consider the restriction of 
<img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1">
 to 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
. This is the continuous
linear functional
<img src="https://www.zhihu.com/equation?tex=\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}" alt="\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}" class="ee_img tr_noresize" eeimg="1">
 on 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
.
If we consider this mapping is as from 
<img src="https://www.zhihu.com/equation?tex=L^{p'}\to (H^p)^*" alt="L^{p'}\to (H^p)^*" class="ee_img tr_noresize" eeimg="1">
, we have:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
    \lVert\phi_f\rVert & =\sup_{\lVert f\rVert_{p'}=1}\frac{\lVert\phi_f\rVert_{(H^p)^*}}{\lVert f\rVert_{p'}}                                                                                                       \\
                  & =\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\left\lvert\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}\right\rvert}{\lVert F\rVert_{H^p}}                                               \\
                  & \leq\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\frac{1}{2\pi}(\int_{-\pi}^{\pi}{\left\lvert F(e^{it})\right\rvert^p d t})^p(\int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^p d t)^{p'}}{\lVert F\rVert_{H^p}} \\
                  & =\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\lVert F\rVert_{H^p}\lVert f\rVert_{p'}}{\lVert F\rVert_{H^p}}                                                                           \\
                  & =1\end{aligned}\\" alt="\begin{aligned}
    \lVert\phi_f\rVert & =\sup_{\lVert f\rVert_{p'}=1}\frac{\lVert\phi_f\rVert_{(H^p)^*}}{\lVert f\rVert_{p'}}                                                                                                       \\
                  & =\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\left\lvert\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}\right\rvert}{\lVert F\rVert_{H^p}}                                               \\
                  & \leq\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\frac{1}{2\pi}(\int_{-\pi}^{\pi}{\left\lvert F(e^{it})\right\rvert^p d t})^p(\int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^p d t)^{p'}}{\lVert F\rVert_{H^p}} \\
                  & =\sup_{\lVert f\rVert_{p'}=1}\sup_{\lVert F\rVert_{H^p}=1}\frac{\lVert F\rVert_{H^p}\lVert f\rVert_{p'}}{\lVert F\rVert_{H^p}}                                                                           \\
                  & =1\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 
 Thus the mapping 
<img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1">
 from
<img src="https://www.zhihu.com/equation?tex=L^{p'}\to (H^p)^*" alt="L^{p'}\to (H^p)^*" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=f\mapsto\phi_f" alt="f\mapsto\phi_f" class="ee_img tr_noresize" eeimg="1">
 is a continuous linear mapping.
The Hahn-Banach theorem tells us that every 
<img src="https://www.zhihu.com/equation?tex=\Lambda\in (H^p)^*" alt="\Lambda\in (H^p)^*" class="ee_img tr_noresize" eeimg="1">
 is of
the form 
<img src="https://www.zhihu.com/equation?tex=\Lambda=\phi_f" alt="\Lambda=\phi_f" class="ee_img tr_noresize" eeimg="1">
 for some 
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
 with
<img src="https://www.zhihu.com/equation?tex=\lVert f\rVert_{p'}\leq\lVert\Lambda\rVert" alt="\lVert f\rVert_{p'}\leq\lVert\Lambda\rVert" class="ee_img tr_noresize" eeimg="1">
. More precisely, any
continuous linear functional 
<img src="https://www.zhihu.com/equation?tex=\Lambda\in (H^p)^*" alt="\Lambda\in (H^p)^*" class="ee_img tr_noresize" eeimg="1">
 can be extended to all
of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
. Thus we get 
<img src="https://www.zhihu.com/equation?tex=f\in L^{p'}" alt="f\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
 with
<img src="https://www.zhihu.com/equation?tex=\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}" alt="\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}" class="ee_img tr_noresize" eeimg="1">
 restricted
back to 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
.

The kernel of mapping 
<img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1">
 is 
<img src="https://www.zhihu.com/equation?tex=f\in  L^{p'}" alt="f\in  L^{p'}" class="ee_img tr_noresize" eeimg="1">
 for which 
<img src="https://www.zhihu.com/equation?tex=\phi_f=0" alt="\phi_f=0" class="ee_img tr_noresize" eeimg="1">
.
This is equivalent
<img src="https://www.zhihu.com/equation?tex=\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}=0" alt="\phi_f(F)=\frac{1}{2\pi}\int_{-\pi}^{\pi}{F(e^{it})f(t)d t}=0" class="ee_img tr_noresize" eeimg="1">
 for all
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, clearly,

<img src="https://www.zhihu.com/equation?tex=\ker{\phi}=\{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=0,1,\cdots\}\\" alt="\ker{\phi}=\{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=0,1,\cdots\}\\" class="ee_img tr_noresize" eeimg="1">


<img src="https://www.zhihu.com/equation?tex=\hat{f}(j)" alt="\hat{f}(j)" class="ee_img tr_noresize" eeimg="1">
 is zero for non-positive frequency 
<img src="https://www.zhihu.com/equation?tex=j" alt="j" class="ee_img tr_noresize" eeimg="1">
 is equivalent to

<img src="https://www.zhihu.com/equation?tex=f\in H^p" alt="f\in H^p" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=\hat{f}(0)=0" alt="\hat{f}(0)=0" class="ee_img tr_noresize" eeimg="1">
. Thus 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
      & \{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=0,1,\cdots\} \\
    = & \{f\in H^{p'}: \int_{-\pi}^{\pi}{f(t)d t}=0\}\end{aligned}\\" alt="\begin{aligned}
      & \{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=0,1,\cdots\} \\
    = & \{f\in H^{p'}: \int_{-\pi}^{\pi}{f(t)d t}=0\}\end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 We
denote this space by 
<img src="https://www.zhihu.com/equation?tex=H^{p'}(0)" alt="H^{p'}(0)" class="ee_img tr_noresize" eeimg="1">
 and obtain an isometry

<img src="https://www.zhihu.com/equation?tex=\label{dual of Hp}
    L^{p'}/ H^{p'}(0)\cong (H^p)^*\\" alt="\label{dual of Hp}
    L^{p'}/ H^{p'}(0)\cong (H^p)^*\\" class="ee_img tr_noresize" eeimg="1">
 
 Now we consider the continuous
linear functionals on 
<img src="https://www.zhihu.com/equation?tex=H^{p}(0)" alt="H^{p}(0)" class="ee_img tr_noresize" eeimg="1">
, We consider the kernel of mapping
<img src="https://www.zhihu.com/equation?tex=L^{p'}\to (H^{p}(0))^*" alt="L^{p'}\to (H^{p}(0))^*" class="ee_img tr_noresize" eeimg="1">
:

<img src="https://www.zhihu.com/equation?tex=\{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=1,2,\cdots\}=H^{p'}\\" alt="\{f\in L^{p'}: \hat{f}(-j)=\int_{-\pi}^{\pi}{e^{i j t}f(t)\frac{dt}{2\pi}}=0, j=1,2,\cdots\}=H^{p'}\\" class="ee_img tr_noresize" eeimg="1">

Thus we obtain an isometry 
<img src="https://www.zhihu.com/equation?tex=\label{dual of Hp(0)}
    (H^{p'}(0))^*\cong L^{p'}/ H^{p'}\\" alt="\label{dual of Hp(0)}
    (H^{p'}(0))^*\cong L^{p'}/ H^{p'}\\" class="ee_img tr_noresize" eeimg="1">


Remark (Topological complement) Two vector subspace 
<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=Y" alt="Y" class="ee_img tr_noresize" eeimg="1">
 are algebraic complement of each other
if 
<img src="https://www.zhihu.com/equation?tex=X+Y=E" alt="X+Y=E" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=X\cap Y=\{0\}" alt="X\cap Y=\{0\}" class="ee_img tr_noresize" eeimg="1">
. We can write 
<img src="https://www.zhihu.com/equation?tex=X\oplus Y=E" alt="X\oplus Y=E" class="ee_img tr_noresize" eeimg="1">
.

Two vector subspace 
<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=Y" alt="Y" class="ee_img tr_noresize" eeimg="1">
 are topological complement of each other
if they are algebraic complement of each other and 
<img src="https://www.zhihu.com/equation?tex=P_X" alt="P_X" class="ee_img tr_noresize" eeimg="1">
 (Projection
from 
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
 to 
<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
) is continuous. If E is Banach space, another equivalent
condition for topological complement is they are algebraic complement of
each other and 
<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=Y" alt="Y" class="ee_img tr_noresize" eeimg="1">
 are closed.


<img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
 and 
<img src="https://www.zhihu.com/equation?tex=Y" alt="Y" class="ee_img tr_noresize" eeimg="1">
 are topological complement of each other means 
<img src="https://www.zhihu.com/equation?tex=E=X\oplus Y" alt="E=X\oplus Y" class="ee_img tr_noresize" eeimg="1">
and 
<img src="https://www.zhihu.com/equation?tex=E\cong X\oplus Y" alt="E\cong X\oplus Y" class="ee_img tr_noresize" eeimg="1">
 in isometry sense.

For 
<img src="https://www.zhihu.com/equation?tex=1<p<\infty" alt="1<p<\infty" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=H^{p'}(0)" alt="H^{p'}(0)" class="ee_img tr_noresize" eeimg="1">
 has a topological complement in 
<img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">
.
Let us see how to construct this. Consider 
<img src="https://www.zhihu.com/equation?tex=f\in L^{p'}" alt="f\in L^{p'}" class="ee_img tr_noresize" eeimg="1">
,
<img src="https://www.zhihu.com/equation?tex=f=\sum_{-\infty}^{\infty}{a_je^{ijt}}" alt="f=\sum_{-\infty}^{\infty}{a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1">
. Set
<img src="https://www.zhihu.com/equation?tex=A(f)=\frac{1}{2}(f+\tilde{f}-\hat{f}(0))=\sum_{j>0}{a_je^{i j t}}\\" alt="A(f)=\frac{1}{2}(f+\tilde{f}-\hat{f}(0))=\sum_{j>0}{a_je^{i j t}}\\" class="ee_img tr_noresize" eeimg="1">

Then 
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
 is the projection of 
<img src="https://www.zhihu.com/equation?tex=L^{p'}" alt="L^{p'}" class="ee_img tr_noresize" eeimg="1">
 onto 
<img src="https://www.zhihu.com/equation?tex=H^{p'}(0)" alt="H^{p'}(0)" class="ee_img tr_noresize" eeimg="1">
.
<img src="https://www.zhihu.com/equation?tex=f-A(f)=\sum_{j\leq 0}{a_je^{i j t}}=\sum_{j\geq 0}{a_{-j}e^{-i j t}}" alt="f-A(f)=\sum_{j\leq 0}{a_je^{i j t}}=\sum_{j\geq 0}{a_{-j}e^{-i j t}}" class="ee_img tr_noresize" eeimg="1">
.
If we write 
<img src="https://www.zhihu.com/equation?tex=F(z)=\sum_{j\geq 0}{a_{-j}z^j}" alt="F(z)=\sum_{j\geq 0}{a_{-j}z^j}" class="ee_img tr_noresize" eeimg="1">
, we have 
<img src="https://www.zhihu.com/equation?tex=F\in H^{p'}" alt="F\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=f(t)=Af(t)+F(e^{-it})" alt="f(t)=Af(t)+F(e^{-it})" class="ee_img tr_noresize" eeimg="1">
. If we write
<img src="https://www.zhihu.com/equation?tex=G(z)=\sum_{j\geq 0}{\overline{a_{-j}}z^j}" alt="G(z)=\sum_{j\geq 0}{\overline{a_{-j}}z^j}" class="ee_img tr_noresize" eeimg="1">
.
<img src="https://www.zhihu.com/equation?tex=G(e^{it})=F(e^{-it})\in H^{p'}" alt="G(e^{it})=F(e^{-it})\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
. Thus we have:

<img src="https://www.zhihu.com/equation?tex=f(t)=A f(t)+\overline{G(e^{it})}\\" alt="f(t)=A f(t)+\overline{G(e^{it})}\\" class="ee_img tr_noresize" eeimg="1">
 Using notation
<img src="https://www.zhihu.com/equation?tex=\overline{H^{p'}}={\overline{h(t)}:h\in H^{p'}}" alt="\overline{H^{p'}}={\overline{h(t)}:h\in H^{p'}}" class="ee_img tr_noresize" eeimg="1">
 and
<img src="https://www.zhihu.com/equation?tex=(H^{p'})^-={h(-t):h\in H^{p'}}" alt="(H^{p'})^-={h(-t):h\in H^{p'}}" class="ee_img tr_noresize" eeimg="1">
. We have:

<img src="https://www.zhihu.com/equation?tex=L^{p'}=H^{p'}(0)\oplus\overline{H^{p'}}=H^{p'}(0)\oplus (H^{p'})^-\\" alt="L^{p'}=H^{p'}(0)\oplus\overline{H^{p'}}=H^{p'}(0)\oplus (H^{p'})^-\\" class="ee_img tr_noresize" eeimg="1">

If we consider

<img src="https://www.zhihu.com/equation?tex=B(f)=\frac{1}{2}(f+\tilde{f}+\hat{f}(0))=\sum_{j\geq 0}{a_je^{i j t}}" alt="B(f)=\frac{1}{2}(f+\tilde{f}+\hat{f}(0))=\sum_{j\geq 0}{a_je^{i j t}}" class="ee_img tr_noresize" eeimg="1">
.
We have:

<img src="https://www.zhihu.com/equation?tex=L^{p'}=H^{p'}\oplus\overline{H^{p'}(0)}=H^{p'}\oplus (H^{p'}(0))^-\\" alt="L^{p'}=H^{p'}\oplus\overline{H^{p'}(0)}=H^{p'}\oplus (H^{p'}(0))^-\\" class="ee_img tr_noresize" eeimg="1">

By topological direct sum we have topological isomorphisms:

<img src="https://www.zhihu.com/equation?tex=L^{p'}/ H^{p'}(0)\cong H^{p'}\\" alt="L^{p'}/ H^{p'}(0)\cong H^{p'}\\" class="ee_img tr_noresize" eeimg="1">
 
<img src="https://www.zhihu.com/equation?tex=L^{p'}/H^{p'}\cong H^{p'}(0)\\" alt="L^{p'}/H^{p'}\cong H^{p'}(0)\\" class="ee_img tr_noresize" eeimg="1">
 By
equation (1) and
(2), we derive a conclusion for 
<img src="https://www.zhihu.com/equation?tex=H^p" alt="H^p" class="ee_img tr_noresize" eeimg="1">
 similar
with dual of 
<img src="https://www.zhihu.com/equation?tex=L^p" alt="L^p" class="ee_img tr_noresize" eeimg="1">
. 
<img src="https://www.zhihu.com/equation?tex=(H^{p})^*\cong H^{p'}\\" alt="(H^{p})^*\cong H^{p'}\\" class="ee_img tr_noresize" eeimg="1">
 
 with the pairing
<img src="https://www.zhihu.com/equation?tex=<G,F>=\frac{1}{2\pi}\int_{-\pi}^{\pi}F(e^{it})G(e^{-it})d t\\" alt="<G,F>=\frac{1}{2\pi}\int_{-\pi}^{\pi}F(e^{it})G(e^{-it})d t\\" class="ee_img tr_noresize" eeimg="1">

where
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=G\in H^{p'}" alt="G\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
, or

<img src="https://www.zhihu.com/equation?tex=<G,F>=\frac{1}{2\pi}\int_{-\pi}^{\pi}F(e^{it})\overline G(e^{it})d t\\" alt="<G,F>=\frac{1}{2\pi}\int_{-\pi}^{\pi}F(e^{it})\overline G(e^{it})d t\\" class="ee_img tr_noresize" eeimg="1">

where
<img src="https://www.zhihu.com/equation?tex=F\in H^p" alt="F\in H^p" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=G\in H^{p'}" alt="G\in H^{p'}" class="ee_img tr_noresize" eeimg="1">
. Besides, we also have

<img src="https://www.zhihu.com/equation?tex=(H^{p}(0))^*\cong H^{p'}(0)" alt="(H^{p}(0))^*\cong H^{p'}(0)" class="ee_img tr_noresize" eeimg="1">
. We can not use same argument for 
<img src="https://www.zhihu.com/equation?tex=p=1" alt="p=1" class="ee_img tr_noresize" eeimg="1">

case since for 
<img src="https://www.zhihu.com/equation?tex=f\in L^{1'}=L^\infty" alt="f\in L^{1'}=L^\infty" class="ee_img tr_noresize" eeimg="1">
, 
<img src="https://www.zhihu.com/equation?tex=\hat{f}" alt="\hat{f}" class="ee_img tr_noresize" eeimg="1">
 no longer in
<img src="https://www.zhihu.com/equation?tex=L^\infty" alt="L^\infty" class="ee_img tr_noresize" eeimg="1">
. We will study 
<img src="https://www.zhihu.com/equation?tex=(H^1)^*" alt="(H^1)^*" class="ee_img tr_noresize" eeimg="1">
 in section 9. Now we only have

<img src="https://www.zhihu.com/equation?tex=(H^1)^*\cong L^{\infty}/ H^{\infty}(0)" alt="(H^1)^*\cong L^{\infty}/ H^{\infty}(0)" class="ee_img tr_noresize" eeimg="1">
 by equation (1).
