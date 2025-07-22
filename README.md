# Desafio-5
El siguiente desafío tiene como objetivo desarrollar un build en docker y configurar un entorno local para que corra una aplicación con docker-compose.

## Herramientas utilizadas
Sandbox AWS
Docker
Netjs
mongodb

## 📂 Estructura del Proyecto


### `Dockerfile`

Define cómo construir la imagen de la aplicación NestJS. Instala dependencias, compila el proyecto y agrega el puerto 3000.

### `docker-compose.yaml`

Levanta dos servicios:

- **app**: la aplicación NestJS, conectada a MongoDB.
- **mongo**: base de datos MongoDB con persistencia local.

Incluye un volumen `mongo_data` para mantener los datos entre sesiones.


