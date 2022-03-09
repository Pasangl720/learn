vi docker-compose.yml
version: "3"
jenkins:
container_name: jenkins
image: jenkins/jenkins
ports:
"9090:9090"
volumes
- "pwd/jenkins-home:/var/jenkins-home"
- networks:
- -net
- networks:
net :
