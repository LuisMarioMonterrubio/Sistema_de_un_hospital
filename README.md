---
# 🏥 Sistema de Gestión Hospitalaria - Hospital SanArte

---

## 📌 Equipo
- **Número de equipo:** 14  
- **Integrantes:**
  - Monterrubio Díaz Luis Mario - Desarrollador y diseñador
  - Santiago Espinoza Sócrates Emiliano - Desarrollador y diseñador

---

## 📖 Descripción del Sistema
El **Sistema de Gestión Hospitalaria** permite a los pacientes **agendar citas médicas** de manera digital.  
El sistema genera una **confirmación en formato PDF** y envía un **correo electrónico automático** con los datos de la cita.  

- **Tipo de sistema:** Desktop App en Java (Swing) con conexión a PostgreSQL  
- **Base de datos:** PostgreSQL (Hospital_SanArte)

---

## 🛠 Librerías y Componentes Externos
- **Librerías Externas:**
  - 📧 Librería de envío de correo (Equipo 2)  
    [Repositorio del componente](#)
  - 🔑 Librería CAPTCHA (Equipo 2)  
    [Repositorio del componente](#)
- **Otras librerías:** Incluidas en la carpeta `/librerias` del proyecto  

---

## 🚀 Funcionalidades Clave
### 🔐 Integración de CAPTCHA  
- Implementada en la pantalla de inicio de sesión.  
- Permite validar que el acceso es realizado por un usuario humano.  
- Usamos la librería de CAPTCHA del **Equipo 2**.  

### 👥 CRUD de Usuarios  
- Administración de usuarios: **Administrador**, **Doctor**, **Paciente**.  
- Operaciones: crear, editar, eliminar y listar usuarios.  

### 🗓 CRUD de Citas Médicas  
- Registro y gestión de citas con fecha, hora y médico asignado.  
- Generación de PDF como comprobante de cita.  

### 📩 Envío de Correo con PDF adjunto  
- Al agendar una cita, se genera un PDF con los detalles y se envía al correo del paciente.  
- Uso de librería de correo electrónico del **Equipo 2**.  

### ⚙ Otras funcionalidades  
- Inicio de sesión con autenticación por tipo de usuario.  
- Interfaz amigable diseñada en **Java Swing**.  

---

## ⚙ Dependencias y Configuración
### 📂 Librerías Usadas
- Librería **JavaMail** (correo electrónico)  
- Librería **CAPTCHA** (Equipo 2)  
- Librerías para generación de PDF (incluidas en `/librerias`)  

### 🔧 Pasos para instalar/ejecutar
1. **Clonar el repositorio**
   bash
   git clone https://github.com/usuario/Hospital_SanArte.git
`

2. **Abrir el proyecto en NetBeans**
3. **Configurar la base de datos PostgreSQL**

   * Importar el script SQL incluido en la carpeta `/database`.
   * Ajustar las credenciales en la clase de conexión.
4. **Agregar librerías externas**

   * Importar todos los `.jar` de la carpeta `/librerias`.
5. **Ejecutar `Main.java`** desde NetBeans.

### 💻 Requisitos Mínimos

* **Java:** JDK 11 o superior
* **Base de Datos:** PostgreSQL 14 o superior
* **IDE recomendado:** NetBeans 12+
* **Sistema Operativo:** Windows / Linux

---

## 📸 Capturas de Pantalla

> *(Agrega capturas del login, CRUD y agendado de citas para mostrar funcionamiento)*

---

## 📜 Licencia

Este proyecto es de uso académico y no está destinado para fines comerciales.

---

✨ *Desarrollado con dedicación por el Equipo 14 para el Hospital SanArte.*



---
