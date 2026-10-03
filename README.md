# Infraestructura 3

## 🎥 Video demostrativo
https://itlaedudo-my.sharepoint.com/:v:/g/personal/20250885_itla_edu_do/IQA3PF9HZ65nRLDoNqOemcbpAX6u14cJ8gA1owLwvEvpwG0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=2E7D9R

---

## 🎯 Propósito del laboratorio

El propósito de esta infraestructura es implementar una comunicación
segura entre una red de usuarios y un servidor Web mediante una VPN
cliente servidor.

La infraestructura debe permitir comprobar que la comunicación entre
el usuario y el servidor solamente es posible cuando el enlace VPN
se encuentra activo.

---

## 🏗️ Infraestructura

La topología está compuesta por:

- 1 FortiGate.
- 1 Router cisco
- 1 ISP.
- 2 switches Cisco.
- 1 servidor Web HTTPS.
- 1 red de usuarios.
- VLAN 10.
- DHCP.
- VPN Site-to-Site.
- NAT.
- Traceroute.

Cada lado de la infraestructura cuenta con un switch Cisco.
La interfaz GigabitEthernet0/0 del switch se conecta hacia el
FortiGate o equipo de red correspondiente, mientras que
GigabitEthernet0/1 se conecta hacia el servidor o usuario.

---

## 🌐 Topología

<img width="542" height="583" alt="image" src="https://github.com/user-attachments/assets/7cb3c88f-6672-44f2-8dcd-7da611eaa4c5" />


---

## 📚 Documentación

- [Documentacion](Documentacion)


---

## ⚙️ Configuraciones

Los running-config de los dispositivos utilizados se encuentran en:

`Documentacion`

---

## 🧪 Evidencias

Las evidencias de configuración y pruebas se encuentran en:

`Documentacion`
