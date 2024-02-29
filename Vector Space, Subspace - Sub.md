
Thm. cancellation law
- $\forall\,x,\,y,\,z\in V$:  $x+z=y+z$ $\implies$ $x=y$

Thm-1.2
(a) $0\cdot x=\vec 0$  $\forall\,x\in V$
(b) $(-a)\cdot x=-(a\cdot x)=a\cdot(-x)$
(c) $a\cdot\vec 0=\vec 0$

---
---

Def.
- Field $F$: a set with  (e.g. $\mathbb{Q},\,\mathbb{R},\,\mathbb{C}$ / $\mathbb{F}_2$ is binary field)
- op.
	- "$+$": $F\times F\to F$ , "$\,\cdot\,$": $F\times F\to F$
- law.
	- identity:
		- $\forall\,a\in F$:  $\exists$ distinct $\,0,\,1\in F$
	                    s.t. $0+a=a$    {"$+$"}
				             $1\cdot a=a$     {"$\,\cdot\,$"}
	- inverse:
		- $\forall\,a\in F$:  $\exists$ $b\in F$  s.t. $b+a=0$   {"$+$"}
		- $\forall\,a\in F$  with  $a\neq0$:  
		           $\,\exists$ $c\in F$  s.t. $c\cdot a=1$    {"$\,\cdot\,$"}
	- commutative:
		- $\forall\,a,\,b\in F$:  $a+b=b+a$,   {"$+$"}
		             $\;a\cdot b = b\cdot a$      {"$\,\cdot\,$"}            
	- associative:
		- $\forall\,a,\,b,\,c\in F$:  $(a+b)+c=a+(b+c)$,   {"$+$"}
	                   $\;(a\cdot b)\cdot c = a\cdot (b\cdot c)$        {"$\,\cdot\,$"}    

Def. of field
- In $F$, $-a$ is the unique "$+$" inverse of $a$
        $\,\dfrac{1}{a}$  is the unique "$\,\cdot\,$" inverse of $a$

Prop. uniqueness of inverse of vector space
- $\forall\, \vec x\in V$:
	- $\vec x + 0\,\vec x= (1+0)\cdot\vec x = \vec x$        $\;\implies$ $0\,\vec x=\vec 0$
	- $\vec x + (-\vec x)=(1-1)\cdot \vec x=0\,\vec x=\vec 0$
	  $\implies$ $-\vec x$ is the unique "$+$" inverse of $\vec x$