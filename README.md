# proyecto universidad (versión aplicación monolítica)

### `npm start`

Comando para levantar la aplicación 

Se abre en la URL http://localhost:5002/ de tu navegador

Aplicación monolítica del proyecto universidad.
Sirve para los siguientes URL (router) con sus servicios Get, Post y Put:
- Proyecto: http://localhost:5002/proyecto
- Etapa Proyecto: http://localhost:5002/etapa-proyecto
- Tipo Proyecto: http://localhost:5002/tipo-proyecto
- Universidad: http://localhost:5002/universidad
- Cliente: http://localhost:5002/cliente

Esta misma se separa en:
- Módulo core (sin servicio Get Proyecto): https://github.com/Rookie-26/core2micro
- Módulo microservicio Get Proyecto: https://github.com/Rookie-26/microget
