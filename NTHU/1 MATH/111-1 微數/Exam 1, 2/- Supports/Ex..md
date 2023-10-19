Ex.
Prove that $f(x)=\begin{cases}1,\;\;\;\,{\rm if}\,x\geq0\\-1,\;{\rm if}\,x<0\end{cases}$ , $\displaystyle\lim_{x\to 0}f(x)$ D.N.E.
$\exists\varepsilon=\dfrac12$ s.t.
case $|1-L|>\dfrac12$:    $\forall\delta>0,\;\exists x=\dfrac12\delta$
                   s.t. $0<|x-0|<\delta\implies|f(x)-L|=|1-L|>\dfrac12=\varepsilon$
case $|-1-L|>\dfrac12$:  $\forall\delta>0,\;\exists x=-\dfrac12\delta$
                   s.t. $0<|x-0|<\delta\implies|f(x)-L|=|-1-L|>\dfrac12=\varepsilon$

Ex. 
Prove that $\sqrt{x}$ is cont. on $[0,\;\infty)$,
which also means $\displaystyle\lim_{x\to c}\sqrt{x}=\sqrt{c},\;\;\forall c\in[0,\;\infty)$.
$\forall\varepsilon>0,\;\exists\delta=min(c,\;(1+\sqrt{2})\sqrt{c}\,\varepsilon)$
s.t. $\because$ $0<|x-c|<c\implies0<x<2c\implies\sqrt{x}+\sqrt{c}<(1+\sqrt2)\sqrt{c}$
			$|\sqrt{x}-\sqrt{c}|=\dfrac{|x-c|}{\sqrt{x}+\sqrt{c}}$
	 $\therefore$ $0<|x-c|<\delta\implies|\sqrt{x}-\sqrt{c}|<\varepsilon$

Ex.
Prove that $sin(x)$ and $cos(x)$ are cont. on $\mathbb{R}$
(1) $\displaystyle\lim_{x\to c}sin(x)=\lim_{t\to 0}sin(c+t)$
    $\displaystyle=sin(c)\lim_{t\to 0}cos(t)+cos(c)\lim_{t\to 0}sin(t)=sin(c)$
(2) $\displaystyle\lim_{x\to c}cos(x)=\lim_{t\to 0}cos(c+t)$
    $\displaystyle=cos(c)\lim_{t\to 0}cos(t)-sin(c)\lim_{t\to 0}sin(t)=cos(c)$


---


Ex. Suppose $\exists\,\displaystyle\lim_{x\to c}f(x)\;\land\;\exists\,\displaystyle\lim_{x\to c}g(x)$
(1) $\forall x\not=c:\;f(x)\leq g(x)\implies \displaystyle\lim_{x\to c}f(x)\leq\lim_{x\to c}g(x)$
(2) $\forall x\not=c:\;f(x)\geq g(x)\implies \displaystyle\lim_{x\to c}f(x)\geq\lim_{x\to c}g(x)$