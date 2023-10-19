
Def.
- Riemann integrable: $\displaystyle\lim_{\|P\|\to 0}S_f(P)$ exists
- double integral
	- $\displaystyle\iint_Rf(x,\,y)dxdy\coloneqq\displaystyle\lim_{\|P\|\to 0}S_f(P)$
- tripple integral
	- $\displaystyle\iiint_Vf(x,\,y,\,z)dxdydz\coloneqq\displaystyle\lim_{\|P\|\to 0}S_f(P)$

Def.
- Riemann sum
	- $\displaystyle S_f(P)=\sum_{i=0}^{n-1}\sum_{j=0}^{n-1}f(t_i,\,s_i)\Delta A_{ij}$
- rectangle
	- $R=[\,a,\;b\,]\times[\,c,\;d\,]=\{\,(x,\;y)\;{\big|}\;\begin{aligned} x\in[\,a,\,b\,] \\ y\in[\,c,\,d\,] \end{aligned}\;\}$
- partition
	- $P\coloneqq\{\,(t_i,\;s_j)\;{\big|}\;{\begin{aligned} {a=t_0<\,...\,<t_n=b} \\ {c=s_0<\,...\,<s_n=d} \end{aligned}}\;\}$
	- where
		- $||P||\coloneqq\max\{\,\Delta A_{ij}\;\big|\;i,\,j=0,\,...\,,\,n-1\}$
		- $A_{ij}\coloneqq(t_{i+1}-t_{i})\cdot(s_{i+1}-s_{i})$

Def.
- $f:B\subset\mathbb{R}^2\to\mathbb{R}$ $\land$ $B$ is bounded
- $\implies$
	- $\displaystyle\iint_Bf(x,\,y)dxdy\coloneqq\iint_R\widetilde{f}(x,\,y)dxdy$
	- where
		- $R\subset\mathbb{R}^2$ is a rectangle s.t. $B\subset R$
		- $\widetilde{f}(x,\,y)\coloneqq\begin{cases}f(x,\,y)&\forall\,(x,\,y)\in B\\\,\;\;\;\;0&\forall\,(x,\,y)\in R-B\end{cases}$