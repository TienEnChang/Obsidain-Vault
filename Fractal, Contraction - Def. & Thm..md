
\[ Metric Space ]

Thm. Extreme Value Thm.
- $X$ compact, nonempty  $\land$  $f:X\to \mathbb{R}$ continuous
- $\implies$
	- $\max(\text{rng}(f))$, $\min(\text{rng}(f))$  exists  [[Compactness - Pf.#^ecc010|{Pf}]]

---

Let $X$ be metric space with metric $d$, $A\subseteq X$

Def. Fractal Space of $X$
- $H(X)\subseteq \mathcal{P}(X)$  metric space with  $h$ ( Hausdorff metric )
- where
	- $H(X)\coloneqq\{\,U\in\mathcal{P}(X)\;|\;U$ nonempty, compact $\}$
	- $h(A,\,B)\coloneqq\max\,\{d(A,\,B),\,d(B,\,A)\}$

Def.
- $d(p,\,A)\coloneqq\min\limits_{x \in A}\,d(p,\,x)$    { exists if $A \in H(X)$ } { $p \in X$ }  [[Fractal, Contraction - Pf.#^7e9f8b|{Pf}]]
- $d(B,\,A)\coloneqq \max\limits_{x \in B}\,d(x,\,A)$   { exists if $A,\,B \in H(X)$ }  [[Fractal, Contraction - Pf.#^393ac3|{Pf}]]

Thm.
- $(X,\,d)$ complete metric space $\implies$ $(H(X),\,h)$ complete metric space

Def.
- nearby region:  $N_r(A)\coloneqq\{\,x\in X\;|\;\exists\,a \in A$  s.t. $d(a,\,x)\leq r\,\}$  where  $r>0$

Prop.
- For $A,\,B \in H(X)$, $r>0$,
	- $A\subseteq N_{r}(B)$  $\land$  $B\subseteq N_{r}(A)$ $\iff$ $h(A,\,B)\leq r$  [[Fractal, Contraction - Pf.#^d2c212|{Pf}]]

Prop.
- $(A_n)_{n\in\mathbb{N}}$ in $H(X)$ nested $\implies$ $\bigcap\limits_{n\in\mathbb{N}}A_n=\lim\limits_{n\to\infty}A_{n}\subseteq H(X)$  [[Fractal, Contraction - Pf.#^104667|{Pf}]]
    { nested: $A_{n}\supseteq A_{n+1}$ $\forall\,n \in\mathbb{N}$ }

---

Def.
- fixed point ($\hat{x}$):  $\hat{x}=f(\hat{x})$
- attractor ($\hat{S}$):    $\hat{S}=\mathscr{F}(\hat{S})=\bigcup\limits_{i=1}^{n}f_{i}(\hat{S})$  where  $\mathscr{F}\coloneqq\{f_{1},\,\cdots,\,f_{n}\}$

Def.
- weak contraction:
	- $f:X\to X$  where
	- $\forall$ distinct $x,\,y\,\in X$:  $d(f(x),\,f(y))<d(x,\,y)$ 
- contraction:
	- $f:X\to X$  where
	- $\exists\,k$  with  $0<k<1$  s.t. $\forall\,x,\,y \in X$:  $d(f(x),\,f(y))<k\,d(x,\,y)$  
- iterated function system, IFS:
	- $\mathscr{F}\coloneqq\{\,f_{1},\,\cdots,\,f_{n}\;|\;f_{i}\,$ are all contraction on $X\,\}$
	- $\mathscr{F}:\mathcal{P}(X)\to \mathcal{P}(X)$  by  $\mathscr{F}(A)\coloneqq\bigcup\limits_{i=1}^{n}f_{i}(A)$  $\forall\,A\subseteq X$

Thm. Contraction Mapping Principle  [[Fractal, Contraction - Pf.#^df5e64|{Pf}]]
- Let
	- $X$  be complete metric space with $d$
	- $f:X\to X$  be contraction
- $\implies$
	- (1)  $\exists\,!$ $\hat{x}\in X$  with  $f(\hat{x})=\hat{x}$
	- (2)  $\forall\,p\in X$:  $(f^{\circ^n}(p))_{n\in\mathbb{N}}$  converges to $\hat{x}\,$

Prop.
- Let
	- $X$  be metric space with $d$
	- $\mathscr{F}\coloneqq\{\,f_{1},\,\cdots,\,f_{n}\,\}$  be IFS on $X$,  with contraction factor $k_{i}$  $\forall\,f_{i} \in \mathscr{F}$
- $\implies$ 
	- (1) $\forall\,A,\,B \in H(X)$  $\forall\,f_{i} \in \mathscr{F}$:  $h(f_{i}(A),\,f_{i}(B))\leq k_{i}\cdot h(A,\,B)$
	- (2) $\forall\,A \in H(X)$  $\forall\,r>0$:  $\bigcup\limits_{i=1}^{n}N_{r}(f_{i}(A))=N_{r}(\bigcup\limits_{i=1}^{n}f_{i}(A))$

Thm. IFS as Contraction
- Let
	- $X$  be complete metric space with $d$
	- $\mathscr{F}$  be IFS on $X$
- $\implies$ 
	- $\mathscr{F}$ contraction on $H(X)$
		- (1)  $\exists\,!$ $\hat{S}\in H(X)$  with  $\mathscr{F}(\hat{S})=\hat{S}$
		- (2)  $\forall\,A\in H(X)$:  $(\mathscr{F}^{\circ^n}(A))_{n\in\mathbb{N}}$  converges to $\hat{S}$
- $\implies$ 
	- $\mathscr{F}(A)\subseteq A$ $\implies$ $\bigcap\limits_{n \in \mathbb{N}}\mathscr{F}^{\circ^{n}}(A)=\lim\limits_{n\to\infty}\mathscr{F}^{\circ^{n}}(A)=\hat{S}$

---

\[ $\mathbb{R}$ ]

Thm. Brouwer fixed point Thm. 
- $X$ compact, nonempty, convex $\subseteq \mathbb{R}$  $\land$  $f:X\to X$ continuous
- $\implies$
	- $\exists$ $\hat{x}\in X$  with  $f(\hat{x})=\hat{x}$  [[Fractal, Contraction - Pf.#^ede849|{Pf for case]] $X=[0, 1]$}