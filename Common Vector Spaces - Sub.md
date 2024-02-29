
$F^n$
- "$+$":
	- Let $u=(a_1,...a_n)$, $v=(b_1,...b_n)$, $\in F^n$
	- $\implies$ $u+v\coloneqq(a_1+b_1,...a_n+b_n)$
- "$\,\cdot\,$":
	- Let $c\in F$
	- $\implies$ $c\,u\coloneqq(c\,a_1,...c\,a_n)$

$M_{m\times n}(F)$
- "$+$":
	- Let $A,\,B\in M_{m\times n}(F)$
	- $\implies$ $(A+B)_{ij}\coloneqq A_{ij}+B_{ij}$  $\,\forall\,i=1,...,m$ $\;j=1,...,n$
- "$\,\cdot\,$":
	- Let $A\in M_{m\times n}(F)$ , $c\in F$
	- $\implies$ $(c\cdot A)_{ij}\coloneqq c\cdot A_{ij}$       $\forall\,i=1,...,m$ $\;j=1,...,n$

$P_n(F)$
- 
	![[Screenshot 2023-09-26 at 6.56.00 PM.png]]


---

$\mathcal{F}(S,\,F)\coloneqq\{\,$$f:S\to F\;|\;S\neq\varnothing\,\}$, functions from set to field
- zero: $\tilde{0}$
- where
	- "$+$":
		- Let $f,\,g\in\mathcal{F}(S,\,F)$
		- $\implies$ $(f+g)(x)\coloneqq f(x)+g(x)$  $\forall x\in S$
	- "$\,\cdot\,$":
		- Let $f\in\mathcal{F}(S,\,F)$ , $c\in F$
		- $\implies$ $(c\cdot f)(x)\coloneqq c\cdot f(x)$  $\forall x\in S$

$P_n(F)\coloneqq\{\,\displaystyle\sum_{k=0}^n a_k\,x^k\;|\;n,\,k\in\mathbb{N}\cup\{0\}\,,\,\forall\,k\leq n:\;a_k\in F\,\}$
$P(F)\subseteq\mathcal{F}(S,\,F)$

---

Def. (Ex.)
- Line $L$
	- Let ${\rm A,\,B}\in L$
	- $\implies$
		- $\forall\,{\rm P}\in L$:  $\exists\,t\in\mathbb{R}$  s.t.  $\vec{\rm AP}= t\,\vec{\rm AB}$
- Plane $E$:
	- Let ${\rm A,\,B,\,C}\in E$  where  $\vec{\rm AB}\nparallel\vec{\rm AC}$
	- $\implies$
		- $\forall\,{\rm P}\in E$:  $\exists\,t_1,\,t_2\in\mathbb{R}$  s.t.  $\vec{\rm AP}= t_1\,\vec{\rm AB}+t_2\,\vec{\rm AC}$
		            $\iff$ $\vec{\rm AP}\cdot(\vec{\rm AB}\times\vec{\rm AC})=0$