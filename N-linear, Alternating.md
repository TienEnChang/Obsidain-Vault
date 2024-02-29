
Rmk. $\text{tr}\not\in\mathcal{L}^{\otimes n}(F^{n})$

Def.
- $\mathcal{L}^{\otimes n}(F^{n})\coloneqq\{\,f \in\mathcal{F}(M_{n}(F),\,F)\;|\;f\,$ n-linear$\;\}$  subspace of  $\mathcal{F}(M_{n}(F),\,F)$
- $\mathcal{L}^{\land n}(F^{n})\coloneqq\{\,\delta \in\mathcal{L}^{\otimes n}(F^{n})\;|\;\delta\,$ alternating$\;\}$  subspace of  $\mathcal{L}^{\otimes n}(F)$
- where
	- n-linear:     $\delta(\begin{bmatrix}\vdots\\u+cv\\\vdots\end{bmatrix})=\delta(\begin{bmatrix}\vdots\\u\\\vdots\end{bmatrix})+c\cdot\delta(\begin{bmatrix}\vdots\\v\\\vdots\end{bmatrix})$
	- alternating:  $\delta(\begin{bmatrix}\vdots\\v\\v\\\vdots\end{bmatrix})=0$  { identical adjacent rows }

Def.
- basis of $\mathcal{L}^{\otimes n}(F^{n})$:  $\big\{\ell_{(k_{1},\,\cdots,\,k_{n})}\big\}_{k_1,\,\cdots,\,k_{n}=1}^{n}$  {$\text{dim}=n^{n}$}
- basis of $\mathcal{L}^{\land n}(F^{n})$:  $\{\,\det \,\}\,$               {$\text{dim}=1$}
	-  where
		- $\ell_{(j_{1},\,\cdots,\,j_{n})}(A)\coloneqq \prod\limits_{i=1}^{n}A_{i,\,j_{i}}$  $\forall\,A\in M_{n}(F)$

Def.
- $\det(A)=\sum\limits_{\sigma \in S_{n}}(-1)^{N(\sigma)}\prod\limits_{i=1}^{n}A_{i,\,\sigma(i)}$
- where
	- $S_{n}\coloneqq\{\;$all permutation $\sigma$ on $\{\,1,\,\cdots,\,n\,\}\,\}$
	- ${N(\sigma)}\coloneqq\#$ of row switching for $\begin{bmatrix}e_{\sigma(1)}\\\vdots\\e_{\sigma(n)}\end{bmatrix}\to \begin{bmatrix}e_{1}\\\vdots\\e_{n}\end{bmatrix}$

Prop.
- (2) $\delta(A)=0$  if  $A$ has two identical rows  { $=0$ if $A$ has zero row }
- (4) $\delta(A)=0$  if  $\text{rank}(A)<n$
	
- (1) $\delta(w(i,\,j))=-\delta(I_{n})$
- (3) $\delta(e_{ij}(a))=\delta(I_{n})$
- (.) $\delta(d_{i}(a))=a\cdot\delta(I_{n})$         { by n-linear }
- (5) $\delta(AB)=\det(A)\,\delta(B)\;$       { $\delta(A)=\delta(I_{n})\det(A)$, $\text{dim}(\mathcal{L}^{\land n}(F^{n}))=1$ }
- (6) $\delta(A^{-1})=\det(A)^{-1}\,\delta(I_{n})$
- (7) $\delta(A^{\top})=\delta(A)$

Thm.
- $\delta \in\mathcal{L}^{\land n}(F^{n})$  $\land$  $\delta(I_{n})=1$ $\iff$ $\delta=\det$

Rmk.
- $\{\,e_{1},\,\cdots,\,e_{n}\,\}$  standard basis of $F^{n}$

---

Pf.
Let $f\in\mathcal{L}^{\otimes n}(F^{n})$, $A\coloneqq\begin{bmatrix}A_{11}e_{1}+\cdots+A_{1n}e_{n}\\\vdots\\ A_{n1}e_{1}+\cdots+A_{nn}e_{n}\end{bmatrix}\in M_{n}(F)$

(1) Generating Set

$\because$  $f(A)=\sum\limits_{k_{1}=1}^{n}A_{1k_{1}}f(\begin{bmatrix}e_{k_{1}}\\\vdots\\A_{n1}e_{1}+\cdots+A_{nn}e_{n}\end{bmatrix})=\sum\limits_{k_{1}=1}^{n}A_{1k_{1}}\cdots[\sum\limits_{k_{n}=1}^{n}A_{nk_{n}}f(\begin{bmatrix}e_{k_{1}}\\\vdots\\e_{k_{n}}\end{bmatrix})]$

.  $=\sum\limits_{k_{1}=1}^{n}\cdots\left[ \sum\limits_{k_{n}=1}^{n}A_{1k_{1}}\cdots A_{nk_{n}}f(\begin{bmatrix}e_{k_{1}}\\\vdots\\e_{k_{n}}\end{bmatrix}) \right]=\sum\limits_{1\leq k_{1},\,\cdots,\, k_{n}\leq n}f(\begin{bmatrix}e_{k_{1}}\\\vdots\\e_{k_{n}}\end{bmatrix})\ell_{(k_{1},\,\cdots,\,k_{n})}(A)$

$\therefore$  $f \in\text{span}(\big\{\ell_{(k_{1},\,\cdots,\,k_{n})}\big\}_{k_1,\,\cdots,\,k_{n}=1}^{n})$

(2) Linear Independence

Let $\big\{a_{(k_{1},\,\cdots,\,k_{n})}\big\}_{k_1,\,\cdots,\,k_{n}=1}^{n}\subseteq F$

.    s.t.  $Z\coloneqq\sum\limits_{1\leq k_{1},\,\cdots,\, k_{n}\leq n}a_{(k_{1},\,\cdots,\,k_{n})}\ell_{(k_{1},\,\cdots,\,k_{n})}=\tilde{0}\in\mathcal{F}(M_{n}(F),\,F)$

$\because$  $\ell_{(k_{1},\,\cdots,\,k_{n})}(\begin{bmatrix}e_{m_{1}}\\\vdots\\e_{m_{n}}\end{bmatrix})=\begin{cases}1&\text{if}\;m_{1}=k_{1},\,\cdots,\, m_{n}=k_{n}\\0&\text{o.w.}\end{cases}$ 
$\therefore$  $Z(\begin{bmatrix}e_{m_{1}}\\\vdots\\e_{m_{n}}\end{bmatrix})=a_{(m_{1},\,\cdots,\,m_{n})}(\begin{bmatrix}e_{m_{1}}\\\vdots\\e_{m_{n}}\end{bmatrix})=0$

$\therefore$  $a_{(k_{1},\,\cdots,\,k_{n})}=0$  $\forall\,k_1,\,\cdots,\,k_{n}\in\{1,\,\cdots,\,n\}$ $\implies$ linear indep.


Pf.

(0) 
- if $\det(A)=0$:  $\det(A^{\top})= 0$
- if $\det(A)\neq 0$:
	- $\det(w(i,\,j)^{\top})$, $\det(d_{i}(a)^{\top})$, $\det(e_{ij}(a)^{\top})$ remains $\implies$ $\det(A^{\top})$ remains

(1)                               (2)
![[Screenshot 2024-01-02 at 5.48.30 PM.png|300]]![[Screenshot 2024-01-02 at 5.51.03 PM.png|400]]

(3)                                          (4)
![[Screenshot 2024-01-02 at 5.53.03 PM.png|400]]![[Screenshot 2024-01-02 at 6.17.00 PM.png|300]]

(5) if $\det(A)=0$:  $\text{rank}(A)<n$ $\implies$ $\text{rank}(AB)<n$ $\implies$ $\delta(AB)=0$
- if $\det(A)\neq 0$:
	- ![[Screenshot 2024-01-02 at 6.47.52 PM.png]]

(6) $\delta(I_{n})=\delta(AA^{-1})=\det(A)\delta(A^{-1})$ $\implies$ $\delta(A^{-1})=\det(A)^{-1}\delta(I_{n})$

(7) $\delta(A^{\top}I_{n})=\det(A^{\top})\delta(I_{n})=\det(A)\delta(I_{n})=\delta(A)$

Pf.
$\because$  (1) $\delta \in\mathcal{L}^{\land n}(F^{n})\subseteq\mathcal{L}^{\otimes n}(F^{n})$ $\implies$ $\delta=\sum\limits_{1\leq k_{1},\,\cdots,\, k_{n}\leq n}\delta(\begin{bmatrix}e_{k_{1}}\\\vdots\\e_{k_{n}}\end{bmatrix})\ell_{(k_{1},\,\cdots,\,k_{n})}$
   (2) $\delta(A)=0$  if  $A$ has two identical rows

   (3) $\delta(\begin{bmatrix}e_{\sigma(1)}\\\vdots\\e_{\sigma(n)}\end{bmatrix})=(-1)^{N(\sigma)}\delta(I_{n})$

$\therefore$  $\delta(A)=\delta(I_{n})\sum\limits_{\sigma \in S_{n}}(-1)^{N(\sigma)}\ell_{(\sigma(1),\,\cdots,\,\sigma(n))}(A)$

$\therefore$  $\det(A)=\sum\limits_{\sigma \in S_{n}}(-1)^{N(\sigma)}\prod\limits_{i=1}^{n}A_{i,\,\sigma(i)}$