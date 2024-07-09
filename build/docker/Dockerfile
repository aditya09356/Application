FROM openjdk:17-oracle
LABEL maintainer=home
WORKDIR /app
COPY libs libs/
COPY resources resources/
COPY classes classes/
ENTRYPOINT ["java", "-cp", "/app/resources:/app/classes:/app/libs/*", "com.Application.Application"]
EXPOSE 8081
