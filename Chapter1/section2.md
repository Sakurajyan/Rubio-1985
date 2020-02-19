Subharmonic Functions
=====================

This section is about a new concept: subharmonic function. Subharmonic
function can be considered as a generalization of harmonic function, as
it preserves some important property of harmonic function such as
maximum principle. On the other hand, we will see why we call it \"sub\"
harmonic: subharmonic function can be controlled by harmonic function.
Also, by some operations like composition and taking absolute value,
subharmonic function can still be subharmonic, but harmonic function can
not. Finally we will begin our study of zeroes of holomorphic function.

Now we give the definition of subharmonic function.

A subharmonic function on an open set $\Omega\subset\mathbb{R}^n$ is a
function v defined on $\Omega$, with values $-\infty\leq v(x)<\infty$
and satisfying the following two conditions:

1.  v is upper semicontinuous in $\Omega$.

2.  For every $x_0\in\Omega$, there is a ball
    $B(x_0,r(x_0))\subset\Omega$, $r(x_0)>0$, such that for every r with
    $0<r<r(x_0)$
    $$v(x_0)\leq\frac{1}{\abs{\Sigma_{n-1}}}\int_{\Sigma_{n-1}}{v(x_0+r\sigma) d\sigma}\label{local submean property}$$

Upper semicontinuous
--------------------

There is two equivalence definition of $v$ being upper semicontinuous in
$\Omega$:

1.  For every $t\in\mathbb{R}$, the set $\{x\in\Omega: v(x)<t\}$ is
    open.

2.  For every $x_0\in\Omega$:
    $$\limsup_{x\to x_0~in~\Omega}{v(x)\leq v(x_0)}\label{upper semicontinuous}$$
    This is equivalent to that for every $y>f(x_{0})$, there exists a
    neighborhood $U$ of $x_{0}$ such that $f(x)<y$ for all $x \in U$.

 \
We prove by contradiction, Suppose that $\limsup{v(x)>v(x_0)}$, we can
find $x_k$, $v(x_0)<v(x_k)<\limsup{v(x)}$. Since
$v^{-1}([-\infty,v(x_k))$ is open and $v(x_0)<v(x_k)$,
$v(x_0)\in v^{-1}([-\infty,v(x_k))$. Thus there is a neighborhood
$U\in\mathscr{N}(x_0)$, $U\subset v^{-1}([-\infty,v(x_k))$. Now we can
find another $x_n\in U$ s.t. $v(x_k)<v(x_n)<\limsup{v(x)}$.
$v(x_n)>v(x_k)$ means $v(x_n)\notin v^{-1}([-\infty,v(x_k))$,
contradicts to $v(x_n)\in U\subset v^{-1}([-\infty,v(x_k))$.

We prove the converse by contradiction. Suppose there is a number
$t_0\in\mathbb{R}$, $v^{-1}([-\infty,t_0))$ is not open. So there is
$x_0\in v^{-1}([-\infty,t_0))$, such that
$\forall U_k\in\mathscr{N}(x_0)$, there is $x_k\in U_k$,
$x_k\notin v^{-1}([-\infty,t_0))$, which is equivalent to
$v(x_k)\geq t$. This contradicts to $\limsup{v(x_k)}\leq v(x_0)<t_0$.

If $v$ is subharmonic, inequality
[\[local submean property\]](#local submean property){reference-type="eqref"
reference="local submean property"} implies another direction of
inequality
[\[upper semicontinuous\]](#upper semicontinuous){reference-type="eqref"
reference="upper semicontinuous"}. Thus we actually have equality in
[\[upper semicontinuous\]](#upper semicontinuous){reference-type="eqref"
reference="upper semicontinuous"}.

An important and frequently used tool is following characterization of
upper simicontinuity.

[\[characterization of semicontinuous\]]{#characterization of semicontinuous
label="characterization of semicontinuous"} $v$ is upper semicontinuous
in $\Omega$ if and only if for every compact $K\subset\Omega$, $v$ is
the limit over $K$ of a decreasing sequence of continuous function.

This proposition is important tool in proof of some following theorems.

The converse part, by using partition of the unity, we construct a
sequence of decreasing function $(u_k)$. We need to prove $v$ is the
limit of $(u_k)$.

For any $x_0\in K$, there is a sequence of balls
$(B(x_{n,i},\epsilon_n))$, $\epsilon_n\to 0$ s.t.
$x_0\in B(x_{n,i},\epsilon_n)$ for all $n$. For each $n$,
$B(x_{n,i},\epsilon_n)$ is in finite open cover
$(B(x_{n,i},\epsilon_n))_i$ of $K$. Since
$m_{n,i}=\sup_{B(x_{n,i},\epsilon_n)}{v}$, $u_n(x_0)\geq v(x_0)$ for all
$n$. By definition of upper semicontinuous, for any $y>v(x_0)$, there is
a neighborhood $U\in \mathscr{N}(x_0)$, $v(x)<y$ for all $x\in U$. Let
$B(x_{n,i},\epsilon_n)\subset U$, $m_{n,i}<y$. Thus $u_n(x_0)<y$ for all
large enough $n$. Since $y$ is any number larger than $v(x_0)$,
$\limsup{u(x)}\leq v(x_0)$. This shows $u(x_0)=v(x_0)$.

Property of subharmonic function
--------------------------------

First, subharmonic function satisfies maximum principle.

Like proof of maximum principle for harmonic function, but we need to
take care of semicontinuous. Assume $v(x_0)=M$, the maximum value.
Choose $r$ to satisfy inequality
[\[local submean property\]](#local submean property){reference-type="eqref"
reference="local submean property"}. If for some
$x\in \partial B(x_0,r)$, $v(x)=m<M$, by semicontinuous,
$\limsup{v(x_k)}\leq v(x)<m+\epsilon<M$. Thus there is a neighborhood
$U\in\mathscr{N}(x)$, $\sup_{x_k\in U}{v(x_k)}<M$. Then
$\frac{1}{\abs{\Sigma_{n-1}}}\int_{\Sigma_{n-1}}{v(x_0+r\sigma) d\sigma}<M=v(x_0)$.
This contradicts to inequality
[\[local submean property\]](#local submean property){reference-type="eqref"
reference="local submean property"}. Then the following is same as proof
for maximum principle for harmonic function.

The best reason why we use name 'subharmonic' is following: $v$ is
subharmonic function if and only if when $v$ less or equal to a harmonic
function $u$ on boundary of region, $v\leq u$ in entire region. We
remind the reader that proposition
[\[characterization of semicontinuous\]](#characterization of semicontinuous){reference-type="ref"
reference="characterization of semicontinuous"} appears as an important
step in proof.

There are two examples of using proposition
[\[characterization of semicontinuous\]](#characterization of semicontinuous){reference-type="ref"
reference="characterization of semicontinuous"} to detail with
subharmonic function $v$. One is if $v$ is not identically equal to
$-\infty$, then
$$\frac{1}{\abs{\Sigma_{n-1}}}\int_{\Sigma_{n-1}}{v(x_0+r\sigma) d\sigma}>-\infty$$
for every $\overline{B(x_0,r)}\subset\Omega$. In proof of this statement
we also use Poisson representation of harmonic function and little
topological trick. Another example is $$\label{equation m(r)}
    m(r)=\frac{1}{\abs{\Sigma_{n-1}}}\int_{\Sigma_{n-1}}{v(r\sigma) d\sigma}$$
is an increasing function.

There is another necessary and sufficient condition for $v$ to be
harmonic using Laplace operator. It says $v$ is subharmonic if and only
if $\Delta v\geq 0$.

Author says we need to show that
$v(x_0)\leq\frac{1}{\abs{\Sigma_{n-1}}}\int_{\Sigma_{n-1}}{v(x_0+r\sigma) d\sigma}$.
But I think this is obvious since we consider $x_0$ which $v(x_0)=0$ and
$v(x)\geq 0$ on $\Omega$. And this inequality is not used in the
following part of proof.

Estimation for zeroes of holomorphic function
---------------------------------------------

We first state that if $v$ is subharmonic, $\phi$ is increasing and
convex function. Then $\phi\circ v$ is also subharmonic. This is useful
when we need to connect holomorphic function with subharmonic function.

Now here comes our first theorem about zero points of holomorphic:
Jensen's formula.

Let F be holomorphic in $D(0,R)$ and suppose that $F(0)\neq 0$. Let
$0<r<R$ and call $z_1,z_2,\cdots,z_n$ the zeroes of $F$ in
$\overline{D(0,r)}$ listed according to their multiplicities. Then:
$$\log{\abs{F(0)}}+\sum_{j=1}^{n}{\log{\frac{r}{\abs{z_j}}}}=\frac{1}{\pi}\int_{-\pi}^{\pi}{\log{\abs{F(re^{it})}}d t}.$$

The proof in book need a lemma:
$\int_{-\pi}^{\pi}{\log{\abs{1-e^{it}}}d t}=0$. You can also refer
section 1 in Chapter 6 of Stein's *Complex Analysis*. The proof there is
very different to the one in this book.

There is an inequality: for $\abs{t}<\frac{\pi}{3}$,
$\log{\frac{1}{\abs{\sin{t}}}}\leq \frac{C_\alpha}{\abs{t}^\alpha}$. I
can prove it using elementary calculus, but I think it is an easy
observation.

To continue our explorer of zeroes of holomorphic function, we show some
connection between holomorphic function and subharmonic function. More
precisely, If $F$ is holomorphic, not identically 0, then
$\log{\abs{F(z)}}$, $\log{^+\abs{F(z)}}=\max{(\log{\abs{F(z)}},0)}$ and
$\abs{F(z)}^a$ for any $0<a<\infty$, are all subharmonic. Then we give
definition of Hardy space on $D$. We define for $f\in H(D)$ ($F$ is
holomorphic in $D$) :

-   $m_0(F,r)=\exp{(\frac{1}{2\pi}\int_{-\pi}^\pi{\log{^+\abs{F(re^{it})}}d t})}$

-   $m_p(F,r)=(\frac{1}{2\pi}\int_{-\pi}^\pi{\abs{F(re^{it})}^p d t})^\frac{1}{p}$

-   $m_\infty(F,r)=\sup_t{\abs{F(re^{it})}}$

This function is an increasing function of $r$ in $[0,1)$ (Hardy convex
theorem), see equation
[\[equation m(r)\]](#equation m(r)){reference-type="eqref"
reference="equation m(r)"} for case $0\leq p<\infty$. $m_\infty(F,r)$ is
also an increasing function but it uses a different method (Hadamard
three-circle theorem).

Now we define Hardy space $H^p$:

For $0<p\leq\infty$, we define $H^p(D)$:
$$H^p(D)=\{F\in H(D):\norm{F}_{H^p}=\sup_{0\leq r<1}{m_p(F,r)<\infty}\}$$
For $p=0$, we have the Nevanlinna class $N$, defined by:
$$N=\{F\in H(D):\sup_{0\leq r<1}{m_0(F,r)<\infty}\}$$ If $0<p<q<\infty$,
we have $H^\infty\subset H^q\subset H^p\subset N$

The first two inclusions are as the same as the inclusion for $L^p$, the
last inclusion is by:
$$(m_0(r))^p=\exp{(p\int_{-\pi}^{\pi}{\log{^+\abs{F}}\frac{dt}{2\pi}})}\leq\int_{-\pi}^{\pi}{\exp{(p\log{^+\abs{F}})\frac{dt}{2\pi}}}$$
Notice that:
$$\int_{-\pi}^{\pi}{\exp{(p\log{^+\abs{F}})\frac{dt}{2\pi}}}=\int_{\substack{t\in [-\pi,\pi]\\ \abs{F}> 1}}{\abs{F}^p \frac{dt}{2\pi}}+\int_{\substack{t\in [-\pi,\pi]\\ \abs{F}\leq 1}}{1 \frac{dt}{2\pi}}$$
Thus: $$(m_0(r))^p\leq\int{\abs{F}^p\frac{dt}{2\pi}}+1$$

There left three theorems in this section. I interpret it shortly and
informally. First one is for $F\in N$, the zeroes $(z_j)$ of F cannot be
too far from the boundary, or $\sum_j{(1-\abs{z_j})<\infty}$. The second
one is that if $\sum_j{(1-\abs{z_j})<\infty}$ holds, the \"Blaschke
product\"
$$B(z)=z^k\prod_{j=1}^\infty{\frac{z_j-z}{1-z\bar{z_j}}\frac{\abs{z_j}}{z_j}}$$
converges uniformly on each compact subset to a function $H^\infty$ and
they have the same zeroes.

If $f$ is holomorphic in an open disc that vanishes on a sequence of
distinct points with a limit point in the disc. Then f is identically 0
(Theorem 4.8 in chapter 2. Stein's Complex Analysis). However in
Blaschke product case, there can be infinitely zeroes, since it can have
limit points on boundary. Thus $B(z)$ can be not identically 0. However,
for any $r<1$, $B(z)$ can only have finite zeroes in
$\overline{D(0,r)}$.

Here is a convention. If for some function $F$ in $D$, the
non-tangential boundary value of F is known to exist at $e^{it}$, we
shall denote it by $F(e^{it})$.

The third theorem is the Blaschke product has properties:
$\abs{B(e^{it})}=1$ for a.e. $t$ and
$$\lim_{r\to 1}{\frac{1}{2\pi}\int_{-\pi}^\pi{\log{\abs{B(re^{it})}}d t}}=0.$$

If $F\in H^p$ with $p\geq 1$, which means $F$ is holomorphic $F$ and can
be write as Poisson (or Poisson-Stieltjes) integral. By Fatou Theorem,
we know that $F(e^{it})$ exists a.e.. In the next section we shall
extend this result to any $p>0$. The above three theorems play important
roles in proving extension.

In proof of theorem 2.19, we assume $F(0)=0$, since we can use function
$\frac{F(z)}{z^k}$ if $F(z)$ has zero of order k in $z=0$. And this
modification does not affect the sum $\sum_j{(1-\abs{z_j})}$.

 The step
$$\sum_1^n{\log{\frac{1}{\abs{z_j}}}}\leq M-n\log{r}-\log{\abs{F(0)}}$$
to $$\sum_1^\infty{\log{\frac{1}{\abs{z_j}}}}\leq M-\log{\abs{F(0)}}$$
is not clear. I think we can not first let $r\to 1$ then $n\to \infty$.
We can not control taking limit for which one first.

In proof of theorem 2.21, the final step is: $$\begin{aligned}
        \abs{1-\frac{z_j-z}{1-z\bar{z_j}}\frac{\abs{z_j}}{z_j}} & =\abs{1-\frac{z_j\abs{z_j}-z\abs{z_j}}{z_j-z\abs{z_j}^2}}
        =\abs{\frac{z_j-z\abs{z_j}^2-z_j\abs{z_j}+z\abs{z_j}}{z_j-z\abs{z_j}^2}}                                                                                                             \\
                                                                & =(1-\abs{z_j})\abs{\frac{z_j+z\abs{z_j}}{z_j-z\abs{z_j}^2}}=(1-\abs{z_j})\abs{z_j}\abs{\frac{e^{it}+z}{e^{it}-z\abs{z_j}}} \\
                                                                & =(1-\abs{z_j})\abs{z_j}\abs{\frac{z'+1}{1-z'\abs{z_j}}}
    \end{aligned}$$ where $z'=z\cdot e^{-it}$. Since $\abs{z_j}<1$,
$\abs{z'}=\abs{z}\leq r$, we have $\abs{z'+1}\leq\abs{z'}+1\leq r+1$,
$\abs{1-z'\abs{z_j}}\geq 1-\abs{z'\abs{z_j}}=1-\abs{z'}\abs{z_j}\geq 1-r$.
Thus
$$\abs{1-\frac{z_j-z}{1-z\bar{z_j}}\frac{\abs{z_j}}{z_j}}\leq(1-\abs{z_j})\frac{1+r}{1-r}$$

In proof of theorem 2.22, we know if $z\bar{w}\neq 1$, then Blaschke
factors: $$\abs{\frac{w-z}{1-\bar{w}z}}=1~if~\abs{z}=1~or~\abs{w}=1$$
Since in $B_n(z)$ $\abs{e^{it}}=1$, I think $B_n(e^{it})=1$ everywhere,
not a.e..

$\abs{B_n(re^{it})}\to 1$ uniformly as $r\to 1$, since $B_n$ is
holomorphic in a neighborhood of $\bar{D}$. This is easy if we choose
$D(0,1+\epsilon)$, s.t. $z\bar{z_j}\neq 1$ in $D(0,1+\epsilon)$.
