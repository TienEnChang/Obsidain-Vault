
Maximal Decreasing Direction: $-\nabla f(x)$
- $\iff$
- $\displaystyle\lim_{a^+\to0}f(x-a\nabla f(x)_{\rm unit})=f(x)-\lim_{a^+\to0}a\cdot{\rm max\;value}^{(+)}$
	- Pf.
		- $\displaystyle\lim_{h\to0}\dfrac{f(\mathbb{X_0}+h\mathbb{V})-f(\mathbb{X_0})}{h}={f_{\mathbb{V}}}'(\mathbb{X_0})=\nabla f(\mathbb{X_0})\cdot\mathbb{V}$
		- $\implies$ $\displaystyle\lim_{h^+\to0}\dfrac{f(\mathbb{X_0}-h\nabla f(\mathbb{X_0})_{\rm unit})-f(\mathbb{X_0})}{h}=-{\rm max\;value}^{(+)}$

凸函數 Convex:   local min = global min
凹函數 Concave:  local max = global max

Gradient Decent
  "$h=\nabla f(x)$"  {multi-var, min}
- decision variable: $a$
- objective function: $\displaystyle\min_{a\geq0}f(x-a\nabla f(x))$
- ![[Screenshot 2023-08-16 at 2.55.35 PM.png]]

Newton's Method
  "$y=f'(x)$"   {single-var, max/min}
- tangent line at $x^k$:  $f'_L(x)=f'(x^k)+f''(x^k)(x-x^k)$
- get root $x^{k+1}$:  $f'_L(x^{k+1})=0$ $\implies$ $x^{k+1}=x^k-\dfrac{f'(x^k)}{f''(x^k)}$    
- stop:
	- $|f'(x^k)|<\varepsilon$  or  $|x^k-x^{k-1}|<\varepsilon$  {$\;\because$ $x^k\to x^{*}$}

Newton's Method
  "$h=\nabla f(x)$"  {multi-var, max/min}
- function at $x^k$:  $\nabla f_{N}(x)=\nabla f(x^k)+\nabla^2 f(x^k)(x-x^k)$
- get root $x^{k+1}$:  $\nabla f_{N}(x^{k+1})=0$
	- $\implies$
		- $x^{k+1}=x^k-\big[\nabla^2 f(x^k)\big]^{-1}\;\nabla f(x^k)$ ,  $\nabla^2$ is Hessian

![[Screenshot 2023-08-18 at 8.04.36 PM.png]]
![[Screenshot 2023-08-18 at 7.45.31 PM.png]]![[Screenshot 2023-08-18 at 7.54.21 PM.png]]