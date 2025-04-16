[[json]]
[[python]]

import json

book = {  
    'title': '1984',  
    'author': 'George Orwell',  
    'isbn': '978-0451524935',  
    'uuid': 'a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11',  
}

Конверт в json

json_string = json.dumps(book) 

Это получится строка {"title": "1984", "author": "George Orwell", "isbn": "978-0451524935", "uuid": "a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11"}

И обратно

string = json.loads(json_string)

Это [[Dictionary]] как изначально