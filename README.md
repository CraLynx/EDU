<p align="center"><a target="_blank"><img src="https://github.com/CraLynx/EDU/blob/main/Logo/logo-site.png" width="400"></a></p>

## Об EduEncryption
Веб-приложения для обучения основным алгоритмам шифрования создана благодаря выпускной квалификационной работе.
В настоящий момент поиск информации в интернете очень время затратный и иногда можно встретить сайты с большим количеством ненужной информации, что приводит к пропаданию интереса в изучении данной науки. Также человек решивший начать изучать криптографию может пропустить азы, что поспособствует в непонимании изучения более сложных тем в криптографии.
Поэтому получение знания на сайте, где информация структурирована, «очищенна» от ненужной информации не только не охладит интерес и понизит время затратность, но и повысит квалификацию будущего специалиста. Также можно отметить, что имеющиеся на сайтах тесты, также повысят квалификацию будущих сотрудников.
   
   
   
## Как развернуть на локальном компьютере(Для администраторов)
## 1. Необходимые компоненты
- Среда разработки [PhpStorm](https://www.jetbrains.com/ru-ru/phpstorm/).
- Пакетны менеджер [Composer](https://getcomposer.org/).
- Фреймворк [Laravel 9.0](https://laravel.com/).
- Язык программирования [Php 8.1](https://www.php.net/).
- Файлы проекта сайта [EduEncryption](https://github.com/CraLynx/EDU).

## 2. Развертывание
После загрузки и установки всех необходимых компонентов, рекомендуется в корне проекта в папке public через командную строку выполнить следующую команду: php -S localhost:80 - запуск dev-сервера
Ниже представено выполнение команды.

<p align="center"><img src="https://github.com/CraLynx/EDU/blob/main/Logo/start_localhost.PNG" width="800"></p>

После этого будет запуститься сервер и будет доступна страница localhost/

## 3. Для полного функционирования проекта
Рекомендуется установить базу данных [MySQL](https://www.mysql.com/)  с определением таблиц для корректно работы веб-приложения

### Папки проекта Laravel:

- **./.env** - файл настроек
- **public/** - папка, в которую обычно "заходит" пользователь
- **routes/web.php** - здесь описываются маршруты сайта
-	**resources/views** - здесь хранятся html-страницы, описываемые с помощью шаблонизатора Blade
-	**databases/migrations** - здесь хранятся php-скрипты, описывающие таблицы в базе данных (миграции).
-	**config/app.php** - конфигурация приложения
-	**config/auth.php** - конфигурация аутентификации/авторизации
-	**app/Http/Controllers** - контроллеры (бизнес-логика приложения)
-	**app/Models** - модели (данные приложения)

### Архитектура проекта:
<p align="center"><img src="https://github.com/CraLynx/EDU/blob/main/Logo/architecture.png" width="700"></p>


