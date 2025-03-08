# 技术部任务 4

## 任务一： JPA 框架学习

### 第一节：概念

1. 什么是 API ?

API 是一种接口能使得两个不同系统，或软件之间能有效地进行相互通信。

API : Application Programming Interface
REST : Representational State Transfer
REST is stateless, What does it mean? 服务器不会保留访问系统的数据。

2. JDBC 在 JAVA 编程中的作用？

JDBC （Java Database Connecticity）是 Java 提供的一种 API， 可以用于连接和操作数据库如 MySQL, PostgreSQL, Oracle 等的接口，这样我们可以用 Java 程序于数据库进行增删改查了。

3. JPA 是什么？它和 JDBC 的关系是什么？

JPA (Java Persistence API) 是 Java 提供的对象关系映射 (ORM)，主要用于简化 Java 应用程序数据库的访问。JPA 本质上是一个更高级的抽象层，它仍需要仍依赖于底层的 JDBC 进行数据库访问。JPA 通过 ORM 简化了数据库的操作，而 JDBC 需要写 SQL。
