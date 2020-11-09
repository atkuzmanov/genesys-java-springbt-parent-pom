# GeneSys

![GeneSys Logo v1.0](GeneSys_Logo_v1.0.png)

**```"Genesis + System = GeneSys"```**   
\- atkuzmanov

---

<!-- TOC -->

- [GeneSys](#genesys)
  - [DESCRIPTION](#description)
  - [SETUP](#setup)
  - [TODOs, WIP & FUTURE DEVELOPMENT](#todos-wip--future-development)
  - [LICENSE](#license)
  - [CONSTRUCTIVE FEEDBACK AND CONTRIBUTIONS TO THE PROJECT ARE WELCOME](#constructive-feedback-and-contributions-to-the-project-are-welcome)
  - [REFERENCES](#references)

<!-- /TOC -->

## DESCRIPTION

This is a `POM` file designed to be a `PARENT POM` in a `Java`, `Spring Boot`, `Maven` and `Maven Enforcer Plugin` environment.

This is a project to be used as a `base` or a `cookie cutter` if you will.

This version of the project is for building a `Java`, `Spring Boot` `Web` and `REST` applications from scratch.

The project comes incorporating or pre-configured to be compatible with the following technologies:

- [Java](https://www.java.com/en/)
- [Spring](https://spring.io/)
- [Spring Boot](https://spring.io/projects/spring-boot)
    - [Spring Cloud](https://spring.io/projects/spring-cloud)
- [Aspect Oriented Programming (AOP)](https://en.wikipedia.org/wiki/Aspect-oriented_programming)
    - [Spring AOP](https://docs.spring.io/spring-framework/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/#overview-aop-instrumentation)
    - [AspectJ](https://www.eclipse.org/aspectj/)
- [Web & REST](https://en.wikipedia.org/wiki/Representational_state_transfer)
    - [Spring MVC](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
        - [Controllers](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#mvc-controller)
        - [Filters](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#filters)
        - [Exception Handling](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html#mvc-exceptionhandlers)
    - [Thymeleaf templates](https://www.thymeleaf.org/documentation.html)
        - [HTML](https://www.w3schools.com/html/html_intro.asp)
        - [CSS](https://www.w3schools.com/css/css_intro.asp)
- [Testing](https://en.wikipedia.org/wiki/Software_testing)
    - [Spring Boot Test](https://docs.spring.io/spring-boot/docs/2.1.5.RELEASE/reference/html/boot-features-testing.html)
        - [JUnit](https://junit.org/junit5/)
        - [Unit Testing](https://en.wikipedia.org/wiki/Unit_testing#:~:text=Unit%20tests%20are%20typically%20automated,an%20individual%20function%20or%20procedure.)
        - [Integration Testing](https://en.wikipedia.org/wiki/Integration_testing)
- [Spring Data](https://spring.io/projects/spring-data)
    - [MySQL](https://dev.mysql.com/doc/connector-j/8.0/en/)
    - [JPA](https://en.wikipedia.org/wiki/Jakarta_Persistence)
    - [DAO](https://en.wikipedia.org/wiki/Data_access_object)
- [Logging](https://en.wikipedia.org/wiki/Log_file)
    - [Structured Logging in JSON format](https://medium.com/@krishankantsinghal/structured-logging-why-and-how-to-achieve-in-java-33974d22accb)
    - [Logback](http://logback.qos.ch/)
    - [SLF4J](http://www.slf4j.org/)
        - [MDC](http://www.slf4j.org/api/org/slf4j/MDC.html)
    - [Logstash](https://github.com/elastic/logstash)
- [Distributed Tracing](https://docs.lightstep.com/docs/understand-distributed-tracing)
    - [Spring Cloud Sleuth](https://spring.io/projects/spring-cloud-sleuth)
    - [Zipkin](https://zipkin.io/)
- [Apache Maven](https://maven.apache.org/index.html)
    - [Apache Maven Enforcer plugin](https://maven.apache.org/enforcer/maven-enforcer-plugin/)
- [Apache Tomcat](http://tomcat.apache.org/)

**Note:** For the relevant versions, please see the [POM file](pom.xml).

---

## SETUP

- Setting up the Maven wrapper

```sh
mvn -N io.takari:maven:wrapper
```

- Building

```
mvn clean install
```

- Running

```
mvn spring-boot:run
```

---

## TODOs, WIP & FUTURE DEVELOPMENT

- :white_large_square: Clean up & tidy up.

- :eight_pointed_black_star: Create a demo application.

- :white_large_square: Add profiles for different environments.

- :white_large_square: Add more useful technologies.

- :white_large_square: Add [Spring Boot Security](https://spring.io/projects/spring-security)

:white_large_square: - Not started.
:eight_pointed_black_star: - In progress.
:white_check_mark: - Done.

---

## LICENSE

[GPL-3.0 License](LICENSE.md)

---

## CONSTRUCTIVE FEEDBACK AND CONTRIBUTIONS TO THE PROJECT ARE WELCOME

[Contact](https://github.com/atkuzmanov)

---

## REFERENCES

> <https://spring.io/>
>
> <http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20>

---
