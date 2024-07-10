# Seguridad de Datos

## Objetivos del Módulo
- Comprender las diferentes tecnologías de seguridad de datos.
- Entender los diversos controles de seguridad para el cifrado de datos.
- Visión general de herramientas de cifrado de discos, archivos y medios extraíbles.
- Comprender los métodos y herramientas para la copia de seguridad y retención de datos.
- Entender la Prevención de Pérdida de Datos (DLP) y las soluciones DLP.
- Comprender la seguridad de datos y su importancia.

## Seguridad de Datos
### Definición
La seguridad de datos implica la aplicación de varios controles de seguridad para evitar el mal uso, destrucción o modificación de datos de manera intencional o accidental.

### Estados Críticos de los Datos
- **Datos en Reposo:** Datos almacenados en un lugar físico.
- **Datos en Uso:** Datos almacenados en memoria.
- **Datos en Tránsito:** Datos que se transfieren a través de algún medio de comunicación.

## Tecnologías de Seguridad de Datos
- **Control de Acceso a Datos:** Autenticación y autorización de usuarios para acceder a datos.
- **Cifrado de Datos:** Transformar información para que no pueda ser leída por partes no autorizadas.
- **Enmascaramiento de Datos:** Ocultar áreas específicas de datos con caracteres o códigos aleatorios.
- **Resiliencia y Copia de Seguridad de Datos:** Hacer copias duplicadas de datos críticos para recuperación.
- **Destrucción de Datos:** Eliminar datos de manera que no puedan ser recuperados.
- **Retención de Datos:** Almacenar datos de manera segura para cumplir con requisitos de cumplimiento o negocio.

## Técnicas de Cifrado de Datos
- **Cifrado de Disco Completo:** Cifrado de todos los datos en un disco excepto el MBR.
- **Cifrado a Nivel de Archivo:** Cifrado que ocurre a nivel del sistema de archivos.
- **Cifrado de Medios Extraíbles:** Prevención del acceso no autorizado a dispositivos como USBs y discos duros portátiles.

### Herramientas de Cifrado de Disco
- **VeraCrypt:** Software para establecer y mantener volúmenes cifrados.
- **BitLocker Drive Encryption**
- **FinalCrypt**
- **Seqrite Encryption Manager**
- **FileVault**
- **Gilisoft Full Disk Encryption**

### Herramientas de Cifrado de Archivos
- **Advanced Encryption Package**
- **AxCrypt**
- **idoo File Encryption**
- **Cryptomator**
- **Encrypto**
- **AES Crypt**

### Herramientas de Cifrado de Medios Extraíbles
- **GiliSoft USB Encryption**
- **idoo USB Encryption**
- **Kakasoft USB Security**
- **Rohos Mini Drive**
- **McAfee File & Removable Media Protection**
- **MFG’s Removable Media Encryption**

## Copia de Seguridad de Datos
### Definición
La copia de seguridad de datos es el proceso de hacer copias duplicadas de datos críticos para reinstaurar un sistema a su estado normal después de un daño o recuperar datos tras una pérdida o corrupción.

### Estrategias de Copia de Seguridad
- **Identificación de Datos Críticos:** Determinar qué datos son esenciales para el negocio.
- **Seleccionar Métodos de Copia de Seguridad:** Copia de seguridad completa, diferencial e incremental.
- **Elegir la Ubicación de la Copia de Seguridad:** In situ, fuera de sitio o en la nube.
- **Tipos de Copia de Seguridad:**
  - **Completa:** Copia de todos los datos del sistema.
  - **Diferencial:** Copia de los datos que han cambiado desde la última copia completa.
  - **Incremental:** Copia solo de los datos que han cambiado desde la última copia (completa o incremental).

### Herramientas de Copia de Seguridad
- **File History (Windows)**
- **Genie Backup Manager Pro**
- **BullGuard Backup**
- **NTI Backup Now EZ**
- **Power2Go 13**
- **Backup4all**

## Retención de Datos
### Definición
La retención de datos es el proceso de almacenar y mantener información importante para cumplir con requisitos de cumplimiento y archivo de datos del negocio.

### Políticas de Retención de Datos
- Definir periodos de retención para diferentes tipos de datos.
- Justificar las razones detrás de los detalles de la política.
- Crear una política sencilla y comprensible.
- Implementar software para gestionar las tareas de retención de datos.

## Prevención de Pérdida de Datos (DLP)
### Definición
La DLP incluye un conjunto de productos y procesos que no permiten a los usuarios enviar datos confidenciales fuera de la organización.

### Tipos de Soluciones DLP
- **Endpoint DLP:** Monitorea y protege sistemas basados en PC.
- **Network DLP:** Monitorea y protege datos en tránsito.
- **Storage DLP:** Monitorea y protege datos en reposo.

### Herramientas DLP
- **MyDLP**
- **SecureTrust Data Loss Prevention**
- **Symantec Data Loss Prevention**
- **McAfee Total Protection**
- **Digital Guardian Endpoint DLP**
- **Check Point Data Loss Prevention**

### Mejores Prácticas para la Implementación DLP
- Identificar los datos sensibles para proteger.
- Evaluar los proveedores de DLP disponibles.
- Implementar la DLP con una base mínima para reducir falsos positivos.
- Mejorar las políticas de DLP para soportar operaciones efectivas y eliminar falsos positivos.
