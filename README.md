# Maven Hello World

This is a simple Maven project to demonstrate the basics of Maven build lifecycle.

---

## 📂 Project Structure

src/main/java → Application source code
src/test/java → Unit test code
pom.xml → Maven configuration file


---

## ⚙️ Prerequisites
- Java JDK 11+ installed
- Maven installed (`mvn -v` to verify)

---

## 🚀 Build Commands

### 1. Compile the project
```bash
mvn compile


Run tests
mvn test

Package into a JAR file
mvn package

The JAR will be generated in the target/ directory.

Run the application
java -cp target/maven-hello-world-1.0-SNAPSHOT.jar com.example.App

Install to local Maven repository (~/.m2/repository)
mvn install

Clean build files
mvn clean


Lifecycle in Short

mvn validate → Validate project

mvn compile → Compile source code

mvn test → Run unit tests

mvn package → Create JAR/WAR

mvn install → Add to local repo

mvn deploy → Push to remote repo
