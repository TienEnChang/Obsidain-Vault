
Def. binomial coefficients
- For $n,\,k\in \mathbb{N} \cup \{0\}$, $k\leq n$:
	- $\displaystyle\binom{n}{k} := \dfrac{n!}{k!\,(n-k)!}= \dfrac{n (n-1) (n-2) \cdots (n-(k-1))}{k!}$

Def. generalized binomial coefficients
- For $r\in\mathbb{R}$:
	- $\displaystyle\binom{r}{k}\coloneqq\begin{cases}\dfrac{r (r-1) (r-2) \cdots (r-(k-1))}{k!}&\text{if}\;k\in\mathbb{N}\\1&\text{if}\;k=0\end{cases}$

Thm. generalized binomial thm.  [[Generalized Binomial Thm - Pf.#^c18909|{Pf}]]
- For $r\geq 0$:  $(1 + x)^r=\sum\limits_{k=0}^{\infty}\displaystyle\binom{r}{k}\,x^k\,$ under $||\cdot||_{\sup}$ on $[-1,\,1]$

Cor.
- On $[-M,\,M]$ for some $M>0$,
	- $|x|=M\cdot[1+(\dfrac{x^{2}}{M^{2}}-1)]^{{\frac{1}{2}}}=M\cdot \sum\limits_{k=1}^{\infty}{\displaystyle {\frac{1}{2}\choose k}}(\dfrac{x^{2}}{M^{2}}-1)^{k}$

===

Lemma.
- For $r\geq 0$:  $\displaystyle\sum_{k=0}^{\infty}\binom{r}{k}$  converges absolutely

Lemma.
- $(r-k)\displaystyle{r\choose k}+(r-(k-1)){\displaystyle r\choose k-1}=r{\displaystyle r\choose k}$