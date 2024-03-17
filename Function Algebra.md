
Def. function algebra
- $\mathcal{A}\subseteq \mathcal{F}(X,\,F)$  with  $X$ metric space, $F$ field
- where
	- (1) $f+g \in \mathcal{A}$
	- (2) $f\cdot g \in \mathcal{A}$
	- (3) $cf \in \mathcal{A}$     $\forall\,f,\,g \in\mathcal{A}$, $\forall\,c \in F$

Def.
- $\mathcal{A}$ vanishes at $p \in X$:  $\forall\,f \in \mathcal{A}$: $f(p)=0$
- $\mathcal{A}$ vanishes nowhere:
	- $\forall\,p \in X$: $\exists\, f \in \mathcal{A}$  s.t. $f(p)\neq 0$
- $\mathcal{A}$ seperates points:
	- $\forall$ distinct $p,\,q \in X$: $\exists\, f \in \mathcal{A}$  s.t. $f(p)\neq f(q)$

---

Prop.
- $\mathcal{A}$ function algebra $\subseteq\mathcal{F}(X,\,\mathbb{R})$
- $\mathcal{A}$ vanishes nowhere & seperates points
- $\implies$ 
	- $\forall$ distinct $p_{1},\,p_{2} \in X$  $\forall\,c_{1},\,c_{2} \in \mathbb{R}$:
	- $\exists\, f \in \mathcal{A}$  s.t. $f(p_{1})=c_{1}$, $f(p_{2})=c_{2}$  [[Function Algebra - Pf.#^581bcd|{Pf}]]

Prop.
- $P(\mathbb{R})\coloneqq\left\{ \sum\limits_{k=0}^{n} a_{k}x^{k}\;|\; \big\{a_{k}\big\}_{k=0}^{n}\subseteq \mathbb{ R},\,n \in \mathbb{N}_{\cup \{0\}} \right\}\subseteq \mathcal{C}^{0}(\mathbb{R})$
- called the collection of polynomials on $\mathbb{R}$
- is <u>function algebra</u> that
	- vanishes nowhere, by $1\equiv x^{0}$
	- seperates points, by $f(x)\coloneqq x$ $\,\forall\, x$

Prop.
- $\Gamma(I)\coloneqq\left\{ \sum\limits_{k=0}^{n} a_{k}\cos(k\theta)+b_{k} \sin(k \theta)\;|\; \big\{a_{k}\big\}_{k=0}^{n},\,\big\{b_{k}\big\}_{k=0}^{n}\subseteq \mathbb{ R},\,n \in \mathbb{N}_{\cup \{0\}} \right\}\subseteq \mathcal{C}^{0}(I)$
- called the collection of trigonometric polynomials on $I\subseteq\mathbb{R}$
- $\implies$ 
- $\Gamma[0,\,2\pi)$ is <u>function algebra</u> that  [[Function Algebra - Pf.#^c6cf1e|{Pf}]]
	- vanishes nowhere, by $1\equiv\cos^{2}(x)+\sin^{2}(x)$
	- seperates points, by
		- $\begin{cases}\cos(x) &\text{if}\;\sin(p)= \sin(q)\\ \sin(x) &\text{o.w.}\end{cases}$
		- since  $\cos(p)=\cos(q)$  $\land$  $\sin(p)=\sin(q)$ $\implies$ $p=q$

---

Prop.
- For $X$ compact,
	- (1) $\mathcal{A}$ function algebra $\subseteq\mathcal{C}^{0}(X)\subseteq C_{b}(X)$ $\implies$ $\overline{\mathcal{A}}$ also  [[Function Algebra - Pf.#^415d1c|{Pf}]]
	- (2) $f \in \overline{\mathcal{A}}$ $\implies$ $|f| \in  \overline{\mathcal{A}}$  [[Function Algebra - Pf.#^e9586c|{Pf}]]

Thm. the Stone-Weierstrass thm.
- $X$ compact
- $\mathcal{A}$ function algebra $\subseteq\mathcal{C}^{0}(X)\subseteq C_{b}(X)$
- $\mathcal{A}$ vanishes nowhere & seperates points
- $\implies$ 
	- $\mathcal{A}$ dense $\subseteq\mathcal{C}^{0}(X)$  { i.e. $\overline{\mathcal{A}}=\mathcal{C}^{0}(X)$ }
		- OR
	- $\forall\,f \in\mathcal{C}^{0}(X)$:  $B_r(f)\cap \mathcal{A}\neq\varnothing$  $\forall\,r>0$
		- OR
	- $\forall\,f \in\mathcal{C}^{0}(X)$:  $\exists$ $(f_n)_{n\in\mathbb{N}}$ in $\mathcal{A}$  s.t. $\lim\limits_{n\to\infty}f_n=f$  { to be checked }

Cor. complex ver. S.W. thm.
- $X$ compact
- $\mathcal{A}$ function algebra $\subseteq\mathcal{C}^{0}(X,\, \mathbb{C})\subseteq C_{b}(X,\,\mathbb{C})$
- $\mathcal{A}$ vanishes nowhere & seperates points
- (\*) $\forall\,f \in \mathcal{A}$: $\overline{f} \in \mathcal{A}$
- $\implies$ 
	- $\mathcal{A}$ dense $\subseteq \mathcal{C}^{0}(X,\, \mathbb{C})$

---

Rmk.
- $\max(f,\,g)\coloneqq\dfrac{f+g}{2}+\dfrac{|f-g|}{2}$  { $\max(f,\,g,\,h)\coloneqq\max(\max(f,\,g),\,h)$ }
- $\min(f,\,g)\coloneqq\dfrac{f+g}{2}-\dfrac{|f-g|}{2}$  { $\min(f,\,g,\,h)\coloneqq\min(\min(f,\,g),\,h)$ }
- $\implies$ 
	- $f,\,g \in \overline{\mathcal{A}}$ $\implies$ $\max(f,\,g)$, $\min(f,\,g) \in \mathcal{\overline{A}}$  { for $\mathcal{A}\subseteq \mathcal{C}_{b}(X)$ }

Rmk. complex-valued functions
- $f:X \to \mathbb{C}$  where  
	- $f=\text{Re}(f)+i\,\text{Im}(f)$ | $\overline{f}=\text{Re}(f)-i\,\text{Im}(f)$
	- $||f||_{\sup}=||\text{Re}(f)||_{\sup}\cdot ||\text{Im}(f)||_{\sup}$
	- $\text{Re}(f)$, $\text{Im}(f)\in\mathcal{F}(X,\,\mathbb{R})$