
- m.g.f.
	-  ![[Screenshot 2024-01-08 at 7.49.56 PM.png]]

Def.
- expectation:
	- $\text{E}(X)\coloneqq I_{\mathbb{R}\,}[[\,x\,{}_{(d,\,\Delta)}F_{X}(x)\,]]$            { need abs. conv. }
		- continuous:  $={\displaystyle\int}_{\mathbb{R}}\,xf_{X}(x)dx$
		- discrete:    $=\sum\limits_{x\,\in\, \mathbb{R}\cap\mathcal{X}}x\,p_{X}(x)$
	
- kth moment:          $\mu_{k}\coloneqq\text{E}(X^{k})$        { $\text{E}(X)\coloneqq\mu=\mu_{1}$ }
- kth central moment:  $\mu_{k}'\coloneqq\text{E}[(X-\mu)^{k}]$

Def.
- variance:  $\text{Var}(X)\coloneqq \sigma^{2}=\mu_{2}'=\text{E}[(X-\mu)^{2}]$
	                   $\,\,\,\,\,=\mu_{2}-{\mu_{1}}^{2}=\text{E}(X^{2})-E(X)^{2}$
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