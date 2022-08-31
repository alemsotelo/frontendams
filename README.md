💻 Portfolio Web - #YoProgramo
En este repositorio se encuentra todo lo relacionado al Frontend del proyecto.

📝 Descripción
Portfolio Web Fullstack realizado como Proyecto Final del curso Argentina Programa - #YoProgramo.

Se trata de una Single Page Application (SPA) realizada utilizando tecnologías Frontend como ser HTML, CSS, Angular y Bootstrap.


✅ Manejo de la App
Podemos ingresar a través del apartado "INGRESO" en el encabezado de la página.
Una vez ingresada a la cuenta, se pueden modificar los datos de Educacion y de Experiencia laboral (en esta primera version)

⌨🖱 Instalación
Si queremos correr la aplicación en un entorno local debemos tener en cuenta lo siguiente:
Clonar el repositorio utilizando GIT o descargando el archivo ZIP:

git clone https://github.com/alemsotelo/frontendams.git

Instalar las dependencias a través de NPM.

npm install

Configurar las variables de entornos en src/enviroments/enviroment.ts, donde configuraremos 3 propiedades:

baseUrl: La URL de base para las conexiones con nuestra API REST. EJ:

baseUrl: "http://localhost:8080"

authApi: La URL para realizar las autenticaciones en nuestra API REST. EJ:

authApi: "http://localhost:8080/api/auth"

frontUrl: La URL para redireccionar y realizar distintas operaciones en nuestro Frontend. EJ:

frontUrl: "http://localhost:4200/portfolio/" (incluir el slash o barra diagonal al final).

Compilar y montar el proyecto utilizando el comando ng serve

IMPORTANTE: Debemos tener un servidor con el proyecto Backend activo para poder obtener los datos y registrar usuarios, caso contrario, no se renderizarán los componentes de Angular. Para más información ir al repositorio backend.
