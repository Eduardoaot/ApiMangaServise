# Usa una imagen base de Java 21
FROM openjdk:21-jdk-slim

# Establece un directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el archivo JAR generado por Maven al contenedor
COPY target/coleccion-0.0.1-SNAPSHOT.jar app.jar

# Expone el puerto en el que tu aplicación Spring Boot está escuchando
EXPOSE 8080

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]