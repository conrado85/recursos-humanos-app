# 💼 Recursos Humanos y Control de Stock

Sistema integral de gestión de empleados, tareas y stock, desarrollado con **React**, **Express**, **TypeScript** y **MySQL**.  
El objetivo del proyecto es ofrecer una herramienta moderna y eficiente para pequeñas y medianas empresas que necesiten llevar control de su personal y de los recursos que manejan.

---

## 🎯 Objetivos del proyecto

- Permitir **registrar, consultar y actualizar empleados**, con cálculo automático de sueldos.
- Gestionar **planillas de tareas o productos**, con control de productividad.
- Implementar un sistema de **control de stock por lotes**, incluyendo alertas por cantidad mínima.
- Crear una **API REST documentada con Swagger**, conectada a una base de datos MySQL.
- Ofrecer una interfaz **intuitiva, moderna y adaptable**, usando **Tailwind UI y ShadCN**.
- Aplicar **TypeScript** para asegurar un código más limpio, robusto y mantenible.

---

## 🧱 Tecnologías utilizadas

### 🖥️ Frontend
- **React (Vite + TypeScript)**
- **Tailwind CSS** para estilos
- **ShadCN/UI** para componentes reutilizables
- **Context API** para manejo de estado global
- **Axios** para consumo de la API

### ⚙️ Backend
- **Express.js** con **TypeScript**
- **MySQL** como base de datos principal
- **Swagger** para documentación de la API
- **Dotenv**, **CORS**, **MySQL2**, **Nodemon / ts-node-dev**

---

## 📁 Estructura del proyecto



```recursos-humanos/
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── context/
│ │ ├── pages/
│ │ ├── routes/
│ │ ├── services/
│ │ └── App.tsx
│ └── index.html
│
└── backend/
├── src/
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── config/
│ └── index.ts
└── .env
```



---

## 🚀 Instalación y ejecución

### 🔹 1. Clonar el repositorio
```bash
git clone https://github.com/tuusuario/recursos-humanos-app.git
cd recursos-humanos-app
```

### 🔹 2. Instalar dependencias.
-- En la carpeta `frontend`

```
cd frontend
npm install
npm run dev
```

-- En la carpeta `backend`

```
cd ../backend
npm install
npm run dev
```

| Método | Ruta             | Descripción                         |
| ------ | ---------------- | ----------------------------------- |
| GET    | `/api/empleados` | Obtener todos los empleados         |
| POST   | `/api/empleados` | Crear un nuevo empleado             |
| GET    | `/api/stock`     | Obtener lista de productos por lote |
| GET    | `/api/tareas`    | Consultar tareas registradas        |

