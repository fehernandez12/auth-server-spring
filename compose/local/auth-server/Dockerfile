# Build
FROM amazoncorretto:17 AS build

# Set the compiled jar
ARG JAR_FILE=*.jar
COPY /build/libs/${JAR_FILE} application.jar

# Run
ENTRYPOINT ["java","-jar","/application.jar"]