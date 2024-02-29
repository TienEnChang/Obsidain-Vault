
Def. vector space over field $F$
- $(V,\,+,\,\cdot\,,\,F)$
- where
	- "$+$": $V\times V\to V$
	  (1) commutative:  $\forall\,\vec v,\,\vec w\in V$:  $\vec v + \vec w = \vec w + \vec v$
	  (2) associative:  $\forall\,\vec u,\,\vec v,\,\vec w\in V$:  $(\vec u +\vec v) + \vec w = \vec u+(\vec v + \vec w)$
	  (3) zero:         $\exists\,\vec 0\in V$  s.t.  $\vec 0 + \vec v = \vec v$  $\forall\,\vec v\in V$
	  (4) inverse:      $\forall\,\vec v\in V$  $\exists\,\vec w\in V$  s.t.  $\vec w + \vec v = \vec 0$
	- "$\,\cdot\,$": $F\times V\to V$
	  (5) identity:     $\exists\,1\in F$  s.t.  $1\vec v = \vec v$  $\forall\vec v\in V$
	  (6) associative:  $\forall\,\vec v\in V$, $\forall\,a,\,b\in F$:  $(ab)\vec v = a(b\vec v)$
	- both
	  (7) distributive I:   $\forall\,\vec v,\,\vec w\in V$, $\forall\,a\in F$:  $a(\vec v + \vec w) = a\vec w + a\vec v$
	  (8) distributive II:  $\forall\,\vec v\in V$, $\forall\,a,\,b\in F$:  $(a+b)\vec v = a\vec v + b\vec v$

Def. subspace of $(V,\,+,\,\cdot\,,\,F)$
- $(W,\,+,\,\cdot\,,\,F)$,  $W\subseteq V$
- where
	- (1) closure under "$+$":
		    $\forall\,\vec x,\,\vec y\in W$:  $\vec x+\vec y\in W$
	- (2) closure under "$\,\cdot\,$":
		    $\forall\,\vec x\in W$, $\forall\,c\in F$:  $c\cdot \vec x\in W$
	- (3) identity of "$+$":
		    $\exists\,\vec 0_{w}\in W$  s.t.  $\vec 0_w + \vec x = \vec x$  $\forall\,\vec x\in W$
	- (4) inverse of "$+$":
		    $\forall\,\vec x\in W$  $\exists\,\vec y\in W$  s.t.  $\vec x + \vec y = \vec 0_w$  

Thm. 1-step test
- $W$ is a vector subspace $V$
- $\iff$
	- (1) $W\subseteq V$
	- (2) $W\neq\varnothing$
	- (2) $\forall\,\vec x,\,\vec y\in W$, $\forall\,c\in F$:  $c\cdot\vec x+\vec y\in W$