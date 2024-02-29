
Def. Equivalence relation
- $\sim$ is a relation on $X$
- where
	1. $\forall\,x\in X$:  $x\sim x$                          {reflexive}
	2. $\forall\,x,\,y\in X$:  $x\sim y$ $\implies$ $y\sim x\;$            {symmetric}
	3. $\forall\,x,\,y,\,z\in X$:  $x\sim y$ $\land$ $y\sim z$ $\implies$ $x\sim z\;$  {transitive}

Def. equivalence class of $x\in X$:  $[x]\coloneqq\{\,y\in X\;|\;y\sim x\,\}$

Def. quotient set of $\sim$ on $X$:  $X/\!\sim\;\,\coloneqq\{\,[x]\;|\;x\in X\,\}$

---

Def. Partition
- $P\subseteq \mathcal{P}(X)$
- where
	1. $\varnothing\not\in P$
	2. $\bigcup\limits_{A\in P}A=X\;$                                 {exhaustion}
	3. $\forall\,A_1,\,A_2\in P$  with  $A_1\neq A_2$:  $A_1\cap A_2=\varnothing$  {pairwise disjoint}
- $\iff$
	1. $\varnothing\not\in P$
	2. $\forall\,x\in X$:  $\exists\,!\,A\in P$  s.t.  $x\in A$   {total & univalent}

Thm.
- $P$ is a partition of $X$ $\implies$ $P$ is a quotient set of $X$ for some $\sim$ 
- $X/\!\sim$ is a quotient set of $X$ $\implies$ $X/\!\sim$ is a partition of $X$

Cor.
- $\forall\,x,\,y\in X$:  $[x]\neq [y]$ $\implies$ $[x]\cap[y]=\varnothing$