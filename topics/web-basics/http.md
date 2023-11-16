# Протокол HTTP

## Теория

- [Обзор протокола](https://developer.mozilla.org/ru/docs/Web/HTTP/Overview),
- Основные методы:
  - [GET](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/GET) - получить данные,
  - [POST](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/POST) - отправить данные, к примеру для создания нового элемента (каждый новый вызод будет создавать новый объект),
  - [PUT](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/PUT) - отправить данные, к примеру для изменения существующего объекта (повторный вызов не изменит текущее состояние),
  - [DELETE](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/DELETE) - удаление объекта,
  - [OPTIONS](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/OPTIONS) - проверяем возможно ли использование метода POST.

- [Использование telnet для HTTP-запросов](https://ru.hexlet.io/courses/http_protocol/lessons/http_1_0/theory_unit)
- [Использование Postman для отправки запросов](https://timeweb.com/ru/community/articles/kak-polzovatsya-postman)

## Практика

- Создать тестовый веб-сервер (подробнее [здесь](../back-end/exercises/simple-web-server-with-express.md))
- Используя telnet и Postman попробовать отправлять GET-запросы (подробнее [здесь](../back-end/exercises/send-requests-telnet-and-postman.md))

## Домашнее задание

- Реализовать метод POST в простейшем сервере (можно использовать этот [пример реализации POST в Express.js](https://expressjs.com/ru/starter/basic-routing.html))
- Выполнить обращение к новому методу из telnet,
- Аналогично для Postman.