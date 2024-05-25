>>> # dictionary
>>> 
>>> 
>>> chai_types = {"Masala" : "Spicy", "Ginger" : "Zesty", "Green": "Mild"} 
>>> chai_types                                                            
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Mild'}
>>> chai_types["Masala"] 
'Spicy'
>>> print(chai_types["Masala"]) 
Spicy
>>> print(chai_types["Masalaa"]) 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'Masalaa'
>>> chai_types                   
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Mild'}
>>> chai_types["Green"] = "Fresh"
>>> 
>>> chai_types
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Fresh'}
>>>     
>>> 
>>> chai_types
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Fresh'}
>>> for chai in chai_types
  File "<stdin>", line 1
    for chai in chai_types
                          ^
SyntaxError: expected ':'
>>> for chai in chai_types:
...     print(chai)
... 
Masala
Ginger
Green
>>> for chai in chai_types:
...     print(chai, chai_types[chai])
... 
... 
Masala Spicy
Ginger Zesty
Green Fresh
>>>
>>> for chai in chai_types:
...  
  File "<stdin>", line 2

    ^
IndentationError: expected an indented block after 'for' statement on line 1
>>> for key, values in chai_types.items():
...     print(key, values)
... 
Masala Spicy
Ginger Zesty
Green Fresh
>>> if "Masala" in chai_types:
...     print("I have masala chai")
... 
I have masala chai
>>> print(len(chai_types)) 
3
>>> chai_types             
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Fresh'}
>>> chai_types["Earl Grey"] = "Citrus"
>>> chai_types                        
{'Masala': 'Spicy', 'Ginger': 'Zesty', 'Green': 'Fresh', 'Earl Grey': 'Citrus'}
>>> chai_types.pop("Ginger") 
'Zesty'
>>> chai_types.popitem()    
('Earl Grey', 'Citrus')
>>>
>>> del chai_types["Green"]
>>> chai_types              
{'Masala': 'Spicy'}
>>> chai_types_copy = chai_types.copy()
>>> tea_shop {                         
  File "<stdin>", line 1
    tea_shop {
             ^
SyntaxError: invalid syntax
>>> tea_shop = {
... "chai" : {"Masala" : "Spicy", "Ginger" : "Zesty"},
... "tea" : {"Green" : "Mild", "Black" : "Strong"} 
... }
>>> tea_shop
{'chai': {'Masala': 'Spicy', 'Ginger': 'Zesty'}, 'tea': {'Green': 'Mild', 'Black': 'Strong'}}
>>> tea_shop["chai"] 
{'Masala': 'Spicy', 'Ginger': 'Zesty'}
>>> tea_shop["chai"]["Ginger"] 
'Zesty'
>>> squared_num = {x:x**2 for x in range(6)}                                                   
>>> sqared_num
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'sqared_num' is not defined. Did you mean: 'squared_num'?
>>> squared_num 
{0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
>>> squared_num.clear()
>>> squared_num
{}
>>> keys = ["Masala", "Ginger", "Lemon"] 
>>> keys
['Masala', 'Ginger', 'Lemon']
>>> default_value = "Delicious" 
>>> new_dict = dict.fromkeys(keys, default_value)
>>> new_dict
{'Masala': 'Delicious', 'Ginger': 'Delicious', 'Lemon': 'Delicious'}
>>> new_dict = dict.fromkeys(keys, keys)
>>> new_dict
{'Masala': ['Masala', 'Ginger', 'Lemon'], 'Ginger': ['Masala', 'Ginger', 'Lemon'], 'Lemon': ['Masala', 'Ginger', 'Lemon']}
>>>