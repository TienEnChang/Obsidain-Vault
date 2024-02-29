
Def. asymptotically bounded above by ( partial order )
- $f(x)=O(g(x))$
	- $\iff$ $\exists\,c> 0$  $\exists\,N>0$  s.t. $\forall\,x> N$:  $0<f(x)<c\cdot g(x)$
	- $\iff$ $\exists\,\lim\limits_{N\to\infty}(\sup\limits_{x>N}\,\{\,\dfrac{f(x)}{g(x)}\,\})$  where  $f,\,g$  pointing up

Def. asymptotically dominated by / negligible as $x\to\infty$
- $f(x)=o(g(x))\;$
	- $\iff$ $\forall\,c> 0$  $\exists\,N>0$  s.t. $\forall\,x> N$:  $0<f(x)<c\cdot g(x)$
	- $\iff$ $\lim\limits_{x\to\infty}\dfrac{f(x)}{g(x)}=0$  where  $f,\,g$  pointing up

Def. equal in asymptotic growth rate ( equivalence )
- $f\;{\overset{\rm \Theta}\sim}\;g$ 
	- $\iff$ $f(x)=\Theta(g(x))$ $\iff$ $f(x)=O(g(x))$  $\land$  $g(x)=O(f(x))$

Def. asymptotic ( equivalence )
- $f\;{\overset{\rm asymp}\sim}\;g$ 
	- $\iff$ $f(x)=g(x)+o(g(x))\;$  i.e.  $g(x)=f(x)+o(f(x))\;$