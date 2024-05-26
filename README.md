# Consumo de datos desde una API REST

## Descripción del Proyecto

Este proyecto tiene como objetivo validar nuestros conocimientos en el consumo de APIs REST mediante la creación de una aplicación interactiva. Utilizando el framework Vue.js y la API Random User, la aplicación permite simular una conversación de chat entre dos personas obtenidas aleatoriamente.

## Funcionalidades

### Visualización de Usuarios:

- La aplicación muestra dos usuarios con sus imágenes y nombres obtenidos de la API Random User.

### Interacción del Usuario:

- Cada usuario puede ingresar mensajes en un campo de entrada.
- Al enviar el mensaje, este se muestra en el área de chat correspondiente.

### Actualización y Feedback:

- Los mensajes se actualizan automáticamente en la interfaz.
- La aplicación permite una experiencia de chat fluida y reactiva.

### Características Adicionales:

- Los usuarios se cargan automáticamente al iniciar la aplicación.
- Cada vez que se recarga la página, se obtienen dos nuevos usuarios aleatorios.

## Uso de la API Random User

Para obtener los datos necesarios, se consulta el siguiente endpoint de la API Random User, que proporciona datos de usuarios aleatorios:

```
https://randomuser.me/api/
```

## Tecnologías Utilizadas

- **Framework**: Vue.js
- **Herramienta de Construcción**: Vite
- **API**: Random User
- **Lenguajes**: JavaScript, HTML, CSS

## Instrucciones para Ejecutar o Visualizar

### Configuración del Proyecto:

Asegúrate de tener Node.js y npm instalados.

1. Clona este repositorio y navega a la carpeta del proyecto.
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
   ```

2. Instala las dependencias necesarias.
   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo.
   ```bash
   npm run dev
   ```

4. Abre tu navegador y ve a `http://localhost:5173` para ver la aplicación en funcionamiento.

## Contribuir

¡Me encantaría contar con tu colaboración para mejorar este proyecto! Si tienes ideas para nuevas funcionalidades, mejoras en la interfaz, corrección de errores o cualquier otra sugerencia, no dudes en contribuir. Aquí tienes cómo puedes hacerlo:

1. Haz un fork de este repositorio para tener una copia en tu cuenta de GitHub.

2. Clona el repositorio a tu máquina local.
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```

3. Crea una nueva rama para trabajar en tu funcionalidad o corrección.
   ```bash
   git checkout -b nombre-de-tu-rama
   ```

4. Realiza los cambios necesarios y confirma los cambios.
   ```bash
   git add .
   git commit -m "Descripción de tus cambios"
   ```

5. Envía tus cambios a tu repositorio fork.
   ```bash
   git push origin nombre-de-tu-rama
   ```

6. Desde tu repositorio fork en GitHub, crea un pull request hacia el repositorio original.

## Agradecimientos

¡Gracias por tu interés en contribuir! Espero tus pull requests y sugerencias para hacer de esta aplicación algo aún más increíble.
