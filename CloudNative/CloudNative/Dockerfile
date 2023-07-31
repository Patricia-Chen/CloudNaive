  
FROM java:8

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone

WORKDIR /app
ADD target/cloud-native-project-0.0.1-SNAPSHOT.jar .

ENTRYPOINT ["java","-jar","cloud-native-project-0.0.1-SNAPSHOT.jar"]
