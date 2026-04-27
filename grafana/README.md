# Домашнее задание к занятию 14 «Средство визуализации Grafana»

## Задание №1
1. Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.
   
<img width="1262" height="1081" alt="image" src="https://github.com/user-attachments/assets/27a26b17-4cdd-4bbc-a092-d562fbcf83c0" />

2. Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.

<img width="2483" height="1495" alt="image" src="https://github.com/user-attachments/assets/3e69630f-e249-4c42-a0ba-5d445c9aec0e" />
   
3. Подключите поднятый вами prometheus, как источник данных.
<img width="2028" height="1441" alt="image" src="https://github.com/user-attachments/assets/78dd077d-f472-4bda-bf23-95b438270d16" />

Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource. 

<img width="2071" height="816" alt="image" src="https://github.com/user-attachments/assets/708d49b4-caba-49bf-ab41-e87a923a61c3" />



## Задание №2

Создайте Dashboard и в ней создайте Panels:

1. утилизация CPU для nodeexporter (в процентах, 100-idle);

<img width="2327" height="1511" alt="image" src="https://github.com/user-attachments/assets/25dd35d8-2b5a-4e13-ac09-c9cdc9b086ed" />

2.CPULA 1/5/15;
количество свободной оперативной памяти;
количество места на файловой системе.
