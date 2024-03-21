
- m.g.f.
	-  ![[Screenshot 2024-01-08 at 7.49.56 PM.png]]

Def.
- expectation:
	- $\text{E}(X)\coloneqq I_{\mathbb{R}\,}[[\,x\,{}_{(d,\,\Delta)}F_{X}(x)\,]]$            { need abs. conv. }
		- continuous:  $={\displaystyle\int}_{\mathbb{R}}\,xf_{X}(x)dx$
		- discrete:    $=\sum\limits_{x\,\in\, \mathbb{R}\cap\mathcal{X}}x\,p_{X}(x)$
	
- kth moment:          $\mu_{k}\coloneqq\text{E}(X^{k})$        { $\text{E}(X)\coloneqq\mu=\mu_{1}$ }
- kth central moment:  $\mu_{k}'\coloneqq\text{E}[(X-\mu)^{k}]$

Def.
- variance:  $\text{Var}(X)\coloneqq \sigma^{2}=\mu_{2}'=\text{E}[(X-\mu)^{2}]$
	                 $\,\,\,\,=\mu_{2}-{\mu_{1}}^{2}=\text{E}(X^{2})-E(X)^{2}$
- skewness:  $\mu'_{3}/\sigma^{3}$
- kurtosis:  $\mu_{4}'/\sigma^{4}$

Def.
- covariance:   $\text{Cov}(X,\,Y)\coloneqq\sigma_{XY}=\text{E}[(X-\mu_{X})(Y-\mu_{Y})]$
- correlation:  $\text{Cor}(X,\,Y)\coloneqq\rho_{XY}=\dfrac{\sigma_{XY}}{\sigma_{X}\sigma_{Y}}$

Def.
- moment generating function:
	- $M_{X}(t)\coloneqq\text{E}(e^{tX})$                       { $\forall\,t$ with abs. conv. }
		- continuous:  $={\displaystyle\int}_{\mathbb{R}}\,f_{X}(x)\,{(e^{t})}^{x}dx$
		- discrete:    $=\sum\limits_{x\,\in\, \mathbb{R}\cap\mathcal{X}}\,p_{X}(x)\,{(e^{t})}^{x}$
	- $\implies$ $M_{X}(0)=1$

Note
- {discrete}
	- binomial:      $M_{X}(t)=[1+p(e^{t}-1)]^{n}$   $\,\,\forall\,t<-\log(1-p)$
	- neg-binomial:  $M_{X}(t)=[\dfrac{pe^{t}}{1-(1-p)e^{t}}]^{r}$   $\forall\,t<-\log(1-p)$
	
	- poisson:       $M_{X}(t)=e^{\lambda(e^{t}-1)}$     $\forall\,t \in \mathbb{R}$
	
- {continuous}
	- uniform:       $M_{X}(t)=\dfrac{e^{bt}-e^{at}}{t(b-a)}$   $\forall\,t \in \mathbb{R}$
	- exponential:   $M_{X}(t)=\dfrac{\lambda}{\lambda-t}$     $\,\,\forall\,t < \lambda$
	- gamma:         $M_{X}(t)=(\dfrac{\lambda}{\lambda-t})^{\alpha}$
	- normal:        $M_{X}(t)=e^{\mu t}\cdot M_{\Phi}(\sigma t)$, $M_{\Phi}(t)=e^{\frac{t^{2}}{2}}$  $\forall\,t \in \mathbb{R}$
		- $X \sim\text{normal}(\mu,\,\sigma^{2})$,  $Z_{\Phi}\coloneqq\dfrac{X-\mu}{\sigma}$


Rmk.
- $M_{X}(0)=1$,  ${M_{X}}^{(k)}(0)=\mu_{(k)}$
- $f(x)=f(0)+\dfrac{f^{(1)}(0)}{1!}t+\dfrac{f^{(2)}(0)}{2!}t^{2}+\cdots$  { taylor expansion }

Rmk.
- $M_{\textbf{X}}(\vec{t}\,)=\prod\limits_{i=1}^nM_{X_{i}}(t_{i})$  { if indep. }
- $M_{\,\sum\limits_{i=1}^{n}X_{i}}(t)=\prod\limits_{i=1}^nM_{X_{i}}(t)$  { if indep. }

Pf.
- $M_{\,\sum\limits_{i=1}^{n}X_{i}}(t)=\text{E}_{\textbf{X}}(e^{\,t\sum\limits_{i=1}^{n}X_{i}})=\text{E}_{\textbf{X}}(\prod\limits_{i=1}^{n}e^{tX_{i}})$
- { indep. } $=\prod\limits_{i=1}^{n}\text{E}_{X_{i}}(e^{tX_{i}})=\prod\limits_{i=1}^nM_{X_{i}}(t)$


Rmk.
- chi-square dist:  

Rmk.
- $\,\chi^{2}\text{-dist}(n)$ $\equiv$ ${\rm gamma}(\alpha=\dfrac{n}2,\,\lambda=\dfrac12)$
	- $M(t)=(\dfrac{1}{1-2t})^{n/2}$  { $\mu=n$, $\sigma^{2}=2n$ }

- $(Z_{\Phi})^{2}\sim\chi^{2}\text{-dist}(1)$ ,  $U_{n}\coloneqq\sum\limits_{i=1}^{n}[(Z_{\Phi})^{2}{}_{(i)}]\sim \chi^{2}\text{-dist}(n)$  where  ${(Z_{\Phi})^{2}}_{(i)}$  i.i.d.

Rmk.
- $\dfrac{(n-1)S_{n}{}^{2}}{\sigma^{2}}\sim \chi^{2}\text{-dist}(n-1)$  { Pf?? }

Rmk.
- $V_{n}\coloneqq\dfrac{Z_{\Phi}}{\sqrt{ \frac{U_{n}}{n} }}\sim\text{t-dist}(n)$
- $W_{m,\,n}\coloneqq\dfrac{U_{m}/m}{U_{n}/n}\sim\text{F-dist}(m,\,n)$  where  $U_{m}$, $U_{n}$  indep.
- { $\text{E}(W_{m,\,n})=\dfrac{n}{n-2}$  for $n>2$ }

