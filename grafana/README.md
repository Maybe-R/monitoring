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

<img width="2425" height="1384" alt="image" src="https://github.com/user-attachments/assets/6fc373fd-520d-4ba0-9c65-d7cd84332fd6" />

3. количество свободной оперативной памяти;
   
<img width="2507" height="1367" alt="image" src="https://github.com/user-attachments/assets/dfa1d5b6-91c9-41e9-acfa-0a130ee3df39" />

4. количество места на файловой системе

<img width="2359" height="1423" alt="image" src="https://github.com/user-attachments/assets/fb458ade-4e7f-4bcc-b062-2f4dc4a46491" />

## Задание №3

Создайте для каждой Dashboard подходящее правило alert — можно обратиться к первой лекции в блоке «Мониторинг».
В качестве решения задания приведите скриншот вашей итоговой Dashboard.

1. утилизация CPU для nodeexporter
<img width="1786" height="1410" alt="image" src="https://github.com/user-attachments/assets/6b0d112b-8385-4748-8054-8b163e72c0c7" />

<img width="2447" height="1521" alt="image" src="https://github.com/user-attachments/assets/523f26e6-a45e-48f7-8bbe-00cdb42fafb6" />

2. CPULA 1/5/15

<img width="2335" height="1417" alt="image" src="https://github.com/user-attachments/assets/99bbb343-c4bb-4e6d-8e79-549d504ef657" />

<img width="2052" height="1495" alt="image" src="https://github.com/user-attachments/assets/a5a7c6a1-72cd-4b38-8292-9fd997c79207" />

3. количество свободной оперативной памяти;

<img width="2217" height="1412" alt="image" src="https://github.com/user-attachments/assets/03e9ec36-4129-49a4-8224-5cde96343047" />

<img width="2358" height="1480" alt="image" src="https://github.com/user-attachments/assets/5afa1191-5198-413b-ad26-533f7ba16add" />

4. количество места на файловой системе

<img width="2200" height="1161" alt="image" src="https://github.com/user-attachments/assets/3e1103cd-e354-41d2-a224-9ec6caefbdee" />

<img width="1581" height="965" alt="image" src="https://github.com/user-attachments/assets/66517e9d-b025-4892-ac40-30198c21fcc6" />


<img width="2372" height="1321" alt="image" src="https://github.com/user-attachments/assets/38fdaa25-2c71-4a3d-92bf-51cd934b278f" />



## Задание №4
Сохраните ваш Dashboard.Для этого перейдите в настройки Dashboard, выберите в боковом меню «JSON MODEL». Далее скопируйте отображаемое json-содержимое в отдельный файл и сохраните его.
В качестве решения задания приведите листинг этого файла - https://github.com/Maybe-R/monitoring/blob/main/grafana/model.json


