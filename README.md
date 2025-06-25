# Конфигурация безопасности коммутатора  
## Топология  
![image](https://github.com/user-attachments/assets/027ec68e-92e7-47d0-9f38-6c15c79fe876)  
## Таблица адресации  
Утсройство | interface/vlan | IP-адрес | Маска подсети   
--- | --- | ---- | ----  
R1 | G0/0/1 | 192.168.10.1 | 255.255.255.0 
--- | Loopback 0 | 10.10.1.1 | 255.255.255.0
S1 | VLAN 10 | 192.168.10.201 | 255.255.255.0
S2 | VLAN 10 | 192.168.10.202 | 255.255.255.0 
PC A | NIC | DHCP | 255.255.255.0
PC B | NIC | DHCP | 255.255.255.0 
## Задачи   
* Настройка основного сетевого устройства  
* Настройка сетей VLAN
* Настройка безопасности коммутатора

![image](https://github.com/user-attachments/assets/e56a233b-e163-4be0-9aba-f3e3e3ec4679)     
![image](https://github.com/user-attachments/assets/c6a93dad-6c05-412f-bca9-4a5df7023f65)  

![image](https://github.com/user-attachments/assets/07e01432-8303-4ee3-99b7-1f20dfbfe802)






