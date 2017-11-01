# sample-spring-boot-app
sample-spring-boot-app


## Build and create jar

```
./gradlew build && java -jar build/libs/gs-spring-boot-0.1.0.jar
```


## Run the curl command to check the service

```$ curl localhost:8080
   Greetings from Spring Boot!
   
   $curl localhost:8080/health
   
   $curl -X POST localhost:8080/shutdown
```


## Test services
```
testCompile("org.springframework.boot:spring-boot-starter-test")
```

## Production grade services

```
    compile("org.springframework.boot:spring-boot-starter-actuator")
```


