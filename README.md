# Proyecto Integrador

Repositorio del **Proyecto Integrador - Tarea 06**, realizado en un entorno virtualizado con Windows Server y Ubuntu Server. En el desarrollo de la práctica se realizaron configuraciones de red, pruebas de conectividad y diferentes verificaciones entre los equipos del laboratorio.

## Contenido del repositorio

El repositorio está organizado en tres carpetas principales, cada una con la información correspondiente a una parte del proyecto.

### Informe

Contiene la documentación técnica del Proyecto Integrador, donde se detallan los procedimientos realizados, las configuraciones aplicadas en los servidores, las pruebas de conectividad y seguridad, los resultados obtenidos y las conclusiones de la práctica.

### Capturas

Contiene las evidencias gráficas obtenidas durante el desarrollo del proyecto. Incluye capturas de las configuraciones realizadas en Windows Server y Ubuntu Server, comandos ejecutados, pruebas de conectividad, configuraciones de red y verificaciones realizadas durante el laboratorio.

### Configuración

Contiene los comandos y configuraciones utilizados durante el desarrollo del proyecto. La información está separada según el sistema operativo e incluye procedimientos relacionados con la configuración de red, pruebas de conectividad, consulta de la tabla ARP, Firewall y otras comprobaciones realizadas en los servidores.

## Entorno de trabajo

La práctica fue desarrollada mediante máquinas virtuales utilizando **VirtualBox**. Los sistemas utilizados fueron:

- Windows Server 2025 Standard Evaluation
- Ubuntu Server
- VirtualBox

La comunicación entre los equipos se realizó mediante una red IPv4 del segmento `192.168.10.0/24`.

## Windows Server

Windows Server se utilizó como servidor principal del laboratorio y se configuró el dominio `telconet.local`. Durante la práctica se realizaron diferentes comprobaciones relacionadas con la red, el dominio y la seguridad del sistema.

Entre las configuraciones y verificaciones realizadas se encuentran:

- Configuración de la interfaz de red.
- Configuración y comprobación de IPv4.
- Verificación de la puerta de enlace.
- Pruebas de conectividad mediante `ping`.
- Comprobación del perfil de red.
- Verificación de la autenticación con el dominio `telconet.local`.
- Revisión del Firewall de Windows.
- Consulta de la tabla ARP.

## Ubuntu Server

Ubuntu Server se utilizó para realizar pruebas de red y comprobar la comunicación con Windows Server y la puerta de enlace. También se utilizaron comandos de Linux para revisar la configuración de las interfaces y la información relacionada con los dispositivos de la red local.

Entre las comprobaciones realizadas se encuentran:

- Revisión de las interfaces de red.
- Consulta de direcciones IPv4.
- Pruebas de conectividad con Windows Server.
- Pruebas de comunicación con la puerta de enlace.
- Consulta de la tabla ARP.
- Consulta de vecinos de red.

## Pruebas realizadas

Durante el desarrollo del proyecto se realizaron pruebas de conectividad utilizando el protocolo ICMP mediante el comando `ping`. Estas pruebas permitieron comprobar la comunicación entre Ubuntu Server, Windows Server y la puerta de enlace configurada en la red.

También se revisaron las tablas ARP de los sistemas para identificar las asociaciones entre direcciones IP y direcciones MAC detectadas dentro de la red local.

En Windows Server se realizaron además verificaciones relacionadas con el perfil de red y el Firewall para comprobar el estado de los servicios y configuraciones involucradas en la comunicación del laboratorio.

## Tecnologías y herramientas utilizadas

- Windows Server 2025
- Ubuntu Server
- VirtualBox
- IPv4
- TCP/IP
- ICMP
- ARP
- PowerShell
- Terminal de Linux
- Firewall de Windows

## Estructura del repositorio

```text
Proyecto-Integrador/
│
├── Informe/
│   └── README.md
│
├── Capturas/
│   └── README.md
│
└── Configuracion/
    ├── README.md
    ├── Ubuntu-Server.md
    └── Windows-Server.md
```

## Objetivo

El objetivo de este repositorio es reunir la documentación, configuraciones, comandos y evidencias correspondientes al desarrollo del Proyecto Integrador. La información permite consultar de forma separada el trabajo realizado en Windows Server y Ubuntu Server, junto con las pruebas y configuraciones realizadas durante la práctica.