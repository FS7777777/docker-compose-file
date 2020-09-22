FROM openjdk:8-jre-alpine
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo 'Asia/Shanghai' >/etc/timezone
ENV JAVA_OPTS -Dspring.config.location=config/application.properties
COPY svc-api.jar /opt/.
WORKDIR /opt
#ENTRYPOINT ["java","-jar","${JAVA_OPTS}","svc-api.jar"]
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar svc-api.jar" ]



