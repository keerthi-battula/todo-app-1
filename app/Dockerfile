FROM maven:3.5-jdk-8
COPY /var/jenkins_home/workspace/todo-app-complete-ci-cd/app/TodoDemo-0.0.1-SNAPSHOT.war app.war
ENTRYPOINT [ "java","-jar","app.war" ]
