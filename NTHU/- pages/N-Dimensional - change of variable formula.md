
Def.
- Jacobian matrix: $J(T)\coloneqq\begin{bmatrix}\dfrac{\partial T_1}{\partial  x_1}&\dfrac{\partial T_2}{\partial  x_2}\\\dfrac{\partial T_2}{\partial  x_1}&\dfrac{\partial T_2}{\partial  x_2}\end{bmatrix}$
- Jacobian: ${\rm det}(J(T))$

Thm.
- Let $\Gamma$ be
	- [[111-2 微數#^404f24|simply-connected]]
	- with [[#^9b2ab8|piecewise-smooth]] boundary
- $T:\Gamma\subset\mathbb{R}^2\to\mathbb{R}^2$
	- be a map $(u,\,v)\mapsto(x,\,y)$
	- defined by $T(u,\,v)=\begin{cases}x=T_1(u,\,v)\\y=T_2(u,\,v)\end{cases}$
	- where
		- $\dfrac{\partial^2}{\partial u^2}$, $\dfrac{\partial^2}{\partial v^2}$ are continuous
		- $T\vert_{{\rm int}(\Gamma)}$ is 1-1
		- $\det(J(\,T\vert_{{\rm int}(\Gamma)}\,))\neq0$
- $\implies$
- $f:\Omega\subset\mathbb{R}^2\to\mathbb{R}$ is continuous, $\Omega=T(\Gamma)$
	- $\displaystyle\iint_{\Omega}f(x,\,y)dxdy=\iint_{\Gamma}f\circ T(u,\,v)\,|\det(J(T))|\,dudv$

Cor.
- polar, cylindrical, spherical:
	- $0\not\in T({\rm int}(\Gamma))\implies T\vert_{{\rm int}(\Gamma)}$ is 1-1