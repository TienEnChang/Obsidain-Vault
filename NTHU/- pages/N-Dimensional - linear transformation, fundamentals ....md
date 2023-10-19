
Def.
- linear transformation
	- $T:\mathbb{R}^2\to\mathbb{R}^2$ defined as $T(\begin{bmatrix}u\\v\end{bmatrix})=\begin{bmatrix}a&b\\c&d\end{bmatrix}\begin{bmatrix}u\\v\end{bmatrix}$
Cor.
- $R=[\,u_1,\,u_2\,]\times[\,v_1,\,v_2\,]$
- $\implies$
	- $T(R)$ is a parallelogram {平行四邊形}
	- area of $T(R)=|\det(T)|\cdot($area of $R)$

Cor.
- $T(u,\,v)-T(u_0,\,v_0)\approx J(T)\begin{bmatrix}u-u_0\\v-v_0\end{bmatrix}$

---

Fundamental Theorem
- of Arithmetic:    $n={p_1}^{a_1}\,{p_2}^{a_2}...\,{p_k}^{a_k}$
- of Algebra:       $P(x)=(x-c_1)(x-c_2)...(x-c_n)$
- of Calculus I:    $\displaystyle\int_a^b f(x)dx=F(b)-F(a)$

---

Thm.
- if $k$ is odd
- (1) $\displaystyle\int_0^{2\pi}\sin^{k}({\theta})d\theta=0$
- (2) $\displaystyle\int_0^{2\pi}\cos^{k}({\theta})d\theta=0$

Pf. (1)
- $\displaystyle\int_0^{2\pi}\sin^{k}({\theta})d\theta$                          { let $t=\theta-\pi$ }
- $=\displaystyle\int_{-\pi}^{\pi}\sin^{k}({t+\pi})dt=\displaystyle\int_{-\pi}^{\pi}-\sin^{k}({t})dt=0$  { $\because\sin^{k}({\theta})$ is odd }

Pf. (2)
- use reduction formula of $\displaystyle\int \cos^n (x) \, dx$