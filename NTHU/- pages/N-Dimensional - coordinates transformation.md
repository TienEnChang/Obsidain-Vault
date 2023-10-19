
Note: coordinates transformation is a type of "mapping"

Method
- special-uv
	- $u=x+y$, $v=x-y$
	- $\implies$ $T(u,\,v)=\begin{cases}x=\frac12(u+v)\\y=\frac12(u-v)\end{cases}$, $\det(J(T))=\dfrac12$

Def.
- polar
	- $T(r,\,\theta)=\begin{cases}x=r\cos(\theta)\\y=r\sin(\theta)\end{cases}$, $\det(J(T))=r$
- cylindrical
	- $T(r,\,\theta,\,z)\coloneqq\begin{cases}x=r\cos(\theta)\\ y=r\sin(\theta)\\ z=z\end{cases}$, $\det(J(T))=r$
- spherical
	- $T(\rho,\,\theta,\,\phi)\coloneqq\begin{cases}x=\rho\sin(\phi)\cos(\theta)\\ y=\rho\sin(\phi)\sin(\theta)\\ z=\rho\cos(\phi)\end{cases}$, $\det(J(T))=-\rho^2\sin(\phi)$
	- where
		- $\phi$ is the angle to z-axis
		- $\theta$ is the angle on xy-plane
		- $\rho$ is the distance
	- and
		- $dT(V)\approx(\rho\sin(\phi)\,d\theta)\cdot(\rho\,d\phi)\cdot d\rho=\rho^2\sin(\phi)\,d\rho\,d\theta\,d\phi$


