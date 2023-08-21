# Shared code for the Eureka! Clinical User Agreement microservice
[Andrew Post](http://www.andrewrpost.com), Salt Lake City, UT

Derived from software previously developed by me and my team at the [Georgia Clinical and Translational Science Alliance (Georgia CTSA)](http://www.georgiactsa.org), [Emory University](http://www.emory.edu), Atlanta, GA


## What does it do?
It contains classes that are shared between `eurekaclinical-user-agreement-webapp` and `eurekaclinical-user-agreement-service`.

## Version 2.0 development series
Latest release: [![Latest release](https://maven-badges.herokuapp.com/maven-central/org.eurekaclinical/eurekaclinical-user-agreement-common/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.eurekaclinical/eurekaclinical-user-agreement-common)

## Version history
### Version 1.1
The version 1 series provides access to all current REST APIs.

## Build requirements
* [Oracle Java JDK 8](http://www.oracle.com/technetwork/java/javase/overview/index.html)
* [Maven 3.2.5 or greater](https://maven.apache.org)

## Runtime requirements
* [Oracle Java JRE 8](http://www.oracle.com/technetwork/java/javase/overview/index.html)
* [Tomcat 7](https://tomcat.apache.org)

## Building it
The project uses the maven build tool. Typically, you build it by invoking `mvn clean install` at the command line. For simple file changes, not additions or deletions, you can usually use `mvn install`. See https://github.com/eurekaclinical/dev-wiki/wiki/Building-Eureka!-Clinical-projects for more details.

## Maven dependency
```
<dependency>
    <groupId>org.eurekaclinical</groupId>
    <artifactId>eurekaclinical-user-agreement-common</artifactId>
    <version>version</version>
</dependency>
```

## Developer documentation
* [Javadoc for latest development release](http://javadoc.io/doc/org.eurekaclinical/eurekaclinical-user-agreement-common) [![Javadocs](http://javadoc.io/badge/org.eurekaclinical/eurekaclinical-user-agreement-common.svg)](http://javadoc.io/doc/org.eurekaclinical/eurekaclinical-user-agreement-common)

## Getting help
Feel free to contact us at help@eurekaclinical.org.

