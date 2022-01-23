FROM adoptopenjdk/openjdk11:latest 
RUN adduser --system --group notes 
ENV MAVEN_VERSION 3.8.4
ENV MAVEN_HOME /usr/lib/mvn
ENV PATH $MAVEN_HOME/bin:$PATH
ENV CENTOS_FRONTEND noninteractive
RUN yum --update add git
RUN mkdir /opt/note
RUN chown -R notes:notes /opt/note
USER notes:notes
WORKDIR /opt/note
RUN git clone https://github.com/callicoder/spring-boot-mysql-rest-api-tutorial.git /opt/note
RUN /usr/lib/mvn package -Dmaven.test.skip=true
ARG JAR_FILE=*.jar
COPY $JAR_FILE /opt/note/
RUN cp ./target/easy-notes-1.0.0.jar /opt/note/easy-note.jar
COPY ${JAR_FILE} easy-note.jar
COPY application.properties application.properties
ENTRYPOINT ["java", "-jar", "/root/easy-notes.jar"]