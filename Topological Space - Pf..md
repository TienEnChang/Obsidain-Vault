..

Pf. Lemma 4.1 ^4e4be2
- "$\implies$"
	- By Hypothesis:  $\forall\,p=(p_1,\,p_2)\in A$:  $\exists\,r>0$  s.t. ${B_r}^{X\times Y}(p)\subseteq A$
	- $\implies$
		- $\forall\,q=(q_1,\,q_2)\in [{B_{\frac{r}2}}^X(p_1)\times {B_{\frac{r}2}}^Y(p_2)]$:
		    $d_{\rm sum}(p,\,q)=d_1(p_1,\,q_1)+d_2(p_2,\,q_2)<\dfrac{r}2+\dfrac{r}2=r$ $\implies$ $q\in {B_r}^{X\times Y}(p)$
	- $\implies$
		- $[{B_{\frac{r}2}}^X(p_1)\times {B_{\frac{r}2}}^Y(p_2)]\subseteq {B_r}^{X\times Y}(p)\subseteq A$
- "$\impliedby$"
	- By Hypothesis:  $\forall\,p=(p_1,\,p_2)\in A\subseteq X\times Y$: 
	                  $\exists\,r_1,\,r_2>0$  s.t. $[{B_{r_1}}^X(p_1)\times {B_{r_2}}^Y(p_2)]\subseteq A$
	- Let $r\coloneqq\min\{r_1,\,r_2\}$
	- $\implies$
		- $\forall\,q=(q_1,\,q_2)\in{B_r}^{X\times Y}(p)\subseteq A$:
			- $d_1(p_1,\,q_1)\leq d_{\rm sum}(p,\,q)<r\leq r_1$ $\implies q_1\in{B_{r_1}}^X(p_1)$
			- $d_2(p_2,\,q_2)\leq d_{\rm sum}(p,\,q)<r\leq r_2$ $\implies q_2\in{B_{r_2}}^Y(p_2)$
	- $\implies$
		- ${B_r}^{X\times Y}(p)\subseteq[{B_{r_1}}^X(p_1)\times {B_{r_2}}^Y(p_2)]\subseteq A$

Pf. 3-1 ^166e65
- ![[Screenshot 2023-10-05 at 4.19.53 PM.png]]

Pf. 3-2 ^1277f1
- ![[Screenshot 2023-10-05 at 4.20.35 PM.png]]

Pf. 3-3 ^dc844c
- ![[Screenshot 2023-10-05 at 4.28.50 PM.png]]

Pf. 3-4 ^b8c403
- ![[Screenshot 2023-10-05 at 5.15.55 PM.png]]

Pf. ^wljaksmdl
- 
	![[2023_10_12 下午7_21 Office Lens.jpg]]

Pf. ^psfmewl
- 
	![[2023_10_12 下午7_58 Office Lens.jpg]]

Pf. ^3dce45
- 
	![[2023_10_12 下午6_03 Office Lens.jpg]]

Pf. ^d9c501
- 
	![[2023_10_12 下午5_40 Office Lens.jpg]]
	![[Screenshot 2023-11-30 at 11.13.29 PM.png]]

Pf. ^bklemlas
- 
	![[Screenshot 2023-11-30 at 11.15.22 PM.png]]
	![[Screenshot 2023-11-30 at 11.15.42 PM.png]]


Pf. 3-5 ^a2c956
- $\forall\,U_i$ are closed: $\bigcap\limits_{i\in I,\;\rm finite}U^c_i$ is open
- $\implies$ $(\bigcup\limits_{i\in I,\;\rm finite}U_i\;)^c$ is open  $\implies$ $\bigcup\limits_{i\in I,\;\rm finite}U_i\;$ is closed

Pf. 3-6 ^7579a3
- $\forall\,U_i$ are closed: $\bigcup\limits_{i\in I,\;\rm any}U^c_i$ is open
- $\implies$ $(\bigcap\limits_{i\in I,\;\rm any}U_i\;)^c$ is open  $\implies$ $\bigcap\limits_{i\in I,\;\rm any}U_i\;$ is closed

Pf. 3-7 ^062b3f
- $U\subseteq X$  is finite  $\implies$  $U=\bigcup\limits_{p\in U,\;\rm finite}\{p\}\;$ is closed

Pf. ^00d67b
- $A$ closed $\subseteq X$  i.e.  $A^c$ open $\subseteq X$
- $\iff$ $A^c\cap Y$ open $\subseteq Y$  i.e.  $A\cap Y$ closed $\subseteq Y$

Pf. ^spnkwnqd
- $\because$  $Y$ open in $X$  $\land$  $\exists$ open $B\subseteq X$  s.t. $B\cap Y=A$
- $\therefore$  $B\cap Y$ open in $X$  $\therefore$  $A$ open in $X$
- ～
- $\because$  $Y$, ${\rm int}_X(A)$ open in $X$
- $\therefore$  $A={\rm int}_Y(A)={\rm int}_X(A)\cap Y$ open in $X$

Pf. ^ajwbkljd
- $\because$  $Y$ closed in $X$  $\land$  $\exists$ closed $B\subseteq X$  s.t. $B\cap Y=A$ 
- $\therefore$  $B\cap Y$ closed in $X$  $\therefore$  $A$ closed in $X$
- ～
- $\because$  $Y$, ${\rm Cl}_X(A)$ closed in $X$
- $\therefore$  $A={\rm Cl}_Y(A)={\rm Cl}_X(A)\cap Y$ closed in $X$

Pf. ^9b621b
- $\because$ $B$ open in $X$ $\iff$ $B\cap Y$ open in $Y$
- $\therefore$ 
  ${\rm int}_X(A)\cap Y=\bigcup\limits_{U\,{\rm open\,in\;X},\,U\subseteq A}(U\cap Y)=\bigcup\limits_{U\cap Y\,{\rm open\,in\;Y},\,U\cap Y\subseteq A\cap Y}(U\cap Y)={\rm int}_Y(A\cap Y)$

Pf. ^60e654
- $\because$ $B$ closed in $X$ $\iff$ $B\cap Y$ closed in $Y$
- $\therefore$
  ${\rm Cl}_X(A)\cap Y=\bigcap\limits_{U\,{\rm closed\,in\;X},\,U\supseteq A}(U\cap Y)=\bigcap\limits_{U\cap Y\,{\rm closed\,in\;Y},\,U\cap Y\supseteq A\cap Y}(U\cap Y)={\rm Cl}_Y(A\cap Y)$

Pf. ^dd9202
- $Y\subseteq X$ $\implies$ $\forall\,p\in{\rm Cl}_Y(A)$:  $p\in{\rm Cl}_X(A)$  { $p\in Y\supseteq{\rm Cl}_Y(A)$ }
- $p\in Y$ $\land$ $p\in{\rm Cl}_X(A)$ $\implies$ $p\in{\rm Cl}_Y(A)$

---

Sol.
![[Screenshot 2023-10-05 at 4.33.25 PM.png]]

Sol.
![[Screenshot 2023-10-05 at 4.33.53 PM.png]]

Sol.
![[Screenshot 2023-10-05 at 4.24.47 PM.png]]

Sol.
![[Screenshot 2023-10-05 at 4.45.30 PM.png]]![[Screenshot 2023-10-05 at 4.46.00 PM.png]]
![[Screenshot 2023-10-05 at 4.46.24 PM.png]]

Sol.
![[Screenshot 2023-10-05 at 5.19.04 PM.png]]