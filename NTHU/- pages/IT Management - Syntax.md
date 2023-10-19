
Practice
- sample exam x2

```python
# -*- coding: utf8 -*-            # Unicode UTF-8
import numpy, pandas, matplotlib  # 考試不能用！！

int, float, str, tuple  # immutable
list, set, dict         # mutable

int(str) str(int) list(tuple) tuple(list) # change type
id(...)  # memory location

not and or  # logic operator 
!= ==       # value comparison
\           # stay in the same line
*           # unpacking (js ...)
```

```python
list = [0] * length
list[a : b+1]         # slice range(a, b+1), can omit
list[-1]              # last element

list2 = list1        -> list2 is list1      # alias
list2 = list1.copy() -> list2 is not list1  # copy
list2 = copy.deepcopy(list1)                # copy, deep
tupe2 = copy.deepcopy(tuple1)               # alias

len(list) sum(list) max(list) min(list)
not list # check empty
```

![[Screenshot 2023-08-15 at 2.22.03 PM.png]]

```python
str.split()
str.find("word", start_idx, end_idx)
str.replace("word1", "word2") str.strip(".txt")
"th" in str
ord("A") chr(65)  # ASCII / Unicode UTF-8

strstr = str * 2
str2 = str1 + "1"
tuple2 = tuple1 + (1,)  # append()
tuple2 = sorted(tuple1) # sort()

zip(tuple1, tuple2)  # 1xn => 2xn
```

```python
set = {"alpha", "beta", "gamma"}
"alpha" in set  # hashing, used for searching

set.add() set.remove
set1 | set2  # union
set1 & set2  # intersection
set1 - set2  # difference
set1 ^ set2  # symetric diff, (A | B) - (A & B)

dict = {"a":1, "b":2, "c":3}

dict["a"] if "a" in dict else "N/A"
dict.get("a", "N/A")
dict.setdefault("a", "create a new value if none")

dict.keys() dict.values()  # list 1xn
dict.items()               # list 2xn
```


```python
for i, item_i in enumerate(list):
    print(list[i], "=", item_i)

for key, value in dict.items():
    print(dict[key], "=", value)

out_list = list(map(lambda param: operation, arg_list))
```

```python
out = value1 if ... else value2

# call by assignment
def function(param1, param2):  # 參數
    return ret1, ret2  # immutable          (call by value)
	                     # mutable 不用 return (call by ref)

out1, out2 = function(arg1, arg2)  # 引數

exit()
```

```python
file_handler = open("file_path", "r/w/a", "utf-8")
  # r = read, w = write new, a = append to existing
  # r+ = read & write, rb/wb = binary file
for line in file_handler
    ...

file_handler.write(str + "\n")
file_handler.close()

with open("file_path", \
					"r/w/a", encoding = "utf-8") as file_handler:
    file_handler.write(str + "\n")

for ...:
    print("message", end=" ")  # print in 1 line

",".join(map(str, list))
print(f"There are a total of {var:(1)(2)(3)} chairs")
  # (1): space occupied
  # (2): float digit precision
  # (3): type. d = decimal/int, f = float, s = string
  # """: include ", \n
```

```python
try:
    ...
except Exception as message:
    print(message, type(message))

raise Exception("message")  # program terminates
```

![[Screenshot 2023-08-15 at 9.40.44 PM.png]]