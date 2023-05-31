#### Mysql面试题（3.22、4.05、4.13、4.20、5.5）

**1、谈谈数据库的三大范式。**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**2、MyISAM 与 InnoDB 的区别是什么？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**3、为什么推荐使用自增 id 作为主键？谈谈你对页分裂的理解。**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、https://blog.51cto.com/u_15015155/2615476）

**4、谈谈一条查询 SQL 是如何执行的？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、[02 为了执行SQL语句，你知道MySQL用了什么样的架构设计吗.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/02 为了执行SQL语句，你知道MySQL用了什么样的架构设计吗.pdf)）

**5、使用 Innodb 的情况下，一条更新语句是怎么执行的？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、[03 用一次数据更新流程，初步了解InnoDB存储引擎的架构设计.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/03 用一次数据更新流程，初步了解InnoDB存储引擎的架构设计.pdf)、[04 借着更新语句在InnoDB存储引擎中的执行流程，聊聊binlog是什么.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/04 借着更新语句在InnoDB存储引擎中的执行流程，聊聊binlog是什么.pdf)）

**6、Innodb 事务为什么要两阶段提交？两阶段提交中，MySQL异常重启（crash），是如何保证数据完整性的？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、https://blog.csdn.net/qq_27851149/article/details/120402224）

**7、WAL 是什么？有什么优缺点？**（https://baijiahao.baidu.com/s?id=1750801557835901172&wfr=spider&for=pc、https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**8、MySQL 有哪些日志？分别有什么作用？MySQL 是如何保证原子性和持久性的？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、https://mp.weixin.qq.com/s/Lx4TNPLQzYaknR7D3gmOmQ、https://baijiahao.baidu.com/s?id=1719905225647709469&wfr=spider&for=pc）

**9、为什么有了 redolog 还需要 binlog？redolog 和 binlog 的区别是什么？**（https://blog.csdn.net/qq_27851149/article/details/120402224、https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**10、谈谈 Buffer Pool 的作用。**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、[11 从数据的增删改开始讲起，回顾一下Buffer Pool在数据库里的地位.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/11 从数据的增删改开始讲起，回顾一下Buffer Pool在数据库里的地位.pdf)）

**11、谈谈 free 链表的作用。如何知道当前数据页是否被缓存？**（[13 从磁盘读取数据页到Buffer Pool的时候，free链表有什么用.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/13 从磁盘读取数据页到Buffer Pool的时候，free链表有什么用.pdf)）

**12、谈谈 flush 链表的作用。**（[14 当我们更新Buffer Pool中的数据时，flush链表有什么用.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/14 当我们更新Buffer Pool中的数据时，flush链表有什么用.pdf)）

**13、谈谈 LRU 链表的作用。什么是缓存命中率？谈谈 LRU 链表可能带来的问题。谈谈 LRU 链表冷热分离机制。**（[15 当Buffer Pool中的缓存页不够的时候，如何基于LRU算法淘汰部分缓存.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/15 当Buffer Pool中的缓存页不够的时候，如何基于LRU算法淘汰部分缓存.pdf)、[16 简单的LRU链表在Buffer Pool实际运行中，可能导致哪些问题.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/16 简单的LRU链表在Buffer Pool实际运行中，可能导致哪些问题.pdf)、[17 MySQL是如何基于冷热数据分离的方案，来优化LRU算法的.pdf](file:///C:/Users/HuoJia/Desktop/学习资料/从 0 开始带你成为MySQL实战优化高手/17 MySQL是如何基于冷热数据分离的方案，来优化LRU算法的.pdf)）

**14、为什么要引入数据页？谈谈数据页的组成。谈谈表空间、数据区以及数据页之间的关系。**（[24 我们写入数据库的一行数据，在磁盘上是怎么存储的.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/24 我们写入数据库的一行数据，在磁盘上是怎么存储的.pdf)、[30 用于存放磁盘上的多行数据的数据页到底长个什么样子.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/30 用于存放磁盘上的多行数据的数据页到底长个什么样子.pdf)、[31 表空间以及划分多个数据页的数据区，又是什么概念.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/31 表空间以及划分多个数据页的数据区，又是什么概念.pdf)）

**15、一行数据在磁盘上是如何存储的？包含了哪些东西？变长字段在磁盘上是如何存储的？NULL 值在磁盘上是如何存储的？一行数据在磁盘上是如何读取的？**（[24 -28我们写入数据库的一行数据，在磁盘上是怎么存储的.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/24 我们写入数据库的一行数据，在磁盘上是怎么存储的.pdf)）

**16、谈谈行溢出是什么。**（[29 理解数据在磁盘上的物理存储之后，聊聊行溢出是什么东西.pdf](file:///D:/学习资料/从 0 开始带你成为MySQL实战优化高手/29 理解数据在磁盘上的物理存储之后，聊聊行溢出是什么东西.pdf)）

**17、索引的优缺点。**（D:\My_WorkSapce\MyNote\数据库\003：索引.md、https://blog.csdn.net/weixin_42073412/article/details/100860370）

**18、索引失效的场景有哪些？**（https://mp.weixin.qq.com/s/WnO_4SoEL6jugkxPHW4KCg）

**19、常见的索引有哪些？谈谈聚簇索引与非聚簇索引的区别.**（D:\My_WorkSapce\MyNote\数据库\003：索引.md、https://mp.weixin.qq.com/s/faOaXRQM8p0kwseSHaMCbg、https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w）

**20、为什么要用 B+ 树，为什么不用普通二叉树、平衡二叉树以及 B 树？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://mp.weixin.qq.com/s/AoPq8poENF9T4mVS1fDFPw）

**21、Hash 索引和 B+ 树索引区别是什么？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w）

**22、什么是回表？什么是覆盖索引？什么是索引下推？**（D:\My_WorkSapce\MyNote\数据库\003：索引.md、https://mp.weixin.qq.com/s/87qsrj-_hG54uxcOlFr35Q）

**23、谈谈什么是事务以及事务的特性（事务的 ACID）。**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**24、MySQL 多事务同时执行造成的问题。**（D:\My_WorkSapce\MyNote\数据库\001：事务.md）

**25、SQL 标准中对事务的4个隔离级别，MySQL 默认支持的隔离级别是什么。**（D:\My_WorkSapce\MyNote\数据库\001：事务.md）

**26、MySQL 如何支持 rc 和 rr 隔离级别。谈谈你对 MVVC 机制的理解。**（D:\My_WorkSapce\MyNote\数据库\001：事务.md）

**27、MVVC 机制能解决哪些问题呢？MVVC 机制不能解决什么问题？**（https://blog.csdn.net/qq_43665821/article/details/123919178、https://blog.csdn.net/m0_37486454/article/details/126881390、https://blog.csdn.net/Edwin_Hu/article/details/124392174、https://blog.csdn.net/m0_71777195/article/details/128075397）

**28、谈谈你对当前读以及快照读的理解。**（https://blog.csdn.net/qingqingxiaocao1989/article/details/125094127）

**29、MySQL 支持哪些锁？简述一下各自的作用。各种锁锁的是什么？查询列没有加索引时，如何加锁？**（https://www.jianshu.com/p/478bc84a7721、https://blog.csdn.net/qingqingxiaocao1989/article/details/125094127、https://blog.csdn.net/mingyuli/article/details/121307742）

**30、一条查询 SQL 执行起来很慢是什么原因？一条查询 SQL 执行起来偶尔很慢是什么原因？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**31、为什么不要使用长事务？**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ）

**32、谈谈你的 SQL 调优思路。**（https://mp.weixin.qq.com/s/MaVYENapeJcLNpYcR7tqBQ、https://mp.weixin.qq.com/s/nEmN4S9JOTVGj5IHyfNtCw）

**33、执行计划中常见的参数有哪些？**（D:\My_WorkSapce\MyNote\数据库\004：执行计划.md）

**34、MySQL 默认隔离级别是RR，为什么阿里等大厂会改成 RC ？**（https://mp.weixin.qq.com/s/mIz0T0v68_dvUgCrj-qdug）

35、数据库调优有哪些？

**36、谈谈 MySQL 的主从有哪些步骤。**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://blog.csdn.net/chuige2013/article/details/128557320）

**37、MySQL 的主从延迟，你怎么解决？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://blog.csdn.net/chuige2013/article/details/128557320）

**38、如果让你做分库与分表的设计，简单说说你会怎么做？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w）

**39、分库分表可能遇到哪些问题？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://blog.csdn.net/zhangzeyuaaa/article/details/120800832）

**40、什么是撞库、脱库和洗库？**（https://mp.weixin.qq.com/s/L0XUMHInnwN9gSYGH2nzdg）

**41、谈谈你是如何解决 MySQL 死锁问题的。**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://blog.csdn.net/ruoshui77/article/details/127330093）

**42、MySQL数据库 cpu 飙升的话，要怎么处理呢？**（https://mp.weixin.qq.com/s/vwHkXGNCdRdx8k7BeBMy9w、https://blog.csdn.net/qq_24792035/article/details/127894604）