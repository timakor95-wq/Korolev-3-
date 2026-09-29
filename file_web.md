Web3
Метод: GET
Статус: 304
Тип: Document

WEB4
коментариев вернулось:5
postId равно 5:  у всех
web5
обьектов ровно 3:да
id:1
id:2
id:3
web6
сравнение: одинаковые 5
параметр postid:номерация страницы
web7
количество обьектов: 2
количество обьектов: 7
гипотиза: _limit выдаёт максимальне количество возращяемых строк
web8

сcылка: https://jsonplaceholder.typicode.com/comments?postId=7&_limit=4
схема: https
порт:443
ПУТЬ:comments
Query:postId=7&,limit=4

сcылка: http://localhost:8080/tasks?page=2&sort=date
схема: http
порт: 8080
ПУТЬ: tasks
Query:sort=date

сcылка: https://api.example.com:3000/users/42/posts?status=active
схема: https
порт: 3000
ПУТЬ: users/42
Query:status=active

Web9
id:/users/2/posts
11,12,13,14,15,16,17,18,19,20
id:/posts?userId=2
11,12,13,14,15,16,17,18,19,20

web10
статус: /users/1 равен 200
Статус: /usrs/11 равен 404
Статус: /users/1?foo=bar равен 200
На сервере не существует 11 пользователя т.к. выдает ошибку 404

web11
Значение загаловка Content-Type: application/json; charset=utf-8
Значение загаловка Content-Length: 1847
B DevTools Content-Type у HTML-страницы и у JSON-ответа они одинаковы

web12
Первя страница /todos?_Limit=5&_page=1 пришло 5 объектов
Вторая страница /todos?_1imit=5&_page=2 пришло 5 объектов
Id первой страницы: 1
Id второй страницы: 6
Параметр _page используется для указания номера страницы прит постраничной обработке данных

