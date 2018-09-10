学习 
[唐亚峰老师的博客](https://blog.csdn.net/memmsc/article/category/7177496/2)
第一章：建工程

第二章：自定义配置
@PropertySource("classpath:my2.properties")
@ConfigurationProperties(prefix = "my2")
cmd 优先级最高
spring-boot2-learning/chapter2 项目根目录下执行打包 mvn package
java -jar chapter2-0.0.1-SNAPSHOT.jar --spring.profiles.active=test --my1.age=32
