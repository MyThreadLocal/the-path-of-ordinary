#### 并发与多线程面试题（3.16、4.14、4.20、5.5）

**1、什么是进程？什么是线程？**（D:\My_WorkSapce\MyNote\JAVA并发\007：Java并发基础常见面试题总结.md）

**2、谈谈线程的生命周期。线程有哪些状态？**（https://blog.csdn.net/liwangcuihua/article/details/120056007、https://blog.csdn.net/acc__essing/article/details/127470780）

**3、为什么要使用多线程？使用多线程可能会带来哪些问题？谈谈线程死锁以及如何避免线程死锁？**（D:\My_WorkSapce\MyNote\JAVA并发\007：Java并发基础常见面试题总结.md）

**4、哪些方法可以创建线程？Runnable 接口和 Callable 接口的区别？**（https://blog.csdn.net/qq_36908872/article/details/115180401、D:\My_WorkSapce\MyNote\JAVA并发\008：Java并发进阶常见面试题总结.md）

**5、为什么要使用线程池？**（D:\My_WorkSapce\MyNote\JAVA并发\001：线程池.md）

**6、ThreadPoolExecutor 有哪些核心参数？并谈谈这些参数的作用。如何监控线程池？**（D:\My_WorkSapce\MyNote\JAVA并发\001：线程池.md、https://blog.csdn.net/Park33/article/details/126402182、https://www.cnblogs.com/cj8357475/p/16032878.html）

**7、谈谈 ThreadPoolExecutor 的饱和策略。**（D:\My_WorkSapce\MyNote\JAVA并发\001：线程池.md）

8、 execute() 和 submit() 以及 shutdown() 和 shutdownNow() 的区别。（D:\My_WorkSapce\MyNote\JAVA并发\001：线程池.md）

**9、常见的线程池有哪些？各自有什么特点？如何确认线程池的大小？**（D:\My_WorkSapce\MyNote\JAVA并发\001：线程池.md）

**10、谈谈你对 AQS 的原理的理解。AQS 对资源的占用有哪些方式？**（D:\My_WorkSapce\MyNote\JAVA并发\004：AQS原理及同步组件.md、https://www.cnblogs.com/chengxiao/p/7141160.html#a1）

**11、谈谈 AbstractQueuedSynchronizer 的常见实现类及其常见方法。各自适合哪些场景？**（D:\My_WorkSapce\MyNote\JAVA并发\004：AQS原理及同步组件.md、https://www.cnblogs.com/chengxiao/p/7141160.html）

**12、ReentrantLock 的公平锁与非公平锁之间有什么区别？**（D:\My_WorkSapce\MyNote\JAVA并发\004：AQS原理及同步组件.md）

**13、谈谈如何自定义 AbstractQueuedSynchronizer 的实现类。谈谈其涉及到的设计模式。**（D:\My_WorkSapce\MyNote\JAVA并发\004：AQS原理及同步组件.md、https://www.cnblogs.com/chengxiao/p/7141160.html）

**14、谈谈 AbstractQueuedSynchronizer 中的等待队列是如何实现的。**（https://www.cnblogs.com/chengxiao/p/7141160.html、https://blog.csdn.net/wmq880204/article/details/114393128）

**15、谈谈独占式 acquire() 、release() 方法底层具体实现流程。**（https://www.cnblogs.com/chengxiao/p/7141160.html、https://blog.csdn.net/wmq880204/article/details/114393128）

**16、谈谈共享式 acquireShared()、releaseShared() 方法底层具体实现流程。**（https://www.cnblogs.com/chengxiao/p/7141160.html、https://blog.csdn.net/wmq880204/article/details/114393128）

**17、谈谈你对 synchronized 的理解。**（D:\My_WorkSapce\MyNote\JAVA并发\008：Java并发进阶常见面试题总结.md）

**18、synchronized 在 java1.6 以后做了哪些优化？**（D:\My_WorkSapce\MyNote\JAVA并发\006：Synchronized在JDK1.6之后的底层优化.md、https://juejin.cn/post/7109450514034589703）

**19、synchronized 和 Reentrantlock 的区别。**（D:\My_WorkSapce\MyNote\JAVA并发\008：Java并发进阶常见面试题总结.md）

**20、谈谈你对 JMM 内存模型的理解。**（D:\My_WorkSapce\MyNote\JAVA并发\008：Java并发进阶常见面试题总结.md、https://mp.weixin.qq.com/s?__biz=MzU0OTE4MzYzMw==&mid=2247533850&idx=4&sn=7477c8346a738e9a234c3b85f1cd0bc4&chksm=fbb1cce4ccc645f238e66ee5d45c9aa85c51f47987a8719e035b51ec8d49c75457b18a1dfae3&scene=27）

**21、谈谈你对 volatile 关键字的理解。谈谈 synchronized 和 volatile 的区别**（D:\My_WorkSapce\MyNote\JAVA并发\008：Java并发进阶常见面试题总结.md）

**22、谈谈你对 ThreadLocal 原理的理解。为什么要用 ThreadLocal？ThreadLocal 是如何做到线程隔离的？**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md、https://www.zhihu.com/question/399087116/answer/2679320042、https://blog.csdn.net/MrBaymax/article/details/126087320）

**23、ThreadLocal 中，ThreadLocalMap 的数据结构。**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md）

**24、ThreadLocalMap 为什么以 ThreadLocal 为 key？**（https://www.zhihu.com/question/399087116/answer/2679320042）

**25、ThreadLocal 的 key 为什么设置成弱引用**（https://blog.csdn.net/foxException/article/details/123496254、https://www.zhihu.com/question/399087116/answer/2679320042）

**26、ThreadLocal 的 value 为什么不设置成弱引用**（https://www.zhihu.com/question/399087116/answer/2679320042）

**27、ThreadLocal 如何解决内存泄漏问题？**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md、https://www.zhihu.com/question/399087116/answer/2679320042）

**28、ThreadLocal 如何解决 hash 冲突的？**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md）

**29、谈谈 ThreadLocal.set() 和 ThreadLocal.get() 的流程。**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md）

**30、谈谈 ThreadLocal 过期 key 的淘汰策略。**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md）

**31、ThreadLocal 是如何扩容的？**（D:\My_WorkSapce\MyNote\JAVA并发\002：ThreadLocal.md）

**32、父子线程如何共享数据？**（https://www.zhihu.com/question/399087116/answer/2679320042）