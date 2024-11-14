# Лабораторная работа 3
Создаем дополнительные машины и проверяем их доступ в интернет ![image](https://github.com/user-attachments/assets/9d823120-3122-446f-acac-5946ef310a5d) командой ping (google.com)
проверяем командой ip a адрес ip: ![image](https://github.com/user-attachments/assets/5f5811f7-4713-460b-a5fe-c56db8e3be8a) у меня они имеют один и тот же адрес и я не знаю как это исправить
проверяем возможность пинговать ![image](https://github.com/user-attachments/assets/0230d528-ddcb-477b-852f-f4a75c22498a)
блокируем отправление пакетов второй машиной на указанный адрес при помощи команды sudo iptables -A OUTPUT -s 10.0.2.15 -j DROP
![image](https://github.com/user-attachments/assets/62d211ba-8184-4023-bb1d-a5f37075678c) итог







