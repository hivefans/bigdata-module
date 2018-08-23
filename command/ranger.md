ranger
===

Apache Ranger提供一个集中式安全管理框架, 并解决授权和审计。

## 补充说明
Apache Ranger提供一个集中式安全管理框架, 并解决授权和审计。它可以对Hadoop生态的组件如HDFS、Yarn、Hive、Hbase等进行细粒度的数据访问控制。  
通过操作Ranger控制台,管理员可以轻松的通过配置策略来控制用户访问权限。
Ranger支持的服务有HDFS、Hbase、Hive、Yarn、Strom、Kafka、Knox、Solor

它主要提供如下特性:
  - 基于策略(Policy-based)的访问权限模型
  - 通用的策略同步与决策逻辑，方便控制插件的扩展接入
  - 内置常见系统(如HDFS、YARN、HBase)的控制插件，且可扩展
  - 内置基于LDAP、文件的用户同步机制，且可扩展
  - 统一的管理界面，包括策略管理、审计查看、插件管理等

### 历史

```
2014年10月，Apache Ranger 0.4发布
2017年3月，Apache Ranger成为Apache的顶级项目之一
```

### 官方主页

```
http://ranger.apache.org/
```
