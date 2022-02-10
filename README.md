Spring Dependency Injection example without XML
======================================

Simplest example how can Spring Dependency example works. 
For all configuration are used annotations without any XML files.

Description
-------------------
* All configuration is in *pooky.projects.AppConfig*
* This class need to be annotated with @Configuration 
* Annotation @ComponentScan will scan and register beans in *pooky.projects.beans*
* To run example use *Main.java*

Interesting reading
----------------------

Spring Depedency Injection and Beans
- https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/using-boot-spring-beans-and-dependency-injection.html

* Difference between annotation @Inject, @Resource and @Autowired
* https://blogs.sourceallies.com/2011/08/spring-injection-with-resource-and-autowired/ 

- In Spring Component can have constructor, which include specific Bean and you don´t have to write @Autowired there
- Otherwise you have to use @Autowired or other import annotation

More demos
-------------------

* Java EE World examples can be found here: https://github.com/Pooky/java-enterprise-examples
* Spring Wordl examples can be found here: https://github.com/Pooky/spring-examples
 
  
