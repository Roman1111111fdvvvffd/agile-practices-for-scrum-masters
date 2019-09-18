# Build and Run
## Install environment
```bash
sudo apt install openjdk-8-jdk-headless
sudo apt install maven
```

## Build with Maven and Run raw distr
```bash
mvn clean verify
java -jar target/dbo-1.0-SNAPSHOT.jar --spring.profiles.active=it
```

# API Doc
http://localhost:8080/swagger-ui.html

# CI
- [Jenkins CI Server](http://54.82.86.207:8080/jenkins/)
- [Sonar Code Quaility Tool](http://54.82.86.207:9000)
