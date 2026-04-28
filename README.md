# playground

Simple Maven-based Java command-line app scaffolded for IntelliJ IDEA.

## Structure

- `pom.xml`: Maven project configuration
- `src/main/java/dev/codex/playground/App.java`: entry point

## Commands

```powershell
mvn compile
mvn exec:java
mvn package
java -jar target/playground-1.0-SNAPSHOT.jar
```

## IntelliJ IDEA

Open the repo as a project and IntelliJ should detect `pom.xml` as a Maven project.
If IDEA prompts for a JDK, use the JDK referenced by your local machine's `JAVA_HOME`.
