
\[ Axioms ]

Def. Topology on $X$
- $\mathcal{T}\subseteq\mathcal{P}(X)$  with
	1. $\varnothing,\,X\in\mathcal{T}$
	2. $\forall\,U_i\in\mathcal{T}$:  $\bigcap\limits_{i\in I,\;\rm finite}U_i\in\mathcal{T}$ 
	3. $\forall\,U_i\in\mathcal{T}$:  $\bigcup\limits_{i\in I,\;\rm any}U_i\in\mathcal{T}$

Def. Inherited topology on $Y\subseteq X$:  $\mathcal{T}_Y\coloneqq\{\,U\cap Y\;|\;U\in\mathcal{T}\,\}$

Def.
- topological space:  $(X,\,\mathcal{T})$
- topological subspace:  $(Y,\,\mathcal{T}_Y)$

Prop.
- $\forall\,U_i$ closed:  $\bigcup\limits_{i\in I,\;\rm finite}U_i\;$ closed  [[Topological Space - Pf.#^a2c956|{Pf}]]
- $\forall\,U_i$ closed:  $\bigcap\limits_{i\in I,\;\rm any}U_i\;$ closed   [[Topological Space - Pf.#^7579a3|{Pf}]]

---

\[ Properties ]

Def.
- open:    $A\in\mathcal{T}$
- closed:  $A^{c}\in\mathcal{T}$
- neighborhood:  $N_p\ni p$  $\land$  $N_p$ open $\subseteq X$  { $p\in X$ }

Def.
- interior:  ${\rm int}_X(A)\coloneqq\bigcup\limits_{{\rm open},\;U\subseteq A}U$   i.e. $\{\,p\in A\;|\;\exists$ nbhd $N_p\subseteq A\,\}$ ^c97ed3
- closure:   ${\rm Cl}_X(A)\coloneqq\bigcap\limits_{{\rm closed},\;U\supseteq A}U$
- boundary:  $\partial_X A\coloneqq {\rm Cl}_X(A)\cap {\rm Cl}_X(A^c)$   i.e. ${\rm Cl}_X(A)-{\rm int}_X(A)$

Prop. Inheritance Principle
- $A$ open $\subseteq Y$ $\iff$ $\exists\,U$ open $\subseteq X$  s.t. $U\cap Y=A$    {by def.}
- $A$ closed $\subseteq Y$ $\iff$ $\exists\,U$ closed $\subseteq X$  s.t. $U\cap Y=A$  {cor.}  [[Topological Space - Pf.#^00d67b|{Pf}]]
- $\implies$
	- $A$ open $\subseteq Y$  $\land$  $Y$ open $\subseteq X$ $\implies$ $A$ open $\subseteq X$        {cor.} [[Topological Space - Pf.#^spnkwnqd|{Pf}]]
	- $A$ closed $\subseteq Y$  $\land$  $Y$ closed $\subseteq X$ $\implies$ $A$ closed $\subseteq X$  {cor.} [[Topological Space - Pf.#^ajwbkljd|{Pf}]]

Prop.
- ${\rm int}_X(A)^c={\rm Cl}_X(A^c)\,$
- ${\rm int}_Y(A\cap Y)={\rm int}_X(A)\cap Y$  [[Topological Space - Pf.#^9b621b|{Pf}]] 
- ${\rm Cl}_Y(A\cap Y)={\rm Cl}_X(A)\cap Y$   [[Topological Space - Pf.#^60e654|{Pf}]] [[Topological Space - Pf.#^dd9202|{by metric}]]

Prop.
- $A$ open $\subseteq X$ $\iff$ $A={\rm int}_X(A)$    [[Topological Space - Pf.#^dc844c|{Pf}]]
- $A$ closed $\subseteq X$ $\iff$ $A={\rm Cl}_X(A)\;$  {cor.}  [[Topological Space - Pf.#^3dce45|{Pf by metric}]]

Prop.
- interior is open    { i.e. ${\rm int_X}\circ{\rm int_X}(U)={\rm int}_X(U)$ }  [[Topological Space - Pf.#^psfmewl|{Pf}]]
- closure is closed   { i.e. ${\rm Cl}_X\circ{\rm Cl}_X(U)={\rm Cl}_X(U)$ }   [[Topological Space - Pf.#^wljaksmdl|{Pf. by metric}]]
- boundary is closed  { since $\partial_X A\coloneqq {\rm Cl}_X(A)\cap {\rm Cl}_X(A^c)$ }

---

\[ Open Balls & Limit Points ]

Def.
- For $p\in X$,
	- open ball:    $B_r(p)\coloneqq\{\,x\in X\;|\;d(p,\,x)<r\,\}$  where  $r>0$ ^14897a
	- closed ball:  $B_r[p]\coloneqq\{\,x\in X\;|\;d(p,\,x)\leq r\,\}$  where  $r>0$
	- circle:       $C_r(p)\coloneqq\{\,x\in X\;|\;d(p,\,x)=r\,\}$  where  $r>0$  

Def.
- $p$ is a limit point of $A$:  $\exists$ $(p_n)_{n\in\mathbb{N}}$ in $A$  s.t. $\lim\limits_{n\to\infty}p_n=p$

Thm. sequence <> ball
- $p$ is a limit point of $A$  $\iff$  $B_r(p)\cap A\neq\varnothing$  $\forall\,r>0$  [[Topological Space - Pf.#^d9c501|{Pf}]]


\[ Metric-induced Topology ]

Def. Induced topology on $X$ from metric $d$
- $\mathcal{T}\coloneqq \{\,U\subseteq X\;|\;\forall\,p\in U$ $\exists\,r>0$  s.t. $B_r(p)\subseteq U\,\}$  [[Topological Space - Pf.#^166e65|{Pf}]]

Def.
- interior (metric):  ${\rm int}_X(A)\coloneqq\{\,p\in A\;|\;\exists\,r>0$  s.t. $B_r(p)\subseteq A\,\}$ ^oawhjfsnko
- closure (metric):   ${\rm Cl}_X(A)\coloneqq\{\,p\in X\;|\;\forall\,r>0$: $B_r(p)\cap A\neq\varnothing\,\}$
  [[Topological Space - Pf.#^bklemlas|{relation by negation}]]

Prop.
- open balls are open  [[Topological Space - Pf.#^1277f1|{Pf}]]
- closed balls are closed  [{Pf by others}](https://math.stackexchange.com/questions/661759/a-closed-ball-in-a-metric-space-is-a-closed-set)
- singletons are closed  ( $\{p\}$  for some  $p\in X$ )  [[Topological Space - Pf.#^b8c403|{Pf}]]

Cor.
- finite sets are closed  [[Topological Space - Pf.#^062b3f|{Pf}]]

---

\[ Special Topology ]

Def.
- discrete topology:  $\mathcal{T}_D\coloneqq\mathcal{P}(X)$  { $=$ topology induced from $d_D$ }

Prop.
- For $X$ discrete,
	- $A\equiv{\rm int}_X(A)$  $\land$  $A\equiv{\rm Cl}_X(A)$  i.e.  $\partial_X A\equiv \varnothing$  
	- all $f:X\to Y$ are continuous

