..

Pf. ^c2e716
Case "$X$ empty":    $\mathcal{C}_{b}(X)=\{\tilde{\varnothing}\}$  clearly complete
Case "$X$ nonempty"
$\because$  $f_{n}\to f$  uniformly
   $\implies$ $\exists\,N\in\mathbb{N}$  s.t. $\forall\,x \in X$:  $|f_{N}(x)-f(x)|<1$
   $\implies$ $\forall\,x \in X$:  $|f(x)|\leq|f(x)-f_{N}(x)|+|f_{N}(x)|<1+||f_{N}||_{\sup\,}$ { $f_{N}\in\mathcal{C}_{b}(X)$ }

$\therefore$  $||f||_{\sup\,}$ exists $\implies$ $f \in\mathcal{C}_{b}(X)$


Pf. ^4d2875
- $(f_{n})_{n \in \mathbb{N}}$ converges uniformly
    { i.e.  $\forall\,\varepsilon>0$  $\exists\,N_{\varepsilon}\in\mathbb{N}$  s.t.  $\forall\,n\geq N_{\varepsilon}$  $\forall\, x\in X$:  $|f_n(x)-f(x)|<\dfrac{\varepsilon}{2}$ }
- $\implies$ $\forall\,x \in X$:  $\forall\,\varepsilon>0$  $\exists\,N_{x,\,\varepsilon}\equiv N_{\varepsilon}$  s.t.  $\forall\,n\geq N_{x,\,\varepsilon}$:  $|f_n(x)-f(x)|<\dfrac{\varepsilon}{2}$
        { i.e. $(f_{n})_{n \in \mathbb{N}}$ converges pointwise }


Pf. ^899846
For "$\implies$":

$(f_{n})_{n \in \mathbb{N}}$ converges uniformly
{ i.e.  $\forall\,\varepsilon>0$  $\exists\,N\in\mathbb{N}$  s.t.  $\forall\,n\geq N$  $\forall\, x\in X$:  $|f_n(x)-f(x)|<\dfrac{\varepsilon}{2}$ }

$\implies$ $\forall\,n,\,m\geq N$  $\forall\, x\in X$:  $|f_n(x)-f_{m}(x)|\leq|f_n(x)-f(x)|+|f_m(x)-f(x)|<\varepsilon$
     { i.e. $(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy }

For "$\impliedby$":

$(f_{n})_{n \in \mathbb{N}}$ uniformly Cauchy

$\implies$ (1)  $\forall\,\varepsilon>0$  $\exists\,N_{\varepsilon}\in\mathbb{N}$  s.t. $\forall\,n,\,m\geq N_{\varepsilon}$  $\forall\, x\in X$:  $|f_n(x)-f_{m}(x)|<\dfrac{\varepsilon}{2}$
.    (2) $(f_{n})_{n \in \mathbb{N}}$ pointwise Cauchy $\implies$ converges pointwise 
                                   { let $f(x)\coloneqq\lim\limits_{n\to\infty}f_{n}(x)$ $\,\forall\,x$ }

$\implies$ $\forall\,x \in X$:  $\forall\,\varepsilon>0$
     $\exists\,N_{x,\,\varepsilon}\in\mathbb{N}$  $\exists\,m_{x}\geq \max\,\{N_{x,\,\varepsilon},\,N_{\varepsilon}\}$  s.t.  $|f_{m_{x}}(x)-f(x)|<\dfrac{\varepsilon}{2}$

$\implies$ $\forall\,n\geq N_{\varepsilon}$  $\forall\,x \in X$:  $|f_n(x)-f(x)|\leq|f_n(x)-f_{m_{x}}(x)|+|f_{m_{x}}(x)-f(x)|<\varepsilon$
     { i.e. $(f_{n})_{n \in \mathbb{N}}$ converges uniformly }