
def: $C^{\infty}(U,\,\mathbb{R})$ contains all $f$ that is $\infty$-differentiable

def
- 0-order: $\Omega^0(U)=\{\;f\;\big|\;f\in C^{\infty}(U,\,\mathbb{R})\;\}$
- 1-order: $\Omega^1(U)=\{\;f\,dx+g\,dy+h\,dz\;\big|\;f,\,g,\,h\in C^{\infty}(U,\,\mathbb{R})\;\}$
- 2-order: $\Omega^2(U)=\{\;f\,dydz+g\,dzdx+h\,dxdy\;\big|\;f,\,g,\,h\in C^{\infty}(U,\,\mathbb{R})\;\}$
- 3-order: $\Omega^3(U)=\{\;f\,dxdydz\;\big|\;f\in C^{\infty}(U,\,\mathbb{R})\;\}$

rule: $dxdy=-dydx$, $dxdx=0$

calculation:

$\Omega^0(U)$
$\stackrel{d}{\longrightarrow}\Omega^1(U):\;d(f)=\dfrac{\partial f}{\partial x}dx+\dfrac{\partial f}{\partial y}dy+\dfrac{\partial f}{\partial z}dz$
$\stackrel{d}{\longrightarrow}\Omega^2(U):\;d(f\,dx+g\,dy+h\,dz)$
$$=\dfrac{\partial f}{\partial y}dydx+\dfrac{\partial f}{\partial z}dzdx+\dfrac{\partial g}{\partial x}dxdy+\dfrac{\partial g}{\partial z}dzdy+\dfrac{\partial h}{\partial x}dxdz+\dfrac{\partial h}{\partial y}dydz$$
$$=(\dfrac{\partial h}{\partial y}-\dfrac{\partial g}{\partial z})dydz+(\dfrac{\partial f}{\partial z}-\dfrac{\partial h}{\partial x})dzdx+(\dfrac{\partial g}{\partial x}-\dfrac{\partial f}{\partial y})dxdy$$
$\stackrel{d}{\longrightarrow}\Omega^3(U):\;d(f\,dydz+g\,dzdx+h\,dxdy)$
$$=(\dfrac{\partial f}{\partial x}+\dfrac{\partial g}{\partial y}+\dfrac{\partial h}{\partial z})dxdydz$$

observation: $d^2=d\circ d=0$

![[DSC_1508_2.JPG.jpg]]