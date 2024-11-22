# spring-cloud-base

springboot、spring cloud alibaba base pom management

# 介绍

引入 Spring Boot、Spring Cloud、Spring Cloud Alibaba 三者 BOM 文件，进行依赖版本的管理，防止不兼容。 在 https://dwz.cn/mcLIfNKt 文章中，Spring Cloud
Alibaba 开发团队推荐了三者的依赖关系

# 版本

[版本说明](https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E)

Maven POM
```xml
  <dependency>
     <groupId>com.nowcode.cloud</groupId>
      <artifactId>spring-cloud-base</artifactId>
      <version>3.2-SNAPSHOT</version>
  </dependency>
```

|版本| SpringBoot | Spring CLoud | Spring Alibaba |
| --- | --- | --- | --- |
| 3.2-SNAPSHOT| 3.2.11| 2023.0.0 | 2023.0.0.0-RC1 |

# 相关文档
- [Spring Cloud Alibaba](https://sca.aliyun.com/docs/2023/overview/what-is-sca/?spm=5176.29160081.0.0.74805c72x9tGJs)
