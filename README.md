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
![image](https://github.com/user-attachments/assets/6746ac13-fb51-4930-9aaf-f471d6458b7e)  
![image](https://github.com/user-attachments/assets/7963d424-f327-487a-809e-aa8731d21f64)    
![image](https://github.com/user-attachments/assets/2f93dfef-5516-4450-b4ea-fc266339ce3c)  
![image](https://github.com/user-attachments/assets/f8b32bd9-2627-4702-a21e-cda67da5f1c0)  
![image](https://github.com/user-attachments/assets/e4deba3b-580b-4586-b6a1-9acb743e082c)  
![image](https://github.com/user-attachments/assets/78d67616-43ff-410f-94f4-b2320249a025)  
![image](https://github.com/user-attachments/assets/0fcbf430-566f-4fd2-9178-a8b9ba5a5b2e)  
![image](https://github.com/user-attachments/assets/6e3c2ce4-306e-4735-9a75-1001f11989a0)   
![image](https://github.com/user-attachments/assets/487410d1-5173-413c-97fd-2a0607b90e3d)  
![image](https://github.com/user-attachments/assets/589958ab-b704-452a-92bd-73585e5d091d)  
![image](https://github.com/user-attachments/assets/4c9a6cd9-71fa-4114-82f8-6c4c0057344a)  
![image](https://github.com/user-attachments/assets/b4980fa3-b967-499e-8d71-1c91f10b929a)  
![image](https://github.com/user-attachments/assets/100164e8-7032-4e3d-800b-d9bf558b00e1)  

--- | Конфигурация безопасности порта по умолчанию | ---
-- | -- | ---
Функция | Настройка по умолчанию 
Защита портов | Disabled
Максимальное количество записей MAC-адресов | 1 
Режим проверки на нарушение безопасности | Shutdown
Aging Time | 0 mins  
Aging Type | Absolute  
Secure Static Address Aging | 0
Sticky MAC Address | 0  
![image](https://github.com/user-attachments/assets/937ea7e3-702d-4deb-8b91-533ec5dd61c0)  
![image](https://github.com/user-attachments/assets/4089f4c5-e140-41d8-85c4-a125eca8ba9f)






















