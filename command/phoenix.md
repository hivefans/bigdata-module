phoenix
===

Phoenix是构建在HBase之上的关系型数据库层

## 补充说明

Apache Phoenix是构建在HBase之上的关系型数据库层，作为内嵌的客户端JDBC驱动用以对HBase中的数据进行低延迟访问。   

Apache Phoenix会将用户编写的sql查询编译为一系列的scan操作，最终产生通用的JDBC结果集返回给客户端。  

数据表的元数据存储在HBase的表中被会标记版本号，所以进行查询的时候会自动选择正确的schema。  

直接使用HBase的API，结合协处理器（coprocessor）和自定义的过滤器的话，小范围的查询在毫秒级响应，千万数据的话响应速度为秒级。  

特性

   - 嵌入式的JDBC驱动，实现了大部分的java.sql接口，包括元数据API 
   - 可以通过多部行键或是键/值单元对列进行建模 
   - 完善的查询支持，可以使用多个谓词以及优化的扫描键 
   - DDL支持：通过CREATE TABLE、DROP TABLE及ALTER TABLE来添加/删除列 
   - 版本化的模式仓库：当写入数据时，快照查询会使用恰当的模式 
   - DML支持：用于逐行插入的UPSERT VALUES、用于相同或不同表之间大量数据传输的UPSERT SELECT、用于删除行的DELETE 
   - 通过客户端的批处理实现的有限的事务支持 
   - 单表——还没有连接，同时二级索引也在开发当中 
   - 紧跟ANSI SQL标准，HIVE不完全支持SQL92，而Phoenix 接近ANSI SQL-2003

### 历史

```
Salesforce 开发了该软件并在2013年捐献给了Apache。2014年5月项目毕业成为顶级项目。
```

### 官方主页

```
https://phoenix.apache.org/
```