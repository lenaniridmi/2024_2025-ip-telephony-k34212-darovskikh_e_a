University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming)  
Year: 2024/2025  
Group: K34212  
Author: Elena Darovskikh  
Lab: Lab3  
Date of create: 10.04.2025  
Date of finished: 11.04.2025

# Лабораторная работа №3 "Использование Asterisk в качестве SIP proxy"

## Цель работы

Изучить программный комплекс Asterisk. Настройка Asterisk для локальных звонков.

## Задание

1. Установить систему server.
   
2. Установить Asterisk.
   
3. Установить soft телефон на рабочую станцию.
   
4. Настроить SIP каналы.

5. Подключиться к SIP каналам soft телефона.

6. Сделать тестовый звонок
   
## Ход выполнения работы 

### Asterisk

Устанавливаем Asterisk

![image](https://github.com/user-attachments/assets/c19b1942-0fa8-4ead-837b-b9761c9b8fc3)

Редактируем файлы конфигурации
`sip.conf` и `extensions.conf`

![image](https://github.com/user-attachments/assets/bcc47a1c-8335-45ec-9f03-2c309e6a39e2)

![image](https://github.com/user-attachments/assets/3e3fa8fd-6a1d-4262-b01f-aa2fa8d5630a)

Проверяем, что всё работает

![image](https://github.com/user-attachments/assets/efee5301-0ea7-4840-8ebb-38a1c943b601)

### Zoiper

Скачиваем ZoiPer5 и распаковываем его

![image](https://github.com/user-attachments/assets/95ce9693-3ad6-4932-af46-792e404fd450)

Заходим в приложение

![image](https://github.com/user-attachments/assets/61ac2d51-2657-449f-ac3c-46c2ee29027b)

Устанавливаем утилиту wine

`sudo apt-get install -y wine32`

Проверяем корректное отображение портов

`sip show peers`

Проверяем звонок

![image](https://github.com/user-attachments/assets/a92bf14f-622e-4f65-bfea-ec076f6374c6)
