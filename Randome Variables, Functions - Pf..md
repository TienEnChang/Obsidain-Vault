.

Pf. p.m.f. ^9d66f6
- "$\implies$":
	1. $\forall\,x\in\mathcal{X}$: $f_X(x)=P(X^{\leftarrow}\{x\})\geq 0$
	2. $\forall\,x\not\in\mathcal{X}$: $f_X(x)=P(X^{\leftarrow}(\{x\}\cap\mathcal{X}))=P(\varnothing)=0$
	3. $\sum\limits_{x\in\mathcal{X}}f_X(x)=P(X^{\leftarrow}(\mathcal{X}))=P(\Omega)=1$
	4. $\forall\,A_X\subseteq\mathbb{R}$: $P_X(A_X)=P(X^{\leftarrow}(A_X\cap\mathcal{X}))=\sum\limits_{x\in A_X\cap \mathcal{X}}f_X(x)$
- "$\impliedby$":
	- Given $\mathcal{X}\subseteq\mathbb{R}$, $f:\mathbb{R}\to \mathbb{R}$
	- $\implies$
		- $\exists\,X:\mathcal{X}\to\mathbb{R}$  where  $X(x)\coloneqq x$
		- $\exists\,P_X:\mathcal{F}_\mathbb{R}\to\mathbb{R}$  where  $P_X(A_X)\coloneqq\sum\limits_{x\in A_X\cap \mathcal{X}}f(x)$  
		- $(\mathcal{X},\,\mathcal{F}_\mathbb{R},\,P_X)$ is a probability space ( why? )
	- $\implies$
		- $f_X(x)\coloneqq P_X(\{x\})\coloneqq\sum\limits_{x'\in \{x\}\cap \mathcal{X}}f(x')=\begin{cases}f(x)&{\rm if}\;x\in\mathcal{X}\\ 0=f(x)&{\rm if}\;x\not\in\mathcal{X}\end{cases}$

Pf. c.d.f ^49c099
- Claim: $A_n^+=(-\infty,\,x+\dfrac1{n}\,]$,  $\lim\limits_{n\to\infty}A_n^+=(-\infty,\,x\,]$
	- $(-\infty,\,x\,]\subseteq A_n^+$  $\forall\,n\in\mathbb{N}$
		- $\implies$ $(-\infty,\,x\,]\subseteq\bigcap\limits_{n\in\mathbb{N}}A_n^+$
	- $\forall\,t\in(-\infty,\,x\,]^c$  $\exists\,n\in\mathbb{N}$  with  $x+\dfrac1n=t$  s.t. $t\in (A_n^+)^c$
		- $\implies$ $(-\infty,\,x\,]^c\subseteq\bigcup\limits_{n\in\mathbb{N}}(A_n^+)^c$ $\implies$ $(-\infty,\,x\,]\supseteq\bigcap\limits_{n\in\mathbb{N}}A_n^+$
- Claim: $A_n^-\coloneqq(-\infty,\,x-\dfrac1{n}\,]$,  $\lim\limits_{n\to\infty}A_n^-=(-\infty,\,x)$
	- $(-\infty,\,x)^c\subseteq (A_n^-)^c$  $\forall\,n\in\mathbb{N}$
		- $\implies$ $(-\infty,\,x)^c\subseteq\bigcap\limits_{n\in\mathbb{N}}(A_n^-)^c$ $\implies$ $(-\infty,\,x)\supseteq\bigcup\limits_{n\in\mathbb{N}}A_n^-$
	- $\forall\,t\in(-\infty,\,x)$  $\exists\,n\in\mathbb{N}$  with  $x-\dfrac1n=t$  s.t. $t\in A_n^-$
		- $\implies$ $(-\infty,\,x)\subseteq\bigcup\limits_{n\in\mathbb{N}}A_n^-$
- "$\implies$":
	1. $\forall\,a,\,b\in\mathbb{R}$  with  $a<b$:
		- $F_X(b)=P_X(\,(-\infty,\,a\,]\,)+P_X(\,(a,\,b\,]\,)\geq P_X(\,(-\infty,\,a\,]\,)=F_X(a)$
	2. $\lim\limits_{t\to x}P_X(\,(-\infty,\,t\,]\,)=\,\lim\limits_{t\to x}(-\infty,\,t\,]\,)$
		- $P_X(\lim\limits_{t\to x+}(-\infty,\,t\,])=P_X(\,(-\infty,\,x\,]\,)=F_X(x)$  {claim 1}
		- $P_X(\lim\limits_{t\to x-}(-\infty,\,t\,])=P_X(\,(-\infty,\,x\,)\,)\neq F_X(x)$  {claim 2}
	3. $\lim\limits_{t\to-\infty}F_X(t)=\lim\limits_{t\to -\infty}P_X(\,(-\infty,\,t\,]\,)=P_X(\,\lim\limits_{t\to -\infty}(-\infty,\,t\,]\,)=P_X(\varnothing)=0$
	   $\lim\limits_{t\to\infty}F_X(t)=\lim\limits_{t\to \infty}P_X(\,(-\infty,\,t\,]\,)=P_X(\,\lim\limits_{t\to \infty}(-\infty,\,t\,]\,)=P_X(\mathbb{R})=1$
- "$\impliedby$":
	- omit

Pf. disjoint points ^d50e3a
- $\forall\,x_1,\,x_2\in D$  with  $x_1\neq x_2$
  $\exists\,r_{x_1},\,r_{x_2}\in\mathbb{Q}$  s.t.  $r_{x_1}\in (F_X(x_1^-),\,F_X(x_1))$,  $r_{x_2}\in (F_X(x_2^-),\,F_X(x_2))$
- $\implies$                                          { By $\mathbb{Q}$ is dense }
	- $r_{x_2}\neq r_{x_2}$
	- $\exists$ 1-1 $f:D\to\mathbb{Q}$ $\implies$ $|D|\leq|\mathbb{Q}|$ is countable

Pf. transformation ^d0f0a2
- $P_Y(A_Y)=P(Y^{\leftarrow}(A_Y))=P(X^{\leftarrow}(g^{\leftarrow}(A_Y)))=P_X(g^{\leftarrow}(A_Y))$
- $f_Y(y)=P(Y^{\leftarrow}\{y\})=P(X^{\leftarrow}(g^{\leftarrow}\{y\}))=\sum\limits_{x\in g^{\leftarrow}\{y\}\cap \mathcal{X}}f_X(x)$ 