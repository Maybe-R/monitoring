Домашнее задание к занятию 15 «Система сбора логов Elastic Stack»

Вам необходимо поднять в докере и связать между собой:

elasticsearch (hot и warm ноды);
logstash;
kibana;
filebeat.
Logstash следует сконфигурировать для приёма по tcp json-сообщений.

Filebeat следует сконфигурировать для отправки логов docker вашей системы в logstash.

В директории help находится манифест docker-compose и конфигурации filebeat/logstash для быстрого выполнения этого задания.

Поднимаем контейнеры:

<img width="691" height="164" alt="image" src="https://github.com/user-attachments/assets/bab81ceb-f7df-4434-8a54-2739e1a26437" />
