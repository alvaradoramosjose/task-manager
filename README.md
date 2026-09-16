# TASK MANAGER REACT
 
A fullstack task management application built with React (Vite) on the frontend and Express (TypeScript) on the backend.
It supports full CRUD operations, user authentication, filtering, pagination, and is fully documented with Swagger and tested with Vitest and Jest.
 
[![CI](https://github.com/alvaradoramosjose/task-manager-react/actions/workflows/ci.yml/badge.svg)](https://github.com/alvaradoramosjose/task-manager-react/actions/workflows/ci.yml)
 
## ?? Instalaci車n local
 
```bash
git clone git@github.com:alvaradoramosjose/task-manager-react.git
cd task-manager-react
npm install
```
 
### Variables de entorno
Crea un archivo `.env` en la ra赤z con las siguientes claves (sin valores reales en este documento):
 
```
DATABASE_URL=
JWT_SECRET=
PORT=
```
 
## ?? Comandos disponibles
 
| Comando          | Descripci車n                              |
|------------------|-------------------------------------------|
| `npm run dev`    | Levanta el entorno de desarrollo           |
| `npm run build`  | Genera el build de producci車n              |
| `npm test`       | Corre las pruebas automatizadas (pendiente 〞 Sesi車n 3) |
 
## ??? Base de datos
 
PostgreSQL con migraciones y seeds gestionados con Prisma (ver M車dulo 2).

