Если нужно передать [[Tuple]] или много значений в функцию
[[python]]
def add_all(ЗВЁЗДОЧКАargs):  
    summary = 0  
    for num in args:  
        summary += num  
    return summary  
  
  
print(add_all(1, 2, 3))    
  
values = [1, 2, 3, 4, 5]  
other_values = [6, 7, 8, 9, 10]  
  
print(add_all(ЗВЁЗДОЧКАvalues)) 
print(add_all(ЗВЁЗДОЧКАvalues, ЗВЁЗДОЧКАother_values))

[[python]]

