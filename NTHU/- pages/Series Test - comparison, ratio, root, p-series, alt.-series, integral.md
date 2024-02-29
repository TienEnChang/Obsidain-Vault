
Let $(a_{k})_{k\in\mathbb{N}}$, $(b_{k})_{n\in\mathbb{N}}$ be sequences in $\mathbb{R}$

- Thm.  the Comparison Test
- $\exists\,N \in\mathbb{N}$  s.t. $\forall\,k\geq N$:  $0\leq a_k\leq b_k$
- $\implies$
	- $\displaystyle\sum_{k=1}^\infty b_k$ converges $\implies$ $\displaystyle\sum_{k=1}^\infty a_k$ converges
	- $\displaystyle\sum_{k=1}^\infty a_k$ diverges $\implies$ $\displaystyle\sum_{k=1}^\infty b_k$ diverges

- ---

- Thm.  the Ratio Test
- $\forall\,k\in\mathbb{N}$:  $a_k\geq0$  $\land$  $\displaystyle\lim_{k\to\infty} \dfrac{a_{k+1}}{a_k}=\lambda$
- $\implies$
	- $\lambda>1\implies$ $\displaystyle\sum_{k=1}^\infty \,a_k$ diverges
	- $\lambda=1\implies$ inconlusive
	- $\lambda<1\implies$ $\displaystyle\sum_{k=1}^\infty \,a_k$ converges

- Thm.  the Root Test
- $\forall\,k\in\mathbb{N}$:  $a_k\geq0$  $\land$  $\displaystyle\lim_{k\to\infty} {}^k\!\!\sqrt{a_k}=\lambda$
- $\implies$
	- $\lambda>1\implies$ $\displaystyle\sum_{k=1}^\infty \,a_k$ diverges
	- $\lambda=1\implies$ inconlusive
	- $\lambda<1\implies$ $\displaystyle\sum_{k=1}^\infty \,a_k$ converges

- Thm.  the Limit Comparison Test
- $\forall\,k\in\mathbb{N}$:  $a_k\geq0$, $b_k>0$  $\land$  $\displaystyle\lim_{k\to\infty} \dfrac{a_{k}}{b_k}=\lambda$
- $\implies$
	- {$\lambda \neq \infty$}  $\lambda>0$ $\implies$ $\displaystyle\sum_{k=1}^\infty \,a_k,\;\displaystyle\sum_{k=1}^\infty \,b_k$  both  converges / diverges 

---


- Thm.  the P-Series Test
- $\displaystyle\sum_{k=1}^\infty \dfrac1{k^{\,p}}$
	- $p>1\implies$ converges
	- $p\leq1\implies$ diverges

- Thm.  the Alternating Series Test (for "converges conditionally")
- $\displaystyle\sum_{k=1}^\infty (-1)^k\,a_k$
	- 1. $\displaystyle\lim_{k\to\infty} a_k=0$
	  2. non-negative
	  3. non-increasing
		- $\implies$  converges

- Thm.  the Integral Test @
- Let  $f:[1,\,\infty)\to\mathbb{R}$  where  $f(k)=a_k$
	- 1. continuous
	  2. non-negative
	  3. non-increasing
	- $\implies$
		- $\displaystyle\int_1^{\infty} f(x)dx$ converges $\iff$  $\displaystyle\sum_{k=1}^\infty a_k$ converges
		- $\displaystyle\int_1^{\infty} f(x)dx$ diverges $\iff$  $\displaystyle\sum_{k=1}^\infty a_k$ diverges