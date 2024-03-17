
\[ Axioms ]

Def. Real Numbers
- $\mathbb{R}\coloneqq\{$ all Cauchy sequences in $\mathbb{Q}$ $\}/\!\sim$ is ordered field with $(+,\,\cdot\,,\,\leq)$
- where
	- $\forall$ Cauchy $(a_n)_{n\in\mathbb{N}}$, $(b_n)_{n\in\mathbb{N}}$ in $\mathbb{Q}$:
		- $(a_n)_{n\in\mathbb{N}}$ $\sim$ $(b_n)_{n\in\mathbb{N}}$ $\iff$ $(a_n-_{\mathbb{Q}}b_n)_{n\in\mathbb{N}}$ converges to $0$

Def. Real Numbers as Ordered Field
- $(\mathbb{R},\,+,\,\cdot\,,\,\leq)$
- where
	- $\forall$ $a\coloneqq[(a_n)_{n\in\mathbb{N}}]$, $b\coloneqq[(b_n)_{n\in\mathbb{N}}]$ $\in\mathbb{R}$:
	- for "$+$":
		- $a+b\coloneqq[(a_n+_{\mathbb{Q}}b_n)_{n\in\mathbb{N}}]$
	- for "$\,\cdot\,$":
		- $\,a\cdot b\coloneqq[(a_n\;{\cdot\,}_{\mathbb{Q}}\;b_n)_{n\in\mathbb{N}}]$
	- for "$\leq$":
		- $a\leq b$ $\iff$ $\exists\;(a'_n)_{n\in\mathbb{N}}\in a$, $(b'_n)_{n\in\mathbb{N}}\in b$  s.t. 
		                 $\,\exists\;N\in\mathbb{N}$  s.t. $\forall\,n>N$:  $a'_n\leq_{\mathbb{Q}}b'_n$

Def. Real Numbers as Metric Space
- $(\mathbb{R},\,d_E)$
- where  $|\cdot|:\mathbb{R}\to\mathbb{R}$  by  $|a|\coloneqq[(|a_n|_\mathbb{Q})_{n\in\mathbb{N}}]$  $\,\forall\;a\coloneqq[(a_n)_{n\in\mathbb{N}}]\in\mathbb{R}$


\[ Properties: Complete ]

Thm.
- $\mathbb{R}$ is complete "metric space" { also $\mathbb{R}^n$ }  [[Real Numbers - Pf.#^c4c8fb|{Pf}]]


\[ Properties: Bounded, Monotone ]

Thm. $\mathbb{R}$ is complete "total ordered set"
- For $A\subseteq\mathbb{R}$,
	- l.u.b. property:  $A\neq\varnothing$  $\land$  $A$ bounded above $\iff$ $\exists\sup(A)$  [[Real Numbers - Pf.#^6b01a2|{Pf}]] 
	- g.l.b. property:  $A\neq\varnothing$  $\land$  $A$ bounded below $\iff$ $\exists\inf(A)$

Prop.
- $A$ closed $\subseteq \mathbb{R}$,
	- $\exists\sup(A)$ $\implies$ $\sup(A)\in A$  { i.e. $\max(A)=\sup(A)$ }  [[Real Numbers - Pf.#^c45e8b|{Pf}]]
	- $\exists\inf(A)$ $\implies$ $\inf(A)\in A$   { i.e. $\min(A)=\inf(A)$ }

Thm.
- $(a_n)_{n\in\mathbb{N}}$ in $\mathbb{R}$ increasing,
	- $(a_n)_{n\in\mathbb{N}}$ converges $\iff$ $(a_n)_{n\in\mathbb{N}}$ is bounded above  [[Real Numbers - Pf.#^440c59|{Pf}]]
	            $\;${ $\displaystyle\lim_{n\to \infty}a_n =\,\sup({\rm rng}(\,(a_n)_{n\in\mathbb{N}}\,)$ }
	
- $(a_n)_{n\in\mathbb{N}}$ in $\mathbb{R}$ decreasing,
	- $(a_n)_{n\in\mathbb{N}}$ converges $\iff$ $(a_n)_{n\in\mathbb{N}}$ is bounded below  [[Real Numbers - Pf.#^440c59|{Pf}]]
	            $\;${ $\displaystyle\lim_{n\to \infty}a_n =\,\inf({\rm rng}(\,(a_n)_{n\in\mathbb{N}}\,)$ }
Cor.
- $(a_n)_{n\in\mathbb{N}}$ in $\mathbb{R}$ monotonic,
	- $(a_n)_{n\in\mathbb{N}}$ converges $\iff$ $(a_n)_{n\in\mathbb{N}}$ is bounded

Prop. (HW)
- $\forall$ $(a_{n})_{n \in \mathbb{N}}$ in $\mathbb{R}$:  $\exists\,$ monotonic $(a_{n_{k}})_{k \in\mathbb{N}}$ in $\mathbb{R}$  {[Pf - Math Stack Exchange](https://math.stackexchange.com/questions/716461/proof-verification-every-sequence-in-bbb-r-contains-a-monotone-sub-sequence)}
Cor.
- $(a_{n})_{n \in \mathbb{N}}$ in $\mathbb{R}$ bounded $\implies$ $\exists\,$ $(a_{n_{k}})_{k \in\mathbb{N}}$ in $\mathbb{R}$ converges 

---

Thm.
- $\mathbb{R}$ has decimal / binary expansion (onto, not unique)  { $|[0,\,1]|\leq |2^{\mathbb{N}}|$ }

Def. 
- $A\subseteq \mathbb{R}$  is convex:  $\forall\,x,\,y\in A$:  $\{\,(1-t)\,x+t\,y\;|\;t \in[0,\,1]\,\}\subseteq A$