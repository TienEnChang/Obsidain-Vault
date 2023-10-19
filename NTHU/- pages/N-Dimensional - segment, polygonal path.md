
Def. line segment
- $\overline{PQ}\coloneqq\{\,P+t\,(Q-P)\;\big|\;t\in[\,0,\,1\,]\,\}$

Thm. MVT on a segment
- $f:U\subset\mathbb{R}^n\to\mathbb{R}$  
- where
	- $U$ is open $\land$ $P,\;Q\in U$
	- $f$ is differentiable on $\overline{PQ}\subset U$
- $\implies$
	- $\exists\,c\in\overline{PQ}$  s.t.  $f(Q)-f(P)=\nabla f(c)\cdot(Q-P)$

---

Def. polygonal path
- $\gamma:[\,a,\;b\,]\to\mathbb{R}^n$
- where
	- $\exists$ partition $\{\,a=t_0<...<t_n=b\,\}$  s.t.
	- $\forall\,i=0,\,...,\,n-1$
		- image of $\gamma\,|_{[\,t_i,\,t_{i+1}\,]}=\overline{\gamma({t_i})\,\gamma(t_{i+1})}$ 

Def. path connected
- $U\subset\mathbb{R}^n$ be open $\land$ non-empty
- where
	- $\forall\,P,Q\in U$
	- $\exists$ polygonal path $\gamma:[\,a,\,b\,]\to U$
		- s.t. $\gamma(a)=P$, $\gamma(b)=Q$

Let
- $f,\,g:U\subset\mathbb{R}^n\to\mathbb{R}$
- where
	- $U\subset\mathbb{R}^n$ be path connected
	- $f,\,g$ are differentiable

Thm.
- $\nabla f=0\implies f= c$
	( $c$ is some constant function )

Cor.
- $\nabla f=\nabla g\implies f= g+c$
  ( $c$ is some constant function )