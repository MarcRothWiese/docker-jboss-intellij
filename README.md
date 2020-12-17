# Docker / JBoss / intellij
Docker, JBOSS and IntelliJ Project

This is a simple Java, JBoss and Docker project
Made in IntelliJ and ready for use

### How to get it up and running.
First have docker installed:
https://docs.docker.com/get-docker/

### Then:

```bash
git clone https://github.com/MarcRothWiese/docker-jboss-intellij.git
cd docker-simplejboss
docker -t simplejboss .
docker run -d -p 8080:8080 simplejboss
```

Go to: http://localhost:8080/simpleboss/
