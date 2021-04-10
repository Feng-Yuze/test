# 第一章 数据库和SQL

## 1-1 数据库是什么
1. **数据库（Database, DB)**：将大量数据保存起来，通过计算机加工而成的可以进行高效访问的数据集合。
2. **数据库管理系统（Database Management System,DBMS)**：用来管理数据库的计算机系统。
### DBMS的种类：
1. **层次数据库(Hierarchical Database, HDB)**  
  现在已经很少使用
3. **关系数据库(Relational Database, RDB)**
  * 现在应用最广泛的数据库
  * 采用行和列组成的二维表来管理数据，简单易懂
  * 使用专门的SQL(Structured Query Language)对数据进行操作
  * 这类DBMS称为关系数据库管理系统(Relational Database Mnagement System, RDBMS)，比较有代表性的RDBMS有：  
       * Oracle Database: 甲骨文公司的RDBMS
       * SQL server: 微软公司的RDBMS
       * DB2： IBM的RDBMS
       * PostgreSQL: 开源的RDBMS
       * MySQL: 开源的RDBMS
  * 面向对象数据库(Object Oriented Database, OODB)
  * XML数据库(XML Database, XMLDB)
  * 键值存储系统(Key-Value Store, KVS)
# 1-2 数据库的结构
## 数据库的常见系统结构  
   客户端/服务器类型(C/S)是最常见的系统结构  
   * 服务器：用来接收其他程序发出的请求，并对该请求进行相应处理的程序（软件），或者是安装了此类程序的设备（计算机）。
   * 客户端：向服务器发出请求的程序（软件），或者是安装了该程序的设备（计算机）。访问由RDBMS管理的数据库，进行数据读写的程序称为RDBMS客户端。
   ![image](https://user-images.githubusercontent.com/80444046/114262613-90d70980-9a13-11eb-8104-d29783ebf2c3.png)
 ## 表的结构
   表：在关系数据库中用来管理数据的二维表  
   根据SQL语句的内容返回的数据同样必须是二维表的形式，返回结果如果不是二维表的SQL语句无法执行
