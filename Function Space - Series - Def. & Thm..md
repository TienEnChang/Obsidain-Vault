
\[ $\mathcal{F}(X,\,\mathbb{R})$ ]

Let $X$ be metric space with $d$,  $(f_{n})_{n \in \mathbb{N}}$ in $\mathcal{F}(X,\,\mathbb{R})$,  $f \in\mathcal{F}(X,\,\mathbb{R})$

Def.
- $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}$ converges
	- uniformly:   $\sum\limits_{n=1}^{\infty}f_{n}$ under $||\cdot||_{\sup}$ exists  { in $\mathcal{C}_{b}(X)$ }
	- pointwise:   $\sum\limits_{n=1}^{\infty}f_{n}(x)$ under $|\cdot|$ exists  $\forall\,x$  { any }
	- absolutely:  $( \sum\limits_{k=1}^{n}|f_{k}| )_{n \in \mathbb{N}}$ converges pointwise

Rmk.
- Series in $\mathbb{R}$ $\iff$ Series of constant function in $\mathcal{C}^{\infty}(X)\subseteq C_{b}(X)$


Thm. Weierstrass M-test
- $(f_{n})_{n \in \mathbb{N}}$ in $\mathcal{C}_{b}(X)$
- where
	- (1)  $\forall\,n \in \mathbb{N}$:  $||f_{n}||_{\text{sup}}\leq M_{n}$  for some  $M_{n}>0$
	- (2)  $\sum\limits_{n=1}^{\infty}M_{n}$ converges
- $\implies$
	- $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}$ converges uniformly, absolutely  [[Function Space - Series - Pf.#^ebd5be|{Pf}]]

Thm. Abel's Test
- $(f_{n})_{n \in \mathbb{N}}$, $(\varphi_{n})_{n \in \mathbb{N}}$ in $\mathcal{F}(X,\,\mathbb{R})$
- where
	- (1)  $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}\,$ converges uniformly
	- (2)  $(\varphi_{n})_{n \in \mathbb{N}}$  (i) bounded
	              (ii)  $\forall\,p \in X$: $\,(\varphi_{n}(p))_{n \in \mathbb{N}}\,$ monotone
- $\implies$ 
	- $( \sum\limits_{k=1}^{n}f_{k}\varphi_{n} )_{n \in \mathbb{N}}\,$ converges uniformly

Thm. Dirichlet’s Test
- $(f_{n})_{n \in \mathbb{N}}$, $(g_{n})_{n \in \mathbb{N}}$ in $\mathcal{F}(X,\,\mathbb{R})$
- where
	- (1)  $(\sum\limits_{k=1}^{n}f_{k})_{n \in \mathbb{N}}$  bounded
	- (2)  $(g_{n})_{n \in \mathbb{N}}\;$  (i)   $\;g_{n}\to \tilde{0}$  uniformly  
	                (ii)   $\!\forall\,p \in X$:  $g_{n}(p)\geq 0$
	                (iii)  $\forall\,p \in X$:  $g_{n}(p)$ decreasing
- $\implies$ 
	- $( \sum\limits_{k=1}^{n}f_{k}g_{n} )_{n \in \mathbb{N}}\,$ converges uniformly


Lemma. Abel's summation formula
-  ![[Screenshot 2024-01-05 at 12.02.58 AM.png]]