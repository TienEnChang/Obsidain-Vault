
Let $X$, $Y$ be topological space, $A\subseteq X$

Def.
- open cover:  $\{U_i\}_{i\in I}$ open in $X$  $\land$  $\bigcup\limits_{i\in I}U_i\supseteq A$
- subcover:  $\{U_{j}\}_{j\in J\subseteq I}$ that covers $A$

Def.
- compact:  $\forall$ open cover $\{U_i\}_{i\in I}$ of $A$:  $\exists$ subcover $\{U_{i_k}\}_{k=1}^{m\in\mathbb{N}}$ of $A$

Thm. inheritance principle
- For $Y\subseteq X$, 
	- $A$ compact $\subseteq Y$ $\iff$ $A$ compact $\subseteq X$  [[Compactness - Pf.#^24abe6|{Pf}]]

Thm. invariance
- For $f:X\to Y$ continuous,
	- $A$ compact $\subseteq X$ $\implies$ $f(A)$ compact $\subseteq Y$  [[Compactness - Pf.#^869e8f|{Pf}]]

---

\[ Metric Space ]

Let $X$ be metric spaces

Thm.
- $A$ compact $\subseteq X$ $\implies$ $A$ closed, bounded $\subseteq X$  [[Compactness - Pf.#^b1e885|{Pf}]]

Thm.
- $A$ compact $\subseteq X$ $\implies$ $\forall\;B$ closed $\subseteq A$:  $B$ compact $\subseteq A$


\[ $\mathbb{R}^n$ ]

Lemma. Combined
- $A_i$ compact $\subseteq X_i$ with $d_i$ $\implies$ $\prod\limits_{i=1}^n A_i$ compact $\subseteq\prod\limits_{i=1}^nX_i$ with $d_{\rm sum}$  [[Compactness - Pf.#^76c634|{Pf}]]

Thm. The Heine-Borel Thm. 
- $A$ compact $\subseteq \mathbb{R}^n$ $\iff$ $A$ closed, bounded $\subseteq \mathbb{R}^n$  [[Compactness - Pf.#^1c8311|{Pf}]] ^dali0y8n

---

\[ Applications: Topological Space ]

Thm. [[Compactness - Pf.#^07cb06|{Pf}]]
- $X$ compact  $\land$  $f:X\to Y$  bijective, continuous $\implies$ $f$ homeomorphism