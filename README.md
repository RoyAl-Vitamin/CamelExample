# CamelExample

Падает с ошибкой  
```java
org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'camelController'
```
НО только при использовании **jdk9**, поэтому использовать нужно только **jdk1.8**! Потому что  
> This release supports only Spring Boot 1.5.x. Support for Spring Boot 2.0.x is coming in Camel version 2.22 which is planned for early summer 2018.

и
> Spring Boot 2 is the first version to support Java 9 (Java 8 is also supported). If you are using 1.5 and wish to use Java 9 you should upgrade to 2.0 as we have no plans to support Java 9 on Spring Boot 1.5.x.

Пример взят с [сайта](https://dzone.com/articles/how-to-integrate-spring-boot-and-apache-camel),
а так же смотрел [офф репо](https://github.com/apache/camel/tree/master/examples/camel-example-spring-boot),
и [туда](https://servicemix.apache.org/docs/4.5.x/jbi/components/servicemix-camel.html) и [сюда](https://servicemix.apache.org/docs/7.x/camel/deployment/osgi-bundle-spring.html)