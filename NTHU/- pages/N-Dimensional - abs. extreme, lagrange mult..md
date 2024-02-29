
Thm.
- $f:D\subset\mathbb{R}^n\to\mathbb{R}^n$ is continuous $\land$ $D$ is closed & bounded
- $\implies$
	- $f$ has abs. max & min

Method. 1
1. find all local extremes: ${\rm int}(D)=D-\partial D$
2. find all abs. extremes: $\partial D$
3. compare

Thm. ^c722d0
- $f,\,g_k:U\subset\mathbb{R}^n\to\mathbb{R}$
	- $U$ is open
	- $f,\,g_k$ are differentiable
- $f\big|_{g_1(\mathbb{X})=0\,\land\, g_2(\mathbb{X})=0\,...}$ has abs. extreme at $\mathbb{X}_0$
- $\implies$
- (1)
	- $\exists\lambda_k\in\mathbb{R}$ s.t. $\nabla f(\mathbb{X}_0)=\displaystyle\sum_{\nabla g_k(\mathbb{X}_0)\neq0}\lambda_k\cdot\nabla g_k(\mathbb{X}_0)$
		- where $\lambda_k$ is called the lagrange multiplier
- (2)
	- tangent line of $L_{(g_k,\,0)}$ at $\mathbb{X_0}$
	- $=$ tangent line of $L_{(f,\,c)}$ at $\mathbb{X_0}$ for some $c$   { tangency condition }

Method. 2
1. $\because$ $\;f$ is continuous
	  $\land$ set $\{\mathbb{X}\,\big|\,g(\mathbb{X})=0\}$ is closed and bounded
	 $\therefore$ $\;f\big|_{g(\mathbb{X})=0}$ has abs. extreme
2. use $\nabla f=\lambda\cdot\nabla g$  => find $\lambda$, $\mathbb{X_0}$