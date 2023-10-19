
Node Choosing Method
- Best Objective Value First
- Depth First (focused, faster to get the first "lower bound")

Custom Algorithm
- knapsack: greedy by "value/weight ratio"
- heuristic
	- rule-based
	- greedy:
		- start with "naive $fs$"
		- step-wise adjustment on $fs$
		- select "$fs$ with largest improvement"
		- repeat, until no better $fs$

Step
- linear relaxation
- branch & bound => candidate bfs, optimal bfs

![[Screenshot 2023-08-16 at 12.18.12 PM.png]]
![[Screenshot 2023-08-16 at 12.26.49 PM.png]]![[Screenshot 2023-08-16 at 12.35.10 PM.png]]