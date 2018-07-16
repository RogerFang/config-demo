# 出门先拼微服务框架
版本：Spring Cloud Finchley
## 系统架构图
![](http://on-img.com/chart_image/5b4c09bee4b07df3b43c1ff2.png)

## 模块说明
1. Zuul：作为服务网关统一处理外部请求、权限认证等\
[史上最简单的SpringCloud教程 | 第五篇: 路由网关(zuul)(Finchley版本)](https://blog.csdn.net/forezp/article/details/81041012)
2. Eureka：服务注册与发现组件\
[史上最简单的 SpringCloud 教程 | 第一篇： 服务的注册与发现Eureka(Finchley版本)](https://blog.csdn.net/forezp/article/details/81040925)
3. Feign：用于业务服务集群代理以及微服务间调用\
[史上最简单的SpringCloud教程 | 第三篇: 服务消费者（Feign）(Finchley版本)](https://blog.csdn.net/forezp/article/details/81040965)\
[微服务 通过EnableFeignClients调用其他服务的api](https://www.cnblogs.com/UniqueColor/p/7130782.html)
4. Config：服务统一配置中心\
[史上最简单的SpringCloud教程 | 第六篇: 分布式配置中心(Spring Cloud Config)(Finchley版本)](https://blog.csdn.net/forezp/article/details/81041028)
5. Hystrix：单个服务的熔断降级保护\
[史上最简单的SpringCloud教程 | 第四篇:断路器（Hystrix）(Finchley版本)](https://blog.csdn.net/forezp/article/details/81040990) 
6. Turbine：将多个服务的Hystrix Dashboard数据进行聚合展示\
[史上最简单的SpringCloud教程 | 第十三篇: 断路器聚合监控(Hystrix Turbine)(Finchley版本)](https://blog.csdn.net/forezp/article/details/81041125)
7. Zipkin：服务链路追踪以及依赖关系分析\
[史上最简单的SpringCloud教程 | 第九篇: 服务链路追踪(Spring Cloud Sleuth)(Finchley版本)](https://blog.csdn.net/forezp/article/details/81041078)
