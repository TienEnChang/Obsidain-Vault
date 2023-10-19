
Def.  gradient
- $\nabla f(\mathbb{X_0})\coloneqq(\displaystyle\dfrac{\partial f}{\partial x_1}(\mathbb{X_0}),\,...\,,\,\displaystyle\dfrac{\partial f}{\partial x_n}(\mathbb{X_0}))$

Def.  partial derivative
- $\displaystyle\dfrac{\partial f}{\partial x_i}(\mathbb{X_0})\coloneqq\lim_{h\to0}\dfrac{f(...\,,\,a_{i}+h,\,...)-f(\mathbb{X_0})}{h}$

Def.  multi-derivative
- $f_{xy}=(f_x)_y$
- $\dfrac{\partial^2 f}{\partial y\partial x}=\dfrac{\partial}{\partial y}(\dfrac{\partial f}{\partial x})$

---

Def.  differentiable
- $\displaystyle\lim_{\mathbb{X\to X_0}}\dfrac{|f(\mathbb{X})-f(\mathbb{X_0})-\nabla f(\mathbb{X_0})\cdot(\mathbb{X-X_0})|}{||\mathbb{X-X_0}||}=0$
- $\iff\displaystyle\lim_{\mathbb{X\to X_0}}\dfrac{f(\mathbb{X})-f(\mathbb{X_0})}{||\mathbb{X-X_0}||}=\lim_{\mathbb{X\to X_0}}\dfrac{\nabla f(\mathbb{X_0})\cdot(\mathbb{X-X_0})}{||\mathbb{X-X_0}||}$

Thm.
- $\forall\;\dfrac{\partial f}{\partial x_i}$  are continuous on a neighborhood of $\mathbb{X_0}$
- $\implies$
	- $f$  is differentiable at $\mathbb{X_0}$

Thm.
- $f_{xy},\;f_{yx}$  are continuous on a neighborhood of $(a,\,b)$
- $\implies$
	- $f_{xy}(a,\,b)=f_{yx}(a,\,b)$

