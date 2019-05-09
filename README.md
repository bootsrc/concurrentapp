# concurrentapp

Java并发技术的应用

* [实现三个线程交替打印1-75](/src/main/java/com/lsm/exam/RobinPrintReentrantLock.java)

* [LockSupport.park()， LockSupport.unpark(thread)](/src/main/java/com/lsm/locksupport/ParkDemo.java)

  LockSupport.park()作用是等待持有许可（permit），获取到了许可后，当前的线程才可以往下继续运行
  
  LockSupport.unpark(thread)作用是发送许可（permit）到线程thread。 一旦这个unpark()执行了。 thread就会立即得到这个许可，会继续往下运行。