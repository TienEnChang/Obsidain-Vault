
Let
- $V$ be vector spaces over field $F$
	- $T\in\mathcal{L}(V)\,$, linear operator on $V$
	- $\beta_{0}$ be standard basis of $V$
- $A \in M_{n}(F)$, $L_{A}\in\mathcal{L}(F^{n})$

Note.
- for $\text{dim}(V)=n<\infty$:  
	- (1)  $\exists$ ordered basis  i.e.  $\beta_{0}=\{e_{1},\cdots,\,e_{n}\}$
	- (2)  $\exists$ column representation  i.e.  $x=[v_{x}]_{\beta_{0}} \in F^{n}$
	- (3)  $\exists$ matrix representation  i.e.  $A=[L_{A}]_{\beta_{0}} \in M_{n}(F)$

Def.
- eigenvalue of $T$:  $\lambda \in F$  with  $T(v)=\lambda v$  for some  $\vec{0} \neq v \in V$
	- { $v$ is eigenvector of $T$ cor. $\lambda$ }
	
- eigenbasis of $T$:  $\beta=\{$ eigenvectors of $T$ $\}$  also a basis of $V$

Def. { finite ver. }
- eigenvalue of $A$:  $\lambda \in F$  with  $(\lambda I_{n}-A) x=\vec{0}$  for some  $\vec{0} \neq x \in F^{n}$

---

Def.
- $T$ is diagonalizable:  $\exists$ eigenbasis of $T$

Def. { finite ver. }
- $T$ is diagonalizable:
	- $\exists$ ordered basis $\beta$ of $V$  s.t.
		- $[T]_{\beta}$ is diagonal
			- OR
		- $[\text{id}_{V}]_{\beta_{0}}^{\beta}[T]_{\beta_{0}}[\text{id}_{V}]_{\beta}^{\beta_{0}}$ is diagonal
			- OR
		- $T(u_{i})=([T]_{\beta})_{ii}\,u_{i}$  $\forall\,u_{i} \in \beta$  { i.e. $([T]_{\beta})_{ii}$ is eigenvalue of $T$ }

Def. { finite ver. }
- $A$ is diagonalizable:
	- $\exists$ eigenbasis of $L_{A}$
		- OR
	- $\exists$ invertible $Q \in M_{n}(F)$  s.t. $\,Q^{-1} A Q$  is diagonal

---

Thm.
- Let
	- $\{\lambda_{i}\}_{i \in I}$ indexing "some distinct" eigenvalues of $T$
	- $\{S_{i}\}_{i \in I}$ indexing set of "some" eigenvectors of $T$ cor. $\lambda_{i}$
- $\implies$ 
	- $S_{i}$ linearly indep.  $\forall\,i \in I$ $\implies$ $\bigcup\limits_{i \in I} S_{i}$ linearly indep. { $S_{i}$ disjoint }
Cor.
- $\{v_{i}\}_{i \in I}$ indexing eigenvector of $T$ cor. $\lambda_{i}$  { each $v_{i}$ cor. different $\lambda_{i}$ }
- $\implies$ $\{v_{i}\}_{i \in I}$ linearly indep.

