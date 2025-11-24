FROM gcr.io/distroless/java17-debian12
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/monitoring.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/monitoring.jar"]

EXPOSE 8080