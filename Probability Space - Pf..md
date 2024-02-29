
Pf.
- Let $(\Omega,\,\varnothing,\,...)$ in $\mathcal{F}_\Omega$
	- $\implies$ $P(\Omega)=P(\Omega)+\sum\limits_{n=2}^\infty P(\varnothing)$ $\implies$ $P(\varnothing)=0$  $\forall\,n\geq 2$
- Let pairwise disjoint $(E_1,\,...\,,E_n,\,\varnothing,\,...)$ in $\mathcal{F}_\Omega$
	- $\implies$ $P(\bigcup\limits_{i=1}^nE_i)=\sum\limits_{i=1}^nP(E_i)+\sum\limits_{i=n+1}^\infty P(\varnothing)$
- $P(E^c)+P(E)=P(E\cup E^c)=P(\Omega)=1$
- $P(B)=P(A)+P(B-A)\geq P(A)$ $\implies$ $P(B-A)=P(B)-P(A)$
- $E\subseteq\Omega$ $\implies$ $P(E)\leq P(\Omega)=1$

Pf.
- $P(A\cup B)$
	- $=P(A\cap B^c)+P(A\cap B)+P(A^c\cap B)$  (pairwise disjoint)
	- $=[P(A)-P(A\cap B)]+P(A\cap B)+[P(B)-P(A\cap B)]$
	- $=P(A)+P(B)-P(A\cap B)$

Pf.
(1) prove by induction
(2) by understanding the logic behind
- $A+B+C={1\choose 1}\,[A\cap B^c\cap C^c+A^c\cap B\cap C^c+A^c\cap B^c\cap C]$
            $\;+{2\choose 1}\,[A\cap B\cap C^c+A\cap B^c\cap C+A^c\cap B\cap C]$
            $\;+{3\choose 1}\,[A\cap B\cap C]$
- $A\cap B+A\cap C+B\cap C={2\choose 2}\,[A\cap B\cap C^c+A\cap B^c\cap C+A^c\cap B\cap C]$
                       $\,\;+{3\choose 2}\,[A\cap B\cap C]$
- $A\cap B\cap C={3\choose 3}\,[A\cap B\cap C]$
- $\implies$
- $\sum\limits_{i=1}^n{E_i}={1\choose 1}\sum\limits_{i=1}^n({{E_1}\!^c\,\cap\,..E_i\,..\,\cap {E_n}\!^c})$
        $+{2\choose 1}\sum\limits_{1\leq i<j\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..\,\cap {E_n}\!^c})$
        $+{3\choose 1}\sum\limits_{1\leq i<j<k\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..E_k\,..\,\cap {E_n}\!^c})$
        ...
- $\sum\limits_{1\leq i<j\leq n}{(E_i\cap E_j)}={1\choose 2}\sum\limits_{i=1}^n({{E_1}\!^c\,\cap\,..E_i\,..\,\cap {E_n}\!^c})$
                 $\;+{2\choose 2}\sum\limits_{1\leq i<j\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..\,\cap {E_n}\!^c})$
                 $\;+{3\choose 2}\sum\limits_{1\leq i<j<k\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..E_k\,..\,\cap {E_n}\!^c})$
                  ...
- $\sum\limits_{1\leq i<j<k\leq n}{(E_i\cap E_j\cap E_k)}={1\choose 3}\sum\limits_{i=1}^n({{E_1}\!^c\,\cap\,..E_i\,..\,\cap {E_n}\!^c})$
                        $+{2\choose 3}\sum\limits_{1\leq i<j\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..\,\cap {E_n}\!^c})$
                        $+{3\choose 3}\sum\limits_{1\leq i<j<k\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..E_k\,..\,\cap {E_n}\!^c})$
                        ...
- $\implies$
- $\because$
	- $\bigcup\limits_{i=1}^n{E_i}=\sum\limits_{i=1}^n({{E_1}\!^c\,\cap\,..E_i\,..\,\cap {E_n}\!^c})+\sum\limits_{1\leq i<j\leq n}({{E_1}\!^c\,\cap\,..E_i\,..E_j\,..\,\cap {E_n}\!^c})+$ ...
	- $1={n\choose 0}-{\sum\limits_{r=0}^n}\;{n \choose r}\,(-1)^r={n\choose 1}-{n\choose 2}+{n\choose 3}...{n\choose n}$
- $\therefore$
	- $\bigcup\limits_{i=1}^n{E_i}=\sum\limits_{i=1}^n{E_i}-\sum\limits_{1\leq i<j\leq n}{(E_i\cap E_j)}+\sum\limits_{1\leq i<j<k\leq n}{(E_i\cap E_j\cap E_k)}\,...$
