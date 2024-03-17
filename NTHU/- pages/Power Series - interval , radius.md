
Notice that  $\displaystyle\sum_{k=1}^{n}$  has been changed to  $\displaystyle\sum_{k=0}^{\infty}$

Def.
- power series:  $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$
	
- interval of convergence:  $I\coloneqq\{\,x\;\big|\;\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$  converges "pointwise" $\,\}$
- radius of convergence:
	- $r$  where  $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$
	  1. converges on  $(a-r,\,a+r)$
	  2. diverges on  $(-\infty,\, a-r)\cup(a+r,\,\infty)$
	- note that
	  1. $r=0$ $\iff$ converges only at  $a$
	  2. $r=\infty$ $\iff$ converges on  $\mathbb{R}$

Prop.
- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$ converges at $c\neq a$
- $\implies$ 
	- converges absolutely on $(a-r,\,a+r)$ where $r=|c-a|$
Prop.
- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$ diverges at $d$
- $\implies$
	- diverges on $(-\infty,\, a-r)\cup(a+r,\,\infty)$ where $r=|d-a|$

Prop.
- $\sum\limits_{{k=0}}^\infty a_k\,(x-a)^k$ converges on $(a-r,\,a+r)$ for some $r\geq 0$
- $\implies$
	- continuous, diff. on $(a-r,\,a+r)$