
\[ In Metric Spaces ]

Let $X$ be metric spaces with $d$

Def.
- $A\subseteq S$ bounded:
	- $\exists\,\xi \in S$  $\exists\,r>0$  s.t. $\,A\subseteq B_{r}(\xi)$  { i.e. $\forall\,a \in A$: $\,d(a,\,\xi)<r$ }
	
- $(p_{n})_{n \in\mathbb{N}}$ bounded:
	- $\text{rng}((p_{n})_{n \in\mathbb{N}})=\{p_{n}\}_{n \in\mathbb{N}}$ bounded  { i.e. $\,\forall\,n \in \mathbb{N}$: $\,d(p_{n},\,\xi)<r$ }
	
- $f$ bounded:
	- $\text{rng}(f)$ bounded  { i.e. $\,\forall\,x \in X$: $\,d(f(x),\,\xi)<r$ }


\[ In Posets ]

Let $X$ be posets with $\leq$ ,  $A\subseteq X$

Def.
- bounded above:  $\exists$ upper bound of $A$ 
- bounded below:  $\exists$ lower bound of $A$ 

Def.
- upper bound:  $x\in X$  where  $x\geq a$  $\forall\,a\in A$    
- lower bound:  $x\in X$  where  $x\leq a$  $\forall\,a\in A$
	
- greatest elem. / maximum:  $\max(A)\coloneqq$ the upper bound of $A\,$ within $A$
- least elem. / minimum:     $\min(A)\coloneqq$ the lower bound of $A\,$ within $A$
	
- l.u.b. / supremum:  $\sup(A)\coloneqq\min\{$ all upper bounds of $A\,\}$  
- g.l.b. / infimum:   $\inf(A)\coloneqq\max\{$ all lower bounds of $A\,\}$

Prop.
- $\exists\sup(A)$ $\land$ $\sup(A)\in A$ $\iff$ $\exists\max(A)$  { $\max(A)=\sup(A)$ }
- $\exists\inf(A)$ $\land$ $\inf(A)\in A$ $\iff$ $\exists\min(A)$   $\;${ $\min(A)=\inf(A)$ }

Prop.
- $A$ is finite, total ordered { i.e. chain } { Hausdorff Principle }
- $\implies$ $\exists\max(A)$, $\exists\min(A)$


\[ In Ordered Field ]

Prop. 
- "$+$" inverse:  $\inf(-A) = -\sup(A)$
- "$\,\cdot\,$" inverse:  $\inf_{} (\dfrac{1}{A}) = \dfrac{1}{\sup_{} (A)}$