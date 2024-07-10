# Monitoreo del Tráfico de Red

## Objetivos del Módulo
- Comprender las firmas del tráfico de red.
- Entender las categorías de firmas de tráfico sospechoso.
- Visión general de técnicas de análisis de firmas de ataque.
- Comprender el monitoreo de red para tráfico sospechoso.
- Visión general de diversas herramientas de monitoreo de red.
- Entender la necesidad y las ventajas del monitoreo del tráfico de red.

## Monitoreo del Tráfico de Red
### Definición
El monitoreo de red es un enfoque de seguridad retrospectivo que implica la supervisión de una red para detectar actividades anormales, problemas de rendimiento, problemas de ancho de banda, etc. Es una parte integral de la seguridad de la red y es una tarea demandante dentro de las operaciones de seguridad de red de las organizaciones.

### Necesidad del Monitoreo de Red
- Los atacantes pueden encontrar formas de eludir las herramientas de seguridad.
- Las herramientas de seguridad a menudo utilizan técnicas de detección basadas en firmas, que no siempre pueden identificar firmas de ataque cambiantes.
- Las herramientas de seguridad generalmente no están diseñadas para identificar anomalías de comportamiento ni detectar actividades de atacantes iniciadas antes y durante un ataque.

### Ventajas del Monitoreo de Red
- Comprender cómo fluye la información en una red.
- Optimizar el rendimiento de la red.
- Investigar brechas de seguridad.
- Evitar cuellos de botella en el ancho de banda.
- Encontrar aplicaciones innecesarias y vulnerables.
- Detectar signos de actividad maliciosa.

## Firmas del Tráfico de Red
### Firmas Normales y de Ataque
- **Firmas Normales:** Patrones de tráfico aceptables permitidos en la red.
- **Firmas de Ataque:** Patrones de tráfico sospechosos que no están permitidos en la red.

Una firma es un conjunto de características del tráfico como la dirección IP de origen/destino, puertos, banderas TCP, longitud de paquetes, tiempo de vida (TTL) y protocolos. Las firmas se utilizan para definir el tipo de actividad en una red.

### Consideraciones para Crear una Línea Base de Tráfico Normal
- Comunicación TCP/IP implica un apretón de manos de tres vías para el tráfico normal.
- Una bandera SYN aparece al inicio y una bandera FIN al final de una conexión.
- Todo el tráfico originado dentro de la zona desmilitarizada (DMZ) es tráfico confiable.
- Cualquier tráfico que viole las políticas de red es tráfico malicioso.

### Categorías de Firmas de Tráfico Sospechoso
- **Informacional:** Tráfico que puede parecer sospechoso pero no necesariamente malicioso.
- **Reconocimiento:** Tráfico que indica un intento de obtener información.
- **Acceso no Autorizado:** Tráfico que indica un intento de obtener acceso no autorizado.
- **Denegación de Servicio (DoS):** Tráfico que indica un intento de DoS que inunda un servidor con una gran cantidad de solicitudes.

## Técnicas de Análisis de Firmas de Ataque
- **Análisis Basado en Contenido:** Inspección de paquetes para detectar firmas de ataque en el contenido.
- **Análisis Basado en Firmas Atómicas:** Análisis de un solo paquete para detectar firmas de ataque.
- **Análisis Basado en Contexto:** Análisis de múltiples paquetes para detectar firmas de ataque en el contexto.
- **Análisis Basado en Firmas Compuestas:** Combinación de técnicas anteriores para un análisis más completo.

## Herramientas de Monitoreo de Red
### Wireshark
- Captura y analiza tráfico de red.
- Componentes: barra de menú, barra de herramientas, barra de filtro, panel de lista de paquetes, panel de detalles de paquetes, panel de bytes de paquetes.

#### Filtros de Wireshark
- **Por Protocolo:** arp, http, tcp, udp, dns, ip.
- **Por Dirección IP:** ip.addr == 10.0.0.4.
- **Por Puertos Específicos:** tcp.port==23.
- **Filtros Adicionales:** tcp.flags.reset==1, http.request, tcp.analysis.retransmission.

### Otras Herramientas de Monitoreo de Red
- **tcpdump:** Analizador de red en línea de comandos.
- **Riverbed Packet Analyzer Plus**
- **OmniPeek**
- **Observer Analyzer**
- **SolarWinds Deep Packet Inspection and Analysis**
- **Xplico**

### Herramientas de Monitoreo de Red Adicionales
- **SolarWinds Network Performance Monitor**
- **ManageEngine OpManager**
- **Capsa Free Network Analyzer**
- **Monitis Network Monitoring Solution**
- **Nagios Network Analyzer**
- **PRTG Network Monitor**

## Monitoreo y Análisis de Tráfico FTP y Telnet
- **FTP:** Usado para transferir archivos, envía datos en texto claro.
- **Telnet:** Proporciona acceso a hosts remotos, transmite datos en texto claro y debe desactivarse para evitar riesgos de seguridad.