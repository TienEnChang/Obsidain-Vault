
\[ general problem of static comparative on $\theta$ ]

Def.
- objective func:   $f(x;\,\theta)$
- constraint func:  $g(x;\,\theta)$   where  $x\in\mathbb{R}^n$, $\theta\in\mathbb{R}^k$
- primal problem
	- $\max\limits_{x}\,f(x;\,\theta)$  sub. to  $g(x;\,\theta)=0$
- dual problem
	- $\min\limits_{x}\,g(x;\,\theta)$  sub. to  $f(x;\,\theta)=0$

Sol.
- Lagrangian
	- primal:
		- $L(x,\,\lambda)\coloneqq f(x;\,\theta)-\lambda\,g(x;\,\theta)$
			- $L_x(x,\,\lambda)=0$ $\implies$ $[f_x-\lambda\,g_x](x;\,\theta)=0$
			- $L_\lambda(x,\,\lambda)=0$ $\implies$ $g(x;\,\theta)=0$,  $[g_x\,x_\theta+g_\theta](\theta)=0$
	- dual:
		- $L^d(x,\,\mu)\coloneqq g(x;\,\theta)-\mu\,f(x;\,\theta)$
			- $L^d_x(x,\,\mu)=0$ $\implies$ $[g_x-\mu\,f_x](x;\,\theta)=0$
			- $L^d_{\mu}(x,\,\mu)=0$ $\implies$ $f(x;\,\theta)=0$,  $[f_x\,x_\theta+f_\theta](\theta)=0$
- $\implies$
- optimal solution
	- primal:
		- implicit:  $x^m=x^m(\theta)$,  $\lambda^m=\lambda^m(\theta)$
		- indirect:  $V^m(\theta)\coloneqq f(x^m(\theta);\,\theta)$,  $L^*(\theta)\coloneqq L|_{(x^m,\,\lambda^m)}(\theta)$
	- dual:
		- implicit:  $x^h=x^h(\theta)$,  $\mu^h=\mu^h(\theta)$
		- indirect:  $V^h(\theta)\coloneqq f(x^h(\theta);\,\theta)$,  $L^{d*}(\theta)\coloneqq L^d|_{(x^h,\,\lambda^h)}(\theta)$
- $\implies$
- envelope theorem / derivative
	- primal:
		- $\dfrac{dV^m}{d\theta}=\dfrac{\partial L}{\partial\theta}|_{(x^m,\,\lambda^m)}$  [[Duality - Primal & Dual#^b0c960|{Pf}]]
		- where  $\dfrac{dV^m}{d\theta}=f_x\,x^m_\theta+f_\theta$,  $\dfrac{\partial L}{\partial\theta}|_{(x^m,\,\lambda^m)}=f_\theta-\lambda^m\,g_\theta$
	- dual:
		- $\dfrac{dV^h}{d\theta}=\dfrac{\partial L^d}{\partial\theta}|_{(x^h,\,\lambda^h)}$
		- where  $\dfrac{dV^h}{d\theta}=g_x\,x^h_\theta+g_\theta$,  $\dfrac{\partial L^d}{\partial\theta}|_{(x^h,\,\lambda^h)}=g_\theta-\mu^h\,f_\theta$


\[ Consumer Behavior ]

Def.
- objective func:   $U(x_1,\,x_2)$
- constraint func:  $E(x_1,\,x_2)=p_1x_1+p_2x_2$
- primal problem
	- $\max\limits_{x}\,U(x_1,\,x_2)$  sub. to  $E(x_1,\,x_2)=\overline{E}$
- dual problem
	- $\min\limits_{x}\,E(x_1,\,x_2)$  sub. to  $U(x_1,\,x_2)=\overline{U}$

Sol.
- primal:  $L(x_1,\,x_2,\,\lambda)\coloneqq U(x_1,\,x_2)-\lambda\,[E(x_1,\,x_2)-\overline{E}]$
- dual:    $L^d(x_1,\,x_2,\,\mu)\coloneqq E(x_1,\,x_2)-\mu\,[U(x_1,\,x_2)-\overline{U}]$
- $\implies$ 
	- (1)
		- $\dfrac{ \partial L }{ \partial \lambda }=0$ $\implies$ $E(x_1,\,x_2)-\overline{E}=0$  { 1st condition of $(x_{1}^{m},\,x_{2}^{m})$ }
		- $\dfrac{ \partial L^{d} }{ \partial \mu }=0$ $\implies$ $U(x_1,\,x_2)-\overline{U}=0$  { 1st condition of $(x_{1}^{h},\,x_{2}^{h})$ }
	- (2)
		- $\dfrac{ \partial L }{ \partial x_{1} },\,\dfrac{ \partial L }{ \partial x_{2} }=0$ $\implies$ $\dfrac{U_{x_{1}}}{E_{x_{1}}}=\lambda=\dfrac{U_{x_{2}}}{E_{x_{2}}}$  { 2nd condition of $(x_{1}^{m},\,x_{2}^{m})$ }
		- $\dfrac{ \partial L^{d} }{ \partial x_{1} },\,\dfrac{ \partial L^{d} }{ \partial x_{2} }=0$ $\implies$ $\dfrac{E_{x_{1}}}{U_{x_{1}}}=\mu=\dfrac{E_{x_{2}}}{U_{x_{2}}}$  { 2nd condition of $(x_{1}^{h},\,x_{2}^{h})$ }
		  
	- $\implies$ {use 隱函數 when $U(x_{1},\,x_{2})$ unknown}
	- (3)
		- $x_{1}^{m}=x_{1}^{m}(p_{1},\,p_{2},\,\overline{E})$,  $x_{2}^{m}=x_{2}^{m}(p_{1},\,p_{2},\,\overline{E})$  |  $\lambda^{m}=\lambda^{m}(p_{1},\,p_{2},\,\overline{E})$
		- $x_{1}^{h}=x_{1}^{h}(p_{1},\,p_{2},\,\overline{U})$,   $x_{2}^{h}=x_{2}^{h}(p_{1},\,p_{2},\,\overline{U})\,\,$  |  $\mu^{h}=\mu^{h}(p_{1},\,p_{2},\,\overline{U})$
	- (4)
		- $U^{m}(p_{1},\,p_{2},\,\overline{E})\coloneqq U(x_{1}^{m},\,x_{2}^{m})$
		- $E^{h}(p_{1},\,p_{2},\,\overline{U})\coloneqq E(x_{1}^{h},\,x_{2}^{h})$
	- (5)
		- $U^{m}(p_{1},\,p_{2},\,E^{h}(p_{1},\,p_{2},\,\overline{U}))=\overline{U}$
		- $E^{h}(p_{1},\,p_{2},\,U^{m}(p_{1},\,p_{2},\,\overline{E}))=\overline{E}$ $\implies$ $x_{1}^{h}=\dfrac{ \partial E^{h} }{ \partial p_{1} }$,  $x_{2}^{h}=\dfrac{ \partial E^{h} }{ \partial p_{2} }$

Sol. &&
- (0)
	- $x^m(p,\,\phi^E)=x^h(p,\,\phi^U)$
	- $U^m(p,\,\phi^E)=\phi^U$,  $E^h(p,\,\phi^U)=\phi^E$
- $\implies$ 
- (1)                             (2)                       (3)
	- $x^m(p,\,\phi^E)=x^h(p,\,U^m(p,\,\phi^E))$     $U^m(p,\,E^h(p,\,\phi^U))=\phi^U$     $\lambda^m=\dfrac1{\mu^h}$
	- $x^h(p,\,\phi^U)=x^m(p,\,E^h(p,\,\phi^U))\,$     $E^h(p,\,U^m(p,\,\phi^E))=\phi^E$
- (4)
	- $\dfrac{\partial L}{\partial \phi^E}|_{(x^m,\,\lambda^m)}=\lambda^m$,  $\dfrac{\partial L^d}{\partial \phi^U}|_{(x^m,\,\lambda^m)}=\mu^h$


\[ Slutsky Equation ]

Claim:  $x^m_1=x^h_1-x^m_3x^m$  i.e.  $\dfrac{\partial x^m}{\partial p_1}=\dfrac{\partial x^h}{\partial p_1}-\dfrac{\partial x^m}{\partial \phi^E}\,x^m$  { TE = SE - (-IE) }



\[ Production Behavior ]

Def.
- objective func:   $C(x,\,y\,;\,p_x,\,p_y)=p_xx+p_yy$
- constraint func:  $Q(x,\,y)$
- primal problem
	- $\min\limits_{x}\,C(x,\,y\,;\,p_x,\,p_y)$  sub. to  $Q(x,\,y)=\bar{q}$

Sol.
- $x^h=x^h(p_x,\,p_y,\,\bar{q})$,  $y^h=y^h(p_x,\,p_y,\,\bar{q})$,  $\mu^h=\mu^h(p_x,\,p_y,\,\bar{q})$
- $C^h(p_x,\,p_y,\,\bar{q})\coloneqq C(x^h(p_x,\,p_y,\,\bar{q}),\,y^h(p_x,\,p_y,\,\bar{q});\,p_x,\,p_y)$
	
- $\dfrac{\partial C^h}{\partial \bar{q}}=\dfrac{\partial L^d}{\partial \bar{q}}|_{(x^h,\,y^h,\,\mu^h)}=\mu^h$

$\because$ when 要素市場 is 完全競爭, 
$\therefore$


---

Pf. ^b0c960
- dual:  similar as below
- primal:
	- $\dfrac{dV^m}{d\theta}=[f_x\,x^m_\theta+f_\theta]|_{(x^m,\,\lambda^m)}$
		- $=\lambda^m\,g_x\,x^m_\theta+f_\theta$  since  $[f_x-\lambda\,g_x]|_{x^m}=\tilde 0$  (zero func.)
		- $=-\lambda^m\,g_\theta+f_\theta\;$   since  $[g_x\,x_\theta+g_\theta]=\tilde 0$
			- $=\dfrac{\partial L}{\partial\theta}|_{(x^m,\,\lambda^m)}$
Cor.
- primal:  $f_x\,x^m_\theta+\lambda^m\,g_\theta=0$
- dual:    $g_x\,x^h_\theta+\mu^h\,f_\theta=0$