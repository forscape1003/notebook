---
title: MongoDB 数据库
---


网站运行需要有大量的数据的读取，同时用户也需要把自己的数据存储到服务器，对于海量数据的操作。 就需要有专门的软件配合，这个软件就是数据库。

当前比较流行的数据库，Oracle 甲骨文，SQL server ，这些都是商业数据库。但是，开源数据库目前更受青睐。一个是 Mysql , 另一个是 MongoDB 。

我们课程中采用 MongoDB 数据库。MongoDB 是非关系型数据库，传统的关系型数据库的 table （表）和 record （记录），在 MongoDB 这里都有对应的替代物。

### MongoDB 基本概念

https://www.mongodb.com/ 是 MongoDB 的官网。http://www.mongoing.com/ 是 MongoDB 中文社区。http://www.mongodb.org.cn/ 是 MongoDB 中文网。

- MongoDB：是一个数据库软件，有时候我们简称它叫一个数据库，但是其实一个 MongoDB 运行起来 可以里面同时运行多个数据库
- Database: 数据库。一般做法是，一个项目对应一个数据库。
- Collection: 集合。类似于关系型数据库下的表的概念，例如全班同学信息。
- Document：文档。一个集合中会包含多个文档（一个文档中存储一个同学的信息）。文档对应关系型数据库中的 记录 这个概念。
