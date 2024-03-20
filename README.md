# Chat Real Time

Este es un proyecto de chat en tiempo real que utiliza Node.js en el backend con Express y Socket.IO, y HTML/CSS/JavaScript en el frontend.

## Características

- Permite a los usuarios unirse a una sala de chat ingresando un nombre de usuario.
- Muestra un mensaje de actualización cuando un usuario se une o abandona la sala.
- Permite a los usuarios enviar mensajes de chat en tiempo real.
- Los mensajes de chat se muestran en la pantalla para todos los usuarios en la sala.

## Instalación

1. Clona este repositorio en tu máquina local utilizando Git:

    ```
    git clone https://github.com/CAntonioGQ/Chat-Real-Time-JavaScript-Express-Socket.io
    ```

2. Ve al directorio del proyecto:


3. Instala las dependencias del proyecto utilizando npm:

    ```
    npm install
    ```

## Uso

1. Ejecuta el servidor Node.js:

    ```
    node Server.js
    ```

2. Abre tu navegador web y accede a `http://localhost:5000` para ver la aplicación de chat en tiempo real.

3. Ingresa un nombre de usuario en la pantalla de unión y haz clic en "Join" para unirte al chat.

4. Escribe mensajes en el cuadro de entrada y haz clic en "Sent" para enviar mensajes a la sala de chat.

## Estructura del Proyecto

- `public/`: Contiene los archivos estáticos (HTML, CSS, JavaScript) para el frontend de la aplicación.
- `server.js`: El archivo principal del servidor Node.js que define la lógica del backend utilizando Express y Socket.IO.

## Contribución

Si encuentras algún problema o tienes alguna idea de mejora, ¡no dudes en abrir un issue o enviar un pull request!

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
