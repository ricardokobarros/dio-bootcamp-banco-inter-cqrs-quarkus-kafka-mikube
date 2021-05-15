FROM openjdk:8

RUN mkdir /usr/myapp

COPY ./ /usr/myapp/
# WORKDIR /usr/myapp/

EXPOSE 8080 
ENTRYPOINT [ "sh", "-c", "ls -la /usr/myapp/" ]
#ENTRYPOINT [ "sh", "-c", "java --enable-preview $JAVA_OPTS -jar /usr/myapp/balance.jar" ]
