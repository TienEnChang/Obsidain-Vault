
Let $(X,\,d)$ be a metric space, $p\in X$, $S\subseteq X$

Def. Sequence
- $(p_n)_{n\in\mathbb{N}}$ in $X$:  $p_n\coloneqq f_p(n)$  where  $f_p:\mathbb{N}\to X$

Def. Limit of Sequence
- $\lim\limits_{n\to\infty}p_n=p$  i.e.  $p_n\to p$ as $n\to\infty$  i.e.  $(p_n)_{n\in\mathbb{N}}$ converges to $p$
- $\iff$
- $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n\geq N$:  $d(p_n,\,p)<\varepsilon$

Def.
- $p$ is a limit point of $S$:  $\exists$ $(p_n)_{n\in\mathbb{N}}$ in $S$  s.t. $\lim\limits_{n\to\infty}p_n=p$
- closure of $S$ in $X$:  ${\rm Cl}_X(S)\coloneqq\{\,$ all limit points of $S$ $\,\}$
- $\implies$
	- $S\subseteq{\rm Cl}_X(S)$

Thm.
- $p$ is a limit point of $S$  $\iff$  $B_r(p)\cap S\neq\varnothing$  $\forall\,r>0$  [[Limit Points - Pf.#^d9c501|{Pf}]]

Thm.
- $S={\rm Cl}_X(S)$  $\iff$  $S$ is closed in $X$  [[Limit Points - Pf.#^3dce45|{Pf}]]

Prop.
- $\forall\,U\subseteq X$: ${\rm Cl}_X(U)$ is closed in $X$  ( $\because$ ${\rm Cl}_X\circ{\rm Cl}_X(U)={\rm Cl}_X(U)$ )
- $\forall\,U\subseteq X$: ${\rm int_X}(U)$ is open in $X$    ( $\because$ ${\rm int_X}\circ{\rm int_X}(U)={\rm int}_X(U)$ )

Prop.
- ${\rm Cl}_X(S)=\bigcap\limits_{{\rm closed},\;U\supseteq S}U$
- ${\rm int}(S)=\bigcup\limits_{{\rm open},\;U\subseteq S}U$

Prop.
- $\forall\,Y$ subspace of $X$, $A\subseteq Y$:  ${\rm Cl}_Y(A)={\rm Cl}_X(A)\cap Y$  [[Limit Points - Pf.#^dd9202|{Pf}]]

---

Def. Denseness
- $S$ is dense in $X$:  ${\rm Cl}_X(S)=X$
- $S$ is somewhere dense in $X$:
	- $\exists\,Y$ open in $X$  s.t. ${\rm Cl}_Y( Y\cap A)=Y$  i.e.  ${\rm Cl}_X(Y\cap A)\supseteq Y$  [[Limit Points - Pf.#^2b7e33|{Pf}]]
- $S$ is nowhere dense in $X$
	- $\neg$ somewhere dense

Prop.
- $A\subseteq\mathbb{Z}$ is closed in $\mathbb{R}$
Cor.
- $\mathbb{Z}$ is nowhere dense in $\mathbb{R}$  [[Limit Points - Pf.#^236c26|{Pf}]]

Ex.
- $\mathbb{Q}$ is dense in $\mathbb{R}$  [[Limit Points - Pf.#^137809|{Pf}]]
- $\mathbb{N}$ is nowhere in $\mathbb{R}$  ($\because$ $\mathbb{N}\subseteq\mathbb{Z}$)

Ex.
- False:  ${\rm Cl}_{X}(A\cup B)\equiv {\rm Cl}_{X}(A)\cup {\rm Cl}_{X}(B)$