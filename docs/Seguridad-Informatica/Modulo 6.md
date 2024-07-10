# Virtualización y Computación en la Nube

## Objetivos del Módulo
- Comprender la virtualización, sus componentes y habilitadores.
- Entender la seguridad y preocupaciones de la virtualización de sistemas operativos.
- Conocer las mejores prácticas para la seguridad en la virtualización de sistemas operativos.
- Entender la computación en la nube y sus beneficios.
- Visión general de los diferentes tipos de servicios de computación en la nube.
- Visión general de los modelos de implementación en la nube.
- Comprender la importancia de la seguridad en la nube y sus mejores prácticas.

## Conceptos Esenciales de Virtualización
La virtualización se refiere a la representación virtual basada en software de una infraestructura de TI que incluye redes, dispositivos, aplicaciones, almacenamiento, etc. Divide los recursos físicos en múltiples entornos simulados individuales.

### Enfoques y Tipos de Virtualización
- **Virtualización Completa**
- **Virtualización Asistida por el SO o Paravirtualización**
- **Virtualización Asistida por Hardware**
- **Virtualización Híbrida**
- **Virtualización de Sistema Operativo**
- **Virtualización de Red**
- **Virtualización de Servidor**
- **Virtualización de Escritorio**

### Componentes de Virtualización
- **Hypervisor / Monitor de Máquina Virtual:** Permite que múltiples sistemas operativos invitados compartan los recursos de hardware de un host.
- **Máquina Invitada / Máquina Virtual:** Instancia independiente de un sistema operativo creada por el monitor de máquina virtual.
- **Máquina Host / Máquina Física:** Proporciona recursos de computación para soportar máquinas virtuales.
- **Servidor de Gestión:** Componentes de la plataforma de virtualización utilizados para gestionar directamente las máquinas virtuales.
- **Consola de Gestión:** Interfaz para acceder, configurar y gestionar el producto de virtualización.

## Seguridad en la Virtualización de Sistemas Operativos
- **Contenedores:** Replican la funcionalidad del sistema operativo del kernel en múltiples instancias de espacio de usuario aislado.
- **Tipos de Contenedores:** Contenedores de sistema operativo y contenedores de aplicación.

### Desafíos y Amenazas de Seguridad en Contenedores
- Código fuente vulnerable
- Gran superficie de ataque
- Falta de visibilidad
- Compromiso de secretos
- Velocidad de DevOps
- Contenedores vecinos ruidosos
- Fuga de contenedores al host
- Ataques basados en red
- Complejidad del ecosistema

## Mejores Prácticas para la Seguridad de Contenedores
- Monitorear CVEs del runtime de contenedores.
- Utilizar herramientas conscientes de las aplicaciones para monitorear interfaces de red de contenedores.
- Configurar aplicaciones para que se ejecuten como usuarios normales.
- Configurar el sistema de archivos raíz del host en modo de solo lectura.
- Usar herramientas de escaneo de seguridad de aplicaciones.
- Realizar escaneos regulares de imágenes en el repositorio.

## Computación en la Nube
La computación en la nube es la entrega bajo demanda de capacidades de TI donde la infraestructura y las aplicaciones se proporcionan a los suscriptores como un servicio medido a través de una red.

### Beneficios de la Computación en la Nube
- **Económicos:** Agilidad empresarial, menores costos de mantenimiento, menos gastos de capital.
- **Operacionales:** Flexibilidad, eficiencia, resiliencia, despliegue rápido de aplicaciones.
- **Personal:** Procesos simplificados, uso eficiente de recursos, menos capacitación.
- **Seguridad:** Respuesta rápida a brechas, interfaz abierta estandarizada para servicios gestionados.

## Tipos de Servicios de Computación en la Nube
- **Infraestructura como Servicio (IaaS)**
- **Plataforma como Servicio (PaaS)**
- **Software como Servicio (SaaS)**
- **Identidad como Servicio (IDaaS)**
- **Contenedores como Servicio (CaaS)**
- **Seguridad como Servicio (SECaaS)**
- **Función como Servicio (FaaS)**

## Modelos de Implementación en la Nube
- **Nube Pública:** Infraestructura abierta al público.
- **Nube Privada:** Infraestructura operada para una sola organización.
- **Nube Comunitaria:** Infraestructura compartida entre varias organizaciones.
- **Nube Híbrida:** Combinación de dos o más nubes que permanecen como entidades únicas.

## Seguridad en la Nube
La seguridad en la nube es una responsabilidad compartida entre el proveedor de servicios en la nube y el cliente.

### Elementos de Seguridad en la Nube
- **IAM:** Gestión de identidades y acceso.
- **Cumplimiento:** Conocimiento de las normas y regulaciones aplicables.
- **Seguridad del Almacenamiento de Datos:** Cifrado, gestión de claves, evaluación periódica de la seguridad.
- **Monitoreo:** Observación de actividades para detectar accesos no autorizados.
- **Seguridad de la Red:** Visibilidad de red, cifrado de datos en tránsito, autenticación multifactor.
- **Gestión de Registros:** Captura y análisis de datos para auditorías de cumplimiento.