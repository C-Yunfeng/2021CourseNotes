### Neural Networks and Deep Learning

#### Introduction

deep learning is one of the most **highly sought after skills** in technology worlds. 炙手可热的技能

**gain and master** those skills

demystify some of that black magic 揭开黑魔法的神秘面纱

**get** your deep learning systems to work well 【使役动词】



**rectify** just means taking a max of 0 which is why you get a function shape like this.

![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210715102129.png)

> [线性修正单元的历史](https://www.cnblogs.com/neopenx/p/4453161.html)，？？？

So is this neighborhood **highly walkable**? 适合步行



There's been a lot of **hype** about neural networks.

This has been an incredibly **lucrative** application of neural networks at multiple companies. 赚钱的

**make huge strides** in the last several years 取得巨大进步

real estate 房地产

time series or **temporal sequence** 时间序列

complex **neural network architecture**

People are just really good at **interpreting** unstructured data. 解释

![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210715104325.png)

Computers are now much better at interpreting unstructured data as well **compared to just a few years ago**.

a lot of the techniques we'll go over will apply to **both** structured data and to unstructured data. 【我肯定想不到要加both】

create **tremendous** economic value 巨大的/very big/excellent

- 小数据和大数据上ML算法与DL算法的比较

  ![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210715161422.png)



- 有趣的是，许多算法创新关注的是让神经网络跑的更快。如讲sigmoid换成ReLU

  ![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210715162501.png)

Tech Data society is **throwing up** one more digital data or computation with the rise of hardware like GPUs. 抛出，如throw up a new question。one more表示“再一次”

let's **go on to** the last video. 接着



the **most important** **building blocks** of deep learning 最重要的组成部分【同义替换】

Perhaps some of you have **some ideas of where** you might want to apply deep learning yourself.

I hope you that way too. 我希望你也这样



#### Basics

we are going to **go over** the basics. 复习

I want to **convey these ideas** using logistic regression **in order to** make the ideas eaiser to understand.

64 by 64 by 2 64\*64\*2

use m **subscript** to **denote** the number of examples 下标；表示

to output all of the training examples into a more **compact notation**, we're going to define a matrix, **capital X**. 紧缩记法；大写的X

so just to recap 简单回顾一下

- m仍是样本数，n是特征数，但X转置了

  ![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210716103532.png)

we'll start to **fetch out** logistic regression using this notation. 推导出/引出/拿出

 

**Conversely**, if Z is very small

**And indeed**, you see that as Z becomes a very negetive number, sigmoid of Z goes very close to zero. 事实上

**Before moving on**, just another note on the notation. 继续之前

- 此课程中把w和b分开，而不是只用θ

  ![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210716160038.png)

an identity vector 单位向量

let's take a look at the cost function. 【我不会加take a】

may not find a **global optimum** 全局最优

But **the intuition to take away** is that  Loss is a function will need to define to measure how good our output is. 直觉告诉我们

- 对数损失函数的有效性，当$\hat y$接近于y时，损失函数变小。所以让损失函数变小的迭代是正确的

  There are a lot of function **with roughly this effect**... 有这样类似的作用。roughly大概

  ![](https://blogjallery.oss-cn-beijing.aliyuncs.com/img/20210716190431.png)

**it turns out that** the logistic function can be viewed as a small neural network. 事实证明

it turns out that i can fly. 原来我能飞

