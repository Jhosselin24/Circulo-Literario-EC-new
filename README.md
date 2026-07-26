# 📚 CÍRCULO LITERARIO EC

Sistema web desarrollado para la gestión, publicación y exploración de obras literarias dentro de una comunidad de lectores y escritores. La plataforma permite a los usuarios registrarse, administrar sus obras, publicar capítulos, gestionar su perfil y acceder a contenido literario de manera organizada e interactiva.

---

# 🎯 Objetivo del Proyecto

Desarrollar un sistema web que fomente la lectura y escritura colaborativa mediante herramientas para la publicación, administración y exploración de obras literarias, facilitando la interacción entre autores y lectores dentro de una comunidad literaria digital.

---

# ✨ Funcionalidades Principales

## 👤 Gestión de Usuarios

* Registro de usuarios.
* Inicio de sesión.
* Recuperación y restablecimiento de contraseña.
* Gestión y actualización de perfil.
* Administración de información personal.

## 📖 Gestión de Obras Literarias

* Creación de obras literarias.
* Edición de obras existentes.
* Eliminación de obras.
* Visualización detallada de obras.
* Consulta y exploración de publicaciones.

## 📝 Gestión de Capítulos

* Creación de capítulos.
* Edición de capítulos.
* Visualización del contenido literario.
* Organización de capítulos por obra.

## 👥 Comunidad Literaria

* Exploración de contenido literario.
* Interacción entre usuarios.
* Acceso a espacios de comunidad.
* Navegación por publicaciones disponibles.

## 🔐 Seguridad y Control de Acceso

* Autenticación de usuarios.
* Protección de rutas privadas.
* Control de acceso basado en autenticación.
* Gestión segura de sesiones.

## 🌐 Integración con Backend

* Consumo de servicios REST mediante API.
* Comunicación entre frontend y backend utilizando Axios.
* Gestión dinámica de datos.
* Actualización automática de la información.

---

# 🛠️ Tecnologías Utilizadas

| Categoría             | Tecnología        |
| --------------------- | ----------------- |
| Frontend              | React             |
| Entorno de Desarrollo | Vite              |
| Lenguaje              | JavaScript (ES6+) |
| Estilos               | CSS3              |
| Cliente HTTP          | Axios             |
| Gestión de Estado     | Context API       |
| Control de Versiones  | Git               |
| Repositorio Remoto    | GitHub            |

> ℹ️ El backend y la base de datos fueron desarrollados como parte de la arquitectura general del proyecto y se integran mediante servicios API REST.

---

# 📂 Estructura del Proyecto

```plaintext
src/
│
├── components/
│   ├── capitulos/
│   ├── Navbar.jsx
│   ├── ObraCard.jsx
│   ├── ObraForm.jsx
│   ├── ObraStats.jsx
│   ├── PrivateRoute.jsx
│   └── ConfirmModal.jsx
│
├── context/
│   └── AuthContext.jsx
│
├── hooks/
│
├── layout/
│
├── pages/
│   ├── Home.jsx
│   ├── Login.jsx
│   ├── Register.jsx
│   ├── Dashboard.jsx
│   ├── Details.jsx
│   ├── Profile.jsx
│   ├── Comunidad.jsx
│   ├── Chat.jsx
│   ├── Contacto.jsx
│   ├── Forgot.jsx
│   ├── Reset.jsx
│   ├── Update.jsx
│   ├── Forbidden.jsx
│   └── NotFound.jsx
│
├── services/
│   ├── api.js
│   ├── axiosConfig.js
│   ├── authService.js
│   ├── userService.js
│   ├── obraService.js
│   └── capituloService.js
│
├── utils/
│
├── App.jsx
├── main.jsx
└── index.css
```

---

# ⚙️ Instalación y Ejecución

## 1. Clonar el repositorio

```bash
git clone https://github.com/Jhosselin24/CIRCULO-LITERARIO-EC.git
```

## 2. Ingresar al proyecto

```bash
cd CIRCULO-LITERARIO-EC/frontend
```

## 3. Instalar dependencias

```bash
npm install
```

## 4. Configurar variables de entorno

Crear un archivo `.env` y configurar la URL correspondiente del backend.

Ejemplo:

```env
VITE_API_URL=http://localhost:3000/api
```

## 5. Ejecutar el proyecto

```bash
npm run dev
```

## 6. Link de la aplicacion desplegada

https://circuloliterarioec.netlify.app/ 

---

## 6. Link de video de funcionamiento del sitio web

https://youtu.be/_LPXppOVqww 

---

# 🚀 Funcionalidades Implementadas

| Funcionalidad                  | Estado |
| ------------------------------ | ------ |
| Registro de usuarios           | ✅      |
| Inicio de sesión               | ✅      |
| Recuperación de contraseña     | ✅      |
| Gestión de perfil              | ✅      |
| Gestión de obras literarias    | ✅      |
| Gestión de capítulos           | ✅      |
| Visualización de obras         | ✅      |
| Dashboard de usuario           | ✅      |
| Comunidad literaria            | ✅      |
| Consumo de API REST            | ✅      |
| Rutas protegidas               | ✅      |
| Integración Frontend - Backend | ✅      |

---

# 📸 Capturas de Pantalla

Se recomienda agregar capturas de pantalla de las principales funcionalidades del sistema:

* Inicio de sesión.
<img width="1116" height="552" alt="image" src="https://github.com/user-attachments/assets/b0ef1d30-2391-45d3-8738-0161c8d31ddb" />

* Registro de usuarios.
<img width="1037" height="480" alt="image" src="https://github.com/user-attachments/assets/fc03d9ac-3cf0-4017-a1c8-62def8849fdc" />

* Dashboard principal.
<img width="1901" height="906" alt="image" src="https://github.com/user-attachments/assets/3431ef89-9ddc-4daa-b21e-8d203a287605" />

* Gestión de obras literarias.
<img width="1042" height="537" alt="image" src="https://github.com/user-attachments/assets/ef10c54c-69f7-4353-8c36-bc28e4621494" />

* Perfil de usuario.
<img width="1041" height="546" alt="image" src="https://github.com/user-attachments/assets/07d97bb6-04a4-4654-8d17-8c5b9a5c6489" />


---

# 📚 Aprendizajes Obtenidos

Durante el desarrollo del sistema web se aplicaron conocimientos relacionados con:

* Desarrollo de sistemas web utilizando React y Vite.
* Arquitectura basada en componentes.
* Gestión de estado mediante Context API.
* Consumo de servicios REST utilizando Axios.
* Implementación de autenticación y autorización.
* Integración entre frontend y backend.
* Gestión de contenido literario mediante interfaces dinámicas.
* Protección de rutas y control de acceso.
* Control de versiones utilizando Git y GitHub.

---

# 👩‍💻 Autora

**Jhosselin Naula**

Estudiante de Desarrollo de Software

GitHub: https://github.com/Jhosselin24

---

# 📄 Licencia

Este proyecto fue desarrollado con fines académicos y educativos.

---


# 🤝 Equipo de Desarrollo

Proyecto desarrollado como parte de las actividades académicas de la carrera de Desarrollo de Software, aplicando metodologías de desarrollo web, integración de servicios y gestión colaborativa mediante Git y GitHub.


