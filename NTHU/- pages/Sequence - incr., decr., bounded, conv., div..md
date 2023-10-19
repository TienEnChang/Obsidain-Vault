-
- Def. Sequence
	- A sequence is a special function
	   $a: A\subseteq \mathbb{N}\to\mathbb{R}$, $A$ is an infinite set
	- special notations
	  (1) $a_n$ $\equiv$ $a(n)$   
	  (2) $\{a_n\}_{n=1}^{\infty}$ $\equiv$ $\{(n, a_n)\,|\,n\in\mathbb{N}\}$

- $\mathbb{Z}$ bijective $\mathbb{N}$:  0, 1, -1, 2, -2 ...  不需考慮兩個方向

- ---

- Def.  $\{a_n\}_{n=1}^{\infty}$  is

|                |                   |
| -------------- | ----------------- |
| increasing     | $a_{n+1}>a_n$     |
| non-decreasing | $a_{n+1}\geq a_n$ |
| non-increasing | $a_{n+1}\leq a_n$ |
| decreasing     | $a_{n+1}<a_n$     |
-
- Tech.  $a_{n+1}-a_n>0$   or   $\dfrac{a_{n+1}}{a_n}>1$   or   $f(n)=a_n$
-
- Def.
- For the set $A={\rm rng}(f)=\{f(x)\;|\;x \in {\rm dom}(f)\}$
- |||
  |--|--|
  |upper bound|${\rm ub}(A)$  where  $\forall\,a\in A$ ,  $a\leq {\rm ub}(A)$|
  |least upper bound / supremum|$\sup(A)\coloneqq$ $\min\{ m\;\vert\; m$ is an upper bound of $A\}$|
  |greatest lower bound / infimum|$\inf(A)\coloneqq$ $\max\{ m\;\vert\; m$ is an lower bound of $A\}$|
  |lower bound |${\rm lb}(A)$  where  $\forall\,a\in A$ ,  $a\geq{ \rm lb}(A)$|
-
- Def.  $n$  sufficiently large:  $\exists\,N\in\mathbb{N}$  s.t.  ${\forall\,n\geq N}$
-
- Def.
	- converges:  $\exists\displaystyle\lim_{n\to \infty}a_n$
	- diverges:  $\nexists\displaystyle\lim_{n\to \infty}a_n$
-