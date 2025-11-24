FROM gcr.io/distroless/java17-debian12
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/notification-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/notification-service.jar"]

EXPOSE 8000