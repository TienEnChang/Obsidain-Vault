
\[ Basis ]

Def.
- proper:  $A\neq X,\;\varnothing$
- disjoint union:  $A\amalg B$ $\iff$ $A\cup B$  $\land$  $A\cap B=\varnothing$

Def. 
- connected:  $\neg$
- disconnected:
	- $\exists\,S$ proper, open, closed $\subseteq A$  { $S\amalg S^c$ (in $A$) $=A$ }
- totally disconnected:
	- $S$ nonempty, connected $\subseteq A$ $\implies$ $S$ singleton

Def.
- path joining $p,\,q \in X$:  $\,\gamma:[0,\,1]\to X$  continuous  $\land$  $\gamma(0)=p$, $\gamma(1)=q$
- path-connected: 
	- $\forall\,p,\,q\in X$:  $\exists$ path $\gamma$ joining them  
	              { $\iff$ $\exists$ path $\,\gamma':[a,\,b]\to X$ joining them }

Def.
- locally connected:
	- $\forall\,x \in X$, $\forall$ neighborhood $N_{x}$:  $\exists$ connected neighborhood $V_{x}\subseteq N_{x}$

Prop. $\varnothing$ & singletons are connected

Thm. $A\subseteq X$ path-connected $\implies$ connected


\[ Topological Space ]

Thm. invariance
- For $f:X\to Y$ continuous,
	- $A$ connected $\subseteq X$ $\implies$ $f(A)$ connected $\subseteq Y$  [[Connectedness - Pf.#^8f648d|{Pf}]]
	- $A$ path-connected $\subseteq X$ $\implies$ $f(A)$ path-connected $\subseteq Y$  [[Connectedness - Pf.#^bfd1ab|{Pf}]]

Prop.
- $X$ seperated by $S$, $S^{c}$ 
	- $A\subseteq X$ connected  $\land$  $A\cap S\neq \varnothing$ $\implies$ $A\subseteq S$

Prop.
- $\forall\,x,\,y,\,z\in X$:  $\exists$ path joining $x,\,y$ and $y,\,z$ $\implies$  $\exists$ path joining $x,\,z$


\[ Metric Space ]

Prop.
- $A\subseteq X$ connected $\implies$ $\forall\,S\subseteq X$  with  $A\subseteq S\subseteq \overline{A}$:  $S$ connected 


\[ $\mathbb{R}$ ]

Prop. $[a,\,b]$ connected $\subseteq \mathbb{R}$  [[Connectedness - Pf.#^83a32a|{Pf}]]

Prop.
- For $A$ open $\subseteq \mathbb{R}^{n}$,  $A$ connected $\iff$ $A$ path-connected 


\[ $\mathcal{F}(X,\,\mathbb{R})$ ]

Thm. Generalized IVT
- $X$ connected  $\land$  $f:X\to\mathbb{R}$ continuous
- $\implies$
- $\forall\,c\in\mathbb{R}$:
	- $\exists\;x,\,y\in X$  s.t. $f(x)<c<f(y)$ $\implies$ $\exists\;z\in X$  s.t. $f(z)=c$  [[Connectedness - Pf.#^116e54|{Pf}]]

Cor. IVT in $\mathbb{R}$
- $\exists\;x,\,y\in \mathbb{R}$  with  $x<y$  s.t. $f(x)<c<f(y)$ $\implies$ $\exists\;z\in (x,\,y)$  s.t. $f(z)=c$

Cor.
- $f:S^n\subseteq\mathbb{R}^{n+1} \to\mathbb{R}$  continuous $\implies$ $\exists\;x_0\in S^n$  s.t. $f(x_0)=f(-x_0)$  [[Connectedness - Pf.#^5ca29b|{Pf}]]