# FreeRTOSLearning
FreeRTOS Study

**裸机编程：**
+ 指针的指针
+ 状态机编程
+ 面向对象的思想：多态，继承，复用（抽象）
+ 高内聚，低耦合
+ 数据结构，链表

**RTOS:**
+ 交互组件
+ 分时，任务优先级
+ 操作系统有丰富的组件(信号量⋯⋯)

---
**关于任务：** 
1. 多任务特性 
2. 多任务实现，配置（任务控制块，就是描述任务属性的结构体） 
3. 任务堆栈 

创建任务：
1. 功能需求
2. 任务创建API ( xTaskCreate(), xTaskCreateStatic() )
   任务句柄：就是一个指针，指向任务控制块
3. 功能实现

---

https://github.com/GreyYu6458/FreeRTOS_study  
https://github.com/crazyskady/FreeRTOS_study  
https://github.com/xupenghu/LearningFreeRTOS/tree/master/  

https://acuity.blog.csdn.net/article/details/83052696  
https://www.sohu.com/a/249346881_505803  
https://blog.csdn.net/lxl584685501/article/details/46638207  

https://www.zhihu.com/question/26645220/answer/229928211  
https://www.zhihu.com/question/301250055?sort=created  
https://www.zhihu.com/question/291405354  
https://www.zhihu.com/question/28724426  
https://www.zhihu.com/question/395354084  
https://www.zhihu.com/question/342441430  

---
linux应用程序开发  
linxu系统编程开发	  
使用linux—〉linxu系统编程开发—〉驱动开发和分析linux内核  
  
https://blog.csdn.net/qq_16933601  
超详细分析Bootloader（Uboot）到内核的启动流程（万字长文！）  
https://blog.csdn.net/qq_16933601/article/details/106244510

---
**嵌入式与Linux那些事(专栏)**
 - Linux块设备驱动详解  
   https://blog.csdn.net/qq_16933601/article/details/103553403  
   
 - 嵌入式软件开发笔试面试知识点总结-操作系统部分  
   https://blog.csdn.net/qq_16933601/article/details/112689117  
   
 - 嵌入式软件开发笔试面试知识点总结-Linux部分  
   https://blog.csdn.net/qq_16933601/article/details/112688721  
   
 - 嵌入式软件开发笔试面试知识点总结-ARM部分  
   https://blog.csdn.net/qq_16933601/article/details/112688634  

---
**技术面问题汇总（Linux C/C++软件工程师） 奇妙之二进制(专栏)**
 - Linux系统软件工程师/嵌入式Linux应用开发工程师 知识体系构建 500篇（持续更新）  
   https://hongjh.blog.csdn.net/article/details/108051988

---
Typora的安装和语法
https://zhuanlan.zhihu.com/p/90561228

---

MicroPython
https://zhuanlan.zhihu.com/p/31934491
不过我们目前在设计一种新方案，我们目前称为uPython，语法规则和库都会做得和原生的python一样
设计思路上和MicroPython不一样，为了适配更小ROM和RAM的单片机，我们会把python代码先编译成uPythonObj的伪机器代码，板子上只要解析一下这个伪机器代码就行，所有的语法解析工作都在PC机上完成，在单片机上的执行效率会高很多，对内存的需求也会小得多。
另外会有计划做开发板的模拟器，这样就可以在脱离板子的基础上也能跑python代码

https://github.com/Skiars/berry

C++ 编写一个解释器
https://blog.csdn.net/q1007729991/article/details/103189736


想自己编写一个解释器，有什么好的建议或者相对简单的解释器代码可供参考?
https://www.zhihu.com/question/31656477/answer/1350602690
https://www.zhihu.com/question/347537041/answer/839006064
https://www.zhihu.com/question/325210206/answer/689285823
https://www.zhihu.com/question/22220383/answer/541019918
https://www.cnblogs.com/CodeWorkerLiMing/p/11073540.html  




