```
mkdir -p src/main/java/com/gnuhub/gradle/example/simple/
touch build.gradle
touch src/main/java/com/gnuhub/gradle/example/simple/HelloWorld.java
gradle build 
java -cp build/classes/main/ com.gnuhub.gradle.example.simple.HelloWorld
```