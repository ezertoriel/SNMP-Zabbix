# SNMP-Zabbix
## Link del Video
https://youtu.be/CqHNPLWo6LQ

## Propósito
Tener servicio de SNMP en la red, un servidor DHCP que este dando direcciones IP a los dispositivos, y un servicio Zabbix para monitorear los dispositivos (Router y Switch). 

## Topología 
<img width="519" height="483" alt="image" src="https://github.com/user-attachments/assets/a5dab065-d90b-4a72-8ac7-1c6eaf7bca74" />


---
## Diagrama Lógico
<img width="1024" height="953" alt="image" src="https://github.com/user-attachments/assets/b0bf038e-f12d-4cf5-b134-f3f85792483b" />



---

## Dispositivos utilizados
1. Router (DHCP)
2. Switch
3. Servidor (SNMP)

---

## Direccionamiento IP
| Red | Equipo/Puerto | IP |
| :--- | :---: | ---: |
| LAN | Router GIG0/0 | 10.8.63.1 |
| LAN | Switch VLAN1 | 10.8.63.5 |
| LAN | Server e0 | DHCP |

## SNMP Desde el servidor hacia el Router funcionando 
<img width="740" height="399" alt="image" src="https://github.com/user-attachments/assets/c0014e19-f439-4d0e-b5cc-fa3d2606e860" />


---
## SNMP Desde el servidor hacia el Switch funcionando 
<img width="677" height="196" alt="image" src="https://github.com/user-attachments/assets/5047cb05-0280-4916-a655-0968314ffe9c" />

## Switch configurado con SNMP
<img width="701" height="365" alt="image" src="https://github.com/user-attachments/assets/fb1a6d08-a8ab-4dd2-867a-4c000bfd026b" />

## Router con DHCP y SNMP

<img width="554" height="295" alt="image" src="https://github.com/user-attachments/assets/86ccca1d-7c48-4ec0-b335-8012fdd6186e" />

## Dispositivos conectados al Zabbix.

<img width="1366" height="537" alt="image" src="https://github.com/user-attachments/assets/ce388837-51b7-4e45-be1e-ac0ed4d3fa5b" />


