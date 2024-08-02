# Étape 1 : Image pour la construction de l'application
FROM eclipse-temurin:17.0.3_7-jdk-jammy

# Définir le répertoire de travail et se positionner dessus
WORKDIR /projects/github/depot/mkutano-frontend

# Copier le snaphot.jar dans le repertoire de travail et le renommer en code-frontend.jar
COPY /projects/github/depot/mkutano-frontend/target/quarkus-app/app/code-frontend-1.0.0-SNAPSHOT.jar  /projects/github/depot/mkutano-frontend/code-frontend.jar

# Exposer le port de l'application
EXPOSE 8089

# Démarrer l'application
CMD ["java", "-jar", "code-frontend.jar"]
