- [B站面试视频参考](https://www.bilibili.com/video/BV1sE411M7Nv?from=search&seid=6755642384610971427)
- [hashmap如何扩容？](#)
  > placeholder
- [equals和"=="的区别？](#)
  > 对于基本类型，"=="比较的是值是否相等，对于引用类型,"=="比较的是地址值是否相同，equals默认情况下，比较的是地址值，不过可以重写该方法，例如String就通过重写该方法，使得比较的是字符串内容。
- [StringBuffer和StringBuilder类的区别](#)
  > 和String类不同的是，StringBuffer和StringBuilder类的对象能够被多次的修改，并且不产生新的未使用对象， StringBuffer是线程安全的，不过StringBuilder具有速度优势，所以大多数情况下建议使用StringBuilder
- [java的volatile关键字？和C语言中的volatile关键字有什么区别？](#)
  > placeholder
- [linkedlist是双向链表，priorityQueue默认是小顶堆？](#)
  > placeholder
- [java的基本类型有哪些？所占字节数？](#)
  > int 4字节, char 2字节, byte 1字节, short 2字节, long 8字节, float 4字节, double 8字节， JVM规范中， boolean变量作为int处理，也就是4字节, boolean数组当做byte数组处理
- [hashmap和hashtable的区别？](#)
  > hashmap是hashtable的轻量级实现，都完成了Map接口，主要区别在于hashmap允许null key和null value，由于非线程安全，效率可能高于hashtable。hashtable是线程安全的。
- [如何对多维数组排序？](#)
  > placeholder
- [map.getOrDefault(c,0)](#)
  > placeholder
- [hashmap死循环问题？concurrentHashmap？](#)
  > placeholder
- [手写hashmap?jdk1.7到jdk1.8是对其有什么实现区别？](#)
  > placeholder
- [线程池?为什么使用线程池？如何设置参数？](#)
  > [美团技术博客](https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan.html)
- Arrays.sort 对字符串数组排序后，改变的是数组指向
- [synchronized底层实现原理?](#)
  > placeholder
- [常见设计模式如工厂模式单例模式如何实现?](#)
  > placeholder

