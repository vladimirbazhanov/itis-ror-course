# Linux

- История появления операционной системы `GNU/Linux`;
- Место `GNU/Linux` в современном мире, влияние на развитие сети Интернет;
- Дистрибутивы ОС `GNU/Linux`: причины существования различных дистрибутивов, технические и идеологические различия;
- Установка ОС `GNU/Linux` в виртуальную машину (`VirtualBox`);
- Команды `man` и `info`;
- Основные приёмы работы в командной строке; Команды `pwd`, `ls`, `cat`, `less`, `cd`, `find`, `touch`, `mkdir`, `rm`, `rmdir`; Редактор `nano`;
- Пайпы и перенаправления;
- Поиск, установка и удаление ПО из репозиториев с помощью менеджера пакетов;
- Управление системой с помощью `systemd`
- Обзор и установка ПО, необходимого для разработки на Ruby:
	- `postgresql`
	- `readline`
	- `openssl`

# Postgresql

- Установка на `GNU/Linux`;
- Утилиты `psql`, `createuser`, `createdb`;
- Язык `SQL`: основы использования;
- Основы теории баз данных;
- Создание и удаление таблиц; Типы данных `Postgresql`;
- Операторы `SELECT`, `INSERT`, `DELETE`; Поиск с условиями;


# GIT

- О проблеме, которую призваны решать системы контроля версий;
- Основные понятия `GIT`: репозиторий, ветка, коммит;
- Командная работа над проектом с помощью `GIT`;

# Ruby

### Основы Ruby
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

### ООП в Ruby

- Всё - объект; Особенности реализации принципов ООП в Ruby;
- Объектный анализ как искусство;
- Классы и объекты: создание объектов, наследование, инкапсуляция, примеси (mixins);

### Ruby like a Pro

- Метапрограммирование: возможности интроспекции, вызов функции vs сигнал объекту, функции `send` и `public_send`;
- Создание кода в runtime, функция `define_method`;
- Конструкция `included`

### Ruby в функциональном стиле

- Немного о функциональном программировании: функции, чистота функции, неизменямость состояния;
- `Proc` и `lambda`-функции;
- ключевое слово `yield`, передача блока как аргумента функции;
- Итераторы;

# Web

- Протокол `HTTP(S)`; Виды (методы) запросов: `GET`, `POST`


# Ruby on Rails

- Краткая история и причины создания Ruby on Rails; Проблемы, которые Rails решает эффективно; Обзор возможностей и принципов: соглашение превыше конфигурации и упор на скорость разработки;
- Быстрый обзор возможностей Rails для создания прототипа новостного сайта (без углубления в детали);

### Rails и данные

- Основные возможности ActiveRecord: связь с БД, модели и миграции.
- Создание, поиск, удаление и изменение данных в БД с помощью моделей ActiveRecord;
- Валидация данных, callbacks и ассоциации;