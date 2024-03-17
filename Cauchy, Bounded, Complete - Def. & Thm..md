
Let $X$ be metric spaces with $d$, $A\subseteq X$

\[ Convergence, Bounded ]

Def.
- $(p_n)_{n\in\mathbb{N}}$ in $X$ is Cauchy:
	- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t. $\forall\,n,\,m >N$:  $d(p_n,\,p_m)<\varepsilon$  
	             { W.L.O.G  $\forall\,n>m> N$ }

Prop.                [[Cauchy Sequence - Pf.#^2f73de|{Pf}]]        $\;$[[Cauchy Sequence - Pf.#^2a414b|{Pf}]]
- $(p_n)_{n\in\mathbb{N}}$ converges $\implies$ Cauchy $\implies$ bounded  
               $\,${strict}     $\,${general}

Contra.
- $(p_n)_{n\in\mathbb{N}}$ unbouned $\implies$ not Cauchy $\implies$ diverges

Prop.
- $(p_n)_{n\in\mathbb{N}}$ is Cauchy,
	- $\exists$ subsequence $(p_{n_k})_{k\in\mathbb{N}}$ converges to $p\in X$
		- $\implies$
			- $(p_n)_{n\in\mathbb{N}}$ converges to $p\in X$
		      $\,${ point of convergence is unique }

\[ Complete ]

Def.
- $X$ is complete:  $\forall\,$ Cauchy $(p_n)_{n\in\mathbb{N}}$ in $X$:  $(p_n)_{n\in\mathbb{N}}$ converges in $X$

Thm.
- $X$ is complete $\iff$ $X$ closed $\subseteq \Omega$   $\forall$ metric space $\Omega\supseteq X$  [{Pf}](https://math.stackexchange.com/questions/1775403/is-every-complete-metric-space-closed)

Prop. inheritence
- For $A$ closed $\subseteq X$, 
	- $X$ is complete $\implies$ $A$ is complete