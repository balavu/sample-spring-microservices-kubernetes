FROM amazoncorretto:17
WORKDIR /app
COPY /var/lib/jenkins/workspace/dso-poc/admin-service/target/admin-service-1.1.jar .
EXPOSE 8080
CMD ["java", "-jar", "admin-service-1.1.jar"]
