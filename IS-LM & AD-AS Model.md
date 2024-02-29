
variable
- dependent: ${x}^\square$ (left hand side)
- independent: $\bf\widetilde{x}$ (right hand side) (endogenous)

IS-LM model  { assume Keynesian ($Y=Y^d$, $I=I^d$) }
(1)
- $C^d=a+b\,Y-\eta_c\,{\bf\widetilde r}$  { desired consumption }
- $I^d=d-\eta_i\,{\bf\widetilde{r}}$       $\;\,${ desired investment }
- $G^d=G_0$
- where
	- $Y^d=C^d+I^d+G^d+(X-M)$  $\land$  $(X-M)=0$ 
	- $r$: real interest rate  { $r\coloneqq i-\pi^e$ }
(2)
- $M^d=P\cdot L(Y,\,\bf\widetilde{i}\,)$   { money demand }
- $M^s=M_0$          { money supply, by central bank }
- where
	- $L(Y,\,{\bf\widetilde{i}}\,)\coloneqq kY-l({\bf\widetilde r}+{{\bf{\pi}}^e})$  { liquidity preference model }
	- ---
	- $Y$: transaction amount = 交易金額 = 收入
	- $i$: nominal interest rate = 持有貨幣的機會成本
- exo
	- $P$: $\dfrac{M^d}{P}$ is called real balance (實質餘額)
	- $\pi^e$: inflation rate
(3)
- $IS$: 
	- ${\bf Y^d}=\dfrac1{1-b}\cdot{(\gamma-\eta\cdot {\bf\widetilde r})}$  where  $\gamma\coloneqq a+d+G_0$,  $\eta\coloneqq  \eta_c+\eta_i$
- $LM$:
	- ${\bf Y^d}=\dfrac{1}{k}\cdot(\dfrac{M_0}{P}+l\,{\pi}^e+l\,{\bf\widetilde r})$  at  $M^d=M^s$

AD-AS
(4)
- $AD$:  $(\dfrac{1-b}\eta+\dfrac{k}{l}){\bf Y^d}=\dfrac{M_0}{l}{\bf\widetilde P}^{-1}+(\pi^e+\dfrac\gamma{\eta})$ 
- $AS:\;$  ${\bf Y^s}=f_{AS}({\bf \widetilde P})$

![[Screenshot 2023-10-27 at 5.53.22 PM.png]]

---

Ex.
- $IS$: ...
- $LM$: ...
- $\implies$
	- $\begin{bmatrix}(1-b)&\eta\\k & -l\end{bmatrix}\begin{bmatrix}Y_{eq}\\ r_{eq}\end{bmatrix}=\begin{bmatrix}\gamma\\ \dfrac{M_0}{P}+l\pi^e\end{bmatrix}$

Ex.
- $Y=C+I_0+G_0$
- $C=a+b\,Y$
- $\implies$
	- $\begin{bmatrix}1&-1\\-b & 1\end{bmatrix}\begin{bmatrix}Y\\ C\end{bmatrix}=\begin{bmatrix}I_0+G_0\\ a\end{bmatrix}$
	- $Y=\dfrac1{1-b}\cdot{(a+I_0+G_0)}$ $\implies$ $\Delta Y=\dfrac1{1-b}$, $\Delta G_0=1$