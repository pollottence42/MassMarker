[[python]]

person = {
	"name" = "John",
	"age" = 21,
}

person["job"] = "Engineer"

person["city"] -- выдаст ошибку
person.Get("city") -- выдаст none
person.Get("city", "New-York") -- выдаст НьюЙорк

for p in person:
	print(person[p])

Но лучше

for item in person.items():
	print(item)

Выдаст кортеж tuple(name, John)
Значит нужно

for item in person.items():
	key, value = item
	print(value)

А короче всего

for key, value in person.item():
	print(key)

Но можно не мучать себя и писать
```
for value in person.values():
	print(value)
```