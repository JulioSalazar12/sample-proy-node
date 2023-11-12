### Crear un Proyecto Node.js con Express y Swagger

A continuación, se presenta una guía paso a paso para iniciar un proyecto Node.js con Express y Swagger para desarrollar una aplicación de finanzas.

#### 1. Iniciar un nuevo proyecto Node.js con npm:

```bash
npm init -y
```

Esto inicializará un nuevo proyecto Node.js y generará un archivo `package.json` con configuraciones predeterminadas.

#### 2. Instalar las dependencias necesarias:

```bash
npm install express swagger-jsdoc swagger-ui-express body-parser
```

- `express`: Framework para construir aplicaciones web en Node.js.
- `swagger-jsdoc`: Genera automáticamente la documentación Swagger a partir de comentarios JSDoc en tu código.
- `swagger-ui-express`: Proporciona una interfaz web para la documentación Swagger.
- `body-parser`: Middleware para analizar el cuerpo de las solicitudes HTTP.

#### 3. Configurar Express y Swagger:

Crea un archivo `app.js` y configúralo para incluir Express y Swagger. Puedes encontrar un ejemplo de configuración en el código proporcionado anteriormente.

#### 4. Definir el esquema de la API en Swagger:

Dentro del archivo `app.js`, utiliza anotaciones JSDoc para describir la API. Asegúrate de definir los endpoint, los métodos HTTP permitidos, y el formato de los datos de entrada y salida.

#### 5. Ejecutar la aplicación:

```bash
node app.js
```

#### 6. Acceder a la documentación Swagger:

Abre tu navegador y visita [http://localhost:3000/api-docs](http://localhost:3000/api-docs). Aquí encontrarás la interfaz de usuario generada automáticamente para explorar y probar tu API.

¡Ahora tienes un proyecto básico Node.js con Express y Swagger para desarrollar tu aplicación de finanzas! Puedes personalizar la lógica de negocio y expandir la API según tus necesidades.