# 题目1
下列说法错误的是：（）

A：数组可以保存基本类型和引用类型数据，而且一个数组只能保存一种类型的数据；

B：一般开发中，会使用一个集合容器保存不同类型的数据	
C：字符串缓冲区的容量可以自动增长，而且能够把添加的数据都转换为字符类型的数据；

D：集合中只能保存引用类型数据，不能保存基本类型数据；

答案: B

# 题目2
下列说法错误的是：（）

A：Java中的数据可以保存在变量或者容器中；

B：Java中的容器包括数组、字符串缓冲区和集合；

C：Java中的数组一旦创建，容量不能更改；

D：Java中数组只能保存引用类型数据；

答案: D

# 题目3
下列属于List集合的特点是？（）

A:  它是一个元素存取无序的集合

B:  它是一个不带有索引的集合

C:  能通过索引操作集合中的元素

D:  集合中不能有重复的元素

答案: C

# 题目4
下面代码运行结果是？ （）

```angular2
List<String> arr=new ArrayList<String>();
arr.add("java");
arr.add("world");
arr.add("hello");
arr.add("java");
arr.remove("java");
System.out.println(arr.contains("java"));
```

A:  false

B:  true

C:  null

D:  运行出错

答案: B

# 题目5
下列说法错误的是：

A：增强for循环可以用来遍历数组和集合；

B：增强for循环遍历集合时，不能修改集合，因为底层还是使用迭代器迭代集合；

C：使用增强for循环遍历数组，冒号左边写的是数组下标；

D：增强for循环书写更简单，所以迭代集合时一般都有增强for循环；

答案: C

# 题目6
下列说法错误的是：（）

A：迭代器是用来迭代集合容器的；

B：一个迭代器可以对一个集合迭代多次；

C：迭代器只能从头到尾迭代，不能倒着迭代；

D：迭代器迭代集合时，不能使用迭代器之外的方法更改集合容器中数据；

答案: B

# 题目7
A：泛型是用来在编译期对数据类型进行强制检查的；

B：泛型是Java中集合的特有技术；

C：泛型在程序编译后就消失了，运行期没有泛型存在，这叫做泛型的擦除；

D：泛型就是类型的变量；定义在类上的泛型，在创建对象时就要赋值，而且类中的静态成员不能使用类上的泛型；

答案: B

# 题目8
下列有关栈结构的特点说法正确的是？ （）

A:  查找元素快

B:  先进后出

C:  先进先出

D:  增删元素慢
答案： B

# 答案9
下面关于队列结构描述正确的是？ （ ）

A:  允许在表的任意一端插入和删除

B:  先进后出

C:  队列的入口、出口各占一侧

D:  增删元素慢

答案: C

# 答案10
下列不属于数组结构的特点是？ （）

A:  是有序的元素序列

B:  查找元素快

C:  增删元素慢

D:  先进后出

答案: D

# 答案11
下列属于数组结构在内存中的特点是? （）

A:  相邻的两个元素使用地址值进行连接

B:  是连续的内存空间

C:  先进后出

D:  先进先出

答案: B

# 答案12
下列有关单向链表说法不正确的是？ （）

A:  增删元素快

B:  查找元素快

C:  查找元素慢

D:  多个结点之间，通过地址进行连接

答案: B

# 答案13
关于单向链表描述正确的是？（）

A:  每个结点包括两个部分：一个是存储数据元素的数据域，另一个是存储下一个结点地址的指针域

B:  每个结点包括三个部分：一个是存储上一个结点地址的指针域，一个是存储数据元素的数据域，另一个是存储下一个结点地址的指针域

C:  最后一个节点的指针域一定指向首节点的地址

D:  想要获取这个节点的数据，不必先获得上一个节点

答案: A

# 答案14
下面说法错误的是：（）

A：栈就有先进后出的特点；

B：队列具有先进先出的特点；

C：链表容量可以自动增长，具有增删快查询慢的特点；

D：可变数组容量不能自动增长，具有增删慢查询快的特点；

答案: D

# 问答题
## 问答1
请问Collection接口下有哪些类型的集合？它们分别是什么？
Set Queue List 类型的集合

Collection 是 Set Queue List 类型的父接口

## 问答2
请问Collection接口中定义的方法，它的所有子类是否都有，而且都会实现这些方法？

Collection 接口中，定义的方法，子类都需要实现这些方法。

## 问答3
请问向Collection集合添加一个元素用什么方法？

使用add方法

## 问答4
请问从Collection集合中删除一个元素用什么方法？这个方法有返回值吗？
使用remove方法，返回boolean方法

## 问答5
请问判断Collection集合中是否包含一个元素用什么方法？
使用contains方法，使用contains方法判断是否包含指定元素，该方法从Collection集合方法继承。

## 问答6
请问用什么方法可以获取Collection集合中元素的数量？
使用Collection接口下的size方法

# 问答题
## 问答 1
请写出数组结构的特点？
数组：连续存储，增删慢，查询快
## 问答 2
请写出链表的特点？
链表： 不连续存储，增删快，查询慢。

## 问答 3
请写出栈结构，链表结构特点
栈： 先进先出。
链表： 不连续存储，使用指针指向下一个存储的节点。

## 问答 4
请写出 ArrayList 集合内部使用的结构
实现 List 接口，使用数组保存元素。

## 问答 5
LinkedList 集合内部使用的结构
实现 List 接口，使用双向链表存储，

