Метод для [[Dictionary]]

person = {  
    "city": "New York",  
    "age": 30,  
    "name": "John",  
}  
additional_person_info = {  
    "job": "Engineer",  
    "married": True,  
    "city": "London"  
}  
person.update(additional_person_info)

Так же можно записать как

person | additional_person_info

[[python]]