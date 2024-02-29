
\[ Metric Space & $\mathcal{F}(X,\,\mathbb{R})$ ]

Def.
- $f$ continuous:
	- $\forall\,p\in X$  $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t.
		- $\forall\,q\in X$  with  $d_{X}(p,\,q)<\delta$:  $d_{Y}(f(p),\,f(q))<\varepsilon$
- $f$ uniformly continuous:
	- $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t.
		- $\forall\,x,\,y\in X$  with  $d_{X}(x,\,y)<\delta$:  $d_{Y}(f(x),\,f(y))<\varepsilon$
- $(f_{n})_{n \in \mathbb{N}}$ equi-continuous:
	- $\forall\,\varepsilon>0$  $\exists\,\delta>0$  s.t.
		- $\forall\,n \in \mathbb{N}$:  $\forall\,x,\,y\in X$  with  $d_{X}(x,\,y)<\delta$:  $d_{Y}(f_{n}(x),\,f_{n}(y))<\varepsilon$

Def.
- continuous functions:   $\mathcal{C}^{k}(X)\coloneqq\{\,f:X\to \mathbb{R}\;|\;f$ continuous, $k$th diff.$\,\}$
- smooth functions:       $\mathcal{C}^{\infty}(X)$                { $\mathcal{C}^{0}(X)\supseteq \cdots\supseteq \mathcal{C}^{\infty}(X)$ }

Thm.
- For $f_{n}\to f\,$ uniformly,
	- $f_{n}$ continuous at $x_{0}$  $\forall\,n \in \mathbb{N}$ $\implies$ $f$ continuous at $x_{0}$
Cor. ^72f966
- $X$ compact:  $\mathcal{C}^{0}(X)$ closed $\subseteq \mathcal{C}_{b}(X)$  { $\mathcal{C}^{0}(X)$ complete metric space } [[Function Space - Sup Norm Metric - Pf.#^8d7f04|{Pf}]]

Thm. 
- $X$ compact:  $f$ continuous $\iff$ $f$ uniformly continuous [[Compactness - Pf.#^4d8ad2|{Pf}]]


Extra.
- $X$ compact  $\land$  $(f_{n})_{n \in\mathbb{N}}$ in $\mathcal{C}^{0}(X)\subseteq \mathcal{C}_{b}(X)$,
	- $f_{n}\to f\,$ under $d_{\sup\,}$ $\implies$ $(f_{n})_{n \in \mathbb{N}}$ equi-continuous 


Thm. Arzela-Ascoli Thm.
- $X$ compact  $\land$  $(f_{n})_{n \in \mathbb{N}}$ in $\mathcal{C}^{0}(X)\subseteq \mathcal{C}_{b}(X)$
- where
	- (1)  $(f_{n})_{n \in \mathbb{N}}$ bounded
	- (2)  $(f_{n})_{n \in \mathbb{N}}$ equi-continuous
- $\implies$ 
	- $\exists$ subsequence $f_{n_{k}}\to f$ under $d_{\sup\,}$  $\land$  $f\in\mathcal{C}^{0}(X)$

Thm. Generalized Heine-Borel
- $X$ compact  $\land$  $\mathscr{F}\subseteq\mathcal{C}^{0}(X)\subseteq \mathcal{C}_{b}(X)$
- $\implies$ 
	- $\mathscr{F}$ is compact $\iff$ $\mathscr{F}$ is (1) closed
	                           (2) bounded
	                           (2) equi-continuous  [[Function Space - Continuity - Pf.#^0f3a2b|{Pf}]]

Lemma.
- $X$ compact $\implies$ $\exists \,U\subseteq X$  countable, dense

---


\[ Metric Space & $\mathcal{C}^{0}(\mathbb{R})$, $\mathcal{C}^{1}(\mathbb{R})$ ]

Thm. The Mean Value Thm.
(#1)  $\,f$ is continuous on $[a,b]$
(#2)  $f$ is differentiable on $(a,b)$
	  $\implies$
	  $\exists\,c\in(a,\;b)$ s.t. ${f(b)-f(a)}=f'(c)({b-a})$ ^be015b

Thm. The Cauchy MVT
(#1)  $\,f,\;g$ satisfies all hypothesis of MVT
(#2)  $g'\neq0$ on $(a,\,b)$  $\land$  $g(b)\neq g(a)$
      $\implies$
	  $\exists\,c\in(a,\;b)$ s.t. $\dfrac{f(b)-f(a)}{g(b)-g(a)}=\dfrac{f'(c)}{g'(c)}$

Thm.
- $f\in\mathcal{C}^{0}(\mathbb{R})$  $\not\!\!\!\!\implies$ $f\in\mathcal{C}^{1}(\mathbb{R})$   [[Function Space - Sup Norm Metric - Pf.#^6be7af|{Pf by Weierstrass function}]]