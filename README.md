# TASK MANAGER
 
A fullstack task management application built with React (Vite) on the frontend and Express (TypeScript) on the backend.
It supports full CRUD operations, user authentication, filtering, pagination, and is fully documented with Swagger and tested with Vitest and Jest.
 
[![CI](https://github.com/alvaradoramosjose/task-manager/actions/workflows/ci.yml/badge.svg)](https://github.com/alvaradoramosjose/task-manager/actions/workflows/ci.yml)
 
## Instalacion local
 
```bash
git clone git@github.com:alvaradoramosjose/task-manager.git
cd task-manager-react
npm install
```
 
### Variables de entorno
Crea un archivo `.env` en la raiz con las siguientes claves (sin valores reales en este documento):
 
```
DATABASE_URL=
JWT_SECRET=
PORT=
```
 
## Comandos disponibles
 
| Comando          | Descripcion                              |
|------------------|-------------------------------------------|
| `npm run dev`    | Levanta el entorno de desarrollo           |
| `npm run build`  | Genera el build de produccion              |
| `npm test`       | Corre las pruebas automatizadas (pendiente ¡ª Sesion 3) |
 
## Base de datos
 
PostgreSQL con migraciones y seeds gestionados con Prisma (ver Modulo 2).

