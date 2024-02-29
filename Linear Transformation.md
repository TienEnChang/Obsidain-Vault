
Let
- $V$, $W$ be vector spaces over field $F$

Def. linear transformation
- $T:V\to W$
- where
	- $\forall\,x,\,y\in V$:  $T(x +_v y)$ = $T(x) +_w T(y)$   {preservation of "$+$"}
	- $\forall\,x\in V$, $c\in F$:  $T(c \cdot_v x)$ = $c \cdot_w T(x)\;$   {preservation of "$\,\cdot\,$"}
- $\implies$
	- $T$ is linear $\iff$ $T(c\cdot x+y)=c\cdot T(x)+T(y)$   { one-step test }

Def.
- null space of $T$:
	- $N(T)$ or ${\rm null}(T)\coloneqq T^{\leftarrow}(\{\,\vec 0_w\,\})$ $\implies$ $N(T)$ is a subspace of $V$  {Thm.}
- range of $T$:
	- $R(T)$ or ${\rm rng}(T)\coloneqq T(V)$ $\implies$ $T(V)$ is a subspace of $W$  {Thm.}

Def.
- nullity of $T$:  ${\rm nullity}(T)\coloneqq{\rm dim}(N(T))$
- rank of $T$:     ${\rm rank}(T)\coloneqq{\rm dim}(T(V))$

---

Thm.
- Let ${\rm dim}(V)<\infty$, with basis $\beta=\{\beta_1,\,...,\,\beta_n\}$
- $\implies$
	- $\forall\,\{w_1,\,...,\,w_n\}\subseteq W$:
	  $\exists\,!$ linear $T:V\to W$  s.t. $T(\beta_i)=w_i$  $\forall\,i=1,\,...,\,n$


