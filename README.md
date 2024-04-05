# Devops2024Training-Java-WAR

docker-tomcat-webapp
A basic tutorial on running a web app on Tomcat using Docker 

Steps
Install Docker.
Clone this repository - $git clone https://github.com/Sneha982/Devops2024Training-Java-WAR.git
cd Devops2024Training-Java-WAR # from your root directory
$docker build -t mywebapp .
$docker run -d --name mywebapp -p 8081:8080 mywebapp
http://localhost:8081
