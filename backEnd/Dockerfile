FROM java:8-jre

MAINTAINER huali.dong@thoghtworks.com

VOLUME /vol/development

RUN mkdir -p /vol/development

WORKDIR /vol/development

COPY ./* /vol/development/app.jar

CMD ["java", "-Xmx200m", "-Djava.security.egd=file:/dev/./urandom","-jar","/vol/development/app.jar"]
