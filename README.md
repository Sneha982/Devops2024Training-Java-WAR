# Devops2024Training-Java-WAR

**docker-tomcat-webapp- A basic tutorial on running a web app on Tomcat using Docker ***


>>Tomcat 404 issues- https://www.topzenith.com/2020/07/http-status-404-not-found-docker-tomcat-image.html

Steps

1. Install Docker.

2. Clone this repository - $git clone https://github.com/Sneha982/Devops2024Training-Java-WAR.git

3. cd Devops2024Training-Java-WAR # from your root directory

4. Install java and maven

5. Build the web app using maven-  mvn clean install

6. Write the Dockerfile

7. $docker build -t mywebapp .

8. $docker run -d --name mywebapp -p 8081:8080 mywebapp

9. http://localhost:8081
