
Note
- curve "$x=y$"
- $\iff$
- (1)
	- ${\rm img}(r)$, where
	- $r:\mathbb{R}\to\mathbb{R}^2$,  $r(t)\coloneqq(t,\,t)$
- (2)
	- $\{(x,\,y)\,\big|\,h(x,\,y)=0\}$, where
	- $h:\mathbb{R}^2\to\mathbb{R}$,  $h(x,\,y)\coloneqq x-y$
- (3)
	- ${\rm graph}(f)$, where
	- $f:\mathbb{R}\to\mathbb{R}$,  $f(x)\coloneqq x$

---

Def.
- level curve (a.k.a implicit curve):
	- $L_c\coloneqq\{(x,\,y)\in{\rm dom}(f)\,\big|\,f(x,\,y)=c\}$
	- where
		- $f:U\subset\mathbb{R}^2\to\mathbb{R}$, $U$ is open

Thm.
- $L_c$ is defined by $f$, $f$ is differentiable
- $(x_0,\,y_0)\in L_c$ $\land$ $\dfrac{\partial f}{\partial y}(x_0,\,y_0)\neq0$
- $\implies$
- (1)
	- $\dfrac{dy}{dx}=-\dfrac{\frac{\partial f}{\partial x}}{\frac{\partial f}{\partial y}}$ at $(x_0,\,y_0)$
	- where $y=y(x)$ in some neighborhood of $(x_0,\,y_0)$
	  by the Implicit Function Theorem
- (2)
	- the tangent line at $(x_0,\,y_0)$
	- can be defined by
		- 1. $\{(x,\,y)\,\big|\,y-y_0=\dfrac{dy}{dx}(x_0,\,y_0)(x-x_0)\}$
		- 2. $\{(x,\,y)\,\big|\,\nabla f(x_0,\,y_0)\cdot(x-y_0,\,y-y_0)=0\}$