
Let
- $f:U\subset\mathbb{R}^n\to\mathbb{R}$ $\land$ $U$ is open

Def. local maximum point
- $\exists$ neighborhood $V\subset U$ of $\mathbb{X_0}$
- s.t. $\forall\mathbb{X}\in V$, $f(\mathbb{X})\leq f(\mathbb{X}_0)$  

Def. local minimum point
- $\exists$ neighborhood $V\subset U$ of $\mathbb{X_0}$
- s.t. $\forall\mathbb{X}\in V$, $f(\mathbb{X})\geq f(\mathbb{X}_0)$  

Def. saddle point
- $\nabla f(\mathbb{X_0})=0$  $\land$  $\neg$ local extreme

Def. stationary point
- $\nabla f(\mathbb{X_0})=0$

Def. critical point
- $\nabla f(\mathbb{X_0})=0$  $\lor$  $\nabla f(\mathbb{X_0})$ D.N.E

---

Thm.
- local extreme $\implies$ critical point
Cor.
- stationary point $\implies$ local extreme  $\lor$  saddle point

Def.
- Hessian matrix: $H(f)=\begin{bmatrix}f_{xx}&f_{xy}\\ f_{yx}&f_{yy}\end{bmatrix}$
- boundary: $\partial S$

Thm. Second Derivative Test
- $\nabla f(\mathbb{X}_0)=0$
- $\nabla f(\mathbb{X})$ is continuous in "some neighborhood of $\mathbb{X_0}$"
- $\implies$
	- $\det H(f)_\mathbb{X_0}<0\implies$ saddle
	- $\det H(f)_\mathbb{X_0}>0$
		- $f_{xx}(\mathbb{X_0})<0\implies$ local max
		- $f_{xx}(\mathbb{X_0})>0\implies$ local min

Method. find local
- $\nabla f(\mathbb{X}_0)=0\,$:    use Second Derivative Test
- $\nabla f(\mathbb{X}_0)$ D.N.E:  use def.
	- $\forall\,r>0$, $\exists\,\mathbb{X}\in B_r(\mathbb{X}_0)$ s.t. $\mathbb{X}>\mathbb{X}_0$  ($\Rightarrow\!\Leftarrow$)