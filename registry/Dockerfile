FROM gcr.io/distroless/java17-debian12
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/registry.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/registry.jar"]

EXPOSE 8761