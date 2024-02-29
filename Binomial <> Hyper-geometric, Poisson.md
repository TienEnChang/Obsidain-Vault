
Note. Urn problem
- with replacement:     $X\sim{\rm binomial}(n,\,p=\dfrac{R}{N})$       {trial indep.}
- without replacement:  $X\sim{\rm hypergeometric}(n,\,N,\,R)$   {x}

Thm.
- $n$ fixed  $\land$
- $N_i\to\infty$, $R_i\to\infty$, $\dfrac{R_i}{N_i}\to p\in[0,\,1]$  as  $i\to\infty$
- $\implies$
	- when (1) $N_i$, $R_i$ sufficiently large (2) $N_i>>n$:
		- $[X\sim{\rm hypergeometric}(n,\,N_i,\,R_i)]\approx[X\sim{\rm binomial}(n,\,p\approx\dfrac{R_i}{N_i})]$

Thm.
- $p_n\to0$, $np_n\to\lambda$  as  $n\to\infty$
- $\implies$
	- when (1) $n$ sufficiently large (2) $p_n\approx 0$:
		- $[X\sim{\rm binomial}(n,\,p_n)]\approx [X_P\sim{\rm Poisson}(\lambda\approx np_n)]$
	- when (3) $k<<n$:
		- $f_X(k)\approx f_{X_P}(k)$
