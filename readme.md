# NoteBookProject
Проект Записная книжка

Технологии проекта
* Maven 3;
* Tomcat8;
* Spring;
* Hibernate;
* MySQL. 

#### CRUD(create, read, update, delete).
Приложение позволяет создавать/добавлять записи в БД, изменять и удалять их. Также есть простейшая фильтрация по дате.

**MYSQL таблица**

* `id` INT(8) NOT NULL AUTO_INCREMENT,
* `message` VARCHAR(100) NOT NULL,
* `date` TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP,
* `done` BIT(1) NOT NULL DEFAULT b'0',

Для frontend части использованы thymeleaf, bootstrap

Для запуска необходимо открыть в IDEA, запустить MYSQL server, в properties прописать логин и пароль для доступа к БД, выполнить скрипт для наполнения БД информацией и запустить.
