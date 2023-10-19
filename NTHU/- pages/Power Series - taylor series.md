
Def.
- Taylor series of $f$ centered at $a$:  $\displaystyle\sum_{k=0}^{\infty}\dfrac{f^{(k)}(a)}{k!}(x-a)^k$

Thm. Taylor's theorem
1. $f$ is (n+1)-th differentiable:
- $\implies$
	- $f(x)=P_n(x)+R_n(x)$
2. $f$ is $\infty$ differentiable $\land$ $\displaystyle\lim_{n\to\infty}R_n(x)=0$
- $\implies$
	- $f(x)=\displaystyle\sum_{k=0}^{\infty}\dfrac{f^{(k)}(a)}{k!}(x-a)^k$

---

Thm.
- $\displaystyle\sum_{k=0}^\infty a_k\,(x-a)^k$ converges
- $\implies$
	- $\displaystyle{S_{\rm pow}}_\infty(x)=$ $\displaystyle\sum_{k=0}^{\infty}\dfrac{{S_{\rm pow}}_\infty\\^{(k)}(a)}{k!}(x-a)^k$ ,  $\dfrac{{S_{\rm pow}}_\infty\\^{(k)}(a)}{k!}=a_k$

Thm.
|           | condensed                                                                | expanded                                |
| --------- | -------------------------------------------------------------------- | --------------------------------------- |
| $e^x$     | $=\displaystyle\sum_{k=0}^{\infty}\dfrac{x^k}{k!}$                   | $=1+\dfrac{x}{1!}+\dfrac{x^2}{2!}...$   |
| $\sin(x)$ | $=\displaystyle\sum_{k=0}^{\infty}(-1)^k\dfrac{x^{(2k+1)}}{(2k+1)!}$ | $=x-\dfrac{x^3}{3!}+\dfrac{x^5}{5!}...$ |
| $\cos(x)$ | $=\displaystyle\sum_{k=0}^{\infty}(-1)^k\dfrac{x^{(2k)}}{(2k)!}$     | $=1-\dfrac{x^2}{2!}+\dfrac{x^4}{4!}...$ |
