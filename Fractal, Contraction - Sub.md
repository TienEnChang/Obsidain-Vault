
Ex.  Show that  $f:\mathbb{R}\to \mathbb{R}$  by  $f(x,\,y,\,z)\coloneqq(\dfrac{\sin(y)}{3},\,\dfrac{\cos(z)}{4},\,\dfrac{x}{5})$ 
     has an unique fixed point
Sol.
(1)
$\because$  $\sin$, $\cos$ are continuous, diff. on $\mathbb{R}$ 
   .
   $\implies$ By Mean Value Thm., $\,\;\forall\,(x_{1},\,y_{1},\,z_{1}),\,(x_{2},\,y_{2},\,z_{2})\in\mathbb{R}$:
   .
	    $\exists\,c_{y}$ between $y_{1},\,y_{2}$  s.t. $\cos(c_{y})(y_{2}-y_{1})=\sin(y_{2})-\sin(y_{1})$
	    $\exists\,c_{z}$ between $z_{1},\,z_{2}$  s.t. $-\sin(c_{z})(z_{2}-z_{1})=\cos(z_{2})-\sin(z_{1})$

$\therefore$  $||f(x_{1},\,y_{1},\,z_{1})-f(x_{2},\,y_{2},\,z_{2})||$
   .
   $=\sqrt{ (\dfrac{\sin(y_{2})-\sin(y_{1})}{3})^{2}+(\dfrac{\cos(z_{2})-\cos(z_{1})}{4})^{2}+(\dfrac{x_{2}-x_{1}}{5})^{2} }$
   .
   $\leq\dfrac{1}{3}\sqrt{ \cos(c_{y})^{2}(y_{2}-y_{1})^{2}+\sin(c_{z})^{2}(z_{2}-z_{1})^{2}+(x_{2}-x_{1})^{2} }$
   .
   $\leq\dfrac{1}{3}\sqrt{ (y_{2}-y_{1})^{2}+(z_{2}-z_{1})^{2}+(x_{2}-x_{1})^{2} }=\dfrac{1}{3}||(x_{1},\,y_{1},\,z_{1})-(x_{2},\,y_{2},\,z_{2})||$
   .
   $\implies$ $f$ is contraction
(2)
$\because$  $\mathbb{R}$ is complete metric space  $\land$   $f$ is contraction on $\mathbb{R}$

$\therefore$  By the contraction mapping principle,  $\exists\,!$ fixed point of $f$ 