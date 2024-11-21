# Лабораторная работа 3
Создаем дополнительные машины и проверяем их доступ в интернет ![image](https://github.com/user-attachments/assets/5ee8c11a-1dc6-4f9c-8fcf-4e09a408af52) командой ping (google.com)
проверяем командой ip a адрес ip: ![image](https://github.com/user-attachments/assets/e62565fc-55ab-4631-9a9f-b3bbff2b125b)
проверяем возможность пинговать ![image](https://github.com/user-attachments/assets/0230d528-ddcb-477b-852f-f4a75c22498a)
блокируем получение пакетов третьей машиной с указанного адреса(второй машины) при помощи команды sudo iptables -A INTPUT -s 10.0.2.4 -j DROP
итог: ![image](https://github.com/user-attachments/assets/fbdce4ff-37bc-4b5c-aefd-30ac13b10931)








