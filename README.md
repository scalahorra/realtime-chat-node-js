# realtime-chat-node-js

## Funcionalidad
Esto es un proyecto para ver el funcionamiento del sistema de websocket.  
El ejercicio es muy sencillo. Consiste en un chat en el que pones mensajes y se tiene que leer y actualizaren todos los sitios donde se esté ejecutando a la vez.

## Instalación

Clonar repositorio
```
$ git clone https://github.com/scalahorra/realtime-chat-node-js.git
```
Instalar dependencias
```
$ npm install
```
Iniciar las conexiones
```
$ npm run dev
```

## Dependencias

### Express
Framework para Node.js que nos permitirá la creación de APIs.

### Morgan
Biblioteca que nos va a permitir tener una trazabilidad de las peticiones que se realizan en la app.

### Socket.io
Biblioteca que nos va a permitir establecer una conexión en tiempo real con el servidor