# Repositorio para la aplicación completa "Seguí tus compras" grupo 7

## Para ejecutar la aplicación

1. Clonar el repo y sus submódulos: `git clone --recurse-submodules https://github.com/Pestigirioso/unq_desasof_app_grupo7`
2. Acceder a la ruta del repositorio: `cd unq_desasof_app_grupo7`
3. En la ruta unq_desasof_backend crear un archivo .env que contendrá lo siguiente:

```
CLIENT_ID = <el client id>
CLIENT_SECRET = <el client secret>
REFRESH_TOKEN = <El refresh token>
```

4. Luego de clonar el repo, ejecutar `docker compose -f unq_desasof_app_grupo7/docker-compose.yml up --build`
5. Para explorar la aplicación, ir a `http://localhost:3000`

- Usuario comprador de ejemplo: user: `buyer1` - pass: `buyer1pass`
- Usuario administrador de ejemplo: user: `admin1` - pass: `admin1pass`

## Para acceder a otros recursos

- Swagger: http://localhost:8000/docs#/
- Grafana: http://localhost:4000/login

## Tecnologías utilizadas

### Backend:

- Python
- fastapi
- pytest

### Frontend

- Node.js
- Typescript
- Vite
- React
- Cypress
