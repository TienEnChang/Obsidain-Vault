 
Def. digitized probability space:  $(\Omega,\,\mathcal{F}_\Omega,\,P)$ $\overset{X}{\longrightarrow}$ $(\mathbb{R},\,\mathcal{F}_\mathbb{R},\,P_X)$

Def. random variable (r.v.)
- $X:\Omega\to\mathbb{R}$,  $\mathcal{X}\coloneqq X(\Omega)$ as new sample space

Def. distribution
- $P:\mathcal{F}_\Omega\to\mathbb{R}$
- $P_X:\mathcal{F}_\mathbb{R}\to\mathbb{R}$
    where  $P_X(A_X)\coloneqq P(E_A)$,  $E_A\coloneqq X^{\leftarrow}(A_X\in\mathcal{F}_\mathbb{R})\in\mathcal{F}_\Omega$
           $\mathcal{F}_{\mathbb{R}}=\sigma(\{\,(-\infty,\,x\,]\;|\;x\in\mathbb{Q}\,\})$

Def.
- $P(X=k)=P_X(\{k\})$,  $P(X>k)=P_X(\{x>k\})$,  $P(X\leq k)=P_X(\{x\leq k\})$

Def. probability mass function   { discrete r.v. }
- $f_X:\mathbb{R}\to\mathbb{R}$  { a.k.a. $p_{X}$ }
- where
	- $\exists\,X$  with  $f_X(x)\coloneqq\begin{cases}P_X(\{x\})&{\rm if}\;\,x\in\mathcal{X}\\0&{\rm o.w.}\end{cases}$
	- $\iff$                       { existence Thm. } [[Randome Variables, Functions - Pf.#^9d66f6|{Pf}]]
	- $\forall\,x\in\mathcal{X}$: $f_X(x)\geq 0$  
	- $\forall\,x\not\in\mathcal{X}$: $f_X(x)=0$
	- $\sum\limits_{x\in\mathcal{X}}f_X(x)=1$        { only possible for discrete r.v. }
- $\implies$
	- $\forall\,A_X\subseteq\mathbb{R}$: $P_X(A_X)=\sum\limits_{x\in A_X\cap \mathcal{X}}f_X(x)$   { $A_X\cap\mathcal{X}$ countable }

Def. cumulative distribution function   { any r.v. }
- $F_X:\mathbb{R}\to\mathbb{R}$
- where
	- $\exists\,X$  with  $F_X(x)\coloneqq P_X(\,(-\infty,\,x\,]\,)$
	- $\iff$                                { existence Thm. } [[Randome Variables, Functions - Pf.#^49c099|{Pf}]]
	- $F_X$ is non-decreasing
		
	- $F_X$ is continuous from the right
		- $F_X(x^+)\coloneqq\lim\limits_{t\to x+}F_X(t)=P_X(\,(-\infty,\,x\,]\,)=F_X(x)$
		- $F_X(x^-)\coloneqq\lim\limits_{t\to x^-}F_X(t)=P_X(\,(-\infty,\,x)\,)\neq F_X(x)$
		
	- $\lim\limits_{t\to-\infty}F_X(t)=0$,  $\lim\limits_{t\to\infty}F_X(t)=1$
		- $\implies$ $\forall\,x\in\mathbb{R}$:  $0\leq F_X(x)\leq 1$   { By 1 & 3 }
- $\implies$
	- $\forall\,(a,\,b\,]\subseteq\mathbb{R}$: $P_X(\,(a,\,b\,]\,)=F_X(b)-F_X(a)$
	- $\forall\,x\in\mathbb{R}$:
		- $f_X(x)=F_X(x)-F_X(x^-)$
		- $F_X(x)=\sum\limits_{x\in (-\infty,\,x\,]\cap \mathcal{X}}f_X(x)$

---

Thm. [[Randome Variables, Functions - Pf.#^d50e3a|{Pf}]]
- The set of disjoint points $D\coloneqq\{\,x\in\mathbb{R}\;|\;F_X(x^-)<F_X(x)\,\}$ is countable

Thm. [[Randome Variables, Functions - Pf.#^d0f0a2|{Pf}]]
- Let $Y=g(X)$, $\mathcal{Y}\coloneqq g(\mathcal{X})$, $g$ might not be 1-1
- $\implies$
- $\forall\,A_Y\subseteq\mathbb{R}$, $y\in\mathbb{R}$:
	- $P_Y(A_Y)=P_X(g^{\leftarrow}(A_Y))$
	- $f_Y(y)=\sum\limits_{x\in g^{\leftarrow}\{y\}\cap \mathcal{X}}f_X(x)$ 
	- $F_Y(y)=\sum\limits_{x\in g^{\leftarrow}((-\infty,\,y\,])\cap \mathcal{X}}f_X(x)$
	       $\;=F_X(g^{\leftarrow}(y))$  if  $g$ strictly increasing