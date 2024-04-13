# Parcial 1: parcial_1DAW_GT1

## Instrucciones para correr el proyecto

### Paso 1: Eliminar imágenes y caché previamente creadas

Para eliminar las imágenes previamente creadas y borrar la caché de esas imágenes, ejecuta el siguiente comando:

 mvn clean package -DskipTests

### Paso 2: Borrar el contenedor y su respectiva imagen
 
 contenedor: java_app
 Imagen: crud-java

Una vez eliminadas las imágenes y la caché, nos vamos al paso 3. 

## Paso 3: Puedes correr el proyecto utilizando Docker Compose con el siguiente comando:

docker-compose up -d    

Este comando construirá las imágenes nuevamente y ejecutará los contenedores necesarios para el proyecto.

## Integrantes del equipo

- Milton Obed Alas Hernandez - AH09062
- Lilian Sofia Tejada Villatoro - TV22008
- David Alfredo Parada Mendoza - PM13119