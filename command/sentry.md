sentry
===

Apache Sentry是一个Hadoop的权限控制的开源组件。

## 补充说明

Sentry提供角色级别的数据权限访问，可以进行细粒度权限划分。例如，在HIve和Impala中，Sentry的SQL权限控制select、insert等语句对服务器、数据库、数据表、视图甚至数据列的访问。  

Sentry对不同的Hadoop组件提供了六类对权限访问策略管理：

  - Sentry支持多权限模型，也支持同一个权限控制策略对多哥计算框架和数据目录的访问；
  - Sentry支持Apache Solr（搜索项目）；
  - Sentry支持SQL表权限和HDFS文件权限同步；
  - Sentry支持数据管理的审计日志；
  - Sentry支持高可用性（HA）；
  - Sentry支持不同集群间权限策略的导入和导出；
  - Sentry支持Apache Kafka，Solr和Apache Sqoop。

### 历史

```
2013年8月Sentry成为Apache的孵化项目
2016年6月sentry成为Apache的顶级开源项目
```

### 官方主页

```
https://sentry.apache.org/
```