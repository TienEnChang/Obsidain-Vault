
\[ $\mathcal{C}_b(X)$ ]

Def. Bounded Functions
- $\mathcal{C}_b(X)\subseteq\mathcal{F}(X,\,\mathbb{R})$  metric space with  $d_{\sup\,}$ ( sup norm metric )
- where
	- $\mathcal{C}_b(X):=\{\,f\in\mathcal{F}(X,\,\mathbb{R})\;|\;f$ bounded $\}$
	- $d_{\rm sup}(f,\,g):=||f-g||_{\rm sup}$                { $||f||_{\rm sup}:=\sup\limits_{x\in X}\,|f(x)|\,$ }

Prop.
- $f$ bounded $\iff$ $||f||_{\rm sup}$ exists   { assume $f\neq\tilde{\varnothing}$ }

---

Def.
- $(f_{n})_{n \in \mathbb{N}}\,$ pointwise bounded:  $\forall\,p\in X$:  $(f_{n}(p))_{n \in \mathbb{N}}$ bounded ( under $|\cdot|$ )
- $(f_{n})_{n \in \mathbb{N}}\,$ uniformly bounded:
	- $(f_{n})_{n \in \mathbb{N}}\,$ bounded ( under $||\cdot||_{\sup}$ )
		- OR
	- $\exists\,r >0$  s.t. $\forall\,n \in \mathbb{N}$:  $||f_{n}||_{\sup}=d(f_{n},\,\tilde{0})<r$

Prop.
- For $(f_{n})_{n \in\mathbb{N}}$ in $\mathcal{C}_{b}(X)$,  $f\in\mathcal{C}_{b}(X)$
	- (1) $f_{n}\to f$ uniformly $\iff$ $f_{n}\to f$ under $d_{\text{sup}}$
	- (2) $(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy $\iff$ $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$

Thm.
- $\forall\,X$:  $\mathcal{C}_{b}(X)$ is complete metric space
         { $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$
           $\implies$ $f_{n}\to f$ uniformly  $\land$  "$f\in\mathcal{C}_{b}(X)$"  [[Function Space - Convergence - Pf.#^c2e716|{Pf}]]
           $\implies$ $f_{n}\to f$ under $d_{\text{sup}}$                }
Cor.
- $(f_{n})_{n \in \mathbb{N}}$ converges under $d_{\text{sup}}$ $\iff$ Cauchy under $d_{\text{sup}}$ $\implies$ bounded

---

Extra.
- Let
	- (1)  $\forall\,n \in \mathbb{N}$:  $||f_{n}-f||_{\text{sup}}\leq M_{n}$  for some  $M_{n}>0$
	- (2)  $\lim\limits_{n\to\infty}M_{n}=0$
- $\implies$ 
	- $f_{n}\to f\,$ uniformly ( not requiring $d_{\sup\,}$ )

---


\[ Metric Space, $\mathcal{F}(X,\,\mathbb{R}^{n})$ ]

Def.
- For $f\in\mathcal{F}(X,\,\mathbb{R}^{n})$,  $||f||_{\rm sup}:=\sup\limits_{x\in X}\,||f(x)||\,$  { all Thm in $\mathbb{R}$ applies in $\mathbb{R}^{n}$ }

