# MySQL 实战 45 讲

Table of Contents
-----------------

* [1. 一条 SQL 查询语句是如何执行的?](#1-一条-sql-查询语句是如何执行的)
* [2. 一条 SQL 更新语句是如何执行的?](#2-一条-sql-更新语句是如何执行的)
* [3. 事务隔离: 为什么你改了我还看不见?](#3-事务隔离-为什么你改了我还看不见)
* [4. 深入浅出索引](#4-深入浅出索引)
* [5. 全局锁和表锁: 给表加个字段怎么有那么多阻碍?](#5-全局锁和表锁-给表加个字段怎么有那么多阻碍)
* [6. 怎么减少行锁对性能对影响?](#6-怎么减少行锁对性能对影响)
* [7. 事务到底是隔离的还是不隔离的?](#7-事务到底是隔离的还是不隔离的)
* [8. 普通索引和唯一索引, 应该怎么选择?](#8-普通索引和唯一索引-应该怎么选择)
* [9. MySQL 为什么有时候会选错索引?](#9-mysql-为什么有时候会选错索引)
* [10. 怎么给字符串字段加索引?](#10-怎么给字符串字段加索引)
* [11. 为什么我的 MySQL 会 ”抖“ 一下?](#11-为什么我的-mysql-会-抖-一下)
* [12. 为什么表数据删掉一半, 表文件大小不变?](#12-为什么表数据删掉一半-表文件大小不变)
* [13. count(*) 这么慢, 怎么办?](#13-count-这么慢-怎么办)
* [14. "order by" 如何工作?](#14-order-by-如何工作)
* [15. 如何正确显示随机消息?](#15-如何正确显示随机消息)
* [16. 为什么 SQL 语句逻辑相同, 性能差异却巨大?](#16-为什么-sql-语句逻辑相同-性能差异却巨大)
* [17. 为什么我只查一行的语句, 也执行那么慢?](#17-为什么我只查一行的语句-也执行那么慢)
* [18. 幻读是什么? 有什么问题?](#18-幻读是什么-有什么问题)
* [19. 为什么我只查一行的语句, 锁这么多?](#19-为什么我只查一行的语句-锁这么多)
* [20. 有哪些提高性能的方法?](#20-有哪些提高性能的方法)
* [21. 如何保证数据不丢?](#21-如何保证数据不丢)
* [22. 如何保证主备一致?](#22-如何保证主备一致)
* [23. 如何保证高可用?](#23-如何保证高可用)
* [24. 备库为什么会延迟好几个小时?](#24-备库为什么会延迟好几个小时)
* [25. 主库出问题了, 从库怎么办?](#25-主库出问题了-从库怎么办)
* [26. 读写分离有哪些坑?](#26-读写分离有哪些坑)
* [27. 如何判断一个数据库是不是出问题了?](#27-如何判断一个数据库是不是出问题了)
* [28. 删库除了跑路, 还能怎么办?](#28-删库除了跑路-还能怎么办)
* [29. 为什么还有 kill 不掉的语句?](#29-为什么还有-kill-不掉的语句)
* [30. 我查那么多数据, 会不会把数据库内存打爆？](#30-我查那么多数据-会不会把数据库内存打爆)
* [31. 到底可不可以用 join?](#31-到底可不可以用-join)
* [32. join 语句怎么优化?](#32-join-语句怎么优化)
* [33. 为什么临时表可以重名?](#33-为什么临时表可以重名)
* [34. 什么时候会使用内部临时表?](#34-什么时候会使用内部临时表)
* [35. 还要使用 Memory 引擎吗?](#35-还要使用-memory-引擎吗)
* [36. 自增主键为什么不是连续的?](#36-自增主键为什么不是连续的)
* [37. insert 语句的锁为什么那么多?](#37-insert-语句的锁为什么那么多)
* [38. grant 之后要 flush privileges 吗?](#38-grant-之后要-flush-privileges-吗)
* [39. 怎么最快地复制一张表?](#39-怎么最快地复制一张表)
* [40. 要不要使用分区表?](#40-要不要使用分区表)
* [41. 自增 ID 用完了怎么办?](#41-自增-id-用完了怎么办)
* [参考资料](#参考资料)

## 1. 一条 SQL 查询语句是如何执行的?



<div align="center"> <img src="logic.png" width="70%"/> </div><br> 







## 2. 一条 SQL 更新语句是如何执行的?





## 3. 事务隔离: 为什么你改了我还看不见?





## 4. 深入浅出索引



## 5. 全局锁和表锁: 给表加个字段怎么有那么多阻碍?



## 6. 怎么减少行锁对性能对影响?

## 7. 事务到底是隔离的还是不隔离的?



## 8. 普通索引和唯一索引, 应该怎么选择?

## 9. MySQL 为什么有时候会选错索引?



## 10. 怎么给字符串字段加索引?



## 11. 为什么我的 MySQL 会 ”抖“ 一下?



## 12. 为什么表数据删掉一半, 表文件大小不变?





## 13. count(*) 这么慢, 怎么办?







## 14. "order by" 如何工作?









## 15. 如何正确显示随机消息?





## 16. 为什么 SQL 语句逻辑相同, 性能差异却巨大?







## 17. 为什么我只查一行的语句, 也执行那么慢?



## 18. 幻读是什么? 有什么问题?







## 19. 为什么我只查一行的语句, 锁这么多?









## 20. 有哪些提高性能的方法?







## 21. 如何保证数据不丢?





## 22. 如何保证主备一致?





## 23. 如何保证高可用?



## 24. 备库为什么会延迟好几个小时?





## 25. 主库出问题了, 从库怎么办?



## 26. 读写分离有哪些坑?





## 27. 如何判断一个数据库是不是出问题了?



## 28. 删库除了跑路, 还能怎么办?



## 29. 为什么还有 kill 不掉的语句?



## 30. 我查那么多数据, 会不会把数据库内存打爆？





## 31. 到底可不可以用 join?



## 32. join 语句怎么优化?



## 33. 为什么临时表可以重名?





## 34. 什么时候会使用内部临时表?



## 35. 还要使用 Memory 引擎吗?



## 36. 自增主键为什么不是连续的?



## 37. insert 语句的锁为什么那么多?



## 38. grant 之后要 flush privileges 吗?





## 39. 怎么最快地复制一张表?



## 40. 要不要使用分区表?

## 41. 自增 ID 用完了怎么办?



## 参考资料

- [MySQL实战45讲-极客时间](https://time.geekbang.org/column/intro/100020801)