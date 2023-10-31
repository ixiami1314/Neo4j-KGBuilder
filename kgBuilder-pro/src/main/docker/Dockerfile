#FROM openjdk:8-jdk

FROM openjdk:8-jre-alpine
MAINTAINER baiyuetong <weijun@baiyuetong.cn>
VOLUME /tmp
ADD pmy-kg-release.jar kg.jar
ENTRYPOINT ["java", "-Xms200m", "-Xmx1G", "-Duser.timezone=GMT+08", "-jar", "/kg.jar"]