# HotelWebApp
Project JD1 IT Academy


Чтобы накатать базу нужно выполнить файл HotelSystem.sql 
Она добавит таблицы для работы БД и минимальный набор номеров для демонстрации работы. 
Пользователя можно создать своего и проверить все возможности, включая повторный заход с оплаченным заказом. 
В приложение заложена возможность входа под admin, но к сожелению не реализована(пока) 
отдельная страница со специальными возможностями (страница менеджера), 
где к примеру будет возможность сформировать отчет о заселении и выселении пользователей на заданные даты. 
Повторюсь, это пока..

Нужно проверить также файл mysql.properties по пути HotelSystem\WEB-INF\classes\mysql.properties и 
поправить там настройки пароля к БД в моем случае там: user=root password=1234.
Итак

1.Накатываем базу - HotelSystem.sql
2.Вписываем правильный пароль к БД.
3.Закидываем папку HotelSystem в webapps Tomcat.
4.Запускаем сервер и переходим в браузере ../HotelSystem (где .. localhost + порт(по умолчанию:8080))
5.Пользуемся)