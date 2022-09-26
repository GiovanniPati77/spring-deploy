## Despliegue de app Spring Boot en Heroku

Crear archivo ``system.properties`` en el proyecto con el contenido:
``
java.runtime.version=18
``

1. Crear cuenta en Heroku.com y github.com
2. Tener configurado git en el ordenador
    1. git config --global user.name "Giovanni"
    2. git config --global user.email giovanni.example.com
3. Subir el proyecto a GitHub desde intellij  desde la opcion: VCS > share project on GitHub
4. Desde Heroku crear app y elegir metodo GitHub y buscar el repositorio subido 
5. Habilitar deploy automatico y ejecutar el Deploy
