# Wildberries-L0

Сервис принимает заказы от брокера сообщений NATS-Streaming в формате JSON, 
полученные данные пишет в БД (PostgreSQL) и в кэш (in memory).
HTTP-сервер выдает данные по id из кэша.

# Запустить сервер:
make

# Отправить с помощью NATS-Streaming сообщение серверу:
make example

## Сервер предоставляет интерфейс из браузера

Вводим ID заказа:

![Иллюстрация к проекту](https://github.com/Ccaswell42/screenshots/blob/main/WB_L0/search.png)


Получаем ответ:

![Иллюстрация к проекту](https://github.com/Ccaswell42/screenshots/blob/main/WB_L0/response.png)
