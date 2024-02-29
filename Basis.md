
Let $V$ be a vector space over field $F$

Def. $\beta$ is a basis of $V$:  $\beta$ lin indep. & generating $\subseteq V$

Def. dimension of $V$:  ${\rm dim}(V)\coloneqq|\beta|$  where  $\beta$ is a basis of $V$

---

Thm.
- $\forall$ generating $G\subseteq V$:  $\exists$ basis $\beta$ of $V$ s.t. $\beta\subseteq G$ 
                                   ... { reducible to basis }

Consider ${\rm dim}(V)<\infty$.

Thm. Replacement Thm.
- $\forall$ finite generating $G\subseteq V$
	- $\forall$ finite lin. indep. $I\subseteq V$:
  (1) $|G|\leq|I|$
  (2) $\exists\,H\subseteq G$  with  $|H|+|I|=|G|$
                s.t.  ${\rm Span}(H\cup I)={\rm Span}(G)$

Cor.
- $\forall$ finite basis $\beta$ of $V$
	- $\forall$ finite lin. indep. $I\subseteq V$:
  - $\exists\,I_\beta\subseteq \beta$  with  $|I_\beta|+|I|=|\beta|$
     		 $\;$s.t.  $I_\beta\cup I$  is also a basis of $V$ 
     		                       ... { extendable to basis }

Cor.
- $\forall$ finite generating $G\subseteq V$:
	1. $|G|\geq{\rm dim}(V)$
    2. $|G|={\rm dim}(V)$ $\iff$ $G$ is a basis of $V$  { minimal generating }
- $\forall$ finite lin. indep. $I\subseteq V$:
	1. $|I|\leq{\rm dim}(V)$
    2. $|I|={\rm dim}(V)$ $\iff$ $I$ is a basis of $V$  { maximal lin. indep. }

Cor.
- $\forall$ basis $\beta$, $\beta'$ of $V$:  $|\beta|=|\beta'|=\dim(V)$
