
\[ Metric Space ]

Let $X$ be metric space, $A\subseteq X$

Def.
- sequentially compact:
	- $\forall$ $(p_n)_{n\in\mathbb{N}}$ in $A$:  $\exists$ $(p_{n_k})_{k\in\mathbb{N}}$ converges to $p\in A$

Def.
- totally bounded:
	- $\forall\, r>0$:  $\exists$ $p_1,\,\cdots,\,p_n\in A$  s.t. $\{B_r(p_i)\}_{i=1}^{n\in\mathbb{N}}$ covers $A$

---

Thm. $A$ totally bounded $\implies$ bounded  [[Sequentially Compact, Totally Bounded - Pf.#^8a4380|{Pf}]]

Thm.
- $A$ not sequentially compact $\implies$ $p\not\in {\rm Cl}_X(A-\{p\})$  $\forall\,p\in A$  [[Sequentially Compact, Totally Bounded - Pf.#^43040f|{Pf}]]

Thm.  [[Sequentially Compact, Totally Bounded - Pf.#^e8a340|{Pf}]]
- $A$ sequentially compact  $\land$  $\{U_i\}_{i\in I}$ open cover of $A$
- $\implies$
	- $\exists\;r>0$  s.t.  $\forall\,p\in A$:  $\exists\,i\in I$  s.t. $U_i \supseteq B_r(p)$  { Lebesgeu number }

---

Thm. 
- $A$ sequentially compact $\iff$ $A$ complete, totally bounded  [[Sequentially Compact, Totally Bounded - Pf.#^eead86|{Pf}]]

Thm. Bolzano-Weierstrass Thm.
- $A$ sequentially compact $\iff$ $A$ compact  [[Sequentially Compact, Totally Bounded - Pf.#^911c6f|{Pf}]]