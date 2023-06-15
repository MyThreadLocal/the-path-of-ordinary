### 分布式面试题（3.24、3.29、3.30、3.31、4.17、4.21）



#### 分布式事务

**1、谈谈常见的分布式事务产生的场景。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=4&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**2、谈谈你对 CAP 理论的理解。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=5&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5、D:\My_WorkSapce\MyNote\分布式\001：分布式概念.md）

**3、谈谈你对 BASE 理论的理解。**（D:\My_WorkSapce\JavaGuide\docs\system-design\distributed-system\BASE理论.md、https://www.bilibili.com/video/BV1Q4411y7ip?p=7&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**4、谈谈你对 2PC 的理解。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=8&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**5、谈谈基于 2PC 实现的 XA 方案。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=9&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**6、谈谈 Seata 的 AT 模式实现的 2PC 方案。**（https://www.bilibili.com/video/BV1Q4411y7ip?p=10&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5、https://mp.weixin.qq.com/s/ujRRtdLOeKEHsHrtDRNXGA）

7、如何解决 @Transaction 在多数据源情况下不生效的情况？（5、6）

8、AT 模式相较于 XA 方案有哪些优点？（6）

**9、什么情况下 Seata 的 AT 模式的全局事务会回滚失败？全局事务的 ABA 问题。**（https://blog.csdn.net/Java_zhujia/article/details/127841538）

10、AT 模式的 undolog 日志中包含哪些内容？（https://blog.csdn.net/zjj2006/article/details/108592370）

11、谈谈你对 TCC 的理解。



**9、谈谈你对分布式事务的理解。分布式事务的各种实现方式、具体流程及其优缺点。**（D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md、https://mp.weixin.qq.com/s/XknegP66mnYboiBx556Kzw、https://mp.weixin.qq.com/s/_56jq_p_nDUiBwaI2MTlmA、https://mp.weixin.qq.com/s/ujRRtdLOeKEHsHrtDRNXGA） 

**10、2PC 协议中如何处理事务参与者与协调者之间的通信失败问题？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=4&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**11、谈谈 3PC 协议在 2PC 协议中做了哪些优化？**（https://mp.weixin.qq.com/s/XknegP66mnYboiBx556Kzw、https://mp.weixin.qq.com/s/_56jq_p_nDUiBwaI2MTlmA）

**12、谈谈分布式事务框架 Seata 以及其各种模式的具体实现步骤。**（D:\My_WorkSapce\MyNote\分布式\002：分布式事务.md、https://mp.weixin.qq.com/s/_56jq_p_nDUiBwaI2MTlmA、https://mp.weixin.qq.com/s/ujRRtdLOeKEHsHrtDRNXGA）









**1、什么是分布式？什么是集群？谈谈分布式集群（分布式系统）的优缺点。**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw、D:\My_WorkSapce\MyNote\分布式\001：分布式概念.md）

**2、谈谈传统单体应用的缺点。为什么要用微服务？**（D:\My_WorkSapce\MyNote\SpringCloud\001：微服务.md）



**4、谈谈你对分布式锁的理解。分布式锁常见的实现方案及其缺点。**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=9&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5、https://mp.weixin.qq.com/s/49hgH3COla3wU0rgyiUVgg）

**5、分布式服务接口的幂等性如何设计？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=60&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**6、如何限流？说一下在工作中的具体实现。**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=61&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**7、集群分布式 session 如何实现？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=62&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）

**8、如何设计一个高并发系统？**（https://www.bilibili.com/video/BV1rY4y1S7ks?p=64&vd_source=1b46608819e0f30afa9bfdc29fd8c0f5）



**13、SpringCloud 的基础功能有哪些？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

**14、谈谈 Eureka 的治理机制。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md、https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

**15、谈谈 Ribbon 和 Nginx 的区别。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

**16、谈谈服务雪崩。**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

**17、Hystrix 提供的服务雪崩的常见解决办法有哪些？**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md）

**18、Feign 解决了什么问题？**（D:\My_WorkSapce\MyNote\SpringCloud\002：Netflix组件.md、https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

**19、谈谈 Zuul 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw、https://mp.weixin.qq.com/s/pGSx8eKFH3YnUos3SM2ITw）

**20、谈谈 Config 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）

**21、谈谈 Bus 的作用是什么？**（https://mp.weixin.qq.com/s/MJrahcDXwxgDr5zBdO3XWw）