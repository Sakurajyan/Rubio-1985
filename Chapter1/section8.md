The Helson-Szego Theorem
========================

In this section, we no longer focus on Lebesgue measure. We will
reexamine some results for boundedness of conjugate function on borel
measure. The main result we give is the Helson-Szego theorem. The
Helson-Szego theorem is a characterization of those positive (Borel)
measure <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=[-\pi,\pi]" alt="[-\pi,\pi]" class="ee_img tr_noresize" eeimg="1"> for which the conjugate function operator
is bounded in <img src="https://www.zhihu.com/equation?tex=L^2(\mu)" alt="L^2(\mu)" class="ee_img tr_noresize" eeimg="1">. More precisely, we answer the problem for what
positive measure the following inequality holds:

<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2 d\mu(t)\leq C\int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^2 d\mu(t)\\" alt="\int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2 d\mu(t)\leq C\int_{-\pi}^{\pi}\left\lvert f(t)\right\rvert^2 d\mu(t)\\" class="ee_img tr_noresize" eeimg="1">

where <img src="https://www.zhihu.com/equation?tex=f(t)=\sum_{j=-n}^{n}{a_je^{ijt}}" alt="f(t)=\sum_{j=-n}^{n}{a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\tilde{f}(t)=-i\sum_{j=-n}^{n}{(\operatorname{sgn}j)a_je^{ijt}}" alt="\tilde{f}(t)=-i\sum_{j=-n}^{n}{(\operatorname{sgn}j)a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1">.
<img src="https://www.zhihu.com/equation?tex=f(t)+i\tilde{f}(t)" alt="f(t)+i\tilde{f}(t)" class="ee_img tr_noresize" eeimg="1"> only left non negative frequency part. We will call
such measures Helson-Szego measures.

Distance from constant function 1 to space <img src="https://www.zhihu.com/equation?tex=\mathscr{P}(0)" alt="\mathscr{P}(0)" class="ee_img tr_noresize" eeimg="1">
-----------------------------------------------------------

To proof <img src="https://www.zhihu.com/equation?tex=1\in\overline{\mathscr{P}(0)}" alt="1\in\overline{\mathscr{P}(0)}" class="ee_img tr_noresize" eeimg="1">, we can use Hahn-Banach
theorem: if <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is locally convex and <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is subspace of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=x_0\in E" alt="x_0\in E" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=x_0\in \bar{F}" alt="x_0\in \bar{F}" class="ee_img tr_noresize" eeimg="1"> if and only if for any <img src="https://www.zhihu.com/equation?tex=f\in E^*" alt="f\in E^*" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=f\vert_F=0 \implies f(x_0)=0" alt="f\vert_F=0 \implies f(x_0)=0" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> are mutually singular if there are disjoint subsets <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=B" alt="B" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathscr{M}" alt="\mathscr{M}" class="ee_img tr_noresize" eeimg="1"> s.t. <img src="https://www.zhihu.com/equation?tex=\nu(E)=\nu(A\cap E)" alt="\nu(E)=\nu(A\cap E)" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\mu(E)=\mu(B\cap E)" alt="\mu(E)=\mu(B\cap E)" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=E\in\mathscr{M}" alt="E\in\mathscr{M}" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> is absolutely
continuous w.r.t. <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=\nu(E)=0" alt="\nu(E)=0" class="ee_img tr_noresize" eeimg="1"> whenever <img src="https://www.zhihu.com/equation?tex=E\in\mathscr{M}" alt="E\in\mathscr{M}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\mu(E)=0" alt="\mu(E)=0" class="ee_img tr_noresize" eeimg="1"> (section 4.2 in Chapter 6 of Stein's Real Analysis).

Thus if <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> are mutually singular and <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> is absolutely
continuous w.r.t. <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1">, then for all <img src="https://www.zhihu.com/equation?tex=E\in\mathscr{M}" alt="E\in\mathscr{M}" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\mu(A\cap E)=\mu(A\cap B\cap E)=0" alt="\mu(A\cap E)=\mu(A\cap B\cap E)=0" class="ee_img tr_noresize" eeimg="1"> and hence <img src="https://www.zhihu.com/equation?tex=\nu(E)=\nu(A\cap E)=0" alt="\nu(E)=\nu(A\cap E)=0" class="ee_img tr_noresize" eeimg="1">.
Therefore <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> is identically zero.

The following lemma is useful in specifying Helson-Szego measure. It
states there is a holomorphic function continuous on boundary can
separate closed Lebesgue measure 0 set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> and set <img src="https://www.zhihu.com/equation?tex=\bar{D}\setminus E" alt="\bar{D}\setminus E" class="ee_img tr_noresize" eeimg="1">.
Using this lemma, we can narrow our candidates non negative measure to
absolutely continuous measure. All Helson-Szego measure <img src="https://www.zhihu.com/equation?tex=d\mu" alt="d\mu" class="ee_img tr_noresize" eeimg="1"> can be
written as <img src="https://www.zhihu.com/equation?tex=d\mu=w(t)dt" alt="d\mu=w(t)dt" class="ee_img tr_noresize" eeimg="1">.

[\[separate zero measure\]]{#separate zero measure
label="separate zero measure"} Let <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> be a closed subset of <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> having
Lebesgue measure 0. Then, there exists a function <img src="https://www.zhihu.com/equation?tex=F\in\mathscr{A}" alt="F\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">
(that is: <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is holomorphic in <img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1"> and continuous on <img src="https://www.zhihu.com/equation?tex=\bar{D}" alt="\bar{D}" class="ee_img tr_noresize" eeimg="1">) such
that <img src="https://www.zhihu.com/equation?tex=F(z)=1" alt="F(z)=1" class="ee_img tr_noresize" eeimg="1"> for every <img src="https://www.zhihu.com/equation?tex=z\in E" alt="z\in E" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\left\lvert F(z)\right\rvert<1" alt="\left\lvert F(z)\right\rvert<1" class="ee_img tr_noresize" eeimg="1">
for every <img src="https://www.zhihu.com/equation?tex=z\in\bar{D}\setminus E" alt="z\in\bar{D}\setminus E" class="ee_img tr_noresize" eeimg="1">.

In theorem 8.4 we assumes <img src="https://www.zhihu.com/equation?tex=w\geq 0" alt="w\geq 0" class="ee_img tr_noresize" eeimg="1"> but in proof this condition is never
used. Suppose <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> is a Borel measure and is finite on all finite
radius balls. Then for any Borel set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> and any <img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1">, there are
an open set <img src="https://www.zhihu.com/equation?tex=O" alt="O" class="ee_img tr_noresize" eeimg="1"> and a closed set <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=E\subset O" alt="E\subset O" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\mu(O-E)\leq\epsilon" alt="\mu(O-E)\leq\epsilon" class="ee_img tr_noresize" eeimg="1"> while <img src="https://www.zhihu.com/equation?tex=F\subset E" alt="F\subset E" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\mu(E-F)\leq\epsilon" alt="\mu(E-F)\leq\epsilon" class="ee_img tr_noresize" eeimg="1">
(proposition 1.3 in Chapter 6 of Stein's Real Analysis).

By above statement, inequality (8.6) in book can be hold.

The following theorem gives a precise formula for the distance we are
looking for:

[\[distance from P(0) to 1\]]{#distance from P(0) to 1
label="distance from P(0) to 1"} For <img src="https://www.zhihu.com/equation?tex=w\geq 0" alt="w\geq 0" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=w\in L^1" alt="w\in L^1" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\inf_{P\in\mathscr{P}(0)}\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert 1-P(e^{it})\right\rvert^p w(t)d t=\exp(\frac{1}{2\pi}\int_{-\pi}^{\pi}\log w(t)d t),1\leq p<\infty\\" alt="\inf_{P\in\mathscr{P}(0)}\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert 1-P(e^{it})\right\rvert^p w(t)d t=\exp(\frac{1}{2\pi}\int_{-\pi}^{\pi}\log w(t)d t),1\leq p<\infty\\" class="ee_img tr_noresize" eeimg="1">


The Helson-Szego theorem
------------------------

By theorem
[\[distance from P(0) to 1\]](#distance from P(0) to 1){reference-type="ref"
reference="distance from P(0) to 1"}, if <img src="https://www.zhihu.com/equation?tex=\log w(t)=-\infty" alt="\log w(t)=-\infty" class="ee_img tr_noresize" eeimg="1">, there is a
sequence of <img src="https://www.zhihu.com/equation?tex=(P_j)\subset\mathscr{P}(0)" alt="(P_j)\subset\mathscr{P}(0)" class="ee_img tr_noresize" eeimg="1">, s.t.
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\left\lvert 1-P_j(e^{it})\right\rvert^2 w(t)d t\to 0" alt="\int_{-\pi}^{\pi}\left\lvert 1-P_j(e^{it})\right\rvert^2 w(t)d t\to 0" class="ee_img tr_noresize" eeimg="1">.
Since the conjugate function of <img src="https://www.zhihu.com/equation?tex=1-P_j(e^{it})" alt="1-P_j(e^{it})" class="ee_img tr_noresize" eeimg="1"> is <img src="https://www.zhihu.com/equation?tex=iP_j(e^{it})" alt="iP_j(e^{it})" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> is Helson-Szego measure, we have
<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\left\lvert P_j(e^{it})\right\rvert^2 w(t)d t\to 0" alt="\int_{-\pi}^{\pi}\left\lvert P_j(e^{it})\right\rvert^2 w(t)d t\to 0" class="ee_img tr_noresize" eeimg="1">.
By
<img src="https://www.zhihu.com/equation?tex=1\leq\left\lvert P_j(e^{it})\right\rvert^2+\left\lvert 1-P_j(e^{it})\right\rvert^2" alt="1\leq\left\lvert P_j(e^{it})\right\rvert^2+\left\lvert 1-P_j(e^{it})\right\rvert^2" class="ee_img tr_noresize" eeimg="1">,
we show <img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}1 w(t)d t= 0" alt="\int_{-\pi}^{\pi}1 w(t)d t= 0" class="ee_img tr_noresize" eeimg="1">. We conclude <img src="https://www.zhihu.com/equation?tex=\log w(t)=-\infty" alt="\log w(t)=-\infty" class="ee_img tr_noresize" eeimg="1">
implies <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> is a trivial measure. Thus we can only focus on
Helson-Szego measure <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> which <img src="https://www.zhihu.com/equation?tex=d\mu=w(t)dt" alt="d\mu=w(t)dt" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=w(t)\in L^1" alt="w(t)\in L^1" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\log w(t)\in L^1" alt="\log w(t)\in L^1" class="ee_img tr_noresize" eeimg="1">.

Given <img src="https://www.zhihu.com/equation?tex=f(t)=\sum_j{a_je^{ijt}}" alt="f(t)=\sum_j{a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1">, operator <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> sends <img src="https://www.zhihu.com/equation?tex=f(t)" alt="f(t)" class="ee_img tr_noresize" eeimg="1"> to
<img src="https://www.zhihu.com/equation?tex=Af(t)=\sum_{j>0}{a_je^{ijt}}" alt="Af(t)=\sum_{j>0}{a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1"> . By easy calculation we have following
identities:

<img src="https://www.zhihu.com/equation?tex=\tilde{f}=-i(A f-\overline{A\bar{f}})~and~A f=\frac{-\tilde{\tilde{f}}+i\tilde{f}}{2}\\" alt="\tilde{f}=-i(A f-\overline{A\bar{f}})~and~A f=\frac{-\tilde{\tilde{f}}+i\tilde{f}}{2}\\" class="ee_img tr_noresize" eeimg="1">


This proof is from P165 in Paul Koosis' *Introduction to Hp spaces*.

By <img src="https://www.zhihu.com/equation?tex=\tilde{f}=-i(Af-\overline{A\bar{f}})" alt="\tilde{f}=-i(Af-\overline{A\bar{f}})" class="ee_img tr_noresize" eeimg="1">, if
<img src="https://www.zhihu.com/equation?tex=\lVert Af\rVert_w\leq C\lVert f\rVert_w" alt="\lVert Af\rVert_w\leq C\lVert f\rVert_w" class="ee_img tr_noresize" eeimg="1">, then

<img src="https://www.zhihu.com/equation?tex=\lVert\tilde{f}\rVert_w\leq \lVert Af\rVert_w+\lVert\overline{A\bar{f}}\rVert_w=\lVert Af\rVert_w+\lVert{A\bar{f}}\rVert_w\leq C\lVert f\rVert_w+C\lVert{\bar{f}}\rVert_w\leq 2C\lVert f\rVert_w\\" alt="\lVert\tilde{f}\rVert_w\leq \lVert Af\rVert_w+\lVert\overline{A\bar{f}}\rVert_w=\lVert Af\rVert_w+\lVert{A\bar{f}}\rVert_w\leq C\lVert f\rVert_w+C\lVert{\bar{f}}\rVert_w\leq 2C\lVert f\rVert_w\\" class="ee_img tr_noresize" eeimg="1">

By <img src="https://www.zhihu.com/equation?tex=Af=\frac{-\tilde{\tilde{f}}+i\tilde{f}}{2}" alt="Af=\frac{-\tilde{\tilde{f}}+i\tilde{f}}{2}" class="ee_img tr_noresize" eeimg="1">, if
<img src="https://www.zhihu.com/equation?tex=\lVert\tilde{f}\rVert_w\leq C\lVert f\rVert_w" alt="\lVert\tilde{f}\rVert_w\leq C\lVert f\rVert_w" class="ee_img tr_noresize" eeimg="1">, then

<img src="https://www.zhihu.com/equation?tex=\lVert Af\rVert_w\leq \frac{1}{2}\lVert\tilde{\tilde{f}}\rVert_w+\frac{1}{2}\lVert\tilde{f}\rVert_w\leq \frac{C}{2}\lVert{\tilde{f}}\rVert_w+\frac{C}{2}\lVert{f}\rVert_w\leq \frac{C^2}{2}\lVert f\rVert_w+\frac{C}{2}\lVert f\rVert_w\leq \frac{C^2+C}{2}\lVert{f}\rVert_w\\" alt="\lVert Af\rVert_w\leq \frac{1}{2}\lVert\tilde{\tilde{f}}\rVert_w+\frac{1}{2}\lVert\tilde{f}\rVert_w\leq \frac{C}{2}\lVert{\tilde{f}}\rVert_w+\frac{C}{2}\lVert{f}\rVert_w\leq \frac{C^2}{2}\lVert f\rVert_w+\frac{C}{2}\lVert f\rVert_w\leq \frac{C^2+C}{2}\lVert{f}\rVert_w\\" class="ee_img tr_noresize" eeimg="1">

Thus conjugate operator bounded in <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> is equivalent to operator <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
bounded in <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1">.

We now talk about how Helson-Szego theorem reached. Every lemmas or
theorems contain different ideas in the path to Helson-Szego theorem.
Lemma 8.10 in book shows we can study boundedness of operator <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
instead of boundedness of conjugate operator. In theorem 8.11 in book,
if we write <img src="https://www.zhihu.com/equation?tex=f(t)=P(e^{it})+e^{it}\overline{Q(e^{it})}" alt="f(t)=P(e^{it})+e^{it}\overline{Q(e^{it})}" class="ee_img tr_noresize" eeimg="1"> for some
<img src="https://www.zhihu.com/equation?tex=P,Q\in\mathscr{P}(0)" alt="P,Q\in\mathscr{P}(0)" class="ee_img tr_noresize" eeimg="1">, we can study the boundedness in space
<img src="https://www.zhihu.com/equation?tex=\mathscr{P}(0)" alt="\mathscr{P}(0)" class="ee_img tr_noresize" eeimg="1"> but we need an additional restriction on some
constants. Later we state theorem 8.12 in book, we further shows the
restriction on the constant in theorem 8.11 in book becomes the
restriction on the norm in quotient space
<img src="https://www.zhihu.com/equation?tex=(H^1(0))^*=L^\infty/ H^\infty" alt="(H^1(0))^*=L^\infty/ H^\infty" class="ee_img tr_noresize" eeimg="1">. The norm on quotient space is naturally
the distance from represent element to space <img src="https://www.zhihu.com/equation?tex=H^\infty" alt="H^\infty" class="ee_img tr_noresize" eeimg="1">.

Now we state the Helson-Szego theorem:

<img src="https://www.zhihu.com/equation?tex=w" alt="w" class="ee_img tr_noresize" eeimg="1"> is a Helson-Szego weight if and only if <img src="https://www.zhihu.com/equation?tex=w(t)=e^{u(t)+\tilde{v}(t)}" alt="w(t)=e^{u(t)+\tilde{v}(t)}" class="ee_img tr_noresize" eeimg="1">
with <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1"> real, bounded and <img src="https://www.zhihu.com/equation?tex=\lVert v\rVert_\infty<\frac{\pi}{2}" alt="\lVert v\rVert_\infty<\frac{\pi}{2}" class="ee_img tr_noresize" eeimg="1">

I also refer another proof of Helson-Szego theorem in P167 in Paul
Koosis' *Introduction to Hp spaces*.

Since <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> is bounded, we have <img src="https://www.zhihu.com/equation?tex=0<C_1<e^u<C_2<\infty" alt="0<C_1<e^u<C_2<\infty" class="ee_img tr_noresize" eeimg="1">. If
<img src="https://www.zhihu.com/equation?tex=w(t)=e^{\tilde{v}(t)}" alt="w(t)=e^{\tilde{v}(t)}" class="ee_img tr_noresize" eeimg="1"> is a Helson-Szego measure, then:

<img src="https://www.zhihu.com/equation?tex=\int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2e^{u+\tilde{v}}d t\leq \int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2C_2e^{\tilde{v}}d t\leq C\int_{-\pi}^{\pi}\lvert{f}(t)\rvert^2C_2e^{\tilde{v}}d t\leq C\int_{-\pi}^{\pi}\lvert{f}(t)\rvert^2\frac{C_2}{C_1}e^{u+\tilde{v}}d t\\" alt="\int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2e^{u+\tilde{v}}d t\leq \int_{-\pi}^{\pi}\lvert\tilde{f}(t)\rvert^2C_2e^{\tilde{v}}d t\leq C\int_{-\pi}^{\pi}\lvert{f}(t)\rvert^2C_2e^{\tilde{v}}d t\leq C\int_{-\pi}^{\pi}\lvert{f}(t)\rvert^2\frac{C_2}{C_1}e^{u+\tilde{v}}d t\\" class="ee_img tr_noresize" eeimg="1">

Thus we just need to consider the case <img src="https://www.zhihu.com/equation?tex=w(t)=e^{\tilde{v}(t)}" alt="w(t)=e^{\tilde{v}(t)}" class="ee_img tr_noresize" eeimg="1">.

Recall conjugate function is real. Suppose
<img src="https://www.zhihu.com/equation?tex=\Phi(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{e^{it}+z}{e^{it}-z}\frac{1}{2}\tilde{v}(t)dt)}" alt="\Phi(z)=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{e^{it}+z}{e^{it}-z}\frac{1}{2}\tilde{v}(t)dt)}" class="ee_img tr_noresize" eeimg="1">.
We have <img src="https://www.zhihu.com/equation?tex=\left\lvert\Phi(z)\right\rvert^2=\exp{(P(\tilde{v}))}" alt="\left\lvert\Phi(z)\right\rvert^2=\exp{(P(\tilde{v}))}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\Phi(z)^2=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{e^{it}+z}{e^{it}-z}\tilde{v}(t)dt)}" alt="\Phi(z)^2=\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}\frac{e^{it}+z}{e^{it}-z}\tilde{v}(t)dt)}" class="ee_img tr_noresize" eeimg="1">.
Now we compute the angle <img src="https://www.zhihu.com/equation?tex=\frac{\Phi^2}{\left\lvert\Phi\right\rvert^2}" alt="\frac{\Phi^2}{\left\lvert\Phi\right\rvert^2}" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \frac{\Phi(z)^2}{\left\lvert\Phi(z)\right\rvert^2} & =\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}(\frac{e^{it}+z}{e^{it}-z}-P_r(\theta-t))\tilde{v}(t)d t)} \\
                                          & =\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}iQ_r(\theta-t)\tilde{v}(t)d t)}                            \\
                                          & =\exp{(i\tilde{\tilde{v}}(re^{i\theta}))}                                                        \\
    \end{aligned}\\" alt="\begin{aligned}
        \frac{\Phi(z)^2}{\left\lvert\Phi(z)\right\rvert^2} & =\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}(\frac{e^{it}+z}{e^{it}-z}-P_r(\theta-t))\tilde{v}(t)d t)} \\
                                          & =\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}iQ_r(\theta-t)\tilde{v}(t)d t)}                            \\
                                          & =\exp{(i\tilde{\tilde{v}}(re^{i\theta}))}                                                        \\
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 If <img src="https://www.zhihu.com/equation?tex=v(t)=\sum_{j}{a_je^{ijt}}" alt="v(t)=\sum_{j}{a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1">, then
<img src="https://www.zhihu.com/equation?tex=\tilde{v}(t)=-i\sum_{j}{(\operatorname{sgn}j)a_je^{ijt}}" alt="\tilde{v}(t)=-i\sum_{j}{(\operatorname{sgn}j)a_je^{ijt}}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\tilde{\tilde{v}}(t)=-\sum_{j\neq 0}{a_je^{ijt}}=-v(t)+a_0=-v(t)+v(0)" alt="\tilde{\tilde{v}}(t)=-\sum_{j\neq 0}{a_je^{ijt}}=-v(t)+a_0=-v(t)+v(0)" class="ee_img tr_noresize" eeimg="1">.
Thus
<img src="https://www.zhihu.com/equation?tex=\frac{\Phi^2}{\left\lvert\Phi\right\rvert^2}=\exp{(-iP(v)+iv(0))}" alt="\frac{\Phi^2}{\left\lvert\Phi\right\rvert^2}=\exp{(-iP(v)+iv(0))}" class="ee_img tr_noresize" eeimg="1">.

Now we have 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        \Phi(z)^2 & =\left\lvert\Phi(z)\right\rvert^2\frac{\Phi(z)^2}{\left\lvert\Phi(z)\right\rvert^2} \\
                  & =\exp{(P(\tilde{v}))}\exp{(-iP(v)+iv(0))}         \\
                  & =\exp{(P(\tilde{v}-iv))}\exp{iv(0))}
    \end{aligned}\\" alt="\begin{aligned}
        \Phi(z)^2 & =\left\lvert\Phi(z)\right\rvert^2\frac{\Phi(z)^2}{\left\lvert\Phi(z)\right\rvert^2} \\
                  & =\exp{(P(\tilde{v}))}\exp{(-iP(v)+iv(0))}         \\
                  & =\exp{(P(\tilde{v}-iv))}\exp{iv(0))}
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">
 Thus we can see the real number <img src="https://www.zhihu.com/equation?tex=\tau" alt="\tau" class="ee_img tr_noresize" eeimg="1"> in book is
<img src="https://www.zhihu.com/equation?tex=v(0)" alt="v(0)" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=\tau" alt="\tau" class="ee_img tr_noresize" eeimg="1"> is irrelevant since
<img src="https://www.zhihu.com/equation?tex=\inf_{g\in H^\infty}{\lVert e^{-i\tau}e^{iv(t)}-g\rVert_\infty}=\inf_{g\in H^\infty}{\lVert e^{iv(t)}-g\rVert_\infty}" alt="\inf_{g\in H^\infty}{\lVert e^{-i\tau}e^{iv(t)}-g\rVert_\infty}=\inf_{g\in H^\infty}{\lVert e^{iv(t)}-g\rVert_\infty}" class="ee_img tr_noresize" eeimg="1">.
Notice that constants are in <img src="https://www.zhihu.com/equation?tex=H^\infty" alt="H^\infty" class="ee_img tr_noresize" eeimg="1">. Thus
<img src="https://www.zhihu.com/equation?tex=\left\lvert e^{iv(t)}-sin\epsilon\right\rvert<1" alt="\left\lvert e^{iv(t)}-sin\epsilon\right\rvert<1" class="ee_img tr_noresize" eeimg="1"> implies
<img src="https://www.zhihu.com/equation?tex=d(e^{iv},H^\infty)<1" alt="d(e^{iv},H^\infty)<1" class="ee_img tr_noresize" eeimg="1">.

The inequality
<img src="https://www.zhihu.com/equation?tex=\left\lvert e^{i\phi(t)}-H(e^{it})\right\rvert\leq\alpha" alt="\left\lvert e^{i\phi(t)}-H(e^{it})\right\rvert\leq\alpha" class="ee_img tr_noresize" eeimg="1"> in book
should be <img src="https://www.zhihu.com/equation?tex=\left\lvert e^{i\phi(t)}-H(e^{it})\right\rvert\leq\alpha_1" alt="\left\lvert e^{i\phi(t)}-H(e^{it})\right\rvert\leq\alpha_1" class="ee_img tr_noresize" eeimg="1">
for some <img src="https://www.zhihu.com/equation?tex=\alpha_1" alt="\alpha_1" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=\inf_{g\in H^\infty}{\lVert e^{iv(t)}-g\rVert_\infty}=\alpha<\alpha_1<1" alt="\inf_{g\in H^\infty}{\lVert e^{iv(t)}-g\rVert_\infty}=\alpha<\alpha_1<1" class="ee_img tr_noresize" eeimg="1">.

An outer function <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> has representation:

<img src="https://www.zhihu.com/equation?tex=F(z)=C\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}w(t)d t})}\\" alt="F(z)=C\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{\frac{e^{it}+z}{e^{it}-z}w(t)d t})}\\" class="ee_img tr_noresize" eeimg="1">

where <img src="https://www.zhihu.com/equation?tex=C=I_F(z)" alt="C=I_F(z)" class="ee_img tr_noresize" eeimg="1"> is constant. Decompose
<img src="https://www.zhihu.com/equation?tex=\frac{e^{it}+z}{e^{it}-z}=P_r(\theta-t)+iQ_r(\theta-t)" alt="\frac{e^{it}+z}{e^{it}-z}=P_r(\theta-t)+iQ_r(\theta-t)" class="ee_img tr_noresize" eeimg="1">, we have:

<img src="https://www.zhihu.com/equation?tex=F(z)=C\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{(P_r(\theta-t)+iQ_r(\theta-t))w(t)d t})}=C\exp{(u(re^{i\theta})+iv(re^{i\theta}))}\\" alt="F(z)=C\exp{(\frac{1}{2\pi}\int_{-\pi}^{\pi}{(P_r(\theta-t)+iQ_r(\theta-t))w(t)d t})}=C\exp{(u(re^{i\theta})+iv(re^{i\theta}))}\\" class="ee_img tr_noresize" eeimg="1">

where <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> is a real harmonic function and <img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1"> its conjugate. Let
<img src="https://www.zhihu.com/equation?tex=r\to 1" alt="r\to 1" class="ee_img tr_noresize" eeimg="1"> and notice <img src="https://www.zhihu.com/equation?tex=\left\lvert C\right\rvert\to 1" alt="\left\lvert C\right\rvert\to 1" class="ee_img tr_noresize" eeimg="1">. Thus we have
<img src="https://www.zhihu.com/equation?tex=F(e^{it})=e^{i\tau}e^{u+iv}" alt="F(e^{it})=e^{i\tau}e^{u+iv}" class="ee_img tr_noresize" eeimg="1">.

We conclude that an outer function has representation
<img src="https://www.zhihu.com/equation?tex=e^{i\tau}e^{u+iv}" alt="e^{i\tau}e^{u+iv}" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=\tau" alt="\tau" class="ee_img tr_noresize" eeimg="1"> is a real number. <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> is a real
harmonic function and <img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1"> its conjugate.
