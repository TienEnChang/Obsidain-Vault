
Let
- $V$ be a vector space over field $F$,  $W$ be a subspace,  $A\subseteq V$

Def.
- $A$ linearly dependent $\subseteq V$:  { i.e. $\exists$ parallel vectors }
    $\exists$ finite $N_A\subseteq A$  s.t.
       $\exists\,(a_{\vec u})_{\vec u\in N_A}$ in $F$  where  $\exists\;a_{\vec u}\neq 0$  s.t. $\vec 0=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u$
Def.
- $A$ linearly independent $\subseteq V$:
    $\forall$ finite $N_A\subseteq A$:
       $\exists\,(a_{\vec u})_{\vec u\in N_A}$ in $F$  s.t. $\vec 0=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u$  $\implies$ $\forall\,\vec u\in N_A$:  $a_{\vec u}=0$
    { trivial representation of $\vec 0$ }

Rmk.
- $A$ is lin. indep. $\subseteq V$ $\implies$ $\vec 0\not\in A$  { $\because$ $\vec 0=1\cdot\vec 0{}+{}...$ }
- $\varnothing$ is lin. indep. $\subseteq V\,$             { $\because$ $\vec 0\neq\sum\limits_{\vec u\in\varnothing}a_{\vec u}\vec u$ , no element }

Thm.
- For $A\supseteq B$,
	- $A$  lin. indep. $\subseteq V$ $\implies$ $B$  lin. indep. $\subseteq V$             { Cor. }
	- $B$  "not" lin. indep. $\subseteq V$ $\implies$ $A$  "not" lin. indep. $\subseteq V$

Thm.
- $A$ linear. indep. $\subseteq V$  $\land$  $\vec v\not\in A$:
	- $A\cup\{\vec v\}$ linear. indep. $\subseteq V$ $\iff$ $\vec v\not\in{\rm Span}(A)$