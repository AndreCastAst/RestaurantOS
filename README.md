# Restaurantos

Un proyecto full-stack para gestionar restaurantes.

## Estructura del Proyecto

```
restaurantos/
├── frontend/        # Aplicación del cliente
├── backend/         # API y lógica del servidor
├── .gitignore       # Configuración de Git
└── README.md        # Este archivo
```

## Requisitos Previos

- Node.js (v18 o superior)
- npm o yarn
- Git

## Instalación y Configuración

### 1. Clonar el repositorio

```bash
git clone https://github.com/AndreCastAst/restaurantos.git
cd restaurantos
```

### 2. Configurar Backend

```bash
cd backend
npm install
# Crear archivo .env con las variables necesarias
cp .env.example .env
npm run dev
```

El backend estará disponible en `http://localhost:3001`

### 3. Configurar Frontend

```bash
cd ../frontend
npm install
npm run dev
```

El frontend estará disponible en `http://localhost:3000`

## Scripts Disponibles

### Backend
- `npm run dev` - Inicia el servidor en modo desarrollo
- `npm run build` - Compila el proyecto
- `npm start` - Inicia el servidor en producción
- `npm test` - Ejecuta las pruebas

### Frontend
- `npm run dev` - Inicia la aplicación en modo desarrollo
- `npm run build` - Compila para producción
- `npm test` - Ejecuta las pruebas

## Contribución

1. Crea una rama para tu feature: `git checkout -b feature/AmazingFeature`
2. Commit tus cambios: `git commit -m 'Add some AmazingFeature'`
3. Push a la rama: `git push origin feature/AmazingFeature`
4. Abre un Pull Request

## Licencia

Este proyecto está bajo la licencia MIT.
