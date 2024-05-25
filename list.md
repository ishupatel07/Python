 #list
>>> 
>>> tea_varities = ["black","green","oolong","white] 
  File "<stdin>", line 1
    tea_varities = ["black","green","oolong","white]
                                             ^
SyntaxError: unterminated string literal (detected at line 1)
>>> tea_varities = ["black","green","oolong","white"] 
>>> print(tea_varities) 
['black', 'green', 'oolong', 'white']
>>> print(tea_varities[1]) 
green
>>> print(tea_varities[-1]) 
white
>>> print(tea_varities[1:3]) 
['green', 'oolong']
>>> print(tea_varities[1:3:1]) 
['green', 'oolong']
>>> print(tea_varities[1:3:0]) 
Traceback (most recent call last):   
  File "<stdin>", line 1, in <module>
ValueError: slice step cannot be zero
>>> print(tea_varities[:@])    
  File "<stdin>", line 1   
    print(tea_varities[:@])
                        ^  
SyntaxError: invalid syntax
>>> print(tea_varities[:2]) 
['black', 'green']
>>> print(tea_varities[3:2]) 
[]
>>> print(tea_varities[2:])  
['oolong', 'white']
>>> print(tea_varities[3])  
white
>>> tea_varities = "Herbal"  
>>> tea_varities[3] = "Herbal" 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> tea_varities[3] = "Herbal"
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> tea_varities[3] = "Herbal"
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> tea_varities = "Herbal"   
>>> tea_varities = ["black","green","oolong","white"] 
>>> tea_varities[3] = "herbal"                       
>>> print(tea_varities) 
['black', 'green', 'oolong', 'herbal']
>>> tea_varities[1:2] = "lemon" 
>>> tea_varities
['black', 'l', 'e', 'm', 'o', 'n', 'oolong', 'herbal']
>>> tea_varities[1:2:0] = "lemon" 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: slice step cannot be zero
>>> tea_varities[1:2:1] = "lemon" 
>>> tea_varities
['black', 'l', 'e', 'm', 'o', 'n', 'e', 'm', 'o', 'n', 'oolong', 'herbal']
>>> tea_varities[1:2:0] = "lemon" 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: slice step cannot be zero
>>> tea_varities = ["black","green","oolong","white"]
>>> tea_varities[1:2]          
['green']
>>> tea_varities[1:2] = ["lemon"] 
>>> tea_varities                 
['black', 'lemon', 'oolong', 'white']
>>> tea_varities[1:3] = ["1",3]   
>>> tea_varities[1:3] = ["1",3]
>>> tea_varities
['black', '1', 3, 'white']
>>> tea_varities = ["black","green","oolong","white"]
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> tea_varities[1:1] 
[]
>>> tea_varities[1:1] = ["1","1"] 
>>> tea_varities                 
['black', '1', '1', 'green', 'oolong', 'white']
>>> tea_varities[1:3] = []     
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> for tea  in tea_varities
  File "<stdin>", line 1
    for tea  in tea_varities
                            ^
SyntaxError: expected ':'
>>> for tea  in tea_varities:
...     print(tea)
... 
black
green
oolong
white
>>> for tea  in tea_varities:
...     print(tea, end="-")
... 
black-green-oolong-white->>> for tea  in tea_varities: 
...     print(tea, end = "-") 
... 
black-green-oolong-white->>> 
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> if "oolong" in tea_varities:
...     print("i have oolong tea")
... 
i have oolong tea
>>> tea_varities.append("Oolong") 
>>> tea_varities       
['black', 'green', 'oolong', 'white', 'Oolong']
>>> if "oolong" in tea_varities:")
... if "oolong" in tea_varities:
  File "<stdin>", line 2
    if "oolong" in tea_varities:
    ^
IndentationError: expected an indented block after 'if' statement on line 1
>>> if "oolong" in tea_varities:
...     print("i have oolong tea")
... 
i have oolong tea
>>> tea_varities.pop()
'Oolong'
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> tea_varities.remove("green") 
>>> 
>>> 

>>> 
>>> tea_varities
['black', 'oolong', 'white']
>>> tea_varities               a")
['black', 'oolong', 'white']
>>> tea_varities.insert(1,"green") 
>>> tea_varities
['black', 'green', 'oolong', 'white']
>>> tea_varities_copy = tea_varities
>>> tea_varities_copy = tea_varities.copy()
>>> tea_varities_copy.append("lemon")      
>>> tea_varities_copy                      
['black', 'green', 'oolong', 'white', 'lemon']
>>> tea_varities      
['black', 'green', 'oolong', 'white']
>>> squared_nums = [] 
>>> 

>>> squared_nums = [x**2 for in range(10)] 
  File "<stdin>", line 1
    squared_nums = [x**2 for in range(10)]
                             ^^
SyntaxError: invalid syntax
>>> range(0,10)       
range(0, 10)
>>> range(0,10)
range(0, 10)
>>> print(range(0,10)) 
range(0, 10)
>>> y = range(0,10)
>>> y
range(0, 10)
>>> squared_nums = [x**2 for in range(10)]
  File "<stdin>", line 1
    squared_nums = [x**2 for in range(10)]
                             ^^
SyntaxError: invalid syntax
>>> squared_nums = [x**2 for x in range(10)] 
>>> squared_nums                            
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
>>> #list comprihansion 