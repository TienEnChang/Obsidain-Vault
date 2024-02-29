
★ Variable => Fixed Value: $x$ => $\tilde{x}$ or $\hat{x}$

Def. utility function:  $U:X\to\mathbb{R}$
     (x) cardinal (v) ordinal

Def. positive monotonic transformation
- $F:\mathbb{R}\to\mathbb{R}$
- where
	- $F'(z)> 0$  $\forall\,z\in{\rm rng}(U)$  { $F$ is 1-1 }
- $\implies$
	- $V=F\circ U$, $U$ represents the same preference relation

Def.
- budget function:  $I(x_1,\,x_2)=p_1 x_1+p_2 x_2-m$
- budget line:      $p_1 x_1+p_2 x_2 = m$
- opportunity set:  $p_1 x_1+p_2 x_2 \leq m$

Rmk.
- $p_1$↑↓:  hinge at $\tilde{x}_1=0$,  $p_1$↓ => rotate outward  (逆時針)
- $p_2$↑↓:  hinge at $\tilde{x}_2=0$,  $p_2$↓ => rotate outward  (順時針)

---

Def. Lagrangian Function
- relation
	- $\exists\,\max\limits_{\vec x,\,\lambda}\,\mathcal{L}(\vec x,\,\lambda)\equiv[\;U(\vec x)-\lambda\cdot I(\vec x)\;]$ $\iff$ $\exists\,\max\limits_{\vec x}\,U|_{I(\vec x)=0}(\vec x)$
	- $\implies$
		- $\exists\,\vec x^*\in X$  $\exists\,\lambda^*\in\mathbb{R}$  s.t. ${}_{(\vec x,\,\lambda)}\nabla\,[\,U(\vec x^*)-\lambda^*\cdot I(\vec x^*)\,]=0$
			                $\iff$
		- $\exists\,\vec x^*\in X$  $\exists\,\lambda_0\in\mathbb{R}$  s.t. ${}_{(\vec x)}\nabla\,U(\vec x^*)=\lambda_0\cdot{}_{(\vec x)}\nabla\,I(\vec x^*)$  $\land$  $I(\vec x^*)=0$
		                           [[N-Dimensional - abs. extreme, lagrange mult.#^c722d0|{ Lagrange Mult. Thm. }]]
- quick formula:
	- $[U_{1},\,U_{2}](x_1,\,x_2)-\lambda\cdot(p_1,\,p_2)=0$  i.e.  $\dfrac{U_{1}}{U_{2}}(x_1,\,x_2)=\dfrac{p_1}{p_2}$  {tangency}
	- $(p_1x_1+p_2x_2-m)=0$
		                     solution: $\lambda^*$, $\vec x^*=(x_1^*,\,x_2^*)$

Def. marginal rate of substitution
- $\forall\,(\tilde{x}_1,\,\tilde{x}_2)\in\{\,U(x_1,\,x_2)=\phi^U\,\}$:  ${\rm MRS}$ or $\dfrac{dx_2}{dx_1}=-\dfrac{U_{1}}{U_{2}}$

Def. relative price:
- $\forall\,(\tilde{x}_1,\,\tilde{x}_2)\in\{\,I(x_1,\,x_2)=0\,\}$:  $\dfrac{p_1}{p_2}=-\dfrac{dx_2}{dx_1}(\tilde{x}_1,\,\tilde{x}_2)$

Def. marginal utility per dollar:  $\dfrac{U_{1}}{p_1}$