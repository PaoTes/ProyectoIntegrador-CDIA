# Catálogo de Productos con React + Vite

Este proyecto es un catálogo de productos creado utilizando React y Vite, con estilos proporcionados por Tailwind CSS y la comunicación con la API de [DummyJSON](https://dummyjson.com/) realizada mediante Axios.

## Tecnologías Utilizadas

* ⚙️**React:** Biblioteca de JavaScript para construir interfaces de usuario.
* ⚙️**Vite:** Herramienta de construcción que proporciona una experiencia de desarrollo extremadamente rápida.
* ⚙️**Tailwind CSS:** Framework de CSS de utilidad que permite un desarrollo rápido y flexible del diseño.
* ⚙️**Axios:** Cliente HTTP basado en promesas para realizar peticiones al API de DummyJSON.
* ⚙️**DummyJSON:** API REST gratuita para obtener datos de productos de prueba.

## 🔶EVIDENCIA 1 - Ejecutando el Proyecto 
**Instalando React-Vite**
 ```bash
> npm create vite@latest 
◇  Package name:
│  proyecto-ev1
◇  Select a framework:
│  React
◇  Select a variant:
│  JavaScript + SWC
└  Done. Now run:
 ```
**Una vez creado, acceder a la carpeta**
 ```bash
cd proyecto-ev1
 ```
**instalar dependencias**
 ```bash
npm install
 ```
**ejecutar proyecto**
 ```bash
npm run dev
 ```
**Instalar tailwind**
 ```bash
npm install tailwindcss @tailwindcss/vite
 ```
**Instalar axios**
 ```bash
npm install axios
 ```


    Esto abrirá la aplicación en tu navegador en `http://localhost:5173` (u otro puerto disponible).

## Estructura del Proyecto (Básica)

├── public/
│   └── ... (recursos estáticos)
├── src/
│   ├── assets/
│   │   └── ... (imágenes, etc.)
│   ├── components/
│   │   └── ProductCard.jsx
│   ├── hooks/
│   │   └── ... (hooks personalizados)
│   ├── services/
│   │   └── api.js (configuración de Axios y llamadas a la API)
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── ... (otros archivos de la aplicación)
├── index.html
├── package.json
├── README.md
├── vite.config.js
└── ... (otros archivos de configuración)

![captura de pantalla ev1-1](https://github.com/user-attachments/assets/d0c84a77-68fd-4fe0-8869-45414d6fcc14)

## 🔶EVIDENCIA 2 - Aplicación React  - Axios , filtros y Estadísticas 

**Modificaciones Funcionales**
* Se implementaron 2 componenetes: ProductList y StatsPanel.
* Mediante Taildwin se crearon 2 paneles, uno para cada componente.
* Modificaciones en el filtrado, para que impacte en el componente ProductList.
* SE mejoró el diseño y la responsividad con Tailwind CSS.


**Estadísticas Aplicadas**
* El producto más caro con nnombre y precio.
* El producto más barato con nnombre y precio.
* La cantidad de Productos cn más de 20 caracteres en el titulo.
* Precio Total de los productos filtrados.
* Promedio de decscuento de los productos filtrados.
* El producto mejor valorado con nombre y porcentaje.

![ev2](https://github.com/user-attachments/assets/2444473e-18b7-4776-88ed-c63f34789259)

