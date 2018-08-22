#20180821
1、创建maven项目，此这个pom文件作为父pom文件

2、创建两个spring-boot子工程，Eureka Server作为服务注册中心，Eureka Client

3、启动一个服务注册中心，只需要一个注解@EnableEurekaServer，这个注解需要在springboot工程的启动application类上

4、浏览器访问http://localhost:8761/；eureka server 是有界面的