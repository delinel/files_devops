# Mon image de base
FROM maven:3-openjdk-17

# Répertoire de travail
WORKDIR /myfront-app

# Copier le snaphot.jar dans le repertoire de travail et le renommer en code-frontend.jar
COPY -r /projects/github/depot/mkutano-frontend/*  /myfront-app

# Exposer le port de l'application
EXPOSE 8080

# Démarrer l'application
ENTRYPOINT ["java", "-jar", "/myfront-app/target/code-frontend-1.0.0-SNAPSHOT-native-image-source-jar/code-frontend-1.0.0-SNAPSHOT-runner.jar"]
