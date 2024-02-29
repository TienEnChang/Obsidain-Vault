
Def.
- sequence $(a_n)_{n\in\mathbb{N}}$ in $X$:
	- defined by $f_{\rm seq}:\mathbb{N}\to X$  where $a_n\coloneqq f_{\rm seq}(n)$  $\forall\,n\in\mathbb{N}$
- 
- tuple / list $(a_1,\,...\,,a_r)$ in $X$:
	- defined by $f_{\rm tuple}:\{\,1,\,...\,,r\in\mathbb{N}\,\}\to X$  where $a_i\coloneqq f_{\rm tuple}(i)$  $\forall\,i\in\mathbb{N}$
- 
- set $\{\,a_1,\,...\,,a_r\,\}$ in $X$

Def.
- permutation of $n$ objects with length $r$:
	- tuple $(a_1,\,...\,,a_r)$ in $\{\,x_1,\,...\,,x_n\,\}$
	  where  $f_{\rm tuple}$ 1-1  i.e.  $a_1,\,...\,,a_r$ distinct
- 
- combination of $n$ objects with size $r$:
	- $\{\,a_1,\,...\,,a_r\,\}\subseteq\{\,x_1,\,...\,,x_n\,\}$

Def.
- set of permutations:  $\mathcal{F}(\{\,1,\,...\,,r\,\},\,\{\,1,\,...\,,n\,\})$
- number of diff permutations:
	- $P_r^n$ or $(n)_r\coloneqq\dfrac{n!}{(n-r)!}$
- number of diff combinations:
	- $C_r^n$ or ${n \choose r}\coloneqq\dfrac{n!}{(n-r)!}\cdot\dfrac1{r!}$


Thm. Binomial Theorem:  $(x+y)^n={\displaystyle\sum_{r=0}^n}\;{n \choose r}\,x^r\,y^{\,n-r}$

Cor. Binomial Identities:  $2^n={\displaystyle\sum_{r=0}^n}\;{n \choose r}$,  $0={\displaystyle\sum_{r=0}^n}\;{n \choose r}\,(-1)^r$
Thm. Combination Identity:  ${n\choose r}={n-1\choose r-1}+{n-1\choose r}$

Thm. Multinomial Theorem:  $(x_1+...+x_r)^n=\sum\limits_{n1+...+n_r=n}{n\choose \,n_1,\,...,\,n_r\,}\,x_1^{n_1}\,x_2^{n_2}...\,x_r^{n_r}$
