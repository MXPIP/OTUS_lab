# Домашнее задание
Проектирование адресного пространства
Схема CLOS






Адресация сети
hostname	interface	IP/MASK	        Description
 spine-1	Ethernet1	10.10.1.0/31	leaf-1
 spine-1	Ethernet2	10.10.1.2/31	leaf-2
 spine-1	Ethernet3	10.10.1.4/31	leaf-3
 spine-1	Loopback1	10.10.10.0/32	
            
 spine-2	Ethernet1	10.10.2.0/31	leaf-1
 spine-2	Ethernet2	10.10.2.2/31	leaf-2
 spine-2	Ethernet3	10.10.2.4/31	leaf-3
 spine-2	Loopback1		
            
  leaf-1	Ethernet1	10.10.1.1/31	 spine-1
  leaf-1	Ethernet2	10.10.2.1/31	 spine-2
  leaf-1	Loopback2	10.10.0.1/32	
            
  leaf-2	Ethernet1	10.10.1.3/31	 spine-1
  leaf-2	Ethernet2	10.10.2.3/31	 spine-2
  leaf-2	Loopback2	10.10.0.2/32	
            
  leaf-3	Ethernet1	10.10.1.5/31	 spine-1
  leaf-3	Ethernet2	10.10.2.5/31	 spine-2
  leaf-3	Loopback2	10.10.0.3/32	

Проверка на доступнорсть
