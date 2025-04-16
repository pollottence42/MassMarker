Если нужно именованные значения или [[Dictionary]] передать в функцию
[[python]]

def introduce(ДВЕЗВЁЗДОЧКИkwargs):  
    for key, value in kwargs.items():  
        print(key)  
        print(value)  
  
  
introduce(name="John", age=30, city="New York")  
  
person = {  
    "city": "New York",  
    "age": 30,  
    "name": "John",  
}  
  
introduce(ДВЕЗВЁЗДОЧКИperson)