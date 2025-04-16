Как list Но не меняется

user_roles = ("admin", "editor", "viewer")

role_1, role_2, role_3 = user_roles
(Распаковка для ровно такого же числа элементов)
Или
role_1, role_2, _ = user_roles
[[python]]

Если кортеж из одного элемента то нужно запятую
roles = ("admin",)

