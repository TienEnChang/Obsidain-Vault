
Note
- pseudo code (文字邏輯 no 變數)
  ![[Screenshot 2023-08-15 at 4.03.23 PM.png]]
- module decoupling
- variable into dictionary
- function wishing
  (假設有人實現，先寫架構) (divide & conquer, lesser error)
	- which is param?
	- which will return?
	- algorithm
		- find_service_plan()
			- find_total()
			- send_one_shuttle()
- debugging
	- type: syntax, logic
	- method
		- scaffolding: print()
		- debugging function: 執行效率下降, not used in production

===

Inventory: a "buffer" between supply & demand

the (Q, R) policy
```python
if I < R: I += Q
```

the (s, S) policy
```python
if I < s: I = S
```
