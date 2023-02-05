## Despliegue de apps Spring Boot en Heroku

1. Crear archivo `system.properties` en el proyecto con el contenido:
```
java.runtime.version=19
```
2. Crear cuenta en heroku.com y github.com.
3. Tener configurado git en el ordenador.
    1. `git config --global user.name "Erableto"`
    2. `git config --global user.email erableto@erableto.com`
4. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción VCS > Share project on GitHub.
5. Desde Heroku, crear la app y elegir el método GitHub y buscar el repositorio subido.
6. Habilitar el deploy automático y ejecutar el deploy.