# 第五章：系统设计

#### 设计的定义：

**Design is the creative process of transforming the problem into a solution, the description of the solution is call the DESIGN.          
**

设计的创意过程是将问题转化为一个解决方案,对解决方案的描述称为设计。

#### 软件体系的结构和要素：

定义：

```
软件体系结构={构件，连接件，约束}
```

* **约束**：对象的连接规则.。
* **连接件**：可以是过程调用，管道，远程调用等，用于表示构建之间的相互作用。
* **构件**：可以是一组代码，如程序模块，也可以是一个独立运行的程序，如数据库服务器。

#### 体系结构风格和策略（Architecture Styles and Strategies）：

![](/assets/t7.png)

* **Piper-and-Filter（管道过滤器\)**

![](/assets/t8.png)

* **Client-Server\(客户端-服务端\)**

![](/assets/t9.png)

* **Peer-to-Peer\(对等\)**

![](/assets/t10.png)

* **Publish-Subscribe\(发布-订阅\) 也叫公布-调用**

![](/assets/t11.png)

* **Repositories\(信息库\)**

![](/assets/t12.png)

* **Laying\(分层\)**

![](/assets/t13.png)

* **Combination（结合）**

![](/assets/t14.png)

#### 设计特性：

独立性

**解耦性：**

![](/assets/t15.png)

> 自上而下的将大问题分解成若干个子问题

六种设计方法：

* **Functional  Decomposition** 功能解耦
* **Future-oriented Decomposition** 面向未来解耦
* **Data-oriented Decomposition**面向数据解耦
* **Process-oriented Decomposition**面向过程解耦
* **Event-oriented Decomposition** 面向事件解耦
* **Object-oriented Decomposition** 面向对象解耦

**内聚性：**

* 巧合内聚（聚合度最低\)

* 逻辑内聚

* 时态内聚

* 过程内聚

* 通信内聚

* 顺序内聚

* 功能内聚

![](/assets/t18.png)

