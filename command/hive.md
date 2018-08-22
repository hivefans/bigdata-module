hive
===

Hive 是一个基于Hadoop的开源数据仓库工具.

## 补充说明

Hive 是一个基于 Hadoop 文件系统之上的数据仓库架构。它为数据仓库的管理提供了许多功能：数据 ETL （抽取、转换和加载）工具、数据存储管理和大型数据集的查询和分析能力。 

同时 Hive 还定义了类 SQL的语言 – Hive QL. Hive QL 允许用户进行和 SQL 相似的操作，它可以将结构化的数据文件映射为一张数据库表，并提供简单的 SQL 查询功能。

还允许开发人员方便地使用 Mapper 和 Reducer 操作，可以将 SQL 语句转换为 MapReduce 任务运行，这对 MapReduce 框架来说是一个强有力的支持。

优点：  
1.Hive 使用类SQL 查询语法, 最大限度的实现了和SQL标准的兼容，大大降低了传统数据分析人员学习的曲线；  

2.使用JDBC 接口/ODBC接口，开发人员更易开发应用；  

3.以MR 作为计算引擎、HDFS 作为存储系统，为超大数据集设计的计算/ 扩展能力；  

4.统一的元数据管理（Derby、MySql等），并可与Pig 、Presto 等共享；  

缺点：

1.Hive 的HQL 表达的能力有限，有些复杂运算用HQL 不易表达；  

2.由于Hive自动生成MapReduce 作业， HQL 调优困难；  

3.粒度较粗，可控性差  

### 历史

```
由FaceBook 2008年把hive项目贡献给Apache
```

### 官方主页

```
https://hive.apache.org/
```
