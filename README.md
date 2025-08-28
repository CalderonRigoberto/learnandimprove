# Proyecto práctica Spring Boot + Postgres + Jib + Docker

### ¿Por qué este tipo de proyectos?

Estoy practicando para demostrar el uso de docker y jib en aplicaciones Java, además de conectar a una base de datos como postgres.

### Referencia de documentación
Para mayor información consulta las siguientes referencias:

* [Jib](https://github.com/GoogleContainerTools/jib)
* [Como usar postgres con Docker](https://www.docker.com/blog/how-to-use-the-postgres-docker-official-image/)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.5/maven-plugin/build-image.html)

### Instrucciones

1. Ejecuta el ciclo de vida de la app con maven install, esto creará la imágen local.
    ```shell
    mvn clean install
    ```
2. Ejecuta  
    ```shell
    docker compose up -d
    ```

