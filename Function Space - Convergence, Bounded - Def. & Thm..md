
\[ $\mathcal{F}(X,\,\mathbb{R})$ ]

Let
- $f\in\mathcal{F}(X,\,\mathbb{R})$,  $(f_{n})_{n \in\mathbb{N}}$ sequence in $\mathcal{F}(X,\,\mathbb{R})$

Def.
- $f_{n}\to f\,$ pointwise {$\lim\limits_{n\to\infty}f_{n}(x)=f(x)\;\;\forall\,x$}:
	- $\forall\,p\in X$: $(f_n(p))_{n\in\mathbb{N}}$ converges to $f(p)$
	
- $f_{n}\to f\,$ uniformly {$\lim\limits_{n\to\infty}f_{n}=f$}:
	- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n\geq N$  $\forall\, x\in X$:  $|f_n(x)-f(x)|<\varepsilon$  { @ }

Def.
- $(f_{n})_{n \in \mathbb{N}}\,$ pointwise Cauchy:  $\forall\,p\in X$: $(f_n(p))_{n\in\mathbb{N}}$ Cauchy
- $(f_{n})_{n \in \mathbb{N}}\,$ uniformly Cauchy: 
	- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n,\,m\geq N$  $\forall\, x\in X$:  $|f_n(x)-f_{m}(x)|<\varepsilon$  { @ }

Def.
- $(f_{n})_{n \in \mathbb{N}}\,$ pointwise bounded:   $\forall\,p\in X$:  $(f_{n}(p))_{n \in \mathbb{N}}$ bounded
- $(f_{n})_{n \in \mathbb{N}}\,$ uniformly bounded:
	- $\exists\,r>0$  s.t.  $\forall\,n \in \mathbb{N}$:  $\forall\,x \in X$:  $|f_{n}(x)|\leq r$  { @ }

Rmk.
- uniformly $\implies$ pointwise  [[Function Space - Convergence, Bounded - Pf.#^4d2875|{Pf}]]

Rmk.
- uniformly Cauchy $\implies$ uniformly bounded  { ?? to be proved }