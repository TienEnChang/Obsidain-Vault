
\[ $\mathcal{C}_b(X)$ ]

Def. Bounded Functions
- $\mathcal{C}_b(X)\subseteq\mathcal{F}(X,\,\mathbb{R})$  metric space with  $d_{\sup\,}$ ( sup norm metric )
- where
	- $\mathcal{C}_b(X):=\{\,f\in\mathcal{F}(X,\,\mathbb{R})\;|\;f$ bounded $\}$
	- $d_{\rm sup}(f,\,g):=||f-g||_{\rm sup}$                { $||f||_{\rm sup}:=\sup\limits_{x\in X}\,|f(x)|\,$ }

Prop.
- $f\in\mathcal{C}_b(X)$ $\iff$ $||f||_{\rm sup}$ exists   { assume $f\neq\tilde{\varnothing}$ }

Thm. Cauchy Criterion
- $f_{n}\to f$ uniformly $\iff$ $(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy  [[Function Space - Convergence, Bounded - Pf.#^899846|{Pf}]]

Prop.
- For $(f_{n})_{n \in\mathbb{N}}$ in $\mathcal{C}_{b}(X)$,  $f\in\mathcal{C}_{b}(X)$
	- (1) $f_{n}\to f$ under $d_{\text{sup}}$ $\iff$ $f_{n}\to f$ uniformly
	- (2) $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$ $\iff$ $(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy
	- (3) $(f_{n})_{n \in \mathbb{N}}$ bounded under $d_{\text{sup}}$ $\iff$ $(f_{n})_{n \in \mathbb{N}}$ uniformly bounded

Thm.
- $\forall\,X$:  $\mathcal{C}_{b}(X)$ is complete metric space
         { $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$
           $\implies$ $f_{n}\to f$ uniformly  $\land$  "$f\in\mathcal{C}_{b}(X)$"  [[Function Space - Convergence, Bounded - Pf.#^c2e716|{Pf}]]
           $\implies$ $f_{n}\to f$ under $d_{\text{sup}}$                }
Cor.
- $f_{n}\to f$ under $d_{\text{sup}}$ $\iff$ $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$

Rmk.
- $(f_{n})_{n \in \mathbb{N}}$ Cauchy under $d_{\text{sup}}$ $\implies$ bounded under $d_{\text{sup}}$

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

