Тихонова Ксения, группа K33391

## Содержание
Лабораторная работа №1

## Порядок выполнения работы:
1. Реализовать клиентскую и серверную часть приложения. Клиент отсылает серверу
сообщение «Hello, server». Сообщение должно отразиться на стороне сервера.
Сервер в ответ отсылает клиенту сообщение «Hello, client». Сообщение должно
отобразиться у клиента.
Обязательно использовать библиотеку socket
Реализовать с помощью протокола UDP

2. Реализовать клиентскую и серверную часть приложения. Клиент запрашивает у
сервера выполнение математической операции, параметры, которые вводятся с
клавиатуры. Сервер обрабатывает полученные данные и возвращает результат
клиенту. Варианты:
a. Теорема Пифагора
b. Решение квадратного уравнения.
c. Поиск площади трапеции.
d. Поиск площади параллелограмма.
Вариант выбирается в соответствии с порядковым номером в журнале. Пятый
студент получает вариант 1 и т.д.
Обязательно использовать библиотеку socket
Реализовать с помощью протокола TCP

3. Реализовать серверную часть приложения. Клиент подключается к серверу. В ответ
клиент получает http-сообщение, содержащее html-страницу, которую сервер
подгружает из файла index.html.
Обязательно использовать библиотеку socket

4. Реализовать двухпользовательский или многопользовательский чат. Реализация
многопользовательского часа позволяет получить максимальное количество
баллов.
Обязательно использовать библиотеку socket. Реализовать с помощью протокола TCP – 100% баллов, с помощью UDP – 80%.
Обязательно использовать библиотеку threading.
Для реализации с помощью UDP, thearding использовать для получения
сообщений у клиента.
Для применения с TCP необходимо запускать клиентские подключения И прием
и отправку сообщений всем юзерам на сервере в потоках. Не забудьте сохранять юзеров,
чтобы потом отправлять им сообщения.

5. Необходимо написать простой web-сервер для обработки GET и POST http
запросов средствами Python и библиотеки socket.

    - Задание: сделать сервер, который может:
        - Принять и записать информацию о дисциплине и оценке по дисциплине.
        - Отдать информацию обо всех оценах по дсициплине в виде html-страницы.