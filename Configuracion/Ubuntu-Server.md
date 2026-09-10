# Comandos utilizados en Ubuntu Server

## 1. Verificar las interfaces y direcciones IP
```bash
ip addr
```
Permite comprobar las interfaces de red y las direcciones IP configuradas en Ubuntu Server.

## 2. Comprobar conectividad con Windows Server
```bash
ping -c 4 192.168.10.226
```
Envía cuatro solicitudes ICMP para comprobar la comunicación entre Ubuntu Server y Windows Server.

## 3. Comprobar conectividad con la puerta de enlace
```bash
ping -c 4 192.168.10.1
```
Permite verificar que Ubuntu Server puede comunicarse con la dirección de la puerta de enlace de la red.

## 4. Consultar la tabla ARP
```bash
arp -a
```
Muestra las asociaciones conocidas entre direcciones IP y direcciones MAC en la red local.

## 5. Consultar vecinos de red
```bash
ip neigh
```
Permite visualizar los vecinos detectados por el sistema y sus direcciones MAC asociadas.
