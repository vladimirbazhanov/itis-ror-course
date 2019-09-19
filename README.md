# Разработка Web-приложений на Ruby on Rails

### Обзор курса

- Темы:
	- Обзор модулей и тем, из которых состоит курс, пояснение необходимости их присутствия в курсе;
	- Обзор целей курса, обзор навыков, которые будут получены в процессе изучения курса, пояснение необходимости их получения для эффективной разработки Web-приложений на Ruby;
	- Обзор ожидаемых результатов по окончании прохождения курса;
	- Курс -> Практика -> Стажировка -> Работа в компании Flatstack;

### [GNU/Linux](GNU-LINUX.md)

### SQL / Postgresql

- Темы:
	- Язык `SQL`: основные идеи, синтаксис, основные операции;
	- Основы теории баз данных;
	- Установка СУБД Postgresql в Debian-based дистрибутивах `GNU/Linux`;
	- Утилиты `psql`, `createuser`, `createdb`;
	- Создание и удаление таблиц; Типы данных `Postgresql`;
	- Операторы `SELECT`, `INSERT`, `DELETE`; Поиск с условиями;
	- Операторы `LIMIT` и `OFFSET`;
	- Оператор `JOIN`; Сложные выборки данных из нескольких таблиц;
	- Оператор `HAVING`;
- Задания:
	- Разработать базу данных, содержащую следующие сущности:
		-	пользователь (имя, фамилия, адрес email, номер телефона, роль, дата/время создания)
		- статья (название, URL, текст, дата/время создания, количество просмотров)
		- фотография (название, URL, описание)
		- комментарий (текст, автор, комментируемая сущность (пользователь, фотография или статья))
	- Наполнить БД тестовыми (случайными) данными.
	- Разработать запросы:
		- Выбор пользователей, не создавших ни одной статьи.
		- Выбор пользователей, не создавших ни одного комментария к фото.
		- Выбор 10 наиболее комментируемых фото.
		- Выбор 10 наиболее комментируемых статей и фото.
		- Все комментарии пользователей, не создавших ни одной статьи.
		- Все комментарии пользователей, загрузивших более 10 фотографий.
		- Все статьи, авторы которых загружали фотографии в текущем месяце.
		- Все статьи, авторы которых создавали статьи в прошлом месяце.

### GIT

- Темы:
	- О проблеме, которую призваны решать системы контроля версий;
	- Основные понятия `GIT`: репозиторий, ветка, коммит;
	- Командная работа над проектом с помощью `GIT`;
- Задания:
	- Создать аккаунт на Github;
	- Создать репозиторий для хранения кода практических заданий, ссылку на репозиторий прислать преподавателю;
	- Настроить доступ в репозиторий по SSH;
	- Добавить в репозиторий код, созданный в предыдущих практических заданиях.
	
### Ruby

- Обзор языка программирования `Ruby`, отличия от других современных языков программирования, используемых для разработки Web-приложений;
- Установка на `GNU/Linux`; Способы установки нескольких версий интерпретатора; Утилита `rbenv`;
- Настройка рабочей среды для продуктивной разработки, использование редактора `VS Code`;
- Утилита `irb`, использование интерактивного интерпретатора;
- Алфавит языка, синтаксис, семантика, зарезервированные слова;
- Соглашение об именовании переменных;
- Структура программы на Ruby;
- Типы данных: `Integer`, `Float`, `String`, `Array`, `Hash`, `Symbol`;
- Управляющие конструкции: `if`, `case`, `while`, `until`;
- Модули и функции: организация исходного кода;
- Обработка ошибок (исключений);
- Всё - объект; Особенности реализации принципов ООП в Ruby;
- Объектный анализ как искусство;
- Классы и объекты: создание объектов, наследование, инкапсуляция, примеси (mixins);
- Метапрограммирование: возможности интроспекции, вызов функции vs сигнал объекту, функции `send` и `public_send`;
- Создание кода в runtime, функция `define_method`;
- Конструкция `included`
- Немного о функциональном программировании: функции, чистота функции, неизменямость состояния;
- `Proc` и `lambda`-функции;
- ключевое слово `yield`, передача блока как аргумента функции;
- Итераторы;

### HTTP

- Краткая история сети Интернет; Гипертекст и протокол `HTTP`.
- Протокол `HTTP`; Виды (методы) запросов: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`.
- Передача дополнительных данных
- `HTTPS`: Безопасность, сертификаты и шифрование;

### Sinatra

- Создание небольшого web-приложения на Ruby и Sinatra;

### Ruby on Rails: Basics

- Краткая история и причины создания Ruby on Rails;
- Проблемы, которые Rails решает эффективно;
- Обзор возможностей и принципов: соглашение превыше конфигурации и упор на скорость разработки;
- Быстрый обзор возможностей Rails для создания прототипа новостного сайта (без углубления в детали);
- Жизненный цикл запроса в Rails; CRUD;
- Модели, представления и контроллеры - отделение данных от кода.
- Основные возможности ActiveRecord: связь с БД, модели и миграции.
- Создание, поиск, удаление и изменение данных в БД с помощью моделей ActiveRecord;
- Валидация данных, callbacks и ассоциации;
- Контроллеры: подготовка данных.
- Представления: шаблонизаторы erb и slim
- Библиотека ActionView: функции для генерирования тегов: `link_to`, `form_tag`, `form_for`, `image_tag`
- Библиотека ActionView: создание форм.

### TDD: Test Driven Development

- Тестирование Ruby и Rails приложений, библиотека RSpec.
- RSpec + Capybara.
- Test Driven Development

### Ruby on Rails: Pro

- Паттерн "Декоратор": библиотека Draper
- Паттерн "Интерактор": библиотека Interactor
- Паттерн "PolicyObject": библиотека Pundit
- Фоновые задачи, создание и управление очередями. Сервис Sidekiq.
- Сервисы мониторинга ошибок. Сервис Rollbar.

### API server with Rails

- Создание API-only web-приложений на Ruby on Rails.
- Библиотека ActiveModelSerializers
- Rails и REST API.
- Rails и JSON API.
- Тестирование API-only web-приложений на Ruby on Rails
- Документирование API-only web-приложений на Ruby on Rails

### Front-end: Webpacker + React.js

- Библиотека Webpacker: Поддержка ES6 в Rails.
- Создание React.js компонентов, взаимодействующих с приложением через API.
