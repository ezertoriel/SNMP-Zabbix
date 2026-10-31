# SNMP-Zabbix

## Propósito
Tener servicio de SNMP en la red, un servidor DHCP que este dando direcciones IP a los dispositivos, y un servicio Zabbix para monitorear los dispositivos (Router y Switch). 

## Topología 
<img width="461" height="561" alt="image" src="https://github.com/user-attachments/assets/4d4606a3-a9c9-4497-b83f-331e90052841" />


---
## Diagrama Lógico
<img width="1024" height="952" alt="image" src="https://github.com/user-attachments/assets/eafce6f3-b661-4e12-bceb-887076282693" />



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



