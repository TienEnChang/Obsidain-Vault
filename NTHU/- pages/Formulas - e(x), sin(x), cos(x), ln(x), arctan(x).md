
Formulas.

|           | condensed                                                            | expanded                                | condition | 
| --------- | -------------------------------------------------------------------- | --------------------------------------- | --------- |
| $e^x$     | $=\displaystyle\sum_{k=0}^{\infty}\dfrac{x^k}{k!}$                   | $=1+\dfrac{x}{1!}+\dfrac{x^2}{2!}...$   |           |
| $\sin(x)$ | $=\displaystyle\sum_{k=0}^{\infty}(-1)^k\dfrac{x^{(2k+1)}}{(2k+1)!}$ | $=x-\dfrac{x^3}{3!}+\dfrac{x^5}{5!}...$ |           |
| $\cos(x)$ | $=\displaystyle\sum_{k=0}^{\infty}(-1)^k\dfrac{x^{(2k)}}{(2k)!}$     | $=1-\dfrac{x^2}{2!}+\dfrac{x^4}{4!}...$ |           |

|              | condensed                                                     | expanded    | condition          |
| ------------ | ------------------------------------------------------------- | --- | ------------------ |
| $\ln(1-x)$   | $=-\displaystyle\sum_{k=0}^\infty\dfrac{x^{k+1}}{k+1}$        |     | for \|$x$\|$<1$    |
| $\arctan(x)$ | $=\displaystyle\sum_{k=0}^\infty\dfrac{(-1)^k}{2k+1}x^{2k+1}$ |     | for \|$x$\|$\leq1$ |

|              | condensed                                                      | expanded        | condition    |
| ------------ | ------------------------------------------------------------ | --------------- | --- |
| $\sqrt{1+x}$ | $=\displaystyle\sum_{k=0}^\infty\binom{\frac12}{k}\,x^{k}$ | $=1+\dfrac12x-\dfrac18x^2...$ | for \|$x$\|$<1$    | 


Technique.
- Taylor series of $\ln$ centered at $a$:
	- $\ln(x)=\ln(a)+\ln(1-(1-\dfrac{x}{a}))$

