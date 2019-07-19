### 多环境的配置-properties
* application-dev.properties
* application-test.properties
* application-prod.properties
* application.properties
```xml
#主配置文件，配置了这个会优先读取里面的属性覆盖主配置文件的属性
spring.profiles.active=dev
```
### 以指定的配置文件运行 jar 包 SpringBoot 项
* java -jar 包 --spring.profiles.active=dev
