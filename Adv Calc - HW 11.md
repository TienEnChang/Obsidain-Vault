
1.
(a)
$\because$  $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$  with  $\dfrac{1}{N}<\varepsilon$
	   s.t.  $\forall\,k\geq N$:  $||f_{k}-\tilde{0}||_{\sup\,}=\sup\limits_{x \in\mathbb{R}}\,|\dfrac{\sin(x)}{k}|=\dfrac{1}{k}\leq\dfrac{1}{N}<\varepsilon$
	   where  $\tilde{0}$  is the zero function
	   
$\therefore$  $f_{k}\to \tilde{0}$  under $d_{\sup\,}$
	 $\implies$ uniformly on $\mathbb{R}$  (by Thm.)
	 $\implies$ pointwise on $\mathbb{R}$

(b)
$\because$  $f_{k}{}'(x)=\dfrac{1\cdot(1+kx^{2})-x\cdot 2kx}{(2kx)^{2}}=\dfrac{1-kx^{2}}{4k^{2}x^{2}}=\dfrac{1}{4k(kx^{2})}-\dfrac{1}{4k}$
	 .
	 $\implies$ $f_{k}{}'(x)\begin{cases}<0&\text{if}\;x^{2}>\frac{1}{k}\\=0&\text{if}\;x^{2}=\frac{1}{k}\\>0&\text{if}\;x^{2}<\frac{1}{k}\end{cases}$
	 .
	 $\implies$ $f_{k}{}'(x)\begin{cases}<0&\text{if}\;x \in\left( -\infty,\,\frac{1}{\sqrt{ k }} \right)\cup\left( \frac{1}{\sqrt{ k }},\,\infty \right)\\=0&\text{if}\;x \in\left\{ -\frac{1}{\sqrt{ k }},\,\frac{1}{\sqrt{ k }} \right\}\\>0&\text{if}\;x \in\left( -\frac{1}{\sqrt{ k }},\,\frac{1}{\sqrt{ k }} \right)\end{cases}$
	 .
	 $\implies$ $\begin{cases}\max\,\{\,f_{k}(x)\;|\;x \in\mathbb{R}\,\}=f_{k}\left( \frac{1}{\sqrt{ k }} \right)=\frac{1}{2\sqrt{ k }}\\\min\,\{\,f_{k}(x)\;|\;x \in\mathbb{R}\,\}=f_{k}\left( -\frac{1}{\sqrt{ k }} \right)=-\frac{1}{2\sqrt{ k }}\end{cases}$

$\therefore$  $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$  with  $\dfrac{1}{N}<4\varepsilon^{2}$
	   s.t.  $\forall\,k\geq N$:  $||f_{k}-\tilde{0}||_{\sup\,}=\sup\limits_{x \in\mathbb{R}}\,|\dfrac{x}{1+kx^{2}}|=\dfrac{1}{2\sqrt{ k }}\leq\dfrac{1}{2\sqrt{ N }}<\varepsilon$
	   where  $\tilde{0}$  is the zero function

$\therefore$  $f_{k}\to \tilde{0}$  under $d_{\sup\,}$
	 $\implies$ uniformly on $\mathbb{R}$  (by Thm.)
	 $\implies$ pointwise on $\mathbb{R}$

(c)
$\because$  $\dfrac{1}{x^{2}}$ increasing on $(-\infty,\,0)$  $\land$  decreasing on $(0,\,\infty)$
	 .
	 $\implies$ $g_{k}(x)\begin{cases}\leq\frac{1}{k^{2}}&\text{if}\;x<-k\;\,\text{or}\;\,x>k\\=\frac{1}{k^{2}}&\text{o.w.}\end{cases}$  $\implies$ $||g_{k}||_{\sup\,}=\dfrac{1}{k^{2}}$

$\therefore$  $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$  with  $\dfrac{1}{N}<\sqrt{ \varepsilon }$
	   s.t.  $\forall\,k\geq N$:  $||g_{k}-\tilde{0}||_{\sup\,}=\dfrac{1}{k^{2}}\leq\dfrac{1}{N^{2}}<\varepsilon$
	   where  $\tilde{0}$  is the zero function

$\therefore$  $g_{k}\to \tilde{0}$  under $d_{\sup\,}$
	 $\implies$ uniformly on $\mathbb{R}$  (by Thm.)
	 $\implies$ pointwise on $\mathbb{R}$

(d)
$\because$  $|g_{k}(x)|=\dfrac{1}{\sqrt{ k }}|\cos(kx)|\leq\dfrac{1}{\sqrt{ k }}$  $\forall\,x \in\mathbb{R}$

$\therefore$  $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$  with  $\dfrac{1}{N}<\varepsilon^{2}$
	   s.t.  $\forall\,k\geq N$:  $||g_{k}-\tilde{0}||_{\sup\,}=\dfrac{1}{\sqrt{ k}}\leq\dfrac{1}{\sqrt{ N }}<\varepsilon$
	   where  $\tilde{0}$  is the zero function

$\therefore$  $g_{k}\to \tilde{0}$  under $d_{\sup\,}$
	 $\implies$ uniformly on $\mathbb{R}$  (by Thm.)
	 $\implies$ pointwise on $\mathbb{R}$

2.
(a)
Given $\mathscr{A}\coloneqq\{\,f\in\mathcal{C}^{0}([0,\,1])\;|\;||f||_{\sup\,}\leq1\,\}$ $\implies$ $\mathscr{A}\subseteq\mathcal{C}^{0}([0,\,1])\cap \mathcal{C}_{b}([0,\,1])$

$\because$  $\forall\,f \in \mathscr{A}$:  $||f-\tilde{0}||_{\sup\,}\leq1$
	 $\implies$ $\mathscr{A}\subseteq B_{2}(\tilde{0})$  where  $\tilde{0}$  is the zero function defined on $[0,\,1]$

$\therefore$  By Def, $\mathscr{A}$ bounded

Let $\,(f_{n})_{n \in \mathbb{N}}$ in $\mathscr{A}$  $\land$  $f_{n}\to f_{0}\in\mathcal{C}^{0}([0,\,1])$ under $d_{\sup\,}$

$\because$  $\forall\,\varepsilon>0$:  $\exists\,N\in\mathbb{N}$
	   s.t.  $\forall\,n\geq N$:
	            $\,d_{\sup\,}(f_{0},\,\tilde{0})-1\leq d_{\sup\,}(f_{0},\,\tilde{0})-d_{\sup\,}(f_{n},\,\tilde{0})\leq d_{\sup\,}(f_{0},\,f_{n})<\varepsilon$
	 .
	 $\implies$ $d_{\sup\,}(f_{0},\,\tilde{0})<1+\varepsilon$  $\forall\,\varepsilon>0$
	 .
	 $\implies$ $d_{\sup\,}(f_{0},\,\tilde{0})\leq 1$  i.e.  $f_{0}\in\mathscr{A}$

$\therefore$  $\text{Cl}_{\mathcal{C}([0,\,1])}(\mathscr{A})\subseteq\mathscr{A}$  i.e.  $\mathscr{A}$ closed $\subseteq\mathcal{C}^{0}([0,\,1])$

(b)
(i)
$\because$  $\forall\,n \in \mathbb{N}$:  $f_{n}|_{\left[ \frac{1}{2^{n+1}},\,\frac{3}{2^{n+2}} \right]}{}'(x)=2^{n+2}$  $\land$  $f_{n}|_{\left[ \frac{3}{2^{n+2}},\,\frac{1}{2^{n}} \right]}{}'(x)=-2^{n+2}$
	 .
	 $\implies$ $\begin{cases}\max\,\{\,f_{n}(x)\;|\;x \in\left[ \frac{1}{2^{n+1}},\,\frac{3}{2^{n+2}} \right]\,\}=f_{n}(\frac{3}{2^{n+2}})=1\\\min\,\{\,f_{n}(x)\;|\;x \in\left[ \frac{1}{2^{n+1}},\,\frac{3}{2^{n+2}} \right]\,\}=f_{n}(\frac{1}{2^{n+1}})=0\end{cases}$
	 
	      $\,\begin{cases}\max\,\{\,f_{n}(x)\;|\;x \in\left[ \frac{3}{2^{n+2}},\,\frac{1}{2^{n}} \right]\,\}=f_{n}(\frac{3}{2^{n+2}})=1\\\min\,\{\,f_{n}(x)\;|\;x \in\left[ \frac{3}{2^{n+2}},\,\frac{1}{2^{n}} \right]\,\}=f_{n}(\frac{1}{2^{n}})=0\end{cases}$
	 .
	 $\implies$ $||f_{n}||_{\sup\,}=1$  $\forall\,n \in\mathbb{N}$

$\therefore$  $f_{n}\in\mathscr{A}$  $\forall\,n \in \mathbb{N}$

(ii)
$\because$  $\forall\,n \in \mathbb{N}$:  $f_{n}(x)\begin{cases}\neq 0&\text{if}\;x \in(\dfrac{1}{2^{n+1}},\,\dfrac{1}{2^{n}})\\=0&\text{o.w.}\end{cases}$  

$\therefore$  $\forall$ distinct $n,\,m \in\mathbb{N}$: 
	   $\sup\limits_{x}\,|f_{n}-f_{m}|=\begin{cases}\sup\limits_{x}\,|f_{n}-\tilde{0}|&\text{if}\;x \in(\dfrac{1}{2^{n+1}},\,\dfrac{1}{2^{n}})\\\sup\limits_{x}\,|\tilde{0}-f_{m}|&\text{if}\;x \in(\dfrac{1}{2^{m+1}},\,\dfrac{1}{2^{m}})\\0&\text{o.w.}\end{cases}$
	 .
	   $\implies$ $||f_{n}-f_{m}||_{\sup\,}=\sup\,\{\,||f_{n}||_{\sup\,},\,||f_{m}||_{\sup\,}\}=\sup\,\{1,\,1\}=1$

(iii)
Assume $\mathscr{A}$ seqeuntially compact

$\implies$ $\exists$ subsequence $(f_{n_{k}})_{k \in \mathbb{N}}$ of $(f_{n})_{n \in \mathbb{N}}$ converges under $d_{\sup\,}$

$\implies$ $(f_{n_{k}})_{k \in \mathbb{N}}$ is Cauchy ($\rightarrow\!\leftarrow$)
	   .
     since by (ii),  $\forall$ distinct $k_{1},\,k_{2} \in\mathbb{N}$:  $||f_{n_{k_{1}}}-f_{n_{k_{2}}}||_{\sup\,}=1$

Thus, $\mathscr{A}$ not seqeuntially compact $\implies$ not compact







$\mathscr{A}$ bounded $\iff$ $\mathscr{A}\subseteq B_{r}(f_{0})$  under  $d_{\sup\,}$  for some  $r>0$, $f_{0} \in\mathcal{C}([0,\,1])$

$\mathscr{A}$ closed
$\iff$ $\text{Cl}_{\mathcal{C}([0,\,1])}(\mathscr{A})\subseteq\mathscr{A}$
$\iff$ $f_{0} \in\mathcal{C}([0,\,1])$  with  $B_{r}(f_{0})\cap A\neq \varnothing$  $\forall\,r>0$ $\implies$ $f_{0} \in\mathscr{A}$
       or
     $\,(f_{n})_{n \in \mathbb{N}}$ in $\mathscr{A}$ converges to $f_{0}$ $\implies$ $f_{0} \in\mathscr{A}$
