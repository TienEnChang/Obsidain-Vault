
Def.
- trial:  $\Omega_0$, $P_0$, $\omega_0$
- experiment:  $\Omega\coloneqq{\Omega_0}^n$, $\omega\coloneqq((\omega_1)_{(0)},\,\cdots,\,(\omega_n)_{(0)})$  

Def. event that occurs on i-th trial
- $E_0(i)\coloneqq{\Omega_0}^{i-1}\times E_0\times {\Omega_0}^{n-i}\in \mathcal{F}_\Omega$  where  $E_0\in \mathcal{F}_{\Omega_0}$
- $\implies$ $P(E_0(i))=P_0(E_0)$

Axiom. trial independence assumption
- $\forall\,i\neq j$:  $P(A_0(i)\cap B_0(j))=P_0(A_0)P_0(B_0)$  where  $A_0,\,B_0\in \mathcal{F}_{\Omega_0}$

---

Def. 
- indicator function:  $1_{E_{0}}(\omega_{0})\coloneqq\begin{cases}1&\text{if}\;\omega_{0}\in E_{0}\\0&\text{o.w.}\end{cases}$

Def.
- Occurrence Indicator Set 事件發生指示集 ($\Omega^*$)
	- $X^*\coloneqq(1_{E_0(1)},\,\cdots,\,1_{E_0(n)})$
	- $\mathcal{X}^*={\rm rng}(1_{E_0(i)})^n=\{0,\,1\}^n$
		
	- $\Omega^*\coloneqq\mathcal{X}^*$
	- $\omega^*\coloneqq((\omega^*)_1,\,\cdots,\,(\omega^*)_n)$ in $\{0,\,1\}$
- $\implies$
	- for $n=\infty$:
	       $\,|\Omega^*|=|\{\,f:\{1,\,\cdots,\,n\}\to\{0,\,1\}\}|=|2^\mathbb{N}|$  is uncountable