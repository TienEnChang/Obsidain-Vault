
Def. Metric on $X$
- $d:X^2\to\mathbb{R}$  where  $\forall\,x,\,y\in X$:
	1. $d(x,\,y)\geq0$               {non-negativity}
	2. $d(x,\,y)=0$ $\iff$ $x=y$
	3. $d(x,\,y)=d(y,\,x)$          {symmetry}
	4. $d(x,\,y)+d(y,\,z)\geq d(x,\,z)$  {triangular inequality}

Def. Inherited metric on $A$ from $(X,\,d)$
- $d_A\coloneqq d\,|{_{A^2}}:A^2\to \mathbb{R}$  where  $d_A(x,\,y)\coloneqq d(x,\,y)$

Def. Metric space:  $(X,\,d)$

Def. Metric subspace of $(X,\,d)$:  $(A,\,d_A)$  where  $A\subseteq X$

Def. Circle , Open Ball
- Let $p\in X$
	- $C_r(p)\coloneqq\{\,x\in X\;|\;d(p,\,x)=r\,\}$  where  $r>0$
	- $B_r(p)\coloneqq\{\,x\in X\;|\;d(p,\,x)<r\,\}$  where  $r>0$

Def.
- standard product:  $<u,\,v>\;\coloneqq\displaystyle\sum_{i=1}^n u_i\,v_i$
- norm:  $||u||\coloneqq\sqrt{<u,\,u>}$

Thm. The Cauchy-Schwarz Inequality
- $||u||\;||v||\geq|<u,\,v>|$
- i.e. $(\displaystyle\sum_{i=1}^n u_i{}^2)\;(\sum_{i=1}^n v_i{}^2)\geq(\sum_{i=1}^n u_i\,v_i)^2$    { look for $x^2+y^2+\,...$ as (1) }

Def.
- Absolute difference (on $\mathbb{R}$):  $d(x,\,y)\coloneqq|x-y|$        [[Metric Space - Pf.#^353580|{Pf}]]
- Taxicab distance (on $\mathbb{R}^n$):    $d(x,\,y)\coloneqq\displaystyle\sum_{i=1}^n|x_i-y_i|$    [[Metric Space - Pf.#^bbd676|{Pf}]]
- Euclidean metric (on $\mathbb{R}^n$):    $d_E(x,\,y)\coloneqq||x-y||$      [[Metric Space - Pf.#^137a05|{Pf}]]
- Discrete metric (on $\mathbb{R}^n$):     $d(x,\,y)\coloneqq\begin{cases}1&{\rm if}\;x\neq y\\0&{\rm if}\;x=y\end{cases}$

Ex.
- Let $\mathscr{C}(X,\,\mathbb{R})\coloneqq\{\,f\;|\;f:X\to\mathbb{R}$ continuous$\,\}$
- $\implies$
- $d(f,\,g)\coloneqq\max\limits_{x\in X}|f(x)-g(x)|$  $\forall\,f,\,g\in\mathscr{C}(X,\,\mathbb{R})$ is a metric on $\mathscr{C}(X,\,\mathbb{R})$  [[Metric Space - Pf.#^85d704|{Pf}]]