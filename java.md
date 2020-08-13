- [hashmap如何扩容？](#)
  > placeholder
- [equals和"=="的区别？](#)
  > 对于基本类型，"=="比较的是值是否相等，对于引用类型,"=="比较的是地址值是否相同，equals默认情况下，比较的是地址值，不过可以重写该方法，例如String就通过重写该方法，使得比较的是字符串内容。
- [StringBuffer和StringBuilder类的区别](#)
  > 和String类不同的是，StringBuffer和StringBuilder类的对象能够被多次的修改，并且不产生新的未使用对象， StringBuffer是线程安全的，不过StringBuilder具有速度优势，所以大多数情况下建议使用StringBuilder
