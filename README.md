# Desafío Blog Frontend II

## Skills fundamentales

1. Usar Sass y el patrón arquitéctonico 7-1 para organizar los estilos del proyecto.

## Flujo de navegación del proyecto

Los requerimientos 3 y 4 de la pauta sugieren el modelo de navegación presentado al usuario. Dicen explícitamente:

- A dar clic al botón de registrar cuenta, debe navegar a la página de login. 
- En el login, al dar clic en el botón iniciar sesión debe navegar a la página principal. (desafio anterior)
- La nueva página del post debe tener un enlace de navegación (desde la principal)

De lo anterior deduciremos por experiencia de usuario que nuestro index.html será la página de login y partir de ella se podrá navegar tanto al registro como a la página principal. Y desde la página principal se podrá navegar al post solicitado. Por experiencia de usuario también implementaremos que al clickear en algún botón en el post, podamos volver a la página principal.




## Instalar Sass

Este es un proceso que se realiza globalmente si queremos utilizarlo frecuentemente aunque también es posible instarlo de forma local a un proyecto en específico. El material del curso lo instala de forma global utilizando el flag -g con el siguiente comando:

`npm install -g sass`

luego de instalado, puedes probar la versión utilizando el comando: 

`sass --version`

**OBS:** Si al intentar instalar en un Mac la terminal responde con un error de autorización deben usar el comando de la siguiente manera: 

`sudo npm install -g sass`

Este comando lanzará un prompt a la terminal para ingresar la clave de usuario y poder completar la operación.

Si la instalación fue correcta, entonces puedes ejecutar el comando que compila los archivos en el manifiesto main.scss y los transforma en un solo archivo style.css en assets/css:

`sass --watch assets/sass/main.scss:assets/css/style.css`

[ENLACE](./assets/sass/abstracts/_variables.scss#L10)


