# project_module4_final
Данный проект был написан на курсе JavaRush, целью проекта было закрепление полученных знаний о Hibernate. Проект реализует один из возможных вариатов устранения проблемы тормозящего запроса к БД.  
Условие задачи - есть реляционная БД MySQL со схемой (страна-город, язык по стране) и есть частый запрос города, который тормозит. 
Решение – вынести все данные, которые запрашиваются часто, в Redis.
MySQL сервер и Redis сервер запускаются как докер-контейнеры. Перед запуском приложения необходимо выполнить скрипт init.sql для добавления данных.

В проекте использовались следующие технологии: Hibernate, MySQL, Redis, Docker.
