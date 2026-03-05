СИСТЕМНЫЕ ТРЕБОВАНИЯ
OpenServer (версия 5.4 или выше)
PHP 8.0 или выше
MySQL 5.7 или выше
Веб-браузер (Chrome, Firefox, Edge)
УСТАНОВКА
2.1. Скопируйте папку проекта в директорию:
C:\OpenServer\home\timka.local\

2.2. Запустите OpenServer.

2.3. Создайте базу данных:

Откройте phpMyAdmin: http://localhost/phpmyadmin
Создайте БД с именем device_db
Импортируйте дамп из файла:
database/device_db.sql
НАСТРОЙКА ПОДКЛЮЧЕНИЯ К БД
Файл: backend/config/database.php

Настройки по умолчанию:

$host = "localhost";
$db_name = "device_db";
$username = "root";
$password = "";
ДОСТУП К САЙТУ
Главная страница:
http://timka.local/backend/index.php

(если проект лежит прямо в C:\OpenServer\home\timka.local\)

УЧЕТНЫЕ ЗАПИСИ ДЛЯ ВХОДА
Администратор:

Логин: admin@volunteers.grodno
Пароль: password123

Тестовый пользователь(клиент):

Логин jvcsj@gmail.com
Пароль UvYwsW2X26D6HLJ