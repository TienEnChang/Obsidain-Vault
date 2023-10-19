
Let $V$ be a vector space over field $F$, $W$ be a subspace

Def. Subspace
- $W$ is a subspace of $V$
- $\iff$
- $W\subseteq V$  $\land$
- $W$ is a vector space over $F$:  $+_w=+_v$ ,  $\cdot\,_w=\cdot\,_v$  with
	1. closure under "$+$":
		   $\forall\,\vec x,\,\vec y\in W$:  $\vec x+\vec y\in W$
	2. closure under "$\,\cdot\,$":
		   $\forall\,\vec x\in W$, $\forall\,c\in F$:  $c\cdot \vec x\in W$
	3. identity of "$+$":
		   $\exists\,\vec 0_{w}\in W$  s.t.  $\vec 0_w + \vec x = \vec x$  $\forall\,\vec x\in W$
	4. inverse of "$+$":
		   $\forall\,\vec x\in W$  $\exists\,\vec y\in W$  s.t.  $\vec x + \vec y = \vec 0_w$  

---

Def.
- ${\rm Span}(\varnothing)\coloneqq\{\vec 0\}$  { trivial subspace of $V$ }
- ${\rm Span}(A)\coloneqq\{\,\vec v\in V\;|\;\exists$ finite $N_A\subseteq A$, $\exists\,\{a_{\vec u}\}_{\vec u\in N_A}\subseteq F$  s.t. $\vec v=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u\,\}$
- $\implies$ $\{\vec 0\},\,A\subseteq {\rm Span}(A)$

Thm.
- ${\rm Span}(A)$ is a subspace of $V$
- ${\rm Span}(A)=\bigcap\limits_{{\rm subspace},\;W\supseteq A}W$      { minimal subspace!! }
  i.e. $W\supseteq{\rm Span}(A)$  $\forall$ subspace $W$ with $W\supseteq A$

Def.
- $A$ is a generating subset of $W$:  ${\rm Span}(A)=W$

Def.
- $A$ is linearly dependent:
    $\exists$ finite $N_A\subseteq A$  s.t.
       $\exists\,\{a_{\vec u}\}_{\vec u\in N_A}\subseteq F$  where  $\exists\;a_{\vec u}\neq 0$  s.t. $\vec 0=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u$
Def.
- $A$ is linearly independent:
    $\forall$ finite $N_A\subseteq A$:
       $\exists\,\{a_{\vec u}\}_{\vec u\in N_A}\subseteq F$  s.t. $\vec 0=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u$  $\implies$ $\forall\,\vec u\in N_A$:  $a_{\vec u}=0$
    { trivial representation of $\vec 0$ }

Rmk.
- $\vec 0\in A$ $\implies$ $A$ lin. dep.  { $\because$ $\vec 0=1\cdot\vec 0$ }
- $\varnothing$ "not" lin. dep.  { $\because$ $\not\exists$ finite $N_A\subseteq A$  
                          s.t. $\exists\,\{a_{\vec u}\}_{\vec u\in N_A}\subseteq F$  s.t. $\vec v=\sum\limits_{\vec u\in N_A}a_{\vec u}\vec u$  }

Thm.
- $A_1\subseteq A_2$:  $A_1$ lin. dep. $\implies$ $A_2$ also
- $A_1\subseteq A_2$:  $A_2$ lin. indep. $\implies$ $A_1$ also  { Cor. }

Rmk.
- $A$ lin. indep. $\land$  $\vec v\in V-A$:
    $A\cup\{\vec v\}$ lin. dep. $\iff$  $\vec v\in{\rm Span}(A)$
    $A\cup\{\vec v\}$ lin. indep. $\iff$ $\vec v\not\in{\rm Span}(A)$

---

Def.
- $\beta$ is a basis of $W$:  $\beta$ is lin indep. &  generating subset of $W$
  { minimal generating subset!! }

Thm.
- $\beta$ is a basis of $W$
- $\iff$
	- $\forall\,\vec v\in W$:  $\exists\,!$ finite $N_\beta\subseteq\beta$, $\exists\,!\,\{a_{\vec u}\}_{\vec u\in N_\beta}\subseteq F$  s.t. $\vec v=\sum\limits_{\vec u\in N_\beta}a_{\vec u}\vec u$
	  i.e.  uniquely expressible as a 
	        linear combination of finitely many vectors in $\beta$

Thm.
- ${\rm Span}(G)=V$ $\implies$ $\exists\,\beta\subseteq G$  s.t. $\beta$ is a basis of $V$

Def.
- dimension of $V$:  ${\rm dim}(V)\coloneqq|\beta|$  where  $\beta$ is a basis of $V$

Rmk.
- ${\rm dim}(M_{m\times n}(F))=m\times n$
- ${\rm dim}(P_n(F))$

\# Below, only consider finite dimensional $V$ cases  { ${\rm dim}(V)<\infty$ }

Thm.  Replacement Thm.
- $\forall$ finite "generating subset $G$" & "lin. indep. subset $I$" of $V$:
  1. $|G|\leq|I|$
  2. $\exists\,H\subseteq G$  s.t. ${\rm Span}(I\cup H)={\rm Span}(G)$  { $|H|=|G|-|I|$ }
Cor.
- Let
	- $\beta$ be a finite basis of $V$:
    $\exists$ lin. indep. subset $I_v\not\$ of $V$      { $|I|\leq|\beta|$ }
    &  $\exists\,I_\beta\subseteq \beta$  with  $|I_\beta|=|\beta|-|I_v|$   { by Thm. $H$ is lin. indep. }
    s.t.  $I_\beta\cup I_v$  is also a basis
{i.e.}
- $\forall$ finite basis $\beta$ of $V$:  $|\beta|={\rm dim}(V)$
Cor.
- $\forall$ finite generating subset $G$ of $V$:  $|G|\geq{\rm dim}(V)$
    $\land$  $|G|={\rm dim}(V)$ $\iff$ $G$ is a basis
- $\forall$ finite lin. indep. subset $I$ of $V$:  $|I|\leq{\rm dim}(V)$
    $\land$  $|I|={\rm dim}(V)$ $\iff$ $I$ is a basis

![[Screenshot 2023-10-17 at 6.59.05 PM.png]]