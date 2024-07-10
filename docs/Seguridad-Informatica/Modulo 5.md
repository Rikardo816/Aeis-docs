# Controles Técnicos de Seguridad de Redes

## Objetivos del Módulo
- Comprender la segmentación de redes y sus tipos.
- Entender los diferentes tipos de firewalls y sus roles.
- Conocer los diferentes tipos de IDS/IPS y sus roles.
- Visión general de los diferentes tipos de honeypots.
- Comprender los diferentes tipos de servidores proxy y sus beneficios.
- Entender los fundamentos de las VPN y su importancia en la seguridad de la red.
- Visión general de la gestión de incidentes de seguridad y análisis de comportamiento del usuario (UBA).
- Visión general de los diferentes antivirus/software anti-malware.

## Segmentación de Redes
La segmentación de redes consiste en dividir una red en segmentos más pequeños para mejorar la seguridad y el rendimiento.

### Tipos de Segmentación de Redes
- **Segmentación Física:** Divide la red en componentes físicos más pequeños utilizando dispositivos intermediarios como switches o routers.
- **Segmentación Lógica:** Utiliza VLANs para aislar lógicamente los dispositivos sin importar su ubicación física.
- **Virtualización de Redes:** Combina recursos de red disponibles y permite a los profesionales de seguridad compartir estos recursos entre los usuarios.

## Firewalls
Un firewall es un dispositivo de software o hardware que monitorea y filtra el tráfico de red entrante y saliente según criterios de seguridad predefinidos.

### Tipos de Firewalls
- **Hardware:** Dispositivo dedicado, filtra tráfico para redes grandes.
- **Software:** Programa instalado en una computadora, filtra tráfico para usuarios individuales.
- **Basados en Host:** Filtran tráfico de una computadora específica.
- **Basados en Red:** Filtran tráfico de una red completa.

### Tecnologías de Firewall
- **Filtrado de Paquetes:** Compara paquetes con criterios predefinidos.
- **Pasarela a Nivel de Circuito:** Monitorea el handshake TCP.
- **Pasarela a Nivel de Aplicación:** Filtra paquetes a nivel de aplicación.
- **Inspección Multicapa Stateful:** Combina aspectos de otras tecnologías.

## IDS/IPS
Un IDS/IPS inspecciona todo el tráfico de red en busca de patrones sospechosos que puedan indicar una violación de seguridad.

### Tipos de IDS/IPS
- **Basados en Firma:** Detectan patrones conocidos de intrusiones.
- **Basados en Anomalías:** Detectan actividades anómalas en la red.
- **Análisis de Protocolo Stateful:** Compara eventos observados con perfiles predefinidos.

### Funciones del IDS/IPS
- Monitorea y analiza actividades de usuarios y sistemas.
- Evalúa la integridad de archivos y sistemas.
- Reconoce patrones típicos de ataque.

## Honeypots
Un honeypot es un sistema de información configurado para atraer y atrapar a quienes intentan penetrar una red.

### Tipos de Honeypots
- **Interacción Baja:** Simulan un número limitado de servicios.
- **Interacción Media:** Simulan un sistema operativo real y aplicaciones.
- **Interacción Alta:** Simulan todos los servicios y aplicaciones de una red.

## Servidores Proxy
Un servidor proxy actúa como intermediario entre un cliente y el servidor real, proporcionando una capa adicional de defensa.

### Beneficios del Proxy
- Oculta direcciones IP internas.
- Filtra solicitudes de sitios externos.
- Mejora la seguridad y privacidad de los dispositivos cliente.
- Mejora la velocidad de navegación.

### Tipos de Proxy
- **Transparente:** El cliente no sabe que está utilizando un proxy.
- **No Transparente:** Requiere configuración en el cliente.
- **SOCKS Proxy:** No permite la recopilación de información sobre el cliente.
- **Proxy Reverso:** Intermediario entre el cliente y el servidor web real.

## VPN
Una VPN utiliza redes públicas para transmitir información de forma segura, asegurando la comunicación a través de canales no seguros.

### Funciones Principales
- **Encapsulación:** Los paquetes se encapsulan para ocultar la información de origen y destino.
- **Cifrado:** Mantiene la confidencialidad de la información.
- **Autenticación:** Los usuarios deben autenticarse para acceder a la VPN.

## Gestión de Incidentes de Seguridad y Análisis de Comportamiento del Usuario (UBA)
### SIEM
Los sistemas de gestión de incidentes y eventos de seguridad (SIEM) recolectan y analizan datos de seguridad de diferentes fuentes para detectar amenazas y gestionar incidentes.

### UBA
El análisis de comportamiento del usuario (UBA) monitorea y analiza el comportamiento de los usuarios para identificar actividades sospechosas que podrían indicar una amenaza interna.

## Software Antivirus/Anti-Malware
Los programas antivirus y anti-malware protegen los sistemas contra software malicioso mediante la detección, prevención y eliminación de amenazas.