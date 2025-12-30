# 🏨 Sistema de Reserva de Hoteles

Sistema web desarrollado para la **gestión y reserva de hoteles**, orientado tanto a **usuarios clientes** como a **administradores**, permitiendo una experiencia sencilla, rápida y organizada para realizar reservas y administrar el sistema.

---

## 📌 Características principales

### 👤 Usuario Cliente
- Registro e inicio de sesión
- Búsqueda de hoteles por departamento
- Consulta de disponibilidad por fechas
- Reserva de habitaciones
- Confirmación de pago
- Visualización, edición y cancelación de reservas

### 🛠️ Administrador
- Panel de administración (Dashboard)
- Gestión de departamentos
- Gestión de hoteles y habitaciones
- Control de precios y capacidad
- Administración completa de reservas
- Visualización de métricas e ingresos

---

## 🌐 Demo en línea

Puedes acceder al sistema desde el siguiente enlace:

👉 **https://nice-grass-07855bf0f.1.azurestaticapps.net**

### 🔑 Credenciales de prueba

Rol: Administrador
Correo: admin@hotel.com
Contraseña: admin123


> 💡 Recomendación: Para una experiencia real, crea un usuario nuevo como cliente.

---

## 🧭 Flujo del sistema (Usuario Cliente)

1. Seleccionar un **departamento**
2. Elegir un **hotel disponible**
3. Seleccionar **fechas de entrada y salida**
4. Elegir habitaciones
5. Confirmar la reserva
6. Realizar el pago
7. Gestionar reservas desde **Mis Reservas**

⚠️ Las reservas deben realizarse con **mínimo 24 horas de anticipación**.

---

## 🛠️ Tecnologías utilizadas

### Front-End
- HTML5
- CSS3
- JavaScript
- Angular

### Back-End
- Java
- Spring Boot
- API REST

### Base de Datos
- MySQL

### Otros
- Azure Static Web Apps
- Git & GitHub

---

## 🗄️ Roles del sistema

| Rol | Descripción |
|---|---|
| USER | Realiza búsquedas y reservas |
| ADMIN | Administra todo el sistema |

---

## 📂 Funcionalidades destacadas

- Autenticación y autorización por roles
- Validación de fechas y disponibilidad
- Cálculo automático de costos
- Gestión centralizada de reservas
- Interfaz intuitiva y responsiva

---

## 🚀 Instalación local (opcional)

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/tu-repositorio.git

# Abrir el proyecto backend
Importar en tu IDE (IntelliJ / Eclipse)

# Configurar base de datos
Configurar application.properties

# Ejecutar el proyecto
Run Spring Boot Application
