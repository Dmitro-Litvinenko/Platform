# ***Проєкт "Бджілка"***

![Logo](/platform/app/assets/images/logo.svg)

## **Про нас**

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset she

---

## Посилання

- [Про нас](#про-нас)
- [API Документація](#api-документація) 
- [Діаграми](#діаграми)
    - [ER Діаграма](#er-діаграма)
- [Скрипти](#скрипти) 
    - [Скрипти завдань](#скрипти-завдань)
    - [Скрипти тестів](#скрипти-тестування) 
- [Встановлення та запуск](#встановлення-та-запуск)

---

# **API Документація**

| HTTP-метод | Шлях (URL)         | Дія                   |
|------------|--------------------|-----------------------|
| GET        | /                  | Головна сторінка      |
| GET, POST, DELETE | /clients/sign_in, /clients/sign_up, /clients/password/new | Авторизація(вхід), реєстрація, скидання пароля користувачів |
| GET, POST, PUT, PATCH, DELETE | /difficulties, /services, /urgencies, /comments, /statuses, /specializations, /positions, /addresses, /orders, /employees, /clients | Операції з ресурсами |
| GET        | /up                | Перевірка стану додатка |

---

# **Діаграми**

## ER Діаграма

![ER-diagram](/docs/ScreenOfDBFinal.png)

---

# **Скрипти**

## Скрипти завдань

- [parser_data.rake](/platform/lib/tasks/parse_data.rake) - Rake задача розпарсування

## Скрипти тестування

- [parse_task_test.rb](/platform/test/tasks/parse_task_test.rb) - Тест для Rake задачі розпарсування

---

# Встановлення та запуск

1. There are many variations of passages of Lorem Ipsum available.
    1. There are many variations of passages of Lorem Ipsum available.
    2. There are many variations of passages of Lorem Ipsum available.
2. There are many variations of passages of Lorem Ipsum available
    1. There are many variations of passages of Lorem Ipsum available
    2. There are many variations of passages of Lorem Ipsum available
    3. There are many variations of passages of Lorem Ipsum available
3. There are many variations of passages of Lorem Ipsum available