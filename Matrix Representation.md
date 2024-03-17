
Def.
- $\beta=\{\beta_1,\,...,\,\beta_n\}$ is an ordered basis
- $\iff$
	- (1) $\beta$ is a basis
	- (2) with total order $\leq_\beta$ on $\beta$:  $\beta_i\leq_\beta \beta_{i+1}$  $\forall(1\leq i\leq(n-1))$
Rmk.
- $\beta=\beta'$ as ordered basis $\iff$ $(\beta,\,\leq_{\beta})=(\beta',\,\leq_{\beta'})$

---

Let
- $V$, $W$ be vector spaces over field $F$
	- with  ${\rm dim}(V)=n<\infty$, ${\rm dim}(W)=m<\infty$
- $\beta$, $\gamma$ be order bases of $V$, $W$
	- with  $\beta\coloneqq\{\,\beta_1,\,...,\,\beta_n\}$, $\gamma\coloneqq\{\,\gamma_1,\,...,\,\gamma_m\}$
- $T:V\to W$ be linear

Def. matrix multiplication
- $(AB)_{ij}\coloneqq\sum\limits_{k=1}^nA_{ik}B_{kj}$  (ith row x jth col)
- where
	- $A\in M_{m\times n}(F)$, $B\in M_{n\times q}(F)$, $AB\in M_{m\times q}(F)$

Def. column vector of $x$
- $[x]_\beta\coloneqq\begin{bmatrix}a_1\\\vdots\\a_n\end{bmatrix}$
- where
	- $\forall\,x\in V$:  $\exists\,!\,(a_1,\,...,\,a_n)$ in $F$  s.t.  $x=\sum\limits_{i=1}^na_i\beta_i$

Def. matrix representation of $T$
- $[T]_\beta^\gamma\in M_{m\times n}(F)$
- where
	- $([T]_\beta^\gamma)_{ij}\coloneqq a_{ij}\in F$
	- $a_{ij}$ determined by  $T(\beta_j)=\sum\limits_{i=1}^ma_{ij}\gamma_i$  $\forall\,j=1,\,...,\,n$  (j-th column)
- $\implies$
	- $[T]_\beta^\gamma=[\,[T(\beta_1)]_\gamma\,|\,...|\,[T(\beta_n)]_\gamma\,]$

Thm.
- $\forall\,u\in V$:  $[T(u)]_\gamma=[T]_\beta^\gamma\cdot[u]_\beta$  ( \[nx1] x \[mxn] = \[mx1] )

---

Let $\beta'$, $\gamma'$ be alternative order bases of $V$, $W$

Def. change of coordinate matrix: $[I_V]_\beta^{\beta'}$

Thm. $\forall\,x\in V$:  $[x]_{\beta'}=[I_V]_\beta^{\beta'}[x]_\beta$

Thm. $\forall\,T\in\mathcal{L}(V,\,V)$:  $[T]_{\beta'}=([I_V]_{\beta'}^{\beta})^{-1}\cdot [T]_\beta\cdot([I_V]_{\beta'}^{\beta})$  {conjugate}

Calc.
- $[x]_e=[I_V]_\beta^e[x]_\beta$  where  $e$ is the standard basis of $V$
- $\implies$
	- $[x]_e=[\,[\beta_1]_e\,|\,...|\,[\beta_n]_e\,]\cdot[x]_\beta$ ,  system of equation => $[x]_\beta$
    - $[x]_\beta=[\,[\beta_1]_e\,|\,...|\,[\beta_n]_e\,]^{-1}\cdot[x]_e$ ,  inverse matrix => $[x]_\beta$

---

Thm.
- $[T]_\beta^\gamma=[U]_\beta^\gamma$ $\iff$ $T=U$

Def.
- zero matrix:  $O_{m,\,n}\coloneqq[T_0]_\beta^\gamma$
- identity matrix:  $I_n\coloneqq[I_V]_{\beta}$

Def.
- Kronecker delta:  $\delta_{ij}\coloneqq\begin{cases}1&{\rm if}\;i=j\\ 0 & {\rm o.w.}\end{cases}$  ^c3952a

- multiplication trans: left vs. right
	![[Screenshot 2023-11-22 at 2.56.14 PM.png]]
	![[Screenshot 2023-11-22 at 2.56.31 PM.png]]