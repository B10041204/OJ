### NC1 大数加法

> <font color='black'>**描述**</font>
>
> 以字符串的形式读入两个数字，编写一个函数计算它们的和，以字符串形式返回。
>
> 数据范围：s.length,t.length<=100000，字符串仅由'0'~‘9’构成
>
> 要求：时间复杂度 O(n)<br/>
><font color='black'>**示例1**</font>
>
>```
>输入："1","99"
>返回值："100"
>说明：1+99=100 
>```
>
><font color='black'>**示例2**</font>
>
>```
>输入："114514",""
>返回值："114514"
>```



### NC32 求平方根

> <font color='black'>**描述**</font>
>
> 实现函数 int sqrt(int x).
> 计算并返回 x 的平方根（向下取整）
>
> 斐波那契数列是一个满足 的数列
>
> 数据范围： 0 <= x < $2^{31}-1$
>
> 要求：空间复杂度 O(1)，时间复杂度 O($logx$)
>
>
> <font color='black'>**示例1**</font>
>
> ```
> 输入：2
> 返回值：1
> ```
> <font color='black'>**示例2**</font>
>
> ```
> 输入：2143195649
> 返回值： 46294
> ```



### NC65 斐波那契数列

> <font color='black'>**描述**</font>
>
> 大家都知道斐波那契数列，现在要求输入一个正整数 n ，请你输出斐波那契数列的第 n 项。
>
> 斐波那契数列是一个满足 的数列
>
> 数据范围：
>
> 要求：空间复杂度 O(1)，时间复杂度 O(n) ，本题也有时间复杂度 O(logn)的解法<br/>
>
> <font color='black'>**输入描述：**</font>
>
> 一个正整数n。
>
> <font color='black'>**返回值描述：**</font>
>
> 输出一个正整数。<br/>
> <font color='black'>**示例1**</font>
>
> ```
> 输入：4
> 返回值：3
> 说明：根据斐波那契数列的定义可知，fib(1)=1,fib(2)=1,fib(3)=fib(3-1)+fib(3-2)=2,fib(4)=fib(4-1)+fib(4-2)=3，所以答案为3。   
> ```
> <font color='black'>**示例2**</font>
>
> ```
> 输入：1
> 返回值：1   
> ```
> <font color='black'>**示例3**</font>
>
> ```
> 输入：2
> 返回值：1   
> ```

### NC75 数组中只出现一次的两个数

> <font color='black'>**描述**</font>
>
> 一个整型数组里除了两个数字只出现一次，其他的数字都出现了两次。请写程序找出这两个只出现一次的数字。
>
> 数据范围：数组长度 2≤n≤1000，数组中每个数的大小 0<val≤1000000
>
> 要求：空间复杂度 O(1)，时间复杂度 O(n)
>
> 提示：输出时按非降序排列。
>
> <font color='black'>**示例1**</font>
> ```
> 输入：>[1,4,1,6]
> 返回值：>[4,6]
> 说明：
> 返回的结果中较小的数排在前面    
> ```
> <font color='black'>**示例2**</font>
> ```
> 输入：>[1,2,3,3,2,9]
> 返回值：>[1,9]
> ```

### NC78 反转链表
> <font color='black'>**描述**</font><br/>
> 给定一个单链表的头结点pHead(该头节点是有值的，比如在下图，它的val是1)，长度为n，反转该链表后，返回新链表的表头。
> 
> 数据范围：0≤n≤1000
> 要求：空间复杂度O(1) ，时间复杂度O(n) 。
> 
> 如当输入链表{1,2,3}时，
> 经反转后，原链表变为{3,2,1}，所以对应的输出为{3,2,1}。
> 以上转换过程如下图所示：
> ![avatar](https://uploadfiles.nowcoder.com/images/20211014/423483716_1634206291971/4A47A0DB6E60853DEDFCFDF08A5CA249)

> <font color='black'>**示例1**</font>
>
> 输入：
> {1,2,3}
>
> 返回值：
> {3,2,1}
>
> <font color='black'>**示例2**</font>
>
> 输入：
> {}
> 
> 返回值：
> {}
> 
> 说明：
> 空链表则输出空    

### NC103 反转字符串



### NC141 判断是否为回文字符串



### NC151 最大公约数



### NC288 打印从1到最大的n位数



### NC298 两个队列实现栈

