# Note+ 📝

Aplicación web full stack para tomar, organizar y sincronizar apuntes con integración en la nube (Google Drive API).  
Proyecto en desarrollo como parte de portafolio para demostrar habilidades en **Angular, Node.js, Tailwind CSS, PostgreSQL y APIs REST**.

---

## 🚀 Cómo Empezar (Getting Started)

Para configurar y ejecutar este proyecto localmente, sigue los siguientes pasos.  
Asegúrate de tener **Node.js** y **Git** instalados en tu sistema.

---

### 📋 Prerrequisitos
- **Node.js**: [https://nodejs.org/](https://nodejs.org/)  
- **Git**: [https://git-scm.com/](https://git-scm.com/)  

---

### 1️⃣ Clonar el Repositorio
```bash
git clone https://github.com/BryShdw/Note-.git
```

### 2️⃣ Configuración del Backend
Navega al directorio del backend e instala las dependencias:
```bash
cd backend
npm install
```
Crea un archivo .env en el directorio del backend con tus variables de entorno:
```bash
DATABASE_URL="postgresql://user:password@localhost:5432/note_db"
JWT_SECRET="tu_clave_secreta_jwt"
```
Inicia el servidor backend:
```bash
npm start
```
El backend estará disponible en: http://localhost:3000 (o el puerto configurado en tu .env).

### 3️⃣ Configuración del Frontend
Abre una nueva terminal, navega al directorio del frontend e instala las dependencias:
```bash
cd ../frontend
npm install
```
Inicia el servidor de desarrollo de Angular:
```bash
ng serve
```
El frontend estará disponible en: http://localhost:4200

### 📌 Tecnologías Utilizadas
* Frontend: Angular, Tailwind CSS, TypeScript

* Backend: Node.js, Express, JWT

* Base de Datos: PostgreSQL

* Otros: Google Drive API, Git, REST APIs