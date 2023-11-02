# Spring Boot Parent Example

Spring Boot Parent Example use *spring-boot-starter-parent* as main parent and add the following features:

- Prevent duplicated dependencies (Maven Enforcer)
- Google Checkstyle (Maven and Puppycrawl Checkstyle)
- Unit test execution (Maven Surefire)
- Java code coverage and reporting (JaCoCo)

---
## Justification

Spring Boot Parent Example is a starter project that use *spring-boot-starter-parent* to quickly build a Spring Boot project.

Using this project will reuse all the default parent implementation and, additionally, will be added some features and pre-configurations.

---
## Requirements

- Java 21
- Maven 3.9.5

---
## Implementation

You can add the following snippet to your *pom.xml*.

```xml
<parent>
    <groupId>com.eightaugusto</groupId>
    <artifactId>eight-spring-boot-parent</artifactId>
    <version>...</version>
</parent>
```