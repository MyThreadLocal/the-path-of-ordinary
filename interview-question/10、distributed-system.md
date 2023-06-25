## 分布式面试题

### 一、分布式事务

#### 	1、分布式事务基础理论

##### 			1.1、分布式事务概念

​			**1.1.1、分布式事务的概念。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=4）

​			**1.1.2、谈谈你对 CAP 理论的理解。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=5、D:\My_WorkSapce\MyNote\分布式\001：分布式概念.md）

​			**1.1.3、谈谈你对 BASE 理论的理解。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=7、D:\My_WorkSapce\JavaGuide\docs\system-design\distributed-system\BASE理论.md）

##### 			1.2、分布式事务产生的场景

​			**1.2.1、本地事务与远程调用相结合。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=4）

​			**1.2.2、单体系统访问多个数据库实例。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=4、https://blog.csdn.net/Wei_Naijia/article/details/128069840）

##### 			1.3、分布式事务的常见解决方案

###### 					1.3.1、2PC 协议

​				**1.3.1.1、谈谈你对 2PC 的理解。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=8、D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）

​				**1.3.1.2、谈谈你对 XA 协议的理解。**（https://blog.csdn.net/BruceLiu_code/article/details/114922914、https://www.bilibili.com/video/BV1Q4411y7ip?p=9）

###### 					1.3.2、3PC 协议

​				1.3.2.1、谈谈你对 3PC 的理解。（D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）

​				1.3.2.2、谈谈 3PC 协议在 2PC 协议中做了哪些优化？（https://mp.weixin.qq.com/s/XknegP66mnYboiBx556Kzw、https://mp.weixin.qq.com/s/_56jq_p_nDUiBwaI2MTlmA）

###### 					1.3.3、TCC 方案

​				**1.3.3.1、谈谈你对 TCC 方案的理解。**（D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）

###### 					1.3.4、本地事务表

​				1.3.4.1、谈谈你对本地事务表方案的理解。（D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）

###### 					1.3.5、可靠消息最终一致性

​				**1.3.5.1、可靠消息实现最终一致性的关键点有哪些？**（https://www.bilibili.com/video/BV1Q4411y7ip?p=24）

​				**1.3.5.2、本地消息表实现最终一致性。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=25）

​				**1.3.5.3、RocketMq 实现最终一致性。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=26、D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）

###### 					1.3.6、最大努力通知方案

​				1.3.6.1、谈谈最大努力通知。（https://www.bilibili.com/video/BV1Q4411y7ip?p=32、D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md）



#### 	2、分布式事务框架 Seata

##### 			2.1、Seata 的整体事务模式

​			**2.1.1、谈谈 Seata 的整体事务模式。**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=9）

​			**2.1.2、Seata 与传统的 XA 分布式事务的区别是什么？**（https://baike.baidu.com/item/XA/6370881?fr=aladdin）

​			2.1.3、Seata 的整体事务模式和常规的事务模式有什么区别？（2.1.1）

##### 			2.2、Seata 的 AT 模式

​			**2.2.1、谈谈 Seata 的 AT 模式。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=10、https://mp.weixin.qq.com/s/ujRRtdLOeKEHsHrtDRNXGA）

​			2.2.2、谈谈 AT 模式的整体执行流程。（2.2.1）

​			**2.2.3、什么情况下 Seata 的 AT 模式的全局事务会回滚失败？全局事务的 ABA 问题。**（https://blog.csdn.net/Java_zhujia/article/details/127841538）

​			2.2.4、AT 模式的 undolog 日志中包含哪些内容？（https://blog.csdn.net/zjj2006/article/details/108592370）

##### 			2.3、Seata 的 XA 模式

​			**2.3.1、谈谈 Seata 的 XA 模式。**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=10）

##### 			2.4、Seata 的 TCC 模式

​			**2.4.1、谈谈 Seata 的 TCC 模式。**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=12）

##### 			2.5、Seata 的 Saga 模式

​			**2.5.1、谈谈 Seata 的 Saga 模式。**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=13）

​		2.6、谈谈 Seata 各模式的特点。



#### 	3、分布式事务应用

​		3.1、谈谈各个解决方案的适用场景以及技术选型。

****

### 二、分布式锁

​	**4、谈谈你对分布式锁的理解。分布式锁常见的实现方案及其缺点。**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=9&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5、https://mp.weixin.qq.com/s/49hgH3COla3wU0rgyiUVgg）

****

### 三、分布式 ID

#### 	1、分布式 ID 的概念

​		1.1、分布式 ID 的产生场景（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=46）

​		1.2、分布式 ID 的条件（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=46）

#### 	2、分布式 ID 的方案

##### 		2.1、UUID 方案

​			**2.1.1、UUID 方案的基本原理**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=47）

​			**2.1.2、UUID 方案的优缺点**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=47）

​			2.1.3、UUID 由哪些部分组成

##### 		2.2、基于数据库的方案

​			**2.2.1、基于数据库自增的 ID 方案的原理**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=48）

​			**2.2.2、基于数据库自增的 ID 方案的优缺点**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=48、https://www.bilibili.com/video/BV1yv4y1c7Vq?p=53）

​			**2.2.3、基于数据库集群模式的自增 ID**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=49）

​			**2.2.4、基于数据库号段模式的 ID 方案**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=50）

##### 		2.3、redis 模式

​			**2.3.1、基于 redis 生成 ID 的原理**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=51）

​			**2.3.2、基于 redis 生成 ID 的优缺点**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=51、https://www.bilibili.com/video/BV1yv4y1c7Vq?p=53）

##### 		2.4、雪花算法

​			**2.4.1、雪花算法的原理**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=52、https://blog.csdn.net/weixin_43731005/article/details/127949824）

​			**2.4.2、雪花算法的 ID 由哪些部分组成**（https://www.bilibili.com/video/BV1yv4y1c7Vq/?p=54、https://blog.csdn.net/weixin_43731005/article/details/127949824）	

​			**2.4.3、雪花算法的优缺点**（https://www.bilibili.com/video/BV1yv4y1c7Vq?p=53、https://blog.csdn.net/weixin_43731005/article/details/127949824）

****

### 三、分布式框架

​	**13、SpringCloud 的基础功能有哪些？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

​	**14、谈谈 Eureka 的治理机制。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md、https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

​	**15、谈谈 Ribbon 和 Nginx 的区别。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

​	**16、谈谈服务雪崩。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

​	**17、Hystrix 提供的服务雪崩的常见解决办法有哪些？**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

​	**18、Feign 解决了什么问题？**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md、https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

​	**19、谈谈 Zuul 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw、https://mp.weixin.qq.com/s/pGSx8eKFH3YnUos3SM2ITw）

​	**20、谈谈 Config 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

​	**21、谈谈 Bus 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

****

### 四、分布式架构

​	**1、什么是分布式？什么是集群？谈谈分布式集群（分布式系统）的优缺点。**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw、D:\My_WorkSapce\MyNote\分布式\001：分布式概念.md）

​	**2、谈谈传统单体应用的缺点。为什么要用微服务？**（D:\My_WorkSapce\MyNote\SpringCloud\001：微服务.md）

​	**8、如何设计一个高并发系统？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=64&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

​	**5、分布式服务接口的幂等性如何设计？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=60&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

​	**6、如何限流？说一下在工作中的具体实现。**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=61&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

​	**7、集群分布式 session 如何实现？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=62&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

​	8、分布式ID