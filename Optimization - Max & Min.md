
Def. 
- consumption set / choice variable:  $X\subseteq\mathbb{R}^n$ , $x\in X$
- objective function:  $f:X\to \mathbb{R}$
- constraint:  $D\subseteq X$

\[ Basic Formulation ]

Def.
- maximization problem:
	- $\max\limits_x\,f(x)$  sub. to  $x\in D_1,\,D_2\cdots$   {econ}
	- or          
	- $\max\,\{\,f(x)\;|\;x\in D_1,\,D_2\cdots\,\}$  or  $\max\,(\,f(\bigcap\limits_{i=1}^nD_i)\,)$   {math}

Def
- solvable:           $\max\,\{\,f(x)\;|\;x\in D\,\}$  exists
- set of maximizers:  ${\rm argmax}\,\{\,f(x)\;|\;x\in D\,\}\coloneqq f^{\leftarrow}(\max\,\{\,f(x)\;|\;x\in D\,\})$

Def
- global maximum:  $x^*\in{\rm argmax}\,\{\,f(x)\;|\;x\in D\,\}$
	
- local maximum: (allow boundary point)
		$x^*\in D$  where  $f(x^*)=\max\,\{\,f(x)\;|\;x\in D\cap B_r(x^*)\,\}$  for some  $r>0$
	
- uncontrained local max:
		$x^*\in D$  where  $f(x^*)=\max\,\{\,f(x)\;|\;x\in{\rm int}(D\cap B_r(x^*))\,\}$  for some  $r>0$
	
- strict local max: 
		$x^*\in D$  where  $f(x^*)>f(x)\;$ $\forall\,x\in (D\cap B_r(x^*))-\{x^*\}$  for some  $r>0$