..

Pf. ^ebd5be
$\because$  (1)
   $(f_{n})_{n \in \mathbb{N}}$ in $\mathcal{C}_{b}(X)$
   $\implies$ $\exists$ $||f_{n}||_{\text{sup}}$  $\forall\,{n \in \mathbb{N}}$
   $\implies$ $\exists$ $[\sum\limits_{k=1}^{n}||f_{k}||_{\text{sup}}]\geq ||\sum\limits_{k=1}^{n}f_{k}||_{\text{sup}}$  $\forall\,n \in\mathbb{N}$ $\implies$ $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}$ in $\mathcal{C}_{b}(X)$
   (2)
   $\;\sum\limits_{n=1}^{\infty}M_{n}$ converges
   $\implies$ $(\sum\limits_{k=1}^{n}M_{k})_{n \in\mathbb{N}}$ Cauchy
   $\implies$ $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$  s.t. $\forall\,n>m\geq N$:  $|\sum\limits_{k=1}^{n}M_{k}-\sum\limits_{k=1}^{m}M_{k}|=\sum\limits_{k=m+1}^{n}M_{k}<\varepsilon$
   $\implies$ $\forall\,n>m\geq N$:  $||\sum\limits_{k=1}^{n}f_{k}-\sum\limits_{k=1}^{m}f_{k}||_{\text{sup}}\leq\sum\limits_{k=m+1}^{n}||f_{k}||_{\text{sup}}\leq\sum\limits_{k=m+1}^{n}M_{k}<\varepsilon$
   $\implies$ $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}$ Cauchy under $d_{\sup\,}$
   (3)
   $\mathcal{C}_{b}(X)$ complete metric space

$\therefore$  $( \sum\limits_{k=1}^{n}f_{k} )_{n \in \mathbb{N}}$ converges under $d_{\text{sup}}$ $\implies$ converges uniformly

$\because$  $\forall\,n \in \mathbb{N}$:  $||\,|f_{n}|\,||_{\text{sup}}=||f_{n}||_{\text{sup}}\leq M_{n}$

$\therefore$  Similarly, $\sum\limits_{n=1}^{\infty}|f_{n}|$  converges uniformly $\implies$ pointwise
   i.e.  $\sum\limits_{n=1}^{\infty}f_{n}$ converges absolutely