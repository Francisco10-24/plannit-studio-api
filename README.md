# Plannit Studio API

Datos de prueba para la app móvil Plannit Studio (marketplace de decoración de eventos, San Salvador).

## Endpoints usados por la app
- `GET  https://cdn.jsdelivr.net/gh/Francisco10-24/plannit-studio-api@main/db.json`
  Devuelve `paquetes`, `extras` y `decoradores` (HTTPS, JSON, CORS habilitado).
- `POST https://jsonplaceholder.typicode.com/posts`
  Simula el envío de la solicitud al decorador (responde `201 Created`, no guarda datos).

## Alternativa
El mismo `db.json` es compatible con my-json-server:
`https://my-json-server.typicode.com/Francisco10-24/plannit-studio-api/paquetes`
(al momento de crear el repo ese servicio respondía 530, por eso la app usa jsDelivr).

Fotos: Unsplash (licencia Unsplash).
