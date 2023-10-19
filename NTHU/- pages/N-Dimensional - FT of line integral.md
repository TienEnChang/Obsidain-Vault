
Def. line integral
- $h:\mathbb{R}^3\to\mathbb{R}^3$ 
	- is a continuous vector field
	- defined by $h(x,\,y,\,z)=(h_1(...),\,h_2(...),\,h_3(...))$
- $c: r(t),\;t\in[\,a,\,b\,]$
	- is [[#^9b2ab8|piecewise-smooth]]
	- defined by $r(t)=(x(...),\,y(...),\,z(...))$
- $\implies$
- $\displaystyle\int_c h\cdot dr\displaystyle$
	- $\displaystyle\coloneqq\int_a^b h(r(t))\cdot[\,r'(t)dt\,]$
	- $=\displaystyle\sum\int_a^b h_k(r(t))\,[\,{r_k}'(t)dt\,]$
	- $=\displaystyle\int_c h_1\,dx+\int_c h_2\, dy+\int_c h_3\, dz$

Thm. Fundamental Theorem of Line Integral
- $f:U\in\mathbb{R}^n\to\mathbb{R}$
	- $U$ is open
	- is [[#^c449c3 |continuously differentiable]]
- $c\in U$
	- is [[#^9b2ab8|piecewise-smooth]]
- $\implies$
- (1) $\displaystyle\int_c \nabla f\cdot dr=f(r(b))-f(r(a))$
- (2) $\displaystyle\oint_c \nabla f\cdot dr=0$