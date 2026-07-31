FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY . .
RUN ./mvnw package -DskipTests || true
EXPOSE 8080
CMD ["java","-jar","target/*.jar"]