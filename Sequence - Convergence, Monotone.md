
Related:  [[2. Limit & Continuity|Limit & Continuity]] in $\mathbb{R}$

---

\[ Metric Spaces: Convergence ]

Let $X$ be metric spaces with $d$,  $p\in X$

Def. Indexed Family
- $\{p_{i}\}_{i\in I}\coloneqq{\rm rng}((p_i)_{i\in I})$ or $\{\,x\in X\;|\;\exists\,i\in I$ s.t. $p_i=x\,\}$
	- sub:
		- $\big\{p_{i_{k}}\big\}_{k=1}^{n}\subseteq\{p_{i}\}_{i\in I}$
	- finite:
		- $\big\{p_{i}\big\}_{i=1}^{n}$             { $n$ 個 }
		- $\big\{p_{(i_{1},\,\cdots,\,i_{k})}\big\}_{i_1,\,\cdots,\,i_{k}=1}^{n}$  { $n^{k}$ 個 }

Def. Sequence
- $(p_n)_{n\in\mathbb{N}}$ in $X$:  $p_n\coloneqq f_{p_n}(n)$  where  $f_{p_n}:\mathbb{N}\to X$

Def. Subsequence of $(p_n)_{n\in\mathbb{N}}$
- $(p_{n_i})_{i\in\mathbb{N}}$  where  $(n_i)_{i\in\mathbb{N}}$ strictly increasing

Def. Limit of Sequence
- $\lim\limits_{n\to\infty}p_n=p$  i.e.  $p_n\to p$ as $n\to\infty$
- $\iff$
- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n\geq N$:  $d(p_n,\,p)<\varepsilon$  i.e.  $p_n\in B_{\varepsilon}(p)$

Def.
- $(p_n)_{n\in\mathbb{N}}$ converges:  $\exists\displaystyle\lim_{n\to \infty}p_n$
- $(p_n)_{n\in\mathbb{N}}$ diverges:   $\nexists\displaystyle\lim_{n\to \infty}p_n$

---

\[ Posets: Monotone ]

Let $X$ be poset, $(a_n)_{n\in\mathbb{N}}$ in $X$

Def.
- strictly increasing:           $a_{n}<a_{n+1}$  $\forall\,{i\in\mathbb{N}}$
- increasing / non-decreasing:   $a_{n}\leq a_{n+1}$  $\forall\,{i\in\mathbb{N}}$
- strictly decreasing:           $a_{n}>a_{n+1}$  $\forall\,{i\in\mathbb{N}}$
- decreasing / non-increasing:   $a_{n}\geq a_{n+1}$  $\forall\,{i\in\mathbb{N}}$

Def.
- monotonic:  increasing $\lor$ decreasing


\[ $\mathbb{R}^n$ ]

Prop.
- $(p_k)_{k\in\mathbb{N}}$ in $\mathbb{R}^n$ converges to $p\in\mathbb{R}^n$
- $\iff$
- $\forall\,i=1,\,...,\,n$:  $(p_{k\,(i)})_{k\in\mathbb{N}}$ in $\mathbb{R}$ converges to $p_{(i)}\in\mathbb{R}$

Prop.
- $(\lambda_k)_{k\in \mathbb{N}}$ in $\mathbb{R}$ converges to $\lambda\in\mathbb{R}$
- $(p_k)_{k\in\mathbb{N}}$ in $\mathbb{R}^n$ converges to $p\in\mathbb{R}^n$
- $\implies$
	- $(\lambda_k\,p_k)_{k\in \mathbb{N}}$ converges to $\lambda\,p$
	- $\lambda,\,\lambda_k\neq 0$  $\forall\,k\in\mathbb{N}$ $\implies$ $(\dfrac{p_k}{\lambda_k})_{k\in \mathbb{N}}$ converges to $\dfrac{p}{\lambda}$