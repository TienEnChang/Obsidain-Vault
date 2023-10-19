
Let $V$ be a vector space over $F$



Def.
- $\forall\,a\in F$: $-a$ denotes its unique "$+$" inverse $\implies-a\in F$

Prop.
- $\forall\, \vec x\in V$:
	- $\vec x + 0\,\vec x= (1+0)\cdot\vec x = \vec x$        $\;\implies$ $0\,\vec x=\vec 0$
	- $\vec x + (-\vec x)=(1-1)\cdot \vec x=0\,\vec x=\vec 0$
	  $\implies$ $-\vec x$ is the unique "$+$" inverse of $\vec x$

Thm. 1-Step Test
- $W\subseteq V$ is a subspace of $V$
- $\iff$
- (1) $W\subseteq V$  $\land$  $W\neq\varnothing$  (i.e. $\vec 0_{v}\in W$)
- (2) $\forall\,\vec x,\,\vec y\in W$, $\forall\,c\in F$:  $c\cdot\vec x+\vec y\in W$

Pf.
- "$W\neq\varnothing\impliedby\vec 0_{v}\in W$":  clearly
- "$W\neq\varnothing\implies\vec 0_{v}\in W$"
	- $W\neq\varnothing$
	- $\implies$ $\exists\,\vec x\in W$
	- $\implies$ $-1\cdot\vec x+\vec x\in W$  { $\because$ (2) }
	- $\implies$ $\vec 0_v\in W$         { $\because$ $\vec x\in V$, $0\,\vec x=\vec 0_v$ }

Pf.
- "$\impliedby$"
	- identity of "$+$":
		- $\vec 0_v + \vec 0_v=\vec 0_v$  $\land$  $\vec 0_{v}\in W$ $\implies$ $\vec 0_w=\vec 0_v$
	- inverse of "$+$":
		- $\because$  $\forall\,\vec x\in W$ $\implies$ $\vec x\in V$
		             $\;\implies$ $\exists\,$$-\vec x\in V$  s.t. $\vec x + (-\vec x)=\vec 0_v=\vec 0_w$
		- $\therefore$  $\vec x\in W$  $\land$  $\vec x + (-\vec x)=\vec 0_w$ $\implies$ $-\vec x\in W$
	- closure under "$+$":
		- $\forall\,\vec x,\,\vec y\in W$:  $1\cdot\vec x+\vec y\in W$ $\implies$ $\vec x+\vec y\in W$
	- closure under "$\,\cdot\,$":
		- $\forall\,\vec x\in W$ $\forall\,c\in F$:  $c\cdot\vec x+\vec 0_w\in W$ $\implies$ $c\cdot\vec x\in W$
- "$\implies$"
- (1)
	- $\because$  $\exists\,\vec 0_{w}\in W$  s.t.  $\vec 0_w + \vec x = \vec x$  $\forall\,\vec x\in W$
	- $\therefore$  $\,\vec 0_{w}\in V$ $\implies$ $\vec 0_w + \vec x = \vec x$  $\forall\,\vec x\in V$ $\implies$ $\vec 0_v=\vec 0_w\in W$
- (2)
	- $\forall\,\vec x,\,\vec y\in W$:  $\vec x+\vec y\in W$
	   $\land$  $\forall\,\vec x\in W$, $\forall\,c\in F$:  $c\cdot \vec x\in W$
	- $\implies$  $\forall\,\vec x,\,\vec y\in W$, $\forall\,c\in F$:  $c\cdot\vec x+\vec y\in W$