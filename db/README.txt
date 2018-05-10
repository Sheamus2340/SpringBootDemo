本项目有2个配置文件，dev,pro 因个人需求周一到周5 启动使用pro,周6 周日 启动使用dev,具体实现可在spring boot 入口main方法中查看
pro,主要使用153 mq,redis等
dev 主要使用自己本机上的mq,redis等
使用前需在本机创建mysql数据库 mydb 具体数据库信息可以在mydb.sql中查看
本项目整合了
shiro 
redis 
mybatis，分页插件，自动代码生成，通用mapper
druid
多数据源方案
spring cache 整合ehcache和redis二级缓存
事物配置
aop
自定义注解
netty
disruptor
quartz定时任务
提供服务的接口等

