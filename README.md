# Main Chat

Proyecto demo para un chat en vivo con SocketIO, pero, con la propuesta de manejar MultInstancias con NestJS y REDIS.

## Importante

Para que esta demo funcione necesita que corra el docker-compose que está en el proyecto [Main Chat](https://github.com/CharlyEstudio/redis-multi-ins-sock-main)

## Dependencias

- [Back](https://github.com/CharlyEstudio/redis-multi-ins-sock-wsapp)
- [Front](https://github.com/CharlyEstudio/redis-multi-ins-sock-front)
- Docker
- Docker Compose
- Redis
- NodeJS
- NPM

## Indicaciones

1. Bajar los proyectos back y front y colocarlos dentro de este proyecto.
2. Tener instalado todas las dependencias.
3. En la terminal ir a la ruta raiz de Main Chat (No de back o de front).
4. Ejecutar ```npm run up```.
5. Abrir 2 exploradores (Puede ser el mismo, pero debe de estar como oculto).

Listo, ya tendrás corriendo multiples instancias del mismo servicio, conectado con SocketIO pero reconocido por REDIS.

***
<p>Se recomienda ver el vídeo</p>
