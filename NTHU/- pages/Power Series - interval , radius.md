
Notice that  $\displaystyle\sum_{k=1}^{n}$  has been changed to  $\displaystyle\sum_{k=0}^{\infty}$


Def.
- power series:
	- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$
Def.
- interval of convergence:
	- $I\coloneqq\{\,x\;\big|\;\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$  converges$\,\}$
Def.
- radius of convergence:
	- $r$  where  $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$
	  1. converges on  $(a-r,\,a+r)$
	  2. diverges on  $(-\infty,\, a-r)\cup(a+r,\,\infty)$
	- note that
	  1. $r=0$ $\iff$ converges only at  $a$
	  2. $r=\infty$ $\iff$ converges on  $\mathbb{R}$


Thm.
- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$  converges at $c\neq a$
- $\implies$ 
	- converges absolutely on $(a-r,\,a+r)$
	  where $r=|c-a|$
Thm.
- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$  diverges at $d$
- $\implies$
	- diverges on $(-\infty,\, a-r)\cup(a+r,\,\infty)$
	  where $r=|d-a|$


Thm. test for radius
- $\displaystyle\lambda\coloneqq\lim_{n\to\infty}\dfrac{|a_{n+1}|}{|a_n|}$
- $\implies$
	- { $\lambda\geq0$ }
	- case $\lambda=0$:   $r=\infty$
	- case $\lambda=\infty$:  $r=0$
	- else:         $r=\dfrac1\lambda$