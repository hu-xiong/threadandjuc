# Java并发多线程JUC包 

注：以下内容基于版本

```properties

java多线程基础
java多线程安全
java多线程jmm内存模型
java多线程juc

```

### 一、java多线程基础

1. ##### 开篇题 实现多线程的方式有几种方式你确定吗? 

 实现多线程的方式有几种方式?
 
 https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-000.md
 
   bothRunnableThread 结果是什么??

 threadbase ThreadinterviewApplicationTests
 
2. ##### 多线程状态流转你真的确定吗?

  请看下面得说法对吗? 
  https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-003-1.md 


 有哪些不同的多线程生命周期? 
 https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-003.md
 
 threadstate 

3. ##### Object 中的线程方法
   
 https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-003-2.md
 
 threadandobject
 
 讲解 wait notify notifyall（很多并发工具类的原理）
 

### 线程安全问题

1. ##### 什么是线程安全？？
2. ##### 有几类线程安全的问题 
3. ##### 如何避免线程安全问题？？如何解决逸出
4. ##### 哪些场景需要额外注意线程安全问题？？

   https://github.com/qiurunze123/threadandjuc/blob/master/docs/threadsafe001.md

### 线程JMM内存模型

  1. ##### JMM内存模型+java对象模型+jvm内存模型
   
   https://github.com/qiurunze123/threadandjuc/blob/master/docs/JMM-1.md

  2. #####  为什么出现了java内存模型 ？
  
   https://github.com/qiurunze123/threadandjuc/blob/master/docs/JMM.md

  3. ##### JMM重点内容
     
   https://github.com/qiurunze123/threadandjuc/blob/master/docs/JMM.md
   
  4. ##### volatile 讲解
  
  https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-5.md

### AQS 并发包的基础 

   1. ##### CAS基础 
   
   https://github.com/qiurunze123/threadandjuc/blob/master/docs/thread-base-6.md
   
   2. ##### AQS基础
   
   https://github.com/qiurunze123/threadandjuc/blob/master/docs/AQS.md

   3. ##### ReentrantLock讲解 CountDownLatch讲解
   
