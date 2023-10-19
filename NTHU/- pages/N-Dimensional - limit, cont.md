
Def.  limit
- $\displaystyle\lim_{\mathbb{X\to X_0}}f(\mathbb{X})=L$
- $\iff$
	- $\forall\,\varepsilon>0,\;\exists\,\delta>0$  s.t. 
	   $0<||\mathbb{X-X_0}||<\delta\implies|f(\mathbb{X})-L|<\varepsilon$

Def. continuity
- $\displaystyle\lim_{\mathbb{X\to X_0}}f(\mathbb{X})=\mathbb{X_0}$

Thm. arithmetics

---

Let
- $f:B_r(\mathbb{X_0})^*\to\mathbb{R}$
- $\gamma:(a,\,b)\to B_r(\mathbb{X_0})^*$
	- is continuous
	- passes through $\mathbb{X_0}$

Thm.
- $\displaystyle\lim_{\mathbb{X\to X_0}}f(\mathbb{X})=L\implies\forall\gamma:\;\displaystyle\lim_{\mathbb{t\to t_0}}(f\circ\gamma)(t)=L$

Cor. non-existence of limit
- $\exists\,\gamma_1,\,\gamma_2$  s.t.
	(1) $\displaystyle\lim_{\mathbb{t\to t_0}}(f\circ\gamma_1)(t)$  D.N.E.
	(2) $\displaystyle\lim_{\mathbb{t\to t_0}}(f\circ\gamma_1)(t)\neq\displaystyle\lim_{\mathbb{t\to t_0}}(f\circ\gamma_2)(t)$
- $\implies$
		- $\displaystyle\lim_{\mathbb{X\to X_0}}f(\mathbb{X})$  D.N.E.

Cor.
- $\neg$ continuous  $\implies$  $\neg$ differentiable