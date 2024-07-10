# Criptografía y PKI

## Objetivos del Módulo
- Comprender las técnicas criptográficas.
- Entender los diferentes algoritmos de cifrado.
- Conocer los diferentes algoritmos de hashing.
- Visión general de diferentes herramientas criptográficas y calculadoras de hash.
- Comprender la Infraestructura de Clave Pública (PKI).
- Entender las firmas digitales y los certificados digitales.

## Criptografía
### Definición
La criptografía es la conversión de datos en un código cifrado que se envía a través de una red privada o pública para proteger datos confidenciales como mensajes de correo electrónico, sesiones de chat, transacciones web, datos personales y aplicaciones de comercio electrónico.

### Objetivos de la Criptografía
- **Confidencialidad:** Garantizar que solo las partes autorizadas puedan acceder a la información.
- **Autenticación:** Verificar la identidad de las partes involucradas.
- **Integridad:** Asegurar que la información no sea alterada durante la transmisión.
- **No repudio:** Garantizar que una parte no pueda negar la autenticidad de su firma en un documento o un mensaje que haya enviado.

### Tipos de Cifrado
- **Simétrico:** Utiliza la misma clave para cifrar y descifrar datos. Ejemplos: DES, AES, RC4, RC5, RC6.
- **Asimétrico:** Utiliza un par de claves (pública y privada) para cifrar y descifrar datos. Ejemplos: RSA, DSA.

## Algoritmos de Cifrado
### DES (Data Encryption Standard)
- Algoritmo de bloque que toma una cadena de texto plano de longitud fija y la transforma en una cadena de texto cifrado de la misma longitud.

### AES (Advanced Encryption Standard)
- Algoritmo de clave simétrica con tamaños de clave de 128, 192 y 256 bits. Utilizado por agencias del gobierno de EE. UU. para proteger información sensible.

### RC4, RC5, RC6
- **RC4:** Cifrado de flujo de clave simétrica.
- **RC5:** Algoritmo de bloque con tamaño de bloque variable, tamaño de clave variable y número de rondas variable.
- **RC6:** Derivado de RC5 con características adicionales como multiplicación de enteros.

## Algoritmos de Hashing
### MD5 y MD6
- **MD5:** Algoritmo que produce un resumen de mensaje de 128 bits.
- **MD6:** Estructura tipo árbol de Merkle que permite el cálculo paralelo de hashes para entradas muy largas.

### SHA (Secure Hash Algorithm)
- **SHA-1:** Produce un resumen de mensaje de 160 bits.
- **SHA-2:** Incluye SHA-256 y SHA-512, que utilizan palabras de 32 y 64 bits respectivamente.
- **SHA-3:** Utiliza la construcción de esponja para crear hashes seguros.

### HMAC (Hash-based Message Authentication Code)
- Combina una función hash criptográfica con una clave criptográfica para proporcionar integridad y autenticación de mensajes.

## Herramientas de Criptografía y Calculadoras de Hash
- **BCTextEncoder:** Encripta texto confidencial en tus mensajes.
- **AxCrypt:** Herramienta de cifrado de archivos.
- **Microsoft Cryptography Tools:** Conjunto de herramientas de cifrado.
- **CryptoForge:** Software de cifrado para datos confidenciales.
- **Cyphertop:** Herramienta de cifrado avanzada.

### Calculadoras de Hash
- **MD5 Calculator**
- **HashMyFiles**
- **Hash Tools (Android)**
- **Hash Droid (Android)**

## Infraestructura de Clave Pública (PKI)
### Definición
Un conjunto de hardware, software, personas, políticas y procedimientos necesarios para crear, gestionar, distribuir, usar, almacenar y revocar certificados digitales.

### Componentes de PKI
- **Autoridad de Certificación (CA):** Emite y verifica certificados digitales.
- **Autoridad de Registro (RA):** Verifica la identidad de las entidades que solicitan un certificado.
- **Sistema de Gestión de Certificados:** Genera, distribuye y almacena certificados.
- **Directorio de Certificados:** Almacena certificados y sus claves públicas.

### Proceso de PKI
1. **Solicitud de Certificado:** El usuario aplica para obtener un certificado.
2. **Emisión de Certificado:** La RA verifica la solicitud y la CA emite el certificado.
3. **Distribución del Certificado:** El certificado se almacena en un directorio.
4. **Validación de Certificado:** El usuario puede verificar la validez del certificado.

## Firmas Digitales y Certificados Digitales
### Firma Digital
- Usa algoritmos de clave asimétrica para proporcionar integridad de datos.
- Se crea con la clave privada del remitente y se verifica con la clave pública.

### Certificado Digital
- Asegura la transmisión segura de claves públicas.
- Emitido por una CA, vincula la clave pública con la identidad de su propietario.

### Atributos de un Certificado Digital
- **Número de serie:** Identidad única del certificado.
- **Emisor:** Identidad de la entidad que emitió el certificado.
- **Sujeto:** Propietario del certificado.
- **Validez:** Periodo de validez del certificado.
- **Algoritmo de firma:** Algoritmo usado para crear la firma.
- **Clave pública:** Utilizada para cifrar mensajes o verificar firmas.
- **Huella digital:** Valor hash del certificado para verificar su integridad.
