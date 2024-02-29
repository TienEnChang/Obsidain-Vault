
$e^x$
- def: $\lim\limits_{n\to\infty}(1+\dfrac{x}n)^n$             [[Poisson - Pf.#^455612|{Pf}]] 
- taylor expansion: $\sum\limits_{n=0}^\infty(\dfrac1{n!}\,x^n)$ 

Discrete Trials
- $X\sim{\rm Poisson}(\lambda)$
- where
	- param:  $\lambda > 0$  where  $\lambda=\lim\limits_{n\to\infty}n\,P_{0}(E_{0})_{n}$
	- sample space:  $\Omega=\Omega_{0}{^{\!\infty}}$
	- count variable:  $\mathcal{X}=\{0,\,1,\,\cdots\,\}$
		- $X(\omega)\coloneqq$ $\#$ of occurrence of $E_{0}$ in $\infty$ trials

Continuous Process
- $N_0\coloneqq0$  $\land$  $(N_t-N_s)\sim{\rm Poisson}(\lambda= \overline{\lambda}(t-s))$
- where
	- param:  $\overline{\lambda} > 0$  |  $t,\,s\in[0,\,\infty)$  with  $t>s$
	- sample space:  $\Omega=\Omega_{0}{^{\!\infty}}$
	- count process:
		- ${N}_t(\omega)\coloneqq$ $\#$ of occurrence of $E_0$ "within $[0,\,t)$ interval"
		- $\mathcal{N}_t=\{0,\,1,\,\cdots\,\}$
- independence
	- $(N_{t_1}-N_{s_1})$, $(N_{t_2}-N_{s_2})$ indep. $\iff$ $[s_1,\,t_1)\cap[s_2,\,t_2)=\varnothing$


Rmk.
- ( ${N}_t(\omega)$ as $\omega$-specific nondecreasing step-function of $t$ )
	![[Screenshot 2023-11-21 at 12.23.16 AM.png]]