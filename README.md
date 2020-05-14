# Tomcat9 with openjdk 14 on CentOS 7
Docker image of Tomcat 9 with openjdk 14 on CentOS 7. SSL activated on  Tomcat and a sample deployed application (sample.war).

Create container as:

$docker run -d --name tomcat9 -p 8443:8443 plutarcog/tomcat9
