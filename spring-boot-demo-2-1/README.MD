# Spring Boot基础教程2-RESTfull API简单项目的快速搭建
* 知识点
    * lombok的简单使用
    * springboot的简单搭建
    * 项目打成jar包
    
# 项目打成jar包注意事项
* 配置文件            
    ```xml
    <properties>
     <!-- <maven.test.skip>true</maven.test.skip> -->
        <skipTests>true</skipTests>
    </properties>
    <plugin>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-maven-plugin</artifactId>
    </plugin>
    ```
