# ECS656U-765PLab2StartingPoint
Based upon https://github.com/sajeerzeji/SpringBoot-GRPC
Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)
1. sudo apt update
2. sudo apt install default-jdk maven
mvn package -Dmaven.test.skip=true; chmod 777 mvnw; ./mvnw spring-boot:run -Dmaven.test.skip=true
4. (From grpc-server folder) chmod 777 mvnw
5. (From grpc-server folder) ./mvnw spring-boot:run -Dmaven.test.skip=true
mvn package -Dmaven.test.skip=true; chmod 777 mvnw; ./mvnw spring-boot:run -Dmaven.test.skip=true
7. (From grpc-client folder e.g. seperate ssh connection) 
8. (From grpc-client folder e.g. seperate ssh connection) ./mvnw spring-boot:run -Dmaven.test.skip=true

https://github.com/Candle-Wick/ECS656U-796PLab2StartingPoint

