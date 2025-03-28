University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming)  
Year: 2024/2025  
Group: K34212  
Author: Elena Darovskikh  
Lab: Lab2  
Date of create: 27.03.2025  
Date of finished: 28.03.2025

## Лабораторная работа №2 "Конфигурация voip в среде Сisco packet tracer"

### Описание
Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены все узлы устройств. Предварительно удалить все предыдущие конфигурационные файлы на маршрутизаторах Cisco 2811, на коммутаторе Cisco catalyst 3560.

### Цель работы
Иизучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

### Ход работы 

### Часть 1

Собираем топологию согласно схеме.

![image](https://github.com/user-attachments/assets/62621e00-7f00-4aad-a2cc-b768d52f0c6d)


Задаем пароли для защиты маршрутизатора:

![image](https://github.com/user-attachments/assets/ce55db1a-b6cf-483d-a247-1e75dbfb8dc8)


Настраиваем интерфейс fa0/0:

![image](https://github.com/user-attachments/assets/15953d1e-3b11-4df4-8cc0-7f22008f6431)


Настраиваем DHCP сервер на маршрутизаторе Cisco 2811 и CallManager Express:

![image](https://github.com/user-attachments/assets/df4c4174-5f01-46a6-b47d-9b635286c7cf)


Настроим интерфейс управления коммутатором в сети VLAN через назначение диапазона портов:

![image](https://github.com/user-attachments/assets/8c0c5706-34e8-421a-b6da-121507ee6182)


Раздаем номера:

![image](https://github.com/user-attachments/assets/2b6c09b8-3bb0-4dc7-bd7b-4948c8e142fb)

Проверяем назначенные номера и ip адреса:

![image](https://github.com/user-attachments/assets/c245cf15-885e-42fd-ae33-df1db68b3531)


Проверяем связность устройств: 

![image](https://github.com/user-attachments/assets/8407b183-e18c-4f43-b96f-aa2041fd3b0c)
![image](https://github.com/user-attachments/assets/26a74968-f553-4454-a07c-02470fad6b18)
![image](https://github.com/user-attachments/assets/2a99ca74-4aa5-49b9-be5f-6fa1d8979224)



### Часть 2

Соберем топологию согласно схеме:

![image](https://github.com/user-attachments/assets/f6f706b2-0d93-40c0-b651-b335558323a5)


Создадим vlan и присваивоим им наименования, зададим маршрут по умолчанию, настроим интерфейс управления коммутатором в сети VLAN через
назначение диапазона портов:

![image](https://github.com/user-attachments/assets/ce491daf-e454-46b6-8ea2-8b20e631c499)

Настраиваем DHCP-сервер для передачи голоса и данных, а также настраиваем услуги телефони:

![image](https://github.com/user-attachments/assets/3c57dc3c-6c00-4473-88ae-6b48e54f0ded)


Присваиваем номера для всех IP-телефонов в сети:

![image](https://github.com/user-attachments/assets/09eca2a5-2fa6-4064-b7b9-47feae801a2e)


Проверим, что выполненяется корректно: 

![image](https://github.com/user-attachments/assets/208d7d01-e566-4f1b-90bd-6fc8ca1d4be5)
