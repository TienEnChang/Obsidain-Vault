
Def. Topology on $X$
- $\mathcal{T}\subseteq\mathcal{P}(X)$  with
	1. $\varnothing,\,X\in\mathcal{T}$
	2. $\forall\,U_i\in\mathcal{T}$:  $\bigcap\limits_{i\in I,\;\rm finite}U_i\in\mathcal{T}$ 
	3. $\forall\,U_i\in\mathcal{T}$:  $\bigcup\limits_{i\in I,\;\rm any}U_i\in\mathcal{T}$

Def. Induced topology on $X$ from metric $d$
- $\mathcal{T}\coloneqq \{\,U\subseteq X\;|\;\forall\,p\in U$ $\exists\,r>0$  s.t. $B_r(p)\subseteq U\,\}$  [[Topological Space - Pf.#^166e65|{Pf}]]

Def. Topological space:  $(X,\,\mathcal{T})$

Def.
- Open in $(X,\,\mathcal{T})$:  $U\in\mathcal{T}$
- Open in $(X,\,d)$:  $U\in$ induced $\mathcal{T}$
- Closed in $(X,\,\mathcal{T})$:  $U^{c}\in\mathcal{T}$

Def.
- Neighborhood of $p\in X$:  $U\ni p$  $\land$  $U$ is open in $(X,\,\mathcal{T})$
- Interior of $U$ in $(X,\,\mathcal{T})$:
	- ${\rm int}(U)\coloneqq\{\,p\in U\;|\;\exists$ neighborhood $N$ of $p$  s.t. $N\subseteq U\,\}$
	        $=\{\,p\in U\;|\;\exists\,r>0$ s.t. $B_r(p)\subseteq U\,\}$  ... 等價敘述
	        $=$ maximum open subset of $U$

Prop.
- $\forall\,p\in X$ $\forall\,r>0$:  $B_r(p)$ is open in $(X,\,d)$  [[Topological Space - Pf.#^1277f1|{Pf}]]

Prop.
- $U$ is open in $(X,\,d)$  $\iff$  $U={\rm int}(U)$ in $(X,\,d)$  [[Topological Space - Pf.#^dc844c|{Pf}]]

Prop.
- $\forall\,p\in X$:  $\{p\}$ is closed in $(X,\,d)$  [[Topological Space - Pf.#^b8c403|{Pf}]]

Prop.
- $\forall\,U_i$  is closed:  $\bigcup\limits_{i\in I,\;\rm finite}U_i\;$ is closed  [[Topological Space - Pf.#^a2c956|{Pf}]]
- $\forall\,U_i$  is closed:  $\bigcap\limits_{i\in I,\;\rm any}U_i\;$ is closed   [[Topological Space - Pf.#^7579a3|{Pf}]]

Cor.
- $U\subseteq X$ is finite  $\implies$  $U=\bigcup\limits_{i\in I,\;{\rm finite}}\{p_i\}$ is closed in $(X,\,d)$  [[Topological Space - Pf.#^062b3f|{Pf}]]

---

Ex.
- For discrete metric space:  all $U\subseteq X$ is open in $(X,\,d)$

Ex.
- False:  ${\rm int}(A\cup B)\equiv{\rm int}(A)\cup{\rm int}(B)$   
- False:  ${\rm int}(B_r(p)\cup C_r(p))\equiv B_r(p)$

Ex.
- $S=\{\,(x,\,y)\in\mathbb{R}^2\;|\;\dfrac12 < x^2+y^2< 1\,\}$  is open in $\mathbb{R}^2$
- Let $S=\{\,(x,\,y)\in\mathbb{R}^2\;|\;y\geq x^3\,\}$, find ${\rm int}(S)$ in $\mathbb{R}^2$

Ex.
- Show that $T=(\bigcup\limits_{n=1}^\infty \{\dfrac1{n}\})\cup\{0\}$ is closed