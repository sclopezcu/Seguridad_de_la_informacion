# Cisco Ethical Hacker – Resumen Módulos 3 y 4

Sebastian López  

# Módulo 3: Recolección de Información y Escaneo de Vulnerabilidades

Este módulo explica cómo un ethical hacker recopila información sobre un sistema objetivo antes de intentar explotarlo.  
Esta fase es fundamental en un **pentest**, ya que permite entender la infraestructura del objetivo.

---

## 1. Reconocimiento Pasivo

El **reconocimiento pasivo** consiste en recopilar información sin interactuar directamente con los sistemas del objetivo.

### Fuentes comunes de información
- OSINT (Open Source Intelligence)
- Redes sociales
- Registros DNS
- Bases de datos WHOIS
- Documentos públicos
- Motores de búsqueda

### Objetivo
Construir un perfil del objetivo identificando:

- Dominios
- Direcciones IP
- Tecnologías utilizadas
- Infraestructura de red

---

## 2. Reconocimiento Activo

El **reconocimiento activo** implica interactuar directamente con los sistemas objetivo para obtener información técnica.

### Actividades comunes
- Escaneo de puertos
- Descubrimiento de hosts
- Enumeración de servicios
- Identificación del sistema operativo

### Herramientas utilizadas
- Nmap
- Netcat
- Wireshark
- Herramientas de enumeración DNS

---

## 3. Escaneo de Vulnerabilidades

El **escaneo de vulnerabilidades** permite identificar debilidades conocidas en sistemas o aplicaciones.

### Vulnerabilidades comunes
- Software desactualizado
- Configuraciones incorrectas
- Puertos abiertos innecesarios
- Servicios vulnerables

### Herramientas comunes
- OpenVAS
- Nessus
- Nikto

---

# Módulo 4: Ingeniería Social

La **ingeniería social** consiste en manipular a las personas para obtener acceso a información confidencial o sistemas.

El factor humano es uno de los **puntos más vulnerables en seguridad informática**.

---

## 1. Pretexting y Suplantación de Identidad

El atacante crea una historia falsa para convencer a la víctima de revelar información.

### Ejemplos
- Hacerse pasar por soporte técnico
- Simular ser personal del departamento de TI
- Solicitar credenciales para resolver un supuesto problema

---

## 2. Ataques Comunes de Ingeniería Social

### Phishing
Correos electrónicos falsos diseñados para robar credenciales o información sensible.

### Spear Phishing
Ataques dirigidos a una persona o empresa específica.

### Vishing
Phishing realizado mediante llamadas telefónicas.

### Smishing
Phishing realizado mediante mensajes SMS.

### Baiting
Uso de incentivos o recompensas para engañar a la víctima.

---

## 3. Ataques Físicos de Ingeniería Social

Estos ataques implican acceso físico al entorno de la víctima.

### Ejemplos
- Tailgating o Piggybacking (seguir a un empleado autorizado para entrar a un edificio)
- Dispositivos USB maliciosos
- Shoulder Surfing (observar contraseñas mientras se escriben)

---

## 4. Herramientas de Ingeniería Social

Algunas herramientas permiten automatizar ataques de ingeniería social.

### Ejemplos
- Social Engineering Toolkit (SET)
- Herramientas de phishing
- Clonadores de sitios web
- Frameworks de campañas de phishing

---

## 5. Principios Psicológicos Utilizados

Los atacantes explotan principios psicológicos para manipular a las personas.

- Autoridad
- Urgencia
- Confianza
- Escasez
- Miedo
