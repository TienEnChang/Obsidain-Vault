
Let $X$ be discrete r.v.

Def.
- expectation / mean:  $\mu_X\coloneqq{E}(X)\coloneqq\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot x]$  { weighted average }
- variance:            ${\sigma_X}^2\coloneqq{\rm Var}(X)\coloneqq {E}((X-\mu_X)^2)$
- standard deviation:  ${\sigma_X}$
  { $\because$ $\sum\limits_{x\in \mathcal{X}}|\,[\cdot]\,|$ converges (absolutely) $\therefore$ unaffected by change of order }
  { $\because$ $\sum\limits_{x\in \mathcal{X}}$ $\therefore$ unaffected by r.v.'s outcome }

Def.
- nth moment:  $E(X^n)$

Def. indicator function (r.v.)
- Let $A\subseteq\Omega$,  $1_A:\Omega\to\mathbb{R}$,  $1_A(\omega)\coloneqq\begin{cases}1&{\rm if}\;\omega\in A\\0&{\rm if}\;\omega\not\in A\end{cases}$
- $\implies$
	- $\mathcal{X}_{1_A}=\{0,\,1\}$
	- $f_{1_A}(0)=1-P(A)$,  $f_{1_A}(1)=P(A)$,  $E({1_A})=P(A)$

Rmk.
- $\mu_X$'s interpretation:  long run average  (Ch.8)
- $\mu_X$'s interpretation:  "center" of mass of p.m.f.
	- $\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot (x-\mu_X)]=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot x)]-[\sum\limits_{x\in \mathcal{X}}f_X(x)]\cdot \mu_X=0$

Rmk.
- ${\sigma_X}$'s interpretation:  for interval $\mu_X\pm k\,{\sigma_X}$  (need same unit)

---

Thm. 
- Let $Y=g(X)$, $\mathcal{Y}\coloneqq g(\mathcal{X})$, $g$ might not be 1-1
- $\implies$
	- $E(Y)=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot g(x)]$  [[Expectation, Variance - Pf.#^b7b38e|{Pf}]]
Cor. 
- $\forall\,a,\,b\in\mathbb{R}$:  $E(a\,X+b)=a\,E(X)+b$  [[Expectation, Variance - Pf.#^598cc2|{Pf}]]
- $\forall\,a,\,b\in\mathbb{R}$:  ${\rm Var}(a\,X+b)=a^2\,{\rm Var}(X)$ ,  $\sigma_{(aX+b)}=|a|\,\sigma_X$  [[Expectation, Variance - Pf.#^d8beb5|{Pf}]]

Thm.
- $\forall\,c\in\mathbb{R}$:  $E((X-c)^2)=\sigma_X^2+(c-\mu_X)^2$  [[Expectation, Variance - Pf.#^72cb9e|{Pf}]]
  { mean square error = var. + bias$^2$ }
Cor.
- $\min\limits_{c\in\mathbb{R}}E((X-c)^2)=\sigma_X^2$  where  $c^*=\mu_X$
Cor.
- $\sigma_X^2=E(X^2)-\mu_X^2$
  { var. = (2nd moment) - (1st moment)^2 }