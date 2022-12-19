## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version-17
```


1. Crear centa en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. git confi --global user.name "{nombre}"
   2. git config ---global user.email {email}
3. Subir el proyecto a GitHub desde Intellij IDEA desde la opcion VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método GitHubb y buscar el repositorio subido
5. Habilitar deploy automatico y ejecutar el Deploy