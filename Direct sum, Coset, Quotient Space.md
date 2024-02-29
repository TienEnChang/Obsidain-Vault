
Let $V$ be a vector space,  $S_1,\,S_2\subseteq V$,  $W_1,\,W_2$ be subspaces

Def. 
- sum:  $S_1+S_2=\{\,s_1+s_2\;|\;s_1\in S_1,\;s_2\in S_2\,\}$
- direct sum:  $V=W_1\bigoplus W_2$  $\iff$  $V=W_1+W_2$  $\land$  $W_1\cap W_2=\{\vec0_v\}$

---

Let $V$ be a vector space,  $W$ be a subspace

Def.
- left "$+$" coset of $W$
       containing $v$:  $v+W=\{v+w\;|\;w\in W\}$  where  $v\in V$
- right "$+$" coset of $W$ 
        containing $v$:  $W+v=\{w+v\;|\;w\in W\}$  where  $v\in V$

Def. quotient space
- $V/W\coloneqq\{\,[x]\coloneqq x+W\;|\;x\in V\,\}$
- where
	- $\forall\,x,\,y\in V$:  $y\sim_{(V/W)} x$ $\iff$ $y\in(x+W)$

Thm.
- $V/W$ is a vector space,  $\vec 0_{(V/W)}=W$
- $\dim(V/W)=\dim(V)-\dim(W)$
