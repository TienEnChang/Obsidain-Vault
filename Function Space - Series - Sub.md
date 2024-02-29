
Ex. $f(x)\coloneqq\sum\limits_{n=0}^{\infty}(\dfrac{x^{n}}{n!})^{2}$  is continuous on $\mathbb{R}$
Sol.

$\because$  $\forall\,x_{0}\in\mathbb{R}$:  let $M\coloneqq|x_{0}|+1$ $\implies$ $x_{0}\in [-M,\,M]$

   let $y_{n}(x)\coloneqq(\dfrac{x^{n}}{n!})^{2}$  $\forall\,x \in \text{dom}(y_{n})\coloneqq[-M,\,M]$

   (1) $\forall\,n \in \mathbb{N}$:  $M_{n}\coloneqq(\dfrac{M^{n}}{n!})^{2}\geq \sup\,\{\,(\dfrac{|x|^{n}}{n!})^{2}\;|\;x \in[-M,\,M]\,\}=||y_{n}||_{\sup\,}$
  
   .            $\implies$ $(y_{n})_{n \in\mathbb{N}}$ in $\mathcal{C}_{b}([-M,\,M])$

   (2) By Ratio Test, $\lim\limits_{n\to \infty}\dfrac{M_{n+1}}{M_{n}}=\lim\limits_{n\to \infty}\dfrac{M^{2}}{(n+1)^{2}}=0$ $\implies$  $\sum\limits_{n=1}^{\infty}M_{n}$ converges

$\therefore$  By Weierstrass M-test,  $\sum\limits_{n=1}^{\infty}y_{n}$ converges uniformly
    i.e. $\sum\limits_{k=0}^{n}(\dfrac{x^{k}}{k!})^{2}\to\sum\limits_{n=0}^{\infty}(\dfrac{x^{n}}{n!})^{2}\,$ uniformly on $[-M,\,M]$

$\because$  $\sum\limits_{k=0}^{n}(\dfrac{x^{k}}{k!})^{2}$ polynomial $\implies$ continuous on $\mathbb{R}\supseteq[-M,\,M]$

$\therefore$  By Thm. $\sum\limits_{n=0}^{\infty}(\dfrac{x^{n}}{n!})^{2}\,$ continuous on $[-M,\,M]\ni x_{0}$  $\forall\,x_{0}\in \mathbb{R}$
                   $\implies$ continuous on $\mathbb{R}$



Ex. $\sum\limits_{n=1}^{\infty}\dfrac{\sin^{2}(nx)}{n^{2}}$ converges uniformly on $\mathbb{R}$ 

Sol.
$\because$  (1) $\forall\,n \in \mathbb{N}$:  $||\dfrac{\sin^{2}(nx)}{n^{2}}||_{\sup\,}\leq\dfrac{1}{n^{2}}$  (2) $\sum\limits_{n=1}^{\infty}\dfrac{1}{n^{2}}$ converges 

$\therefore$  By Weierstrass M-test, $\sum\limits_{n=1}^{\infty}\dfrac{\sin^{2}(nx)}{n^{2}}$ converges uniformly on $\mathbb{R}$ 



Ex. $\sum\limits_{n=1}^{\infty}\dfrac{e^{-\frac{x^{2}}{n}}}{n}$  converges uniformly at $x_{0}\in\mathbb{R}$ ?  No.
Sol.
$\because$  $\forall\,x\in\mathbb{R}$:  $\forall\,n\geq\lceil x{}^{2} \rceil$:  $-\dfrac{x^{2}}{n}>-1$ $\implies$ $0\leq\dfrac{e^{-1}}{n}\leq\dfrac{e^{-\frac{x^{2}}{n}}}{n}$

$\therefore$  By Comparison Test,  $\sum\limits_{n=1}^{\infty}\dfrac{e^{-1}}{n}$  diverges $\implies$ $\sum\limits_{n=1}^{\infty}\dfrac{e^{-\frac{x^{2}}{n}}}{n}$  diverges  $\forall\,x\in\mathbb{R}$

