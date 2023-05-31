### JVM面试题（3.14、3.15、3.21、4.20、5.5）

**1、谈谈类的生命周期以及 JAVA 类加载过程。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\类加载过程.md、https://blog.csdn.net/y277an/article/details/93999101、https://blog.csdn.net/zero_97/article/details/122296932、https://blog.csdn.net/qq_21383435/article/details/117518679）

**2、讲一下双亲委派模型的工作流程以及优点。**（https://blog.csdn.net/axiaobaoa/article/details/125011774、https://blog.csdn.net/y277an/article/details/93999101）

**3、讲一下 JAVA 创建一个对象的过程。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md、https://blog.csdn.net/y277an/article/details/93999101）

**4、谈谈 JVM 的内存分配策略以及内存分配的并发问题。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md、https://blog.csdn.net/y277an/article/details/93999101）

**5、谈谈对象的内存布局。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md、https://blog.csdn.net/y277an/article/details/93999101）

**6、谈谈对象的访问定位有哪些方式。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md、https://blog.csdn.net/clover_lily/article/details/80095580）

**7、运行时数据区中包含哪些区域？哪些线程共享？哪些线程独享？分别谈谈它们各自的作用。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\[加餐]大白话带你认识JVM.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md）

8、说一下方法区和永久代的关系。（D:\My_WorkSapce\JavaGuide\docs\java\jvm\Java内存区域.md）

**9、谈谈你对分代理论的理解。**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\[加餐]大白话带你认识JVM.md、D:\My_WorkSapce\MyNote\JVM\002：JVM分代模型.md）

**10、什么时候新生代对象会进入老年代。**（D:\My_WorkSapce\MyNote\JVM\003：JVM垃圾回收机制.md）

**11、谈谈动态年龄判断规则。**（D:\My_WorkSapce\MyNote\JVM\003：JVM垃圾回收机制.md、https://blog.csdn.net/Aaron_Tang_/article/details/115602893）

**12、老年代空间分配担保规则。**（D:\My_WorkSapce\MyNote\JVM\003：JVM垃圾回收机制.md）

**13、什么情况下老年代会触发GC。**（D:\My_WorkSapce\MyNote\JVM\004：JVM垃圾回收器.md）

**14、JAVA 用什么方法确定哪些对象该被清理，并说明各自的优缺点。GCRoots 对象分为哪几种？**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**15、JDK 中有几种引用类型？**（D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**16、标记清除、标记复制、标记整理分别是怎样清理垃圾的？**（D:\My_WorkSapce\MyNote\JVM\003：JVM垃圾回收机制.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**17、新生代垃圾收集器有哪些？老年代垃圾收集器有哪些？哪些是单线程垃圾收集器，哪些是多线程垃圾收集器？各有什么特点？各基于哪一种垃圾收集算法？**（D:\My_WorkSapce\MyNote\JVM\004：JVM垃圾回收器.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**18、讲一下 CMS 垃圾收集器的四个步骤。**（D:\My_WorkSapce\MyNote\JVM\004：JVM垃圾回收器.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**19、CMS 垃圾收集器有什么缺点？**（D:\My_WorkSapce\MyNote\JVM\004：JVM垃圾回收器.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md）

**20、G1 垃圾收集器的步骤。**（D:\My_WorkSapce\MyNote\JVM\004：JVM垃圾回收器.md、D:\My_WorkSapce\JavaGuide\docs\java\jvm\JVM垃圾回收.md、https://blog.csdn.net/sermonlizhi/article/details/124867348）

**21、谈谈 G1 垃圾收集器的设计思想。G1 垃圾处理器的特点有哪些？**（https://blog.csdn.net/sermonlizhi/article/details/124867348）

**22、什么是内存溢出？哪些区域可能会内存溢出？谈谈各种内存溢出可能出现的原因？**（[072、大厂面试题：什么是内存溢出？在哪些区域会发生内存溢出.pdf](file:///D:/学习资料/从0开始带你成为JVM实战高手【完整】/072、大厂面试题：什么是内存溢出？在哪些区域会发生内存溢出.pdf)）

**23、Metaspace 区域内存溢出的时候，应该如何解决？**（[087、动手实验：Metaspace区域内存溢出的时候，应该如何解决？.pdf](file:///D:/学习资料/从0开始带你成为JVM实战高手【完整】/087、动手实验：Metaspace区域内存溢出的时候，应该如何解决？.pdf)）

**24、JVM 栈内存溢出，应该如何解决？**（[088、动手实验：JVM 栈内存溢出的时候，应该如何解决？.pdf](file:///D:/学习资料/从0开始带你成为JVM实战高手【完整】/088、动手实验：JVM 栈内存溢出的时候，应该如何解决？.pdf)）

**25、JVM 堆内存溢出，应该如何解决？**（[089、动手实验：JVM 堆内存溢出的时候，应该如何解决？.pdf](file:///D:/学习资料/从0开始带你成为JVM实战高手【完整】/089、动手实验：JVM 堆内存溢出的时候，应该如何解决？.pdf)）

26、生产环境的系统的 JVM 参数怎么设置的？为什么要这么设置？

27、生产环境中的 JVM 优化经验可以聊聊？

28、谈谈你在生产环境解决过的 JVM OOM 问题？