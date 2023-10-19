$\exists\,f$ s.t. $\exists\,f^{-1}$ $\land$ $f$ is continuous
$\implies$ $f^{-1}$ is continuous
{
Let $y_0\in(c,\,d)$ $x_0\in(a,\,b)$ s.t. $f(x_0)=y_0$
By Thm. $f$ is 1-1 $\land$ cont. $\implies$ $f$ is increasing $\lor$ decreasing

$\forall \varepsilon>0$ $\exists\,\varepsilon'=\dfrac12\;min\{x-a,\,b-x,\,\varepsilon\}$
case "increasing":
	$f(x_0-\varepsilon')<f(x_0)<f(x_0+\varepsilon')$
	$\exists$
}

Thm.
(#) $\exists\,f$ s.t. $\exists\,f^{-1}$ $\land$ $f$ is differentiable
	$\implies$
	(1) $f^{-1}$ is differentiable
	(2) $\forall x$ with $f'(x_0)\neq0$, $\exists\,y_0$ s.t. ${f^{-1}}'(y_0)=\dfrac1{f'(x_0)}$
{
$\forall \varepsilon>0$ $\exists\,\delta>0$ s.t. $0<|x-x_0|<\delta$ $\implies$ $|\dfrac{x-x_0}{f(x)-f(x_0)}-\dfrac1{f'(x_0)} |<\varepsilon$
$\implies$ $|\dfrac{f^{-1}(y)-f^{-1}(y_0)}{y-y_0}-\dfrac1{f'(x_0)} |<\varepsilon$
}