# Define a imagem base (imagem com java 11)
FROM openjdk:11.0.4-jre-slim

# cria diretório na imagem
RUN mkdir /app

# copia o .jar para a imagem
COPY target/dsmovie-0.0.1-SNAPSHOT.jar /app/dsmovie.jar

# define o comando de execução do .jar
CMD ["java", "-jar", "/app/dsmovie.jar"]
