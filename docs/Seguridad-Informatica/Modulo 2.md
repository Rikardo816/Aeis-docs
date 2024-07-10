# Identificación, Autenticación y Autorización

## Objetivos del Módulo
- Comprender la terminología, principios y modelos de control de acceso.
- Entender la gestión de identidad y acceso (IAM).
- Conocer la gestión de acceso de usuarios.
- Tener una visión general de los diferentes tipos de autenticación.
- Entender la contabilidad de usuarios.
- Visión general de los diferentes tipos de autorización.

## Principios y Modelos de Control de Acceso
El control de acceso es la restricción selectiva del acceso a un recurso o sistema de red. Utiliza la identificación, autenticación y autorización del usuario para restringir o conceder acceso a un recurso específico.

### Terminología de Control de Acceso
- **Sujeto:** Usuario o proceso que desea acceder a un recurso.
- **Objeto:** Recurso específico que el usuario desea acceder.
- **Monitor de Referencia:** Verifica las reglas de control de acceso.
- **Operación:** Acción realizada por un sujeto sobre un objeto.

### Principios de Control de Acceso
- **Separación de Funciones (SoD):** Asigna diferentes privilegios a individuos para evitar que una sola persona tenga derechos completos de autorización.
- **Necesidad de Saber:** Acceso solo a la información necesaria para realizar una tarea específica.
- **Principio de Mínimos Privilegios (POLP):** Extiende la necesidad de saber, proporcionando solo el acceso necesario, ni más ni menos.

### Modelos de Control de Acceso
- **Control de Acceso Obligatorio (MAC):** Solo el administrador puede asignar privilegios.
- **Control de Acceso Discrecional (DAC):** El usuario final tiene acceso completo a la información que posee.
- **Control de Acceso Basado en Roles (RBAC):** Permisos asignados según los roles de usuario.
- **Control de Acceso Basado en Reglas (RB-RBAC):** Permisos asignados dinámicamente según reglas definidas por el administrador.

## Gestión de Identidad y Acceso (IAM)
IAM asegura que las personas adecuadas tengan el acceso adecuado en el momento adecuado.

### Gestión de Identidad de Usuario (IDM)
- **Identificación del Usuario:** Métodos para asegurar que un individuo tiene una identidad válida.
- **Repositorio de Identidad:** Base de datos donde se almacenan los atributos relacionados con las identidades de los usuarios.

## Tipos de Autenticación
La autenticación valida la identidad de un individuo con un sistema, aplicación o red.

### Métodos de Autenticación
- **Autenticación por Contraseña:** Combinación de nombre de usuario y contraseña.
- **Autenticación con Tarjeta Inteligente:** Dispositivo con chip que contiene información personal para autenticar al usuario.
- **Autenticación Biométrica:** Identificación basada en características físicas como huellas dactilares, retina, estructura de venas, reconocimiento facial, iris y voz.
- **Autenticación de Dos Factores:** Uso de dos factores diferentes de autenticación para verificar la identidad.
- **Autenticación de Inicio de Sesión Único (SSO):** Permite al usuario autenticarse en múltiples servidores con una sola contraseña.

## Tipos de Sistemas de Autorización
La autorización controla el acceso a la información para un individuo.

### Métodos de Autorización
- **Autorización Centralizada:** Uso de una unidad de autorización centralizada para toda la red.
- **Autorización Descentralizada:** Cada recurso de la red mantiene su propia unidad de autorización.
- **Autorización Implícita:** Acceso a recursos en nombre de otros usuarios.
- **Autorización Explícita:** Autorización separada para cada recurso solicitado.

## Contabilidad de Usuarios
La contabilidad mantiene un registro de las acciones de los usuarios en la red, ayudando a identificar acciones autorizadas y no autorizadas. Los datos de la cuenta pueden usarse para análisis de tendencias, detección de brechas de datos e investigaciones forenses.