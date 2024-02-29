
Def. Partial Order
- $\leq$ is a relation on $X$
- where
	1. $\forall\,x\in X$:  $x\leq x$                          {reflexive}
	2. $\forall\,x,\,y\in X$:  $x\leq y$ $\land$ $x\geq y$ $\implies$ $x=y\;$    {antisymmetric}
	3. $\forall\,x,\,y,\,z\in X$:  $x\leq y$ $\land$ $y\leq z$ $\implies$ $x\leq z\;$  {transitive}

Def. partial order set:  $(X,\,\leq)$

Def.
- For $x,\,y\in X$
	- $x,\,y$ are comparable:  $x\leq y$  $\lor$  $x\geq y$  for some $\leq$ on $X$

Def.
- $\leq$ is a total order on $X$:
	- $\leq$ is a partial order  $\land$  $\forall\,x,\,y\in X$:  $x,\,y$ are comparable

Note
- $a\leq b$ ${\;\not\!\!\!\implies}$ $ka\leq kb$  $\forall k$  (乘法：需注意正負號)

---

Def. Ordered Field  {total ordered}
- $(F,\,+,\,\cdot\,,\,\leq)$
- where
	- $\forall\,a,\,b\in F$:    $a\leq b$  $\lor$  $a\geq b$
	- $\forall\,a,\,b,\,c\in F$:  $a\leq b$ $\implies$ $a+c\leq b+c$   {"$+$" rule}
	- $\forall\,a,\,b\in F$:    $a,\,b\geq 0$ $\implies$ $a\cdot b\geq 0$     {"$\,\cdot\,$" rule}

Prop.
- $\subseteq$ is a partial order on $\mathcal{P}(X)$
- $\mathbb{Q}$, $\mathbb{R}$ are ordered fields with $(+,\;\cdot\,,\;\leq)$