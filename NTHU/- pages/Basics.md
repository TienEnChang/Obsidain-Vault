
Mathematical Program
- objective function:  $\min$ $f(x)$               | $f:\mathbb{R}^n\to\mathbb{R}$
- constraints
	- sign:            $x_i\leq 0$
	- functional:      $g_i\,(x)\leq b_i$  $\forall i=1\,...\,m$  | $g_i:\mathbb{R}^n\to\mathbb{R}$
- decision variable:   $x\in\mathbb{R}^n$                 $\,$| (vector)

Transformation
- $\max$ $f(x)$ $\iff$ $\min$ $-f(x)$
- $g_i\,(x)= b_i$ $\iff$ $g_i\,(x)\leq b_i$  $\land$  $-g_i\,(x)\leq -b_i$

Solution / Region
- feasible:  all constraints are satisfied
- optimal:   feasible  $\land$  objective function is at best value

Binding:  $g_i\,(\cdot)\leq b_i$ is binding at $\bar x$ $\iff$ $g_i\,(\bar x)=b_i$  (boundary)


Linear Program / Model
- $f(x)=\displaystyle\sum_{j=1}^n c_j\,x_j$ :  $\min$ $f(x)$ $\implies$ $\min$ $c^{\top}x$
- $g_i\,(x)=\displaystyle\sum_{j=1}^n A_{ij}\,x_j$ :  $g_i\,(x)\leq b_i$  $\forall i=1\,...\,m$ $\implies$ $Ax\leq b$
	- ( $x\in\mathbb{R}^n$, $b\in\mathbb{R}^m$, $A\in\mathbb{R}^{m\times n}$)

Isoquant Line
- name
	- Indifference Line (Econ)
	- Level Curve (Math)
- formula
	- $L_k\coloneqq\{\,x\,\big|\,c^{\top}x=k\,\}$   ($k$ is the objective value)
	- $L_c\coloneqq\{\,\mathbb{X}\in{\rm dom}(f)\,\big|\,f(\mathbb{X})=c\,\}$

Types of LP
- infeasible          unbounded               finitely optimal
- ![[Screenshot 2023-08-06 at 5.01.52 PM.png|190]]|![[Screenshot 2023-08-06 at 5.03.02 PM.png|230]]|![[Screenshot 2023-08-06 at 5.04.08 PM.png|230]]
- ![[Screenshot 2023-08-06 at 5.00.44 PM.png]]


Ex Program:  Production & Inventory
- Decision Variable
	- x1, x2, x3, x4                 ... Production
- Objective Function
	- $\min$
		- (9, 12, 10, 12)$^{\top}$ x
		- + y1 + y2 + y3 + y4        ... Ending Inventory
			- where
				- y1 = x1 - 100
				- y2 = y1 + x2 - 150
				- y3 = y2 + x3 - 200
				- y4 = y3 + x4 - 170
- Constraints
	- x, y $\geq$ 0
- Compact Formulation (Generalized)
	- Let
		- $x_t$ be the production amount
		- $y_t$ be the ending inventory
	- (params)
		- $c_t$ be the unit production cost  
		- $d_t$ be the demanded amount
	- (index sets)
		- $N=\{\,1,\,...,\,n\,\}$ where $n\,$ is the total number of days
	- Find
		- $\min$ $\displaystyle\sum_{t\in N}(c_t\,x_t+y_t)$
		- s.t.
			- $y_0=0$
			- $y_t=y_{t-1}+x_t-d_t$  $\forall t\in N$
			- $x_t,\,y_t\geq0$  $\forall t\in N$

Ex Program:.  Personnel Scheduling
- Decision Variable
	- x1, x2, x3, x4, x5, x6, x7     ... shift types
- Objective function
	- $\min$ $\displaystyle\sum_{j=1}^7 x_j$
- Constraints
	- x1  +  x4 + x5 + x6 + x7 $\geq$ 110
	- x2  +  x5 + x6 + x7 + x1 $\geq$ 80
	- x3  +  x6 + x7 + x1 + x2 $\geq$ 150
	- x4  +  x7 + x1 + x2 + x3 $\geq$ 30
	- x5  +  x1 + x2 + x3 + x4 $\geq$ 70
	- x6  +  x2 + x3 + x4 + x5 $\geq$ 160
	- x7  +  x3 + x4 + x5 + x6 $\geq$ 120
	- x $\geq$ 0
- Compact Formulation (Generalized)
	- Let
		- $x_t$ be the personnel amount for each shift types
	- (params)
		- $d_t$ be the demanded personnel amount for each day
	- (index sets)
		- $N=\{\,1,\,...,\,n\,\}$ where $n\,$ is the total number of days
	- Find
		- $\min$ $\displaystyle\sum_{t\in N}x_t$
		- s.t.
			- $\displaystyle\sum_{i\in N}x_i-(x_{a}+x_{b})\geq d_t$  $\forall t\in N$
				- where $a=t+1$ $\rm mod$ $7$, $b=t+2$ $\rm mod$ $7$
			- $x_t\geq0$  $\forall t\in N$

![[Screenshot 2023-08-08 at 5.59.49 PM.png]]