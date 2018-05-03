# CCNA: Routing and Switching Essentials


## Skills Assessment - Student Training  

En esta practica vamos a realizar la configuracion de una red simple para
que que pueda tener conexion con IPv4, switch security, inter VLAN routing,
OSPF.
Los pasos serian los siguientes:

- Part 1: Initialize Devices  
- Part 2: Configure Device Basic Settings  
- Part 3: Configure Switch Security, VLANs, and Inter-VLAN Routing   
- Part 4: Configure OSPF  

Despues de hacer las 4 partes vamos a implementar la practica con los siguientes pasos:

- Part 5: Implement DHCP and NAT for IPv4  
- Part 6: Configure NTP  


Para la realizacion de la practica hemos usado la herramienta GNS3 y los
dispositivos usados son los siguientes:
- Router: Cisco C7200 (c7200-adventerprisek9-mz.152-4.M7.image)
- Switch: CiscoIOSvL2 (vios_l2-adventerprisek9-m.vmdk.SSA.152-4.0.55.E)
- NetworkAutomation GNS3 (Sistema operativo Ubuntu + extras (Ansible, Paramiko...)

Dado que son imagenes simuladas de sistemas operativos de *CISCO*, pueden 
fallar/faltar algunos comandos, pero salvo error en la descarga esta todo lo necesario.

Para poder realizar toda la orquestacion/automatizacion mediante **ANSIBLE**, debemos
tener una configuracion inicial en los dispositivos *CISCO* descritos anteriormente o 
introducir manualmente la configuracion inicial segun la necesidad o los requirimientos 
de la practica.

La configuracion inicial necesaria para cada dispositivo esta en la carpeta 
"Initial Setup"

