### Spring Boot基础教程4-配置文件-多环境配置--yaml
```xml
#配置文件环境配置
spring:
  profiles:
    active: dev
    
  #jackson
  jackson:
    date-format: yyyy-MM-dd HH:mm:ss
    time-zone: Asia/Chongqing

#端口
server: 
  port: 8888
    
---
spring:
  profiles: dev
server:
  port: 8080
  
---
spring:
  profiles: prod
server:
  port: 8082
  
---
spring:
  profiles: test
server:
  port: 8081
```
