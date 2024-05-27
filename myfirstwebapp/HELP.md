# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#using.devtools)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

## JSP

/src/main/resources/META-INF/resources/WEB-INF/jsp/sayHello.jsp

/say-hello-jsp => SayHelloController - sayHelloJsp method => sayHello

/WEB-INF/jsp/sayHello.jsp

## Login JSP
/login => com.in28minutes.springboot.myfirstwebapp.login.LoginController => login.jsp

##
localhost:8080/login

B1: Identifies correct Controller method  
/login => LoginController.gotoLoginPage

B2: Executes Controller method  
=> Puts data into model   
=> Returns view name => login

B3: Identifies correct View  
/WEB-INF/jsp/login.jsp

B4: Executes view