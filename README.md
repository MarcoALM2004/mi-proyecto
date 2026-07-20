# Rosita Computer

## Descripción

Rosita Computer es una plataforma web desarrollada para la venta online de computadoras personalizadas según el presupuesto del cliente. El sistema permite visualizar productos, configurar equipos, gestionar pedidos y brindar una experiencia de compra sencilla e intuitiva.

---

## Integrantes

- Diego Mayora – QA / Líder del proyecto
- Adrian Cornejo – Backend y Seguridad
- Kevin Chate – Frontend
- John Sepúlveda – API y Chatbot
- Marco León – Documentación

---

## Tecnologías utilizadas

### Backend
- Java
- Spring Boot
- Spring Security
- JPA / Hibernate
- MySQL

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Chatbot
- Python

### Herramientas
- Git
- GitHub
- GitHub Actions
- Azure

---

## Estructura del proyecto

```text
RositaComputer
│
├── backend/
├── frontend/
├── chatbot/
├── database/
├── docs/
└── .github/workflows/
```

---

## Requisitos

Antes de ejecutar el proyecto se debe tener instalado:

- Java JDK 17 o superior
- Maven
- MySQL
- Python (para el chatbot)
- Git

---

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/repositorio.git
```

---

### 2. Configurar la base de datos

- Crear la base de datos.
- Importar el script SQL incluido.
- Configurar las credenciales en `application.properties`.

---

### 3. Ejecutar el Backend

```bash
mvn spring-boot:run
```

---

### 4. Ejecutar el Frontend

Abrir el proyecto del frontend y ejecutarlo desde el servidor correspondiente.

---

### 5. Ejecutar el Chatbot

```bash
python app.py
```

---

## Funcionalidades

- Registro e inicio de sesión.
- Catálogo de productos.
- Configuración de computadoras por presupuesto.
- Carrito de compras.
- Gestión de pedidos.
- Panel administrativo.
- Chatbot de asistencia.

---

## GitHub Actions

El repositorio cuenta con flujos de trabajo de Integración Continua (CI) y Despliegue Continuo (CD), los cuales automatizan la compilación, validación y despliegue del proyecto.

---

## Despliegue

El sistema se encuentra preparado para su despliegue utilizando Azure y GitHub Actions.

---

## Manual de uso

1. Iniciar sesión.
2. Explorar el catálogo de productos.
3. Configurar la computadora según el presupuesto.
4. Agregar productos al carrito.
5. Confirmar el pedido.

---

## Licencia

Proyecto desarrollado con fines académicos para el curso Herramientas de Desarrollo.
