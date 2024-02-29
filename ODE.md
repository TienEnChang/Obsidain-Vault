
Let $X,\,Y$ be metric space with metric $d_{X}$, $d_{Y}$

Def.
- Lipschitz map:         [[ODE#^73cd32|{ uniformly continuous }]]
	- $f:X\to Y$  where
	- $\exists\,L\geq0$  s.t.  $\forall\,x,\,y\in X$:  $d_{Y}(f(x),\,f(y))\leq L\,d_{X}(x,\,y)$

Thm. ODE's existence & uniqueness Thm.
- $U$ open $\subseteq \mathbb{R}^{n}$,  $p \in U$  $\land$  $F:U\to\mathbb{R}^{n}$  Lipschitz with  $L$
- $\implies$ 
	- $\exists\,\varepsilon>0$,  $r>0$,  $\gamma:[-\varepsilon,\,\varepsilon]\to \overline{B_{r}(p)}$
	- s.t.
		- (1) $\gamma'(t)=F(\gamma(t))\;\;\;\forall\,t \in(-\varepsilon,\,\varepsilon)$
		- (2) $\gamma(0)=p$

Rmk.
- Let
	- $T:\mathcal{C}^{0}([0,\,1])\to\mathcal{C}^{0}([0,\,1])$
		- by  $(Tf)(x)\coloneqq{\displaystyle\int}_{0}^{x}f(t)dt$  $\forall\,x \in[0,\,1]$  $\forall\,f \in\mathcal{C}^{0}([0,\,1])$
	- $\mathscr{F}\coloneqq\{\,Tf\;|\;f\in\mathcal{C}^{0}([0,\,1]),\,||f||_{\sup\,}\leq 1\,\}$
- $\implies$ 
	- $\overline{\mathscr{F}}$  compact but  $\mathscr{F}$ "not" closed $\subseteq\mathcal{C}^{0}([0,\,1])$

Thm.
-  ![[Screenshot 2024-01-05 at 12.35.03 AM.png]]


Pf. ^73cd32
Case $L=0$:  $\forall\,\varepsilon>0$  $\forall\,x,\,y\in X$:  $d_{Y}(f(x),\,f(y))=0$
Case $L\neq 0$:  $\forall\,\varepsilon>0$  $\forall\,x,\,y\in X$  with  $d_{X}(x,\,y)<\dfrac{\varepsilon }{L}$:  $d_{Y}(f(x),\,f(y))<\varepsilon$