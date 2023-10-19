
![[Screenshot 2023-08-31 at 12.32.36 AM.png|300]]|![[Screenshot 2023-08-31 at 12.32.01 AM.png|350]]

BA
- Parameter Estimation
	- Descriptive:  Statistics
	- Predictive:   Machine Learning
- Decision Making
	- Prescriptive: Mathematical Programming

Note
- pseudocode => code
- conceptual model => mathematical model

Problem: Facility & Customer Service

Index Set
- $i\in I$:  candidate customer
- $j\in J$:  candidate site (facility)
- $k\in K$:  candidate scale level (facility)
Variables
- $x_{jk}\in\{0,\,1\}$:  facility site-scale decision
- $y_{ij}\in\{0,\,1\}$:  customer-site service decision
- $w_j\in\mathbb{R}^+$:   engineer-site employment decision
Parameters
- $a_{ij}\in\{0,\,1\}$:  customer-site service possibility
- $m_{jk}\in\mathbb{R}^+$:  engineer-site-scale hosting capacity
              (same scale, diff city => diff capacity)
- $h_i\in\mathbb{R}^+$:  customer service-hour demand
- $s\in\mathbb{R}^+$:  engineer service-hour capacity
=
- $f_{jk}\in\mathbb{R}^+$:  rent for site-scale
- $d_{ij}\in\mathbb{R}^+$:  customer-site service cost per 1 hour/engineer
- $c_j\in\mathbb{R}^+$:  engineer-site hosting cost

Objective Function
- $\min$
	- office rent:  $\displaystyle\sum_{j\in J}\sum_{k\in K}f_{jk}\,x_{jk}$
	- service cost:  $\displaystyle\sum_{i\in I}\sum_{j\in J}d_{ij}\,h_i\,y_{ij}$
	- hosting cost:  $\displaystyle\sum_{j\in J}c_{j}\,w_j$
Constraints
- facility site
	- only be built with 1 scale:  $\displaystyle\sum_{k\in K}x_{jk}\leq1\;\;\;\forall{j\in J}$
- customer-site
	- must be served by 1 avail site:  $\displaystyle\sum_{j\in J}a_{ij}\,y_{ij}=1$  $\forall{i\in I}$
	- only be served by built site:  $y_{ij}\leq\displaystyle\sum_{k\in K}x_{jk}$  $\forall{i\in I},\;{j\in J}$
- engineer-site-scale
	- limited hosting capacity:  $w_j\leq\displaystyle\sum_{k\in K}m_{jk}\,x_{jk}$  $\forall{j\in J}$
- customer-engineer
	- must satisfy service demand:  $s\,w_{j}\geq\displaystyle\sum_{i\in I}h_i\,y_{ij}$  $\forall{j\in J}$

Greedy
- evaluation
	- set site: each customers $\geq$ 1 built + avail site
	- set customer: closest built site w. enough capacity
	- set engineer: satisfy the demand
- step
	- start with "naive $fs$"
	- step-wise adjustment on $fs$
	- select "$fs$ with largest improvement"
	- repeat, until no better $fs$