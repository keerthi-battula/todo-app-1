FROM maven:3.5-jdk-8
COPY artifacts/todo-app/TodoDemo-0.01-SNAPSHOT.war app.war
ENTRYPOINT [ "java","-jar","app.war" ]
