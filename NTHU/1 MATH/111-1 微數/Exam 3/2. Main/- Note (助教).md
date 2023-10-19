Fourier transformation
$f(x)=a_0+a_1\,cos(x)+...\,+a_k\,cos(kx)+b_1$
- $a_0=\dfrac1{2\pi}\displaystyle\int_0^{2\pi}f(x)dx$
- $a_k=\dfrac1{\pi}\displaystyle\int_0^{2\pi}f(x)cos(kx)dx$
- $b_k=\dfrac1{\pi}\displaystyle\int_0^{2\pi}f(x)sin(kx)dx$   彼此間線性獨立
(#)
- $\displaystyle\int_0^{2\pi}cos(nx)dx=0$ , $\displaystyle\int_0^{2\pi}cos^2(nx)dx=\pi$ 
- $\displaystyle\int_0^{2\pi}sin(nx)dx=0$ , $\displaystyle\int_0^{2\pi}sin^2(nx)dx=\pi$

常見積分
(1) $\displaystyle\int sin^m(x)cos^n(x)dx$
case $m=2k+1$:    let $u = cos(x),\; du=-sin(x)dx$
case $m,\;n$ are even: 
	$sin(x)cos(x)=sin(2x)$
	$sin^2(x)=\dfrac{1-cos(2x)}{2}$
	$cos^2(x)=\dfrac{1+cos(2x)}{2}$

(2) $\displaystyle\int tan^m(x)sec^n(x)dx$
case $m,\,n$ are odd:
	$\displaystyle\int tan^{2k+1}(x)sec^{2k+1}(x)dx$
	= $\displaystyle\int (sec^2(x)-1)^ksec^{2k}(x)\cdot tan(x)sec(x)dx$
	  let $u = sec(x),\;du=tan(x)sec(x)dx$
	= $\displaystyle\int (u^2-1)^ku^{2k}du$
case $m$ is even:
	$\displaystyle\int tan^{2k}(x)sec^n(x)dx$
	= $\displaystyle\int (sec^2(x)-1)^{k}sec^n(x)dx$ = $\displaystyle\sum_{N}\int sec^N(x)dx$

(3) let $u=\sqrt{x},\;2udu=dx$

