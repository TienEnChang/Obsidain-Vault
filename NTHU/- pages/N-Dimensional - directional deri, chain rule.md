
Let
- $f:U\subset\mathbb{R}^n\to\mathbb{R}$
- $\gamma:(a,\,b)\to U$
- where  $U$  is open


Def.  directional derivative
- $\displaystyle {f_{\mathbb{V}}}'(\mathbb{X_0})\coloneqq\lim_{h\to0}\dfrac{f(\mathbb{X_0}+h\mathbb{V})-f(\mathbb{X_0})}{h}$
- where  $\mathbb{V}$  is a unit vector

Thm.
- differentiable  $\implies$  continuous

Thm.
- $f$  is differentiable at  $\mathbb{X_0}$
- $\implies$
	- $\forall\,\mathbb{V}:\;\displaystyle f_{\mathbb{V}}\\'(\mathbb{X_0})=\nabla f(\mathbb{X_0})\cdot\mathbb{V}$
	- where  $\mathbb{V}$  is a unit vector

Thm. chain rule
- $f,\,\gamma$  are differentiable
- $\implies$
	- $\dfrac{d}{dt}(f\circ\gamma)(t)=\nabla f(\gamma(t))\cdot\gamma'(t)$