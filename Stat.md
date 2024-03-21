
Lemma.
- $\text{E}(aX+b)=a\text{E}(X)+b$,  $\text{Var}(aX+b)=a^{2}\text{Var}(X)$
- $M_{(aX+b)}(t)=e^{bt}M_{X}(at)$

Rmk.
- $\text{E}(\overline{X}_{n})=\text{E}(\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i})=\dfrac{1}{n}\sum\limits_{i=1}^{n}\text{E}(X_{i})=\mu$   { if i.i.d. }
- $\text{Var}(\overline{X}_{n})=\text{Var}(\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i})=\dfrac{1}{n^{2}}\sum\limits_{i=1}^{n}\text{Var}(X_{i})=\dfrac{\sigma^{2}}{n}$  { if i.i.d. }

---

Lemma. Markov's inequality
- $P_{X}(|x|\geq r)\leq\dfrac{\text{E}(|X|)}{r}$

Lemma. Chebyshev's inequality
- $P_{X}(|x-\mu|\geq k\sigma)\leq\dfrac{1}{k^{2}}$  { $P_{X}[(\mu-\sigma,\,\mu+ \sigma)^{\mathsf{c}}]\leq 1$ }

Def.
- $X_{n}\to\alpha$ in $k$th mean:   $\lim\limits_{n\to\infty} \text{E}(|X_{n}-\alpha|^{k})=0$   { unbiased estimator }
	
- $X_{n}\to\alpha$ in prob.:  
	- $\forall\,r>0$:  $\lim\limits_{n\to\infty} P_{X_{n}}(|x_{n}-\alpha|\geq r)=0$   { consistent estimator }
- $X_{n}\to\alpha$ almost surely:
	- $\forall\,r >0$:  $\exists$ subseq. $X_{n_{k}}$ s.t. $\lim\limits_{k\to\infty} P_{X_{n_{k}}}(|x_{n_{k}}-\alpha|\geq r)=0$
	
- $X_{n}\to X$ in dist.:
	- $\lim\limits_{n\to\infty}F_{X_{n}}(x)=F_{X}(x)$  $\forall$ continuous point $x$ of $F_{X}$  { Def }
		- OR
	- $\lim\limits_{n\to\infty}M_{X_{n}}(t)=M_{X}(t)$  $\forall\,t\in$ open interval containing $0$  { Thm. $\impliedby$ } {Pf?? @1}


\[ Main ]

Def.
- sample mean:      $\overline{X}_{n}\coloneqq \dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i}$   
- sample variance:  $S_{{n}}{}^{2}\coloneqq\dfrac{1}{n-1}\sum\limits_{i=1}^{n}(X_{i}-\overline{X}_{n})^{2}$

Thm. Law of Large Number (Weak)
- $X_{i}$ i.i.d. with  $\text{E}(X_{i})=\mu$, $\text{Var}(X_{i})=\sigma^{2}$ $\,\,\forall\,i \in \mathbb{N}$
- $\implies$ 
	- $\hat{\mu}\coloneqq\overline{X}_{n}\to\mu$ in prob.
	- $\hat{\mu}_{k}\coloneqq[\dfrac{1}{n}\sum\limits_{i=1}^{n}(X_{i})^{k}]\to \mu_{k}$ in prob.  {cor.}
	- $\hat{\sigma}^{2}\coloneqq[\dfrac{1}{n}\sum\limits_{i=1}^{n}(X_{i}-\overline{X}_{n})^{2}]\to\sigma^{2}$ in prob.  {cor.}  {Pf?? @2}

Rmk. Generalized LLN
- (1) $X_{i}$ pairwise uncorrelated  { i.e. $\text{Cov}(X_{i},\,X_{j})=0$  $\forall\,i \neq j$ }  { has Pf.}
- (2) $\text{Var}(X_{i})=\sigma \neq \infty$

Cor. Monte Carlo method on integral estimation: 
- $X_{i}\,$ i.i.d. $\sim\text{uniform}(0,\,1)$
- $g$  with
	- $I(g)={\displaystyle\int}_{0}^{1}[g \circ f_{X_{i}}](x)dx\eqqcolon\text{E}(g(X_{i}))$ $\,\,\forall\,i \in \mathbb{N}$
	- $\hat{I}_{n}(g)\coloneqq\dfrac{1}{n}\sum\limits_{i=1}^{n}g(X_{i})$
- $\implies$ 
	- $\hat{I}_{n}(g)\to I(g)$ in prob.  { discrete $\overset{\text{simulate}}{\to}$ continuous }


Thm. Central Limit Theorem  {Strict}
- $X_{i}$ i.i.d. with  $\text{E}(X_{i})=\mu$, $\text{Var}(X_{i})=\sigma^{2}$ $\,\,\forall\,i \in \mathbb{N}$
- $\implies$ 
	- $\text{std}(\overline{X}_{n})=\sqrt{ n }\left(\dfrac{\overline{X}_{n}-\mu}{{\sigma}}\right)\to Z_{\Phi}$ in dist.   { $\mu_{\overline{X}_{n}}=\mu$, ${\sigma_{\overline{X}_{n}}}^{2}=\dfrac{\sigma^{2}}{n}$ }


\[ Sub ]




Rmk.
- $X_{n}\to\alpha$ in prob.  $\land$  $Y_{n}\to \beta$ in prob. $\implies$ $cX_{n}+dY_{n}\to c\,\alpha+d\,\beta$ in prob.
- $X_{n}\to\alpha$ in prob.  $\land$  $g$ continuous at $\alpha$ $\implies$ $g(X_{n})\to g(\alpha)$ in prob.  {Pf?? @3}

===

Ex.
- $X_{n}\sim\text{Poison}(\lambda_{n})$  where  $\lim\limits_{n\to\infty}\lambda_{n}=\infty$
- $\implies$ 
	- $\text{std}(X_{n})=(\dfrac{X_{n}-\lambda_{n}}{\sqrt{ \lambda_{n} }})\to Z_{\Phi}$ in dist.

Cor.
- $X_{i}$ i.i.d. with  $\text{E}(\ln X_{i})=\mu$, $\text{Var}(\ln X_{i})=\sigma^{2}$ $\,\,\forall\,i \in \mathbb{N}$
- $\implies$ 
	- $\text{std}[\,\ln \left( \prod\limits_{i=1}^{n}X_{i} \right)^{\frac{1}{n}}]=\text{std}[\dfrac{1}{n}\sum\limits_{i=1}^{n}\ln X_{i}]\to Z_{\Phi}$  in dist.

Prop.
- $(n-1)\dfrac{S_{n}{}^{2}}{\sigma^{2}}=\dfrac{1}{(n-1){\sigma}^{2}}[\sum\limits_{i=1}^{n}{(X_{i}-\overline{X}_{n})^{2}}]^{2}\sim \chi^{2}\text{-dist}(n-1)$

Prop.
- $\sqrt{ n }\,\left( \dfrac{\overline{X}_{n}-\mu}{S_{n}} \right)\sim\text{t-dist}(n-1)$



\[ Sample ]

Thm.
- $\overline{X}_{n}$, $(X_{i}-\overline{X}_{1})$, $\cdots$, $(X_{i}-\overline{X}_{n})$  are indep.  {Pf??}

Cor.
- (1) $\overline{X}_{n}$ ${\perp\!\!\!\perp}$ $S^{2}{}_{\!{n}}$  (2) $\hat{\mu}$ ${\perp\!\!\!\perp}$ $\hat{\sigma}$



===

Pf. Generalized LLN
- $X_{i}$ pairwise uncorrelated { i.e. $\text{Cov}(X_{i},\,X_{j})=0$ $\forall\,i\neq j$ }
- $\implies$ 
	- $\text{Var}(\overline{X}_{n})=\dfrac{1}{n^{2}}\text{Var}(\sum\limits_{i=1}^{n}X_{i})$
	- $=\dfrac{1}{n^{2}}\text{E}([\sum\limits_{i=1}^{n}X_{i}-\mu]^{2})$
	- $=\dfrac{1}{n^{2}}\text{E}([\sum\limits_{i=1}^{n}X_{i}-\mu][\sum\limits_{j=1}^{n}X_{j}-\mu])$
	- $=\dfrac{1}{n^{2}}\text{E}(\sum\limits_{i=1}^{n}\sum\limits_{j=1}^{n}[X_{i}-\mu][X_{j}-\mu])$
	- $=\dfrac{1}{n^{2}}\sum\limits_{i=1}^{n}\sum\limits_{j=1}^{n}\text{E}([X_{i}-\mu][X_{j}-\mu])$
	- $=\dfrac{1}{n^{2}}\sum\limits_{i=1}^{n}\text{E}([X_{i}-\mu]^{2})$
		- since  $\text{E}([X_{i}-\mu][X_{j}-\mu])=\text{Cov}(X_{i},\,X_{j})$
	- $=\dfrac{\sigma^{2}}{n}$

Pf.
Let $U\coloneqq|X|$, $\forall\,r>0$:

$\text{E}(U)={\displaystyle\int}_{0}^{\infty}uf_{U}(u)du\geq{\displaystyle\int}_{r}^{\infty}rf_{U}(u)du=r\cdot\text{P}_{U}(u\geq r)$ $\implies$ $\dfrac{\text{E}(|X|)}{r}\geq P_{X}(|x|\geq r)$

Pf.
$P_{X}[(\mu-k\sigma,\,\mu+k \sigma)^{\mathsf{c}}]=P_{X}(\{x \;|\;(x-\mu)^{2}< k^{2 }\sigma^{2}\}^{\mathsf{c}})$
$=P_{(X^{2}-\mu)}[(-k^{2 }\sigma^{2},\,k^{2 }\sigma^{2})^{\mathsf{c}}]\leq\dfrac{\text{E}((X-\mu)^{2})}{k^{2}\sigma^{2}}=\dfrac{1}{k^{2}}$

Pf.
$P_{\overline{X}_{n}}[(\mu-r,\,\mu+r)^{\mathsf{c}}]\leq\dfrac{\text{Var}(\overline{X}_{n})^{2}}{r^{2}}=\dfrac{\sigma^{2}}{nr^{2}}\to 0$  as  $n\to \infty$

Pf.
$\dfrac{1}{n}\sum\limits_{i=1}^{n}(X_{i}-\overline{X}_{n})^{2}=[\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i}^{2}]-2\overline{X}\cdot[\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i}]+\overline{X}^{2}\cdot[\dfrac{1}{n}\sum\limits_{i=1}^{n}1]$
$=\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i}^{2}-2\overline{X}^{2}+\overline{X}^{2}=\dfrac{1}{n}\sum\limits_{i=1}^{n}X_{i}^{2}-\overline{X}^{2}$
$\to \mu_{2}-\mu_{1}{}^{2}=\sigma^{2}$  in prob.

===


Pf.
$M_{X_{n}}(t)=e^{\lambda_{n}(e^{t}-1)}$
$\implies$ $M_{Z_{n}}(t)=e^{-\sqrt{ \lambda_{n} }t}\cdot M_{X_{n}}(\dfrac{t}{\sqrt{ \lambda_{n} }})$  { let $Z_{n}\coloneqq\dfrac{X_{n}-\lambda_{n}}{\sqrt{ \lambda_{n} }}$ }
$\implies$ $M_{Z_{n}}(t)=e^{-\sqrt{ \lambda_{n} }t}\cdot e^{\lambda_{n}(e^{\frac{t}{\sqrt{ \lambda_{n} }}}-1)}$
$\implies$ $\ln(M_{Z_{n}}(t))=-\sqrt{ \lambda_{n} }t+\lambda_{n}(e^{\frac{t}{\sqrt{ \lambda_{n} }}}-1)$  { use $e^{x}=\sum\limits_{k=0}^{\infty}\dfrac{x^{k}}{k!}$ }
$\implies$ $\ln(M_{Z_{n}}(t))=-\lambda_{n}(\dfrac{t}{\sqrt{ \lambda_{n} }})^{1}-\lambda_{n}(\dfrac{t}{\sqrt{ \lambda_{n} }})^{0}+\lambda_{n}\sum\limits_{k=0}^{\infty}\dfrac{1}{k!}(\dfrac{t}{\sqrt{ \lambda_{n} }})^{k}=\sum\limits_{k=2}^{\infty}\dfrac{t^{k}}{k!}(\dfrac{1}{\sqrt{ \lambda_{n} }})^{k-2}$
$\implies$ 
$\lim\limits_{n\to\infty}\ln(M_{Z_{n}}(t))=\dfrac{t^{2}}{2}+\lim\limits_{n\to\infty}\sum\limits_{k=3}^{\infty}\dfrac{t^{k}}{k!}(\dfrac{1}{\sqrt{ \lambda_{n} }})^{k-2}=\dfrac{t^{2}}{2}$
$\lim\limits_{n\to\infty}M_{Z_{n}}(t)=e^{\frac{t^{2}}{2}}=M_{\Phi}(t)$


Pf.
let $Y_{i}\coloneqq X_{i}-\mu$ $\implies$ $Z_{n}=\sum\limits_{i=1}^{n}\dfrac{Y_{i}}{\sigma \sqrt{ n }}$

{ use taylor expansion }
$M_{Y_{i}}(t)=M_{Y_{i}}(0)+{M_{Y_{i}}}'(0)\,t+\dfrac{1}{2}{M_{Y_{i}}}''(0)\,t^{2}+\varepsilon_{t}$  { $\varepsilon_{t}$ "[[Asymptotic - Big O, Small O|negl to]]" $\,t^{2}$ as $t\to0$ }
$=1+{\mu_{Y_{i}}}_{(1)} t+\dfrac{1}{2}{\mu_{Y_{i}}}_{(2)}t^{2}+\varepsilon_{t}$
$=1+\dfrac{1}{2}\sigma^{2}t^{2}+\varepsilon_{t}$

$\lim\limits_{n\to\infty}M_{Z_{n}}(t)=\lim\limits_{n\to\infty}M_{Y_{i}}(\dfrac{t}{\sigma \sqrt{ n }})^{n}$
$=\lim\limits_{n\to\infty}(1+\dfrac{t^{2}}{2n}+\varepsilon_{n})^{n}$  { $\varepsilon_{n}$ negl to $(\dfrac{t}{\sigma \sqrt{ n }})^{2}$ as $n \to \infty$ }
$=e^{\frac{t^{2}}{2}}\,$                { $e^{x}=\lim\limits_{n\to\infty}(1+\dfrac{x}{n})^{n}$ }
$=M_{\Phi}(t)$


Pf.