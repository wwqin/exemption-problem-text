# \#0  在网页内找出全部题目()

# \#3  MergeSortGoGoGo

## Introduction

There are 16, 000, 000 int64 values stored in an unordered array. Please
supplement the `MergeSort()` function defined in `mergesort.go` to sort this
array.

Requirements and rating principles:
* (30%) Pass the unit test.
* (20%) Performs better than `sort.Slice()`.
* (30%) Profile your program with `pprof`, analyze the performance bottleneck.
* (10%) Have a good code style.
* (10%) Document your idea and code.

NOTE: **go 1.12 is required**

## How to use

Please supplement the `MergeSort()` function defined in `mergesort.go` to accomplish
the home work.

**NOTE**:
1. There is a builtin unit test defined in `mergesort_test.go`, however, you still
   can write your own unit tests.
2. There is a builtin benchmark test defined in `bench_test.go`, you should run
   this benchmark to ensure that your parallel merge sort is fast enough.
3. **github**: https://github.com/big747386/MergeSortGoGoGo


How to test:
```
make test
```

How to benchmark:
```
make bench
```

# \#4  Python problem

## Introduction

One day, when Boss Wang was socking himself in programming, he suddenly got a call from his girlfriend.

'I wanna have a python as my pet, go and buy one for me ASAP.' She said.

But Boss Wang was not willing to, so he told her,  ' Look, I have finished my extraordinary programming yesterday, I need some rest.' 

'Really?', his girlfriend said, 'I have a software which can test whether programming will end correctly with any input or not, Hmmm, bad news, your programming didn't pass it. '

'No! you can never have done it. Literally, that's impossible!'

'You should NEVER neglect the power of a girl，go，buy my python.'

##  Problem

- How can Boss Wang's girlfriend produce that software? Is that a easy work or not? 
- Whether Boss Wang would buy a python for his girlfriend?
- Is that lawful to keep a python as pet in China?

# \#5  URL去哪儿了

## Introduction

每当你在浏览器输入www.baidu.com的时候，网页就会被打开，那么，你有没有好奇过当你在浏览器输入URL的时候究竟发生了什么才能让浏览器显示出网页。

##  Problem

简述从 URL 输入到页面展现的过程

# \#6  自适应

## Introduction

通常我们看到的网页一般会有多种表现方式，比如你在电脑打开知乎可能是这个样子，在手机上打开可能又是另一个样子，所以这是怎么实现的呢。

##  Problem

简述网页实现自适应的几种方法


# \#7  什么是Web Accessibility以及如果实现无障碍网页浏览（简单列举几种方法）

# \#8  尝试着部署一个本地的web服务或者应用，讲一下它的设计模式，组成结构以及消息传递方式，并且尽可能多的讲出其中的原理:）

# \#9  迎新前夕，王老板写完了迎新网页，这时，路过的产品经理小张说道：“你这个让用户等待太久了，点个注册过五六秒才有结果，不行的呀”，王老板狡辩称：“这是后端的锅”。那么，聪明的你能帮助可怜的后端小哥哥完成这个优化吗？
注：注册操作需要验证邮箱，你需要用java完成整个注册流程，只需用户名，不需要写入密码和其他信息，最后要持久化到数据库。

# \#10  蟹老板和鱼

## Introduction

众所周知海洋中有很多种类的鱼，每种鱼都有自己的口味。所以蟹老板只能准备很多种的食材。可是因为种类实在太多，蟹老板实在太笨，有点记不住。他只能找来了聪明的你来回答他的问题。（蟹老板为了识别食材给了每种食材一个编号）。
已知蟹老板的操作有
（1） 询问某种食材有多少个。
（2） 增加某种食材多少个（可能原来没有这种食材）。
（3） 拿出某种食材多少个来做菜（可能是全部拿出）。
（4） 询问目前最少的食材是那一种。
（5） 把食材a和食材b归为一类（归为一类后原来和食材a一类的也和食材b一类）。
（6） 某种食材的那一大类食材有多少种食材以及食材一共有多少个。
ps : 已知海中有些种类的鱼特别多，所以有些操作可能会用很多次。

##  Problem

1、实现方法限为C语言、伪代码、不会前两者的可以口头描述。
2、因为蟹老板的客人太多，蟹老板会向你提出很多问题，所以朴素的想法无法解决它的问题。
3、如果有优秀的方法，方法越多分越高，方法的时间越快，空间使用越少评分越高。
4、可以不用实现所有的功能，没有标准答案。
