# Hospital Nueva Vida - Sistema de Gestión de Citas Médicas

## Descripción
La aplicación "Hospital Nueva Vida" es un sistema simple de gestión de citas médicas desarrollado con **React**, utilizando **IndexedDB** para el almacenamiento de citas en el navegador y compatible con **PWA (Progressive Web App)** para funcionalidad offline.

## Características
- **Autenticación de Usuario:** Inicio y cierre de sesión con almacenamiento en `localStorage`.
- **Gestión de Citas:** Permite agregar, visualizar y eliminar citas utilizando **IndexedDB**.
- **Interfaz Simple:** Botones claros y acceso rápido a las funcionalidades.
- **PWA:** La aplicación es instalable y funciona sin conexión gracias al **Service Worker**.

## Tecnologías Utilizadas
- **Frontend:** React, React Router, Vite
- **Almacenamiento:** IndexedDB
- **PWA:** Service Worker, Manifest.json
- **Estilos:** CSS simple

## Estructura del Proyecto
```
hospital-nueva-vida/
├─ public/
│   ├─ manifest.json
│   ├─ service-worker.js
│   └─ index.html
├─ src/
│   ├─ components/
│   │   ├─ PatientForm.jsx
│   │   ├─ DoctorsList.jsx
│   │   └─ PatientsList.jsx
│   ├─ hooks/
│   │   └─ useAuth.js
│   ├─ utils/
│   │   └─ indexedDB.js
│   ├─ App.tsx
│   ├─ main.tsx
│   └─ styles.css
└─ package.json
```

## Instrucciones para Ejecutar
1. Clonar el repositorio.
2. Instalar las dependencias con:
```
npm install
```
3. Ejecutar la aplicación en modo desarrollo:
```
npm run dev
```
4. Acceder en el navegador a:
```
http://localhost:5173
```

Carlos Farias Galdames

