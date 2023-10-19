
Note: default direction = counterclockwise

Thm. Green's Thm.
- $P,Q:U\subset\mathbb{R}^2\to\mathbb{R}$
	- is [[#^c449c3 |continuously differentiable]]
- $\Omega$ is the region with
	- the outer bound $c_1\in U$
	- the inner bound $c_2\in U$
		- which are [[#^d47ff4|simple]], [[#^c55d83|closed]], [[#^9b2ab8|piecewise-smooth]] curve
- $\implies$
	- $\displaystyle\iint_{\Omega}(\dfrac{\partial Q}{\partial x}-\dfrac{\partial P}{\partial y})dxdy=\mathrlap{\hskip{.11em}\circlearrowleft}{\int}_{c_1}\;Pdx+Qdy-\mathrlap{\hskip{.11em}\circlearrowleft}{\int}_{c_2}\;Pdx+Qdy$

Thm.
- $\displaystyle {\rm Area}(\Omega)=\iint_{\Omega}1dxdy$
	- (1) $=\displaystyle\mathrlap{\hskip{.11em}\circlearrowleft}{\int}_c\;xdy$
	- (2) $=\displaystyle\mathrlap{\hskip{.11em}\circlearrowleft}{\int}_c-ydx$
	- (3) $\displaystyle=\dfrac12\mathrlap{\hskip{.11em}\circlearrowleft}{\int}_c-ydx+xdy$