
\[ $\mathcal{F}(X,\,\mathbb{R})$ ]

Let
- $f\in\mathcal{F}(X,\,\mathbb{R})$,  $(f_{n})_{n \in\mathbb{N}}$ sequence in $\mathcal{F}(X,\,\mathbb{R})$

Def.
- $f_{n}\to f\,$ pointwise  {$f(x)=\lim\limits_{n\to\infty}f_{n}(x)$ $\,\forall\,x\,$ under $|\cdot|\,$}
	- $\forall\,p\in X$: $(f_n(p))_{n\in\mathbb{N}}$ converges to $f(p)$
	
- $f_{n}\to f\,$ uniformly  {$f=\lim\limits_{n\to\infty}f_{n}$ under $||\cdot||_{\sup}$,  if in $\mathcal{C}_{b}(X)$}
	- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n\geq N$  $\forall\, x\in X$:  $|f_n(x)-f(x)|<\varepsilon$  { @ }

Def.
- $(f_{n})_{n \in \mathbb{N}}\,$ pointwise Cauchy:  $\forall\,p\in X$: $(f_n(p))_{n\in\mathbb{N}}$ Cauchy
- $(f_{n})_{n \in \mathbb{N}}\,$ uniformly Cauchy: 
	- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n,\,m\geq N$  $\forall\, x\in X$:  $|f_n(x)-f_{m}(x)|<\varepsilon$  { @ }

Rmk.
- uniformly $\implies$ pointwise  [[Function Space - Convergence - Pf.#^4d2875|{Pf}]]
- uniformly  $\land$  pointwise to $f$ $\implies$ uniformly to $f$  { ?? to be proved }

Thm. Cauchy Criterion
- $f_{n}\to f$ uniformly $\iff$ $(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy  [[Function Space - Convergence - Pf.#^899846|{Pf}]]