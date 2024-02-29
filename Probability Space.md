
Def. probability space: $(\Omega,\,\mathcal{F}_\Omega,\,P)$


\[ sample space, sigma-field ]

Def. sample space $\Omega$
- meaning:
	- a set that includes all possible <u>outcomes</u> in a random phenomenon
- types
	- discrete:   $\Omega$ is countable,   $\mathcal{F}_\Omega=\mathcal{P}(\Omega)=2^{\Omega}=\mathcal{F}(\Omega,\,\{\,0,\,1\,\})$
	- continuous: $\Omega$ is uncountable, $\mathcal{F}_\Omega$ ??

Def.
- outcome:  $\omega\in\Omega$
- event:    $E\in\mathcal{F}_\Omega$  i.e. "measurable" $E\in\mathcal{P}(\Omega)$


\[ probability measure ]

Def. classical approach
- $P(E)\coloneqq\dfrac{\#E}{\#\Omega}$
- where 1. $\Omega$ is finite
        2. $P$ is symmetric  i.e. $\forall\,\omega\in\Omega$: $P(\{\omega\})=\dfrac1{\#\Omega}$
           ( all outcomes are equally likely )

Def. modern approach
- $P:\mathcal{F}_\Omega\to[0,\,1]$
- where
	1. $\forall\,E\in{F}_\Omega$: $P(E)\geq 0$   {non-negativity}
	2. $P(\Omega)=1$             {total one}
	3. $\forall$ pairwise disjoint $(E_n)_{n\in\mathbb{N}}$ in $\mathcal{F}$
	          ( i.e. $\forall\,i\neq j$: $E_i\cap E_j=\varnothing$ ):
	          $P(\bigcup\limits_{n\in\mathbb{N}}E_n)=\sum\limits_{n\in\mathbb{N}}P(E_n)$           {additivity}
- $\implies$
	- $P(\varnothing)=0$
	- $\forall$ pairwise disjoint $(E_1,\,...\,,E_n)$ in $\mathcal{F}_\Omega$:  $P(\bigcup\limits_{i=1}^nE_i)=\sum\limits_{i=1}^nP(E_i)$
	- $\forall\,E\in{F}_\Omega$:  $P(E^c)=1-P(E)$
	- $\forall\,A,\,B\in\mathcal{F}_\Omega$ with $A\subseteq B$:  $P(A)\leq P(B)$  $\land$  $P(B-A)=P(B)-P(A)$
	- $\forall\,E\in{F}_\Omega$:  $P(E)\leq1$
- $\implies$
	- $\forall\,A,\,B\in\mathcal{F}_\Omega$:  $P(A\cup B)=P(A)+P(B)-P(A\cap B)$
	- $\forall\,(E_1,\,...\,,E_n)$ in $\mathcal{F}_\Omega$:  $P(\bigcup\limits_{i=1}^n{E_i})=\sum\limits_{1\leq i\leq n}P({E_i})-\sum\limits_{1\leq i<j\leq n}{P(E_i\cap E_j)}+\sum\limits_{1\leq i<j<k\leq n}{P(E_i\cap E_j\cap E_k)}\,...$