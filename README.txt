# 🛍️ Kkarhua - Frontend

## 📋 Requisitos Previos
- Node.js 16+ y npm
- Backend corriendo en `http://localhost:8080`

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone <url-del-repositorio>
cd frontend

# Instalar dependencias
npm install
```

## ▶️ Ejecución

### Modo Desarrollo
```bash
npm run dev
```
La aplicación estará disponible en: `http://localhost:5173`

### Modo Producción
```bash
# Compilar
npm run build

# Previsualizar build
npm run preview
```

## 🧪 Testing
```bash
# Ejecutar tests
npm test

# Tests con cobertura
npm run test:coverage
```

## 📁 Estructura Principal
```
src/
├── pages/          # Páginas de la aplicación
├── componentes/    # Componentes reutilizables
├── context/        # Contextos (Auth, Carrito)
└── assets/         # Recursos estáticos
```

## 🔑 Usuarios de Prueba
- **Admin**: super-admin / contraseña
- **Cliente**: cliente@test.com / contraseña

## ⚙️ Configuración
El backend debe estar corriendo en `http://localhost:8080/api`

## 🛠️ Tecnologías
- React + Vite
- React Router
- Bootstrap 5
- Context API

---
**Nota**: Asegúrate de que el backend esté corriendo antes de iniciar el frontend.