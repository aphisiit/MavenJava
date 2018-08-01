# How to run project java via maven

#### Run project
```sh
mvn exec:java -D"exec.mainClass"="com.example.anno.Main"
```

#### Build Project to jar
```sh
mvn clean compile package
```

#### Run project with jar
```sh
java -jar .\target\anno-1.0-SNAPSHOT.jar com.example.anno.Main
```
