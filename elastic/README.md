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

Проверяем интерфейс kibana:

<img width="2509" height="1527" alt="image" src="https://github.com/user-attachments/assets/c992049c-917c-422a-8994-523a2a639943" />

Добавим паттерн и проверим связку:

<img width="1351" height="683" alt="image" src="https://github.com/user-attachments/assets/0fc1e4f2-4469-4dfd-bb3d-817f68568642" />

<img width="1909" height="1001" alt="image" src="https://github.com/user-attachments/assets/4818bd90-66b1-4344-8d9b-3f166e743b96" />

Использовала директорию help при развертывании.

Задание 2
Перейдите в меню создания index-patterns в kibana и создайте несколько index-patterns из имеющихся.

Перейдите в меню просмотра логов в kibana (Discover) и самостоятельно изучите, как отображаются логи и как производить поиск по логам.

В манифесте директории help также приведенно dummy-приложение, которое генерирует рандомные события в stdout-контейнера. Эти логи должны порождать индекс logstash-* в elasticsearch. Если этого индекса нет — воспользуйтесь советами и источниками из раздела «Дополнительные ссылки» этого задания.

Создаем паттерн logstash-*:

<img width="1882" height="978" alt="image" src="https://github.com/user-attachments/assets/d2f7c43b-89af-4a93-b7e4-0691c747abaa" />

<img width="1925" height="1016" alt="image" src="https://github.com/user-attachments/assets/014c6310-3700-4945-a8d4-325111b4514b" />





