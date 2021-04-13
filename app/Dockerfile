FROM maven:3.5-jdk-8
COPY C:/WINDOWS/system32/config/systemprofile/AppData/Local/Jenkins/.jenkins/workspace/ci-final@2/app/target/*.war app.war
ENTRYPOINT [ "java","-jar","app.war" ]
