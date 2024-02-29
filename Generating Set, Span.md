
Let
- $V$ be a vector space over field $F$,  $W$ be a subspace,  $A\subseteq V$

Def
- ${\rm Span}(\varnothing)\coloneqq\{\vec 0\}$  
- ${\rm Span}(A)\coloneqq\{\,\vec v\in V\;|\;\exists$ finite $N_A\subseteq A$, $\exists\,(a_{\vec u})_{\vec u\in N_A}$ in $F$  s.t. $\vec v=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u\,\}$

Rmk. $A\subseteq {\rm Span}(A)$

Def. $A$ generating $\subseteq V$:  ${\rm Span}(A)=V$

Thm. ${\rm Span}(A)$ is a subspace of $V$

Def. $\{\vec 0\}={\rm Span}(\varnothing)$ is trivial subspace

---

Thm.
- ${\rm Span}(A)=\bigcap\limits_{{\rm subspace},\;W\supseteq A}W$  { minimal "subspace" containing $A$ }
  i.e. $W\supseteq{\rm Span}(A)$  $\forall$ subspace $W$ with $W\supseteq A$