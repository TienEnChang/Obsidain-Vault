
.

Pf. 1-1 ^b41af7
- $\forall (n,\;m)\in \mathbb{N}^2$: $f(n,\;m)\coloneqq (\displaystyle\sum_{k=1}^{n+m-2}k)+m$
- ![[Screenshot 2023-09-22 at 11.18.03 PM.png|600]]
- ![[Screenshot 2023-09-22 at 11.19.05 PM.png|600]]
- ![[Screenshot 2023-09-22 at 11.19.56 PM.png|600]]
- ![[Screenshot 2023-09-22 at 11.20.28 PM.png|600]]


Pf. 1-2 ^296471
- case $A$ is finite:  $A$ is countable
- case $A$ is infinite:
	1. Let $\widetilde{f}:A\to f(A)$  where $\widetilde{f}(x)\coloneqq f(x)$
		$\because$  $f$ is 1-1
	   $\implies$ $\widetilde{f}$ is bijective
	   $\implies$ $|A|=|f(A)|$ $\implies$ $f(A)$ is infinite
	2.  $\because$  $S$ is countable  $\land$  $f(A)\subseteq S$
	   $\implies$ $S$ is denumerable
	   $\implies$ $\exists$ bijective $g:\mathbb{N}\to S$
	   $\because$  $f(A)\subseteq S$ $\implies$ $S$ is infinite
	   
![[Screenshot 2023-09-27 at 4.58.42 PM.png|700]]
Pf. 1-2-wrong 
Assume $\exists$ 1-1 $f:X\to S$  where  $S$ is countable
- case $S$ is finite:
	- $\implies$ $\exists$ bijective $n:{\rm Rng}(f)\to \{1,2,...N\in\mathbb{N}\}$
		    $\land$  bijective $f\circ n:X\to \{1,2,...N\in\mathbb{N}\}$
	- $\implies$ $X$ is finite
- case $S$ is denumerable:
	- case $f$ is onto:
		- $\implies$ $\exists$ bijective $n:{\rm Cod}(f)\to \mathbb{N}$  $\land$  bijective $f\circ n:X\to \mathbb{N}$
		- $\implies$ $X$ is denumerable
	- case $f$ is not onto:
		- $\implies$ $\exists$ bijective $n:{\rm Rng}(f)\to$ a subset of $\mathbb{N}$
		- $\implies$ ?

Pf. 1-3 ^c8f556
- $X\subseteq S$
- $\implies$ $\exists$ 1-1 $f:X\to S$  where  $f(x)=x$
- By Thm.
	- $S$ is countable $\implies$ $X$ is countable
Pf. (by contradiction)
- Assume $\exists\,A\subseteq S$  s.t. $A$ is uncountable (is infinite)
- $\implies$ $S$ is infinite  $\because$ $S$ is countable
- $\implies$ $S$ is denumerable
- $\implies$ $A$ is denumerable (is countable) 


Pf. 1-4 ^ae3bbd
- $S$ is denumerable
- $\implies$ $S$ is countable $\land$ $X$ is countable
- $\implies$ $X$ is denumerable  ( $\because$ $X$ is infinite )


Pf. 1-5 ^65395d
- Let
	- case $X_i=\{\,x_{1},...,x_{n}\,\}$ is finite:
		- $\implies$ ${\rm Seq}(X_i)\coloneqq(x_{1},...,x_{n},...)$ where $x_{k}=x_n$ $\forall\,k>n$
	- case $X_i=\{\,x_{1},...,x_{n},...\,\}$ is infinite:
		- $\implies$ ${\rm Seq}(X_i)\coloneqq(x_{1},...,x_{n},...)$
- Let
	- $M\coloneqq\{\,x_{ij}=j$-th element of $i$-th element of $\{\,{\rm Seq}(X_n)\,\}_{n=1}^\infty$$\,\}$
	  ![[Screenshot 2023-09-22 at 9.54.41 PM.png|300]]
- $\implies$ $\exists$ bijective $f:\mathbb{N}^2\to M$  where $f(i,\,j)\coloneqq x_{ij}$
        $\land$  bijective $n:\mathbb{N}\to\mathbb{N}^2$  ( By Thm. )
- $\implies$ $\exists$ bijective $f\circ n:\mathbb{N}\to M$
- $\implies$ $\exists$ onto $g:\mathbb{N}\to\bigcup\limits_{i\in\mathbb{N}}X_i$   ($g$ is not 1-1 if $\exists\,X_i$ is finite)
- Let
	- $h:\bigcup\limits_{i\in\mathbb{N}}X_i\to\mathbb{N}$  where  $h(x)\coloneqq$ smallest element in $g^{-1}(\{x\})\subseteq\mathbb{N}$
	  ( By the Well-ordering Principle )
	- $\implies$ $h$ is 1-1
- By Thm.
	- $\mathbb{N}$ is countable $\implies$ $\bigcup\limits_{i\in\mathbb{N}}X_i$ is countable


Pf. 1-6 ^f28697
- ![[Screenshot 2023-09-22 at 10.54.26 PM.png|600]]

Pf. 1-7 ^895a9c
- ![[Screenshot 2023-09-22 at 10.57.13 PM.png|600]]

Pf. 1-8 (by induction) ^3ba3c1
- case $n=1$: $A^1$ is countable
- case $n=k$:
	- Assume $A^k$ is countable
	- $\implies$ By Thm, $A^k\times A$ is countable
	- $\implies$ $A^{k+1}$ is countable  ( $\because$ $|A^k\times A|=|A^{k+1}|$ )
- ![[Screenshot 2023-09-22 at 11.25.08 PM.png|600]]


Pf. 1-9 ^f300b4
- Let $f:\mathbb{N}\to\mathbb{Z}$  where $f(n)\coloneqq\begin{cases}\dfrac{n}2&{\rm if}\;n\;{\rm is\;even}\\-\dfrac{n-1}2&{\rm if}\;n\;{\rm is\;odd}\end{cases}$
- $\implies$ $f$, $f^{-1}:\mathbb{Z}\to\mathbb{N}$ are bijective
- $\implies$ $Z$ is denumerable


Pf. 1-10 ^a8d7c6
- $\mathbb{Q}\coloneqq\{\,\dfrac{p}{q}\;|\;p\in\mathbb{Z},\,q\in\mathbb{N}\,\}$  where  $\dfrac{p}{q}$ is an unique expression
- $\implies$ $\exists$ bijective $f:\mathbb{Z}\times\mathbb{N}\to\mathbb{Q}$  where  $f(p,\,q)\coloneqq\dfrac{p}{q}$
- $\implies$ $f^{-1}:\mathbb{Q}\to\mathbb{Z}\times\mathbb{N}$  is bijective
- By Thm.
	- $\mathbb{Z}\times\mathbb{N}$ is countable $\implies$ $\mathbb{Q}$ is countable
	- $\implies$ $\mathbb{Q}$ is denumerable  ( $\because$ $\mathbb{Q}$ is infinite )

Pf. 1-11 (by Cantor’s diagonal method) ^aa29ae
- Assume $(0,\,1)$ is countable
- $\implies$ $\exists$ bijective $f:\mathbb{N}\to (0,\,1)$
- Let ${\rm all\,\textendash\, dec}:(0,\,1)\to\mathcal{F}(\mathbb{N},\,\{0,...,9\})$ be the decimal expansion function
	- where  $0.a_1a_2a_3...\mapsto(a_1,\,a_2,\,a_3,...)$  and  $0.a_1...\overline{999}$ be illegal
- Let ${\rm special\,\textendash\,dec}:\mathbb{N}\to \{0,...,9\}$
	- where  $\forall\,n\in\mathbb{N}$:
	  ${\rm special\,\textendash\,dec}(n)\neq{\rm all\,\textendash\,dec}(f(n))(n)$  $\implies$  ${\rm special\,\textendash\,dec}\not\in{\rm all\,\textendash\,dec}(f(\mathbb{N}))$
	  ${\rm special\,\textendash\,dec}(n)\neq 9$  $\implies$  ${\rm special\,\textendash\,dec}\in{\rm all\,\textendash\,dec}((0,\,1))$
- $\implies$ 
	- $f(\mathbb{N})\neq (0,\,1)$,  $(0,\,1)$ is uncountable

Pf. 1-12 ^59ef2c
- Let $f:(0,\,1)\to\mathbb{R}$  where  $f(x)\coloneqq \tan(\pi x-\dfrac\pi2)$
- $\implies$ $f$ is bijective  ( $\because$ $\tan$ is bijective )
- $\implies$ $|(0,\,1)|=|\mathbb{R}|$

Pf. 1-13 (by Cantor’s diagonal method) ^1e88b1
- Assume $\mathcal{F}(\mathbb{N},\,\{0,\,1\})$ is countable
- $\implies$ $\exists$ bijective $f:\mathbb{N}\to \mathcal{F}(\mathbb{N},\,\{0,\,1\})$
- Let $g:\mathbb{N}\to \{0,\,1\}$  where  $g(n)\coloneqq\begin{cases}0,&{\rm if}\;f(n)(n)=1\\1,&{\rm if}\;f(n)(n)=0\end{cases}$
- $\implies$ $g\not\in f(\mathbb{N})=\mathcal{F}(\mathbb{N},\,\{0,\,1\})$  ($\rightarrow\!\leftarrow$)

Pf. 1-14 ^74fb5f
- Let  $f:A\to B$ be 1-1,  $g:B\to A$ be 1-1
- $\implies$ $B\supseteq f(A)$  $\land$  $A\supseteq g(B)$
- $\implies$ $g(B)\supseteq g\circ f(A)$  $\land$  $f(A)\supseteq f\circ g(B)$
- $\implies$
	- $A\supseteq g(B)\supseteq g\circ f(A)\supseteq g\circ f\circ g(B)$...
	- $B\supseteq f(A)\supseteq f\circ g(B)\supseteq f\circ g\circ f(A)$...
- Let
	- $\{\,A_n\,\}_{n=1}^\infty$  where  $A_1=A-g(B)$,  $A_2=g(B)- g\circ f(A)$...
	- $\{\,B_n\,\}_{n=1}^\infty$  where  $B_1=B- f(A)$,  $B_2=f(A) - f\circ g(B)$...
- $\implies$
	- $\exists\,A_r\coloneqq A-\bigcup\limits_{n\in\mathbb{N}}A_n$, $B_r\coloneqq B-\bigcup\limits_{n\in\mathbb{N}}b_n$ s.t. $A_r=g(B_r)$, $B_r=f(A_r)$
- Let
	- $h_{12}:A_1\to B_2$,  $h_{12}(x)\coloneqq f(x)$  $\implies$  $h_{12}$ is bijective
	- $h_{21}:A_2\to B_1$,  $h_{21}(x)\coloneqq g^{-1}(x)$  $\implies$  $h_{21}$ is bijective
	- $h_{34}:A_3\to B_4$,  $h_{34}(x)\coloneqq f(x)$  $\implies$  $h_{34}$ is bijective
	- $h_{43}:A_4\to B_3$,  $h_{43}(x)\coloneqq g^{-1}(x)$  $\implies$  $h_{43}$ is bijective
	- ...
	- $h_{rr}:A_r\to B_r$,  $h_{rr}(x)\coloneqq f(x)=g^{-1}(x)$  $\implies$  $h_{rr}$ is bijective
- Let
	- $h:A\to B$,  $h(x)\coloneqq\begin{cases}f(x)&{\rm if}\;x\in A_i\;\land\;i\;{\rm is\;odd},\;{\rm or\;if}\;x\in A_r\\g^{-1}(x)&{\rm if}\;x\in A_i\;\land\;i\;{\rm is\;even}\end{cases}$
	- $\implies$
		- $h$ is bijective $\implies$ $|A|=|B|$
	  ![[PSX_20230923_140741.jpg|600]]

Let
- $\forall\,a\in(0,\,1)$  let its unique binary expression
	 be  $0.\,a_1\,a_2\,a_3...$  where $a_i\in\{0,1\}$ $\forall\,i\in\mathbb{N}$, 
	 and  $0.\,a_1...\overline{111}$  be illegal

Pf. 1-15  (by binary expression) ^35cf24
- for $\geq$:
	- Let $f:(0,\,1)\to(0,\,1)\times(0,\,1)$  where  $f(x)=(\dfrac12,\,x)$
		- $\implies$ $f$ is 1-1 (not onto)
- for $\leq$:
	- Let $g:(0,\,1)\times(0,\,1)\to(0,\,1)$
		 where  $g(0.\,a_1\,a_2\,a_3...,\;0.\,b_1\,b_2\,b_3...)\coloneqq0.\,a_1\,b_1\,a_2\,b_2...$
	- $\implies$
		-  $g$ is 1-1 (not onto)  { $\because$ $(0.\overline{111},\,0)\mapsto0.\overline{0101}$ }
- By SB Thm.
	- $\implies$ $|(0,\,1)\times(0,\,1)|=|(0,\,1)|$

Pf. 1-16  (by binary expression) ^ed6639
- We know that $2^{\mathbb{N}}\coloneqq\{\,\{\,a_n\,\}_{n=1}^\infty\;|\;a_i\in\{0,1\}\;\;\forall\,i\in\mathbb{N}\,\}$
- Let $i:\mathcal{P}(\mathbb{N})\to2^\mathbb{N}$
	  where $\varnothing\mapsto(0,...,0,...)$
		    $\{1,\,2,\,3\}\mapsto(1,\,1,\,1,\,0,...,0,...)$
		    $\mathbb{N}\mapsto(1,...,1,...)$
	- $\implies$ $i$ is bijective 
- for $\leq$:
	- Let $f:[\,0,\,1)\to2^{\mathbb{N}}$  where  $0.\,a_1\,a_2\,a_3...\mapsto(a_1,\,a_2,\,a_3...)$
	- $\implies$ $f$ is 1-1 (not onto)
	- $\implies$ $f\circ i^{-1}:[\,0,\,1)\to\mathcal{P}(\mathbb{N})$  is 1-1
- for $\geq$:
	- Let $g:2^{\mathbb{N}}\to[\,0,\,1)$  where  $(a_1,\,a_2,\,a_3...)\mapsto0.\,a_10\,a_20\,a_30 ...$
	- $\implies$ $g$ is 1-1 (not onto)
	- $\implies$ $i\circ g:\mathcal{P}(\mathbb{N})\to[\,0,\,1)$  is 1-1
- By SB Thm.
	- $\implies$ $|[\,0,\,1)|=|\mathcal{P}(\mathbb{N})|$!

Pf. 1-17  (by induction)  ^1105d6
![[Screenshot 2023-09-27 at 4.53.47 PM.png|600]]