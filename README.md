# A-Book - 2019
Addres Book - Online Contact Manager

## Описание проекта

Проект реализуется в рамках стажировки Geekbrains 24.08 - 12.10 2019 года.

Проект предоставляет REST API к онлайн базе контактов, кроме этого в составе проекта находится собственные клиентский и административные модули.

## High Level Design
Верстка и логика на фронтэнде - SPA, ReactJS  
Архитектура фронтэнда - модульная  
Framework для верстки - bootstrap  
Бэкэнд - NodeJS  
База Данных - MySQL

## Функциональные требования
1.	Личный кабинет с карточками контактов c авторизацией
2.	Создание новых карточек контактов
3.	Изменение (модификация, редактирование) контакта
4.	Удаление существующих контактов
5.	Поиск текущих контактов (по любому полю/части поля)
6.	Работа с выборкой (сортировка по критериям)

## Нефункциональные требования
1.	Проверка данных, вводимых в соответствующие поля (напр., регулярными выражениями что телефон это телефон, почта это почта)
2.	Возможность авторизации пользователя
3.	Страны, населенные пункты - реализовать в виде отдельных справочников, что бы пользователь мог их выбирать готовые / найти нормальный API
4.  UI и backend независимы, работа через интерфейсы
5.  Предусмотреть связи между контактами (группы)
6.  Проверка повторяемости вводимых контактов (если уже есть контакт с таким именем или номером телефона, надо проверить и вывести предупреждение)


## Модели данных/Сущности
### Страна
    Описание находится /server/controllers/countryController.js
### Населенный пункт/Город
    Описание находится /server/controllers/cityController.js
### Сотовый телефон
    Описание находится /server/controllers/phoneController.js
### Адрес электронной почты
    Описание находится /server/controllers/emailController.js
### Сайт
    Описание находится /server/controllers/wwwController.js
### Коммуникаторы
    Описание находится /server/controllers/imController.js
### Персона
    Описание находится /server/controllers/personController.js
### Контакт
    Описание находится /server/controllers/contactController.js
### Пользователь
    Описание находится /server/controllers/userController.js
### Организация
    Описание находится /server/controllers/orgController.js



## Роли
1. Куратор - Шиков Олег
2. Product Owner / BackEnd - Танкибаев Абзал(https://github.com/AbzalT)
3. FrontEnd - Бородин Никита(https://github.com/nikitabor1)
4. FrontEnd / Designer - Сезько Яна(https://github.com/YanaSezko)
5. FrontEnd / JS - Кадискалиев Бауржан(https://github.com/BaurzhanKadis)
6. FrontEnd - Гладилин Андрей(https://github.com/brdx1)
7. FrontEnd - Головей Илья(https://github.com/IlGoloviy)
8. BackEnd -  Хокконен Марина(https://github.com/sunnyima)
