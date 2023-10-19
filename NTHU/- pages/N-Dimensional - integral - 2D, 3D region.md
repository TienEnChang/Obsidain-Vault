
Def.
- type I region
	- $\Omega\coloneqq\{\,(x,\;y)\;{\big|}\;\begin{align} x\in[\,a,\,b\,] \\ y\in[\,\phi_1(x),\,\phi_2(x)\,] \end{align}\;\}$
	- where
		- $\phi_1,\phi_2:[\,a,\,b\,]\to\mathbb{R}$ are continuous
- type II region
	- $\Omega\coloneqq\{\,(x,\;y)\;{\big|}\;\begin{align} x\in[\,\psi_1(y),\,\psi_2(y)\,] \\ y\in[\,c,\,d\,] \end{align}\;\}$
	- where
		- $\psi_1,\psi_2:[\,c,\,d\,]\to\mathbb{R}$ are continuous

Def.
- basic region
	- $\Omega\coloneqq\bigcup\limits_{k=1}^n\Omega_k$
		- $\Omega_k$ is either type I or II
		- $\forall\,i\neq j$, $\Omega_i$ and $\Omega_j$ are sticked together
- sticked together
	- $\Omega_1\cap\Omega_2$ $\subset$ $\partial\,{\Omega_1}\cup\partial{\,\Omega_2}$ (非正式用法)

Def.
- 3D region
	- $V\coloneqq\{\,(x,\;y,\;z)\;{\bigg|}\;\begin{align} x\in[\,a,\,b\,] \\ y\in[\,\phi_1(x),\,\phi_2(x)\,]\\ z\in[\,\psi_1(x,\,y),\,\psi_2(x,\,y)\,] \end{align}\;\}$
	- where
		- $\phi_1,\,\phi_2:[\,a,\,b\,]\to\mathbb{R}$
		- $\psi_1,\,\psi_2:\{\,(x,\;y)\;{\big|}\;\begin{align} x\in[\,a,\,b\,] \\ y\in[\,\phi_1(x),\,\phi_2(x)\,] \end{align}\;\}\to\mathbb{R}$
			- are all continuous

Thm.
- $f$ is continuous on $\Omega$
- $\implies$
- $\displaystyle\iint_{\Omega}f(x,\,y)dxdy$
	- $=\displaystyle\int_a^b[\int_{\phi_1(x)}^{\phi_2(x)}f(x,\,y)dy\,]\,dx$  for type I
	- $=\displaystyle\int_c^d[\int_{\psi_1(y)}^{\psi_2(y)}f(x,\,y)dx\,]\,dy$  for type II

Thm.
- $f$ is continuous on $V$
- $\implies$
- $\displaystyle\iiint_{V}f(x,\,y\,z)dxdydz$
	- $=\displaystyle\int_{a}^{b}[\int_{\phi_1(x)}^{\phi_2(x)}[\int_{\psi_1(x,\,y)}^{\psi_2(x,\,y)}f(x,\,y,\,z)dz\,]\,dy\,]\,dx$

---

Method.
- area of $\Omega$ = $\displaystyle\iint_{\Omega}1dxdy$
- volume of $V$ = $\displaystyle\iiint_{V}1dxdydz$

Method.
- type II: $\Omega=\{\,(x,\;y)\;{\big|}\;\begin{align} x\in[\,\sqrt{y},\,1\,] \\ y\in[\,0,\,1\,] \end{align}\;\}$
	- $\displaystyle\iint_{\Omega}\dfrac{y\,e^{x^2}}{x^3}dxdy=\int_0^1y\,[\int_{y}^{1}\dfrac{e^{u}}{u^2}du\,]\,dy=\int_0^1y\,[\,{\rm Ei}(x)-\dfrac{e^x}{x}\,]\bigg|_{y}^{1}\,dy$ 
- vs.
- type I:  $\Omega=\{\,(x,\;y)\;{\big|}\;\begin{align} x\in[\,0,\,1\,] \\ y\in[\,0,\,x^2\,] \end{align}\;\}$
	- $\displaystyle\iint_{\Omega}\dfrac{y\,e^{x^2}}{x^3}dxdy=\int_0^1[\dfrac{\,e^{x^2}}{x^3}\cdot\dfrac{(x^2)^2}2]\,dx=\int_{0}^{1}\dfrac14{e^{u}}du$
