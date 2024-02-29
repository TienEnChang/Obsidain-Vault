
Def. $\sigma$-field on set $X$
- $\mathcal{F}\subseteq\mathcal{P}(X)$                { $E$ measurable: $E\in\mathcal{F}$ }
- where
	1. $\varnothing$, $X\in\mathcal{F}$
	2. $\forall\,A\in\mathcal{F}$: $A^c\in\mathcal{F}$
	3. $\forall\,A_i\in\mathcal{F}$: $\bigcup\limits_{i\in \mathbb{N}}A_i\in\mathcal{F}$

Def. measure on $\sigma$-field $\mathcal{F}$
- $\mu:\mathcal{F}\to\mathbb{R}$
- where
	1. $\forall\,A\in\mathcal{F}$: $\mu(A)\geq 0$    {non-negativity}
	2. $\mu(\varnothing)=0$
	3. $\forall$ pairwise disjoint $(A_n)_{n\in\mathbb{N}}$ in $\mathcal{F}$:
	          $\mu(\bigcup\limits_{n\in\mathbb{N}}A_n)=\sum\limits_{n\in\mathbb{N}}\mu(A_n)$    {additivity}
- $\implies$
	- $\forall$ increasing $(A_n)_{n\in\mathbb{N}}$ in $\mathcal{F}$ ( i.e. $A_1\subseteq\,...\,\subseteq A_n\,...$ ):
	    $\mu(\bigcup\limits_{n\in\mathbb{N}}A_n)=\lim\limits_{n\to\infty}\mu(A_n)$
	- $\forall$ decreasing $(A_n)_{n\in\mathbb{N}}$ in $\mathcal{F}$ ( i.e. $A_1\supseteq\,...\,\supseteq A_n\,...$ ):
	    $\mu(\bigcap\limits_{n\in\mathbb{N}}A_n)=\lim\limits_{n\to\infty}\mu(A_n)$
	    by assuming at least one of the $A_n$ has finite measure