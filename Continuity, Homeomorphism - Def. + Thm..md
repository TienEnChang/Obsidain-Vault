
Related:  [[2. Limit & Continuity|Calculus I & II - Limit & Continuity]]

\[ In Topological Spaces ]

Let $X$, $Y$, $Z$ be topological spaces

Def. continuous function
- $f:X\to Y$
    where  $\forall\;A$ open $\subseteq Y$:  $f^{\leftarrow}(A)$ open $\subseteq X$
     i.e.  $\forall\;A$ closed $\subseteq Y$:  $f^{\leftarrow}(A)$ closed $\subseteq X$

Thm.
- $f_1$, $f_2$ are continuous $\implies$ $f_2\circ f_1$ is continuous

Def. homeomorphism
- $f:X\to Y$
- where
	- $f$ is bijective
	- $f$, $f^{-1}$ are continuous

Def.
- $X$, $Y$ are homeomorphic:  $\exists$ homeomorphism $f:X\to Y$

Thm. inheritance
- $f:X\to Y$ homeo $\implies$ $f|_A:A\to f(A)$ homeo  $\forall\, A\subseteq X$

Prop.
- ${\overset{\rm homeo}\sim}$ is equiv. relation on $\{\,$ all topological spaces $\}$  [[Continuity, Homeomorphism - Pf.#^ca2b27|{Pf}]]

Def.
- topological property / invariant:  preserved under homeomorphism

Method.
- Assume $\exists$ homeo $f:X\to Y$
  $\implies$ topological invariant "not" preserved  ($\rightarrow\!\leftarrow$)

---

\[ In Metric Spaces ]

Let $X$, $Y$ be metric spaces with $d_X$, $d_Y$, and $f:X\to Y$

Thm. using ball (general)
- $f$ is continuous
- $\iff$
- $\forall\,p\in X$  $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t. ${B_{\delta}}^X(p)\subseteq f^{\leftarrow}({B_{\varepsilon}}^Y(f(p)))$  [[Continuity, Homeomorphism - Pf.#^2fe0de|{Pf}]]
	- OR
- $\forall\,x\in X$  $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t.  $\forall\,y\in X\,$ with $|x-y|<\delta$:  $|f(x)-f(y)|<\varepsilon$
	- OR
- $\forall\,x\in X$:  $\lim\limits_{t\to x}f(t)=f(x)$

Thm. using seqeunce (strict)
- $f$ is continuous
- $\iff$
- $\forall\,(p_n)_{n\in\mathbb{N}}$ in $X$ converges to $p\in X$:  $(f(p_n))_{n\in\mathbb{N}}$ converges to $f(p)$  [[Continuity, Homeomorphism - Pf.#^c823a8|{Pf}]]
	- OR
- $\forall\,x\in X$:  $\lim\limits_{n\to \infty}f(x_{n})=f(x)$  for any  $(x_{n})_{n \in \mathbb{N}}$ converges to $x$

Thm.
- $m_a:X\to\mathbb{R}$  by  $m_a(x)\coloneqq d(a,\,x)$  is continuous  [[Continuity, Homeomorphism - Pf.#^02ea6b|{Pf}]]


(uniformly continuous)

Def. uniformly continuous
- $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t. $\forall\,x\in X$:  ${B_{\delta}}^X(x)\subseteq f^{\leftarrow}({B_{\varepsilon}}^Y(f(x)))$
	- OR
- $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t. $\forall\,x,\,y \in X\,$ with $\,|x-y|<\delta$:  $|f(x)-f(y)|<\varepsilon$

Thm.
- For $f:X\to Y$ uniformly continuous,
	- $(p_n)_{n\in\mathbb{N}}$ Cauchy in $X$ $\implies$ $(f(p_n))_{n\in\mathbb{N}}$ Cauchy in $Y$  [[Continuity, Homeomorphism - Pf.#^5da1a9|{Pf}]]

Extra.
- $Y$ complete  $\land$  $f:X\to Y$ uniformly continuous on $A\subseteq X$
	- $\implies$ $f$ continuous on $\text{Cl}_{X}(A)$  {Pf?}

---

\[ In $\mathbb{R}^n$ ]

Thm. (field op.)
- $+,\,-,\,\times:\mathbb{R}^2\to\mathbb{R}$  and  $\div:\mathbb{R}\times(\mathbb{R}-\{0\})\to\mathbb{R}$  are continuous  [[Continuity, Homeomorphism - Pf.#^78d67d|{Pf}]]

Cor.
- polynomials are continuous  ( including $\det$ )
	 { since 1. $\text{id}_\mathbb{R}$ continuous,
	        2. $[\,\star\circ(f,\,g)\,](x)\coloneqq f(x)\star g(x)$ $\;\forall\,f,\,g\in\mathcal{F}(S,\,\mathbb{R})$ }

Thm. (vector space op.)
- $+:\mathbb{R}^n\times\mathbb{R}^n\to\mathbb{R}^n$  and  $\cdot:\mathbb{R}\times\mathbb{R}^n\to\mathbb{R}^n$  are continuous  [[Continuity, Homeomorphism - Pf.#^266223|{Pf}]]

Cor. $\sin$, $\cos$, $\tan$, ${\rm arc}\ldots$, $\exp$, $\ln$ are continuous

Thm.
- Let
	- $X$ be a metric space with $d_X$
	- $f:X\to \mathbb{R}^n$,  $f(x)\coloneqq(f_1(x),\,...,\,f_n(x))$
	                where  $f_i:X\to\mathbb{R}$  $\forall\,i=1,\,...,\,n$
- $\implies$
	- $f$ is continuous $\iff$ $f_1$, ..., $f_n$ are continuous

