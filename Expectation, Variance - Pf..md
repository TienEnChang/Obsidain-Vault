.

Pf. transformation ^b7b38e
- $E(Y)$
	- $=\sum\limits_{y\in \mathcal{Y}}[f_Y(y)\cdot y]$
	- $=\sum\limits_{y\in \mathcal{Y}}[\sum\limits_{x\in g^{\leftarrow}\{y\}\cap \mathcal{X}}[f_X(x)]\cdot y\,]=\sum\limits_{y\in \mathcal{Y}}[\sum\limits_{x\in g^{\leftarrow}\{y\}\cap \mathcal{X}}[\,f_X(x)\cdot g(x)\,]\,]$
	- $=\sum\limits_{x\in g^{\leftarrow}(\mathcal{Y})\cap \mathcal{X}}[\,f_X(x)\cdot g(x)\,]=\sum\limits_{x\in \mathcal{X}}[\,f_X(x)\cdot g(x)\,]$

Pf. linear transformation of $E(X)$ ^598cc2
- $E(aX+b)=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot (ax+b)]$  (by Thm.)
  $=a\cdot\sum\limits_{x\in \mathcal{X}}[\,f_X(x)\cdot x\,]+b\cdot\sum\limits_{x\in \mathcal{X}}[f_X(x)]=a\,E(X)+b$ 

Pf. ^d8beb5
- ${\rm Var}(aX+b)=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot (ax+b-(a\mu_X-b))^2]$
  $=a^2\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot (x-\mu_X)^2)]=a^2\,{\rm Var}(X)$

Pf. ^72cb9e
- $E((X-c)^2)=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot ((x-\mu_X)-(c-\mu_X))^2$
  $=\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot (x-\mu_X)^2]-2(c-\mu_X)\sum\limits_{x\in \mathcal{X}}[f_X(x)\cdot(x-\mu_X)]+(c-\mu_X)^2$
  $=\sigma_X^2-2(c-\mu_X)\cdot 0+(c-\mu_X)^2$

