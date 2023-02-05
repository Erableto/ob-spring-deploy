## Despliegue de apps Spring Boot en Heroku

1. Crear archivo `system.properties` en el proyecto con el contenido:
```
java.runtime.version=19
```
2. Crear cuenta en heroku.com y github.com.
3. Tener configurado git en el ordenador (ejecutar únicamente la primera vez que se instala git):
    1. `git config --global user.name "Erableto"`
    2. `git config --global user.email erableto@erableto.com`
4. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub.
5. Desde Heroku, crear la app y elegir el método GitHub y buscar el repositorio subido.
6. Habilitar el deploy automático y ejecutar el deploy.

## Ejercicio 1

* Probar a empaquetar la aplicación con maven package desde IntelliJ IDEA.
* Desde el terminal en IntelliJ IDEA, verificar que se ejecuta correctamente con el comando:
```
java -jar target/ob-spring-deploy-1.0.jar
```
* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

* Desplegar el API REST de Laptops en Heroku y verificar el funcionamiento desde Postman.

## Proveedores Cloud

* Heroku -- Java, Spring, PostgreSQL... https://heroku.com
* Netlify -- Frontend (React, Angular...) https://netlify.com
* Vercel -- Frontend (React, Angular...) https://vercel.com