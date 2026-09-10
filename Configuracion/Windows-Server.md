# Comandos utilizados en Windows Server

## 1. Verificar la configuración de red
```powershell
ipconfig
```
Muestra las interfaces de red, direcciones IPv4, máscara de subred y puerta de enlace configuradas en Windows Server.

## 2. Verificar la configuración de red completa
```powershell
ipconfig /all
```
Muestra información detallada de los adaptadores de red, incluyendo dirección MAC, DNS, DHCP y otros parámetros.

## 3. Probar conectividad mediante ICMP
```powershell
ping 192.168.10.X
```
Permite comprobar la comunicación con otro dispositivo de la red. La dirección IP debe reemplazarse por la del equipo que se desea comprobar.

## 4. Consultar la tabla ARP
```powershell
arp -a
```
Muestra las asociaciones entre direcciones IP y direcciones MAC conocidas por Windows Server.

## 5. Consultar el perfil de red
```powershell
Get-NetConnectionProfile
```
Permite comprobar el perfil de red activo y el estado de autenticación del dominio. En el laboratorio se utilizó para verificar la conexión asociada al dominio telconet.local.

## 6. Verificar las reglas del Firewall de Windows
```powershell
Get-NetFirewallProfile
```
Muestra el estado de los perfiles del Firewall de Windows y permite comprobar si están habilitados.

## 7. Consultar reglas del Firewall
```powershell
Get-NetFirewallRule
```
Permite visualizar las reglas configuradas en el Firewall de Windows.
