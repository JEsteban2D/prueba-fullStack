# 🛍️ CRUD de Productos - Prueba Full Stack

Este proyecto es una prueba Full Stack que implementa un CRUD de productos utilizando **Angular 19** en el frontend y **Node.js con Express** en el backend.  
Los productos se obtienen por defecto desde la API pública [FakeStoreAPI](https://fakestoreapi.com/products), pero también se puede configurar para usar una base de datos **MySQL**.

## 🚀 Tecnologías Utilizadas
### Frontend:
- Angular 19
- TypeScript
- CSS

### Backend:
- Node.js
- Express.js
- MySQL (opcional)

## 📂 Estructura del Proyecto

### 📌 **Frontend (Angular)**
Ubicado en la carpeta `/prueba-front-angular`, está compuesto por:
- **3 Componentes** para organizar la lógica de la interfaz.
- **1 Modelo (`Product.ts`)** para definir la interfaz de los productos.
- **1 Servicio (`ProductService.ts`)** para la conexión con el backend.

### 📌 **Backend (Node.js + Express)**
Ubicado en la carpeta `/prueba-back-node`, tiene:
- **`index.js`** → Archivo principal que inicia el servidor.
- **`routes/`** → Carpeta que contiene:
  - `apiRoutes.js` → Maneja las peticiones a la API FakeStore.
  - `dbRoutes.js` → Maneja la conexión con la base de datos (comentado por defecto).
- **`db.js`** → Configuración de la conexión a MySQL (opcional).

## ▶️ Cómo Ejecutar el Proyecto FRONT
- **cd prueba-front-angular
- **npm install
- **ng serve    # O usa npm start

## ▶️ Cómo Ejecutar el Proyecto BACK
- **cd prueba-back-node
- **npm install
- **node index
