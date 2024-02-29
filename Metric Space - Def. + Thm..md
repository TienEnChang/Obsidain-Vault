
\[ Axioms ]

Def. Metric on $X$
- $d:X^2\to\mathbb{R}$  where  $\forall\,x,\,y\in X$:
	1. $d(x,\,y)\geq0$               {non-negativity}
	2. $d(x,\,y)=0$ $\iff$ $x=y$
	3. $d(x,\,y)=d(y,\,x)$          {symmetry}
	4. $d(x,\,y)+d(y,\,z)\geq d(x,\,z)$  {triangular inequality}

Def. Inherited metric on $Y\subseteq X$
- $d_Y\coloneqq d\,|{_{Y^2}}:Y^2\to \mathbb{R}$  where  $d_Y(x,\,y)\coloneqq d(x,\,y)$

Def.
- metric space:  $(X,\,d)$
- metric subspace:  $(Y,\,d_Y)$

---

\[ Common Metrics ]

Def. 
- standard product:  $<u,\,v>\;\coloneqq\displaystyle\sum_{i=1}^n u_i\,v_i$
- norm:  $\;||u||\coloneqq\sqrt{<u,\,u>}$               { $=||u||_2$ }
	
- $\ell_p$ norm:  $||u||_p\coloneqq[\sum\limits_{i=1}^n|u_{i}|^p]^{\frac1p}\,$ 
- $p$-adic norm:  $|z|_{p}=p^{-k}$  where  $k=\max\,\{\,n\in \mathbb{N}\;|\;z\equiv 0\;(\text{mod}\; p^n)\,\}$


Def. $\mathbb{R}^n$ metrics
- taxicab:    $d(x,\,y)\coloneqq||x-y||_1=\sum\limits_{i=1}^n|x_{i}-y_{i}|$       [[Metric Space - Pf.#^bbd676|{Pf}]]
- Euclidean:  $d_E(x,\,y)\coloneqq||x-y||_2=[\sum\limits_{i=1}^n(x_{i}-y_{i})^2]^{\frac12}\,$  [[Metric Space - Pf.#^137a05|{Pf}]]

Def. $M_{m\times n}(\mathbb{R})$ metrics
- taxicab:    $\,d(A,\,B)\coloneqq\sum\limits_{i=1}^n\sum\limits_{j=1}^m|A_{ij}-B_{ij}|$
- Euclidean:  $d_E(A,\,B)\coloneqq[\sum\limits_{i=1}^n\sum\limits_{j=1}^m(A_{ij}-B_{ij})^2]^{\frac12}\,$

Def. special metrics
- discrete:   $d_D(x,\,y)\coloneqq\begin{cases}1&{\rm if}\;x\neq y\\0&{\rm if}\;x= y\end{cases}$
- $p$-adic:     $d(x,\,y)\coloneqq|x-y|_p$       { for $\mathbb{Q}$ }

---

\[ Equivalent Metric ]

Def. 
- $d_1$, $d_2$ are equivalent metrics on $X$
- $\iff$
- $\exists\,\alpha,\,\beta> 0$  s.t. $\forall\,x,\,y\in X$:  
   (1) $\alpha\cdot d_1(x,\,y)\leq d_2(x,\,y)\leq \beta\cdot d_1(x,\,y)$
       or
   (2) $\alpha\cdot d_2(x,\,y)\leq d_1(x,\,y)\leq \beta\cdot d_2(x,\,y)$

Prop.
- Let $d_1$, $d_2$ be equivalent metrics on $X$,  $(p_n)_{n\in X}$ in $X$
- $\implies$
	- $\lim\limits_{n\to \infty}p_n=p$ in $d_1$ $\iff$ $\lim\limits_{n\to \infty}p_n=p$ in $d_2$  [[Metric Space - Pf.#^apwnvjk|{Pf}]]

---

\[ Combined Metric ]

Def. 
- $d_{\rm max}(p,\,q)\coloneqq {\max}\{\,d_1(p,\,q),\,d_2(p,\,q)\,\}$   { $\approx$ $\ell_\infty$ norm }
- $d_{\rm sum}(p,\,q)\coloneqq d_1(p,\,q)+d_2(p,\,q)\,$        { $\approx$ $\ell_1$ norm }
- $d_C(p,\,q)\coloneqq \sqrt{d_1(p,\,q)^2+d_2(p,\,q)^2}$      { $\approx$ $\ell_2$ norm }  [[Metric Space - Pf.#^dalngkd|{Pf}]]
- where
	- $d_1$, $d_2$ be metrics on $X_1$, $X_2$
	- $p,\,q\in X_1\times X_2$  with  $p=(p_1,\,p_2)$, $q=(q_1,\,q_2)$

Prop.
- $d_{\max}$, $d_{\rm sum}$, $d_C$ are equivalent metrics on $X_1\times X_2$
- $d_{\max}(p,\,q)\leq d_C(p,\,q)\leq d_{\rm sum}(p,\,q)\leq 2\,d_{\max}(p,\,q)$  $\forall\,p,\,q\in X_1\times X_2$


\[ Norm Inequalities ]

Thm.
- triangular "$\leq$" inequality:  $|a+b|$ "$=$" if 同號
                                     "$<$" if 異號

Thm. The Cauchy-Schwarz Inequality
- $||u||\;||v||\geq|<u,\,v>|$
- i.e. $(\displaystyle\sum_{i=1}^n u_i{}^2)\;(\sum_{i=1}^n v_i{}^2)\geq(\sum_{i=1}^n u_i\,v_i)^2$    { look for $x^2+y^2+\,...$ as (1) }
