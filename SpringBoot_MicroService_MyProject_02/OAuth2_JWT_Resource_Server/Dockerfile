FROM adoptopenjdk:11-jre-hotspot
COPY target/*.jar app.jar
COPY /src/main/resources/static/user/image/profile_placeholder.png /src/main/resources/static/user/image/profile_placeholder.png 
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8080
