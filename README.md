
## Despliegue de apps Spring Boot en heroku 
Crear el archivo 'system.properties' en el proyecto con el contenido:
...
java.runtime.version=17
...

1. Crear cuenta en heroku.com y github.com
2. Tener configurado en el ordenador:
   1. `git config --global user.name ""aquí el nombre elegido"`
   2. `git config --global user.email ""aquí el email elegido`
3. Subir el proyecto a github desde Intellij IDEA desde la opción VCS -> share project on Github
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático (según proyecto) y ejecutar Deploy


