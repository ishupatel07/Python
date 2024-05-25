>>> chai = "app" 
>>> chai
'app'
>>> print(chai) 
app 
>>> chai = "app 2" 
>>> chai[0]     
'a' 
>>> chai 
'app 2'
>>> chai[0:5] 
'app 2'
>>> chai[0:4] 
'app '
>>> chai[0:3] 
'app'
>>> chai[0:6] 
'app 2'
>>> chai[-1]  
'2' 
>>> num_list = "0123456789" 
>>> num_list[:] 
'0123456789'
>>> num_list[3:] 
'3456789'
>>> num_list[:7] 
'0123456'
>>> num_list[0:7:2] 
'0246'
>>> num_list[0:7:3] 
'036'
>>> num_list[0:7:5] 
'05'
>>> chai
'app 2'
>>> print(chai.)
  File "<stdin>", line 1
    print(chai.)
               ^
SyntaxError: invalid syntax
>>> #
>>> #unicode string
>>> 
>>> 
>>> 
>>> print(chai.lower()) 
app 2
>>> print(chai.upper()) 
APP 2
>>> print(chai)         
app 2
>>> chai = "         app              2        " 
>>> print(chai.trim()) 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'str' object has no attribute 'trim'. Did you mean: 'strip'?
>>> print(chai.strip()) 
app              2
>>> chai = "Lemoon"     
>>> print(chai.replace("Lemon", "Ginger")) 
Lemoon
>>> print(chai.replace("Lemon", "Ginger"))
Lemoon
>>> print(chai.replace("Lemon", "Ginger"))
Lemoon
>>> chai
'Lemoon'
>>> print(chai.replace("Lemon", "Ginger"))
Lemoon
>>> print(chai.replace("Lemoon", "Ginger")) 
Ginger
>>> chai = "1, 2, 3, 4"
>>> print(chai.split(,)) 
  File "<stdin>", line 1
    print(chai.split(,))
                     ^
SyntaxError: invalid syntax
>>> print(chai.split())  
['1,', '2,', '3,', '4']
>>> print(chai.split(", ")) 
['1', '2', '3', '4']
>>> chai = "123 3" 
>>> print(chai.find("3"))   
2
>>> print(chai.find("3"))) 
  File "<stdin>", line 1
    print(chai.find("3")))
                         ^
SyntaxError: unmatched ')'
>>> print(chai.find(3)))   
  File "<stdin>", line 1
    print(chai.find(3)))
                       ^
SyntaxError: unmatched ')'
>>> print(chai.find("3")) 
2
>>> print(chai.count("3")) 
2
>>> chai_type = "masala" 
>>> quantity = 2
>>> order = "I ordered {} cups of {} chai" 
>>> print(order.format(quantity, chai_type)) 
I ordered 2 cups of masala chai
>>>                                         
>>> 
>>> chai_variety = ["lemon", "masala", "ginger"]
>>> ["lemon", "masala", "ginger"] 
['lemon', 'masala', 'ginger']
>>> ["lemon", "masala", "ginger"]
['lemon', 'masala', 'ginger']
>>> chai_variety = ["lemon", "masala", "ginger"]
>>> chai_varity
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'chai_varity' is not defined. Did you mean: 'chai_variety'?
>>> chai_variety 
['lemon', 'masala', 'ginger']
>>> print("".join("chai_variety")) 
chai_variety
>>> print("".join(chai_variety))   
lemonmasalaginger
>>> print(" ".join(chai_variety)) 
lemon masala ginger
>>> type(chai_variety) 
<class 'list'>
>>> chai
'123 3'
>>> chai = "masala chai" 
>>> print(len(chai)) 
11
>>> chai
'masala chai'
>>> for letter in chai:
...     print(letter)
... 
m
a
s
a
l
a

c
h
a
i
>>> chai = "he said, "\masala chai is awesome\" " 
  File "<stdin>", line 1
    chai = "he said, "\masala chai is awesome\" "
                       ^
SyntaxError: unexpected character after line continuation character
>>> chai = "he said, \"masala chai is awesome\" " 
>>> chai = "he said, \"masala chai is awesome\" " 
>>> chai                                          
'he said, "masala chai is awesome" '
>>> chai = "masala\nCHAI" 
>>> chai
'masala\nCHAI'
>>> print(chai) 
masala
CHAI
>>> chai = r"Masala\nChai" 
>>> chai
'Masala\\nChai'
>>> print(chai) 
Masala\nChai
>>> chai = r"c:\user\pwd\
... 
  File "<stdin>", line 1
    chai = r"c:\user\pwd\
           ^
SyntaxError: unterminated string literal (detected at line 2)
>>> chai = r"c:\\user\\pwd\\ 
  File "<stdin>", line 1
    chai = r"c:\\user\\pwd\\
           ^
SyntaxError: unterminated string literal (detected at line 1)
>>> chai = r"c:\\user\\pwd\\"
>>> chai
'c:\\\\user\\\\pwd\\\\'
>>> chai = r"c:\\user\\pwd"   
>>> chai
'c:\\\\user\\\\pwd'
>>> print(chai) 
c:\\user\\pwd
>>> chai = 
  File "<stdin>", line 1
    chai =
           ^
SyntaxError: invalid syntax
>>> chai   
'c:\\\\user\\\\pwd'
>>> chai = "123" 
>>> print("123" in chai)  
True
>>>