# Mon image de base
FROM maven:3-openjdk-17

# Répertoire de travail
WORKDIR /projects/github/depot/mkutano-frontend

# Copier le snaphot.jar dans le repertoire de travail et le renommer en code-frontend.jar
#COPY /projects/github/depot/mkutano-frontend/target/quarkus-app/app/code-frontend-1.0.0-SNAPSHOT.jar  /projects/github/depot/mkutano-frontend/code-frontend.jar

# Exposer le port de l'application
EXPOSE 8089

# Démarrer l'application
CMD ["java", "-jar", "target/code-frontend-1.0.0-SNAPSHOT-native-image-source-jar/code-frontend-1.0.0-SNAPSHOT-runner.jar"]
