# docker-jboss-intellij
Docker, JBOSS and IntelliJ Project

This is a simple Java, JBoss and Docker project
Made in IntelliJ and ready for use

###How to get it up and running.
First have docker installed:

###Then:

```bash
git clone https://github.com/MarcRothWiese/docker-jboss-intellij.git
cd docker-jboss-intellij
docker -t jboss_intellij .
docker run -d -p 8080:8080 jboss_intellij
```

Go to: http://localhost:8080/
