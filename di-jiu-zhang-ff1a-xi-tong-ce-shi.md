# 第九章：系统测试

#### 软件配置的定义：

```
 A collection of system components delivered to a particular customer
```

**交付给特定客户的一个系统组件集合。**

**version的定义：**

```
 A configuration for a  particular system is sometimes called Version
```

**某个特定系统的配置。**

#### 系统测试过程：

1. 功能测试
2. 性能测试
3. 验收测试
4. 安装测试

> 注：单元测试那一章讲了 单元测试和集成测试，白盒法和黑盒法均属于单元测试，这一章主要关注于整个系统的测试。具体英文释义在前一章。黑盒法也可以用于功能测试中

#### 功能测试的主要方法（因果图法\)：

![](/assets/屏幕快照 2017-06-22 下午7.17.34.png)

> input 是因，output是果

#### 性能测试（１３种测试及举例）

| 测试名 | 中文 | 举例 |
| :--- | :--- | :--- |
| Stress Test | 压力测试 | 处理指定数量的设备和用户 |
| Volume Test | 容量测试 | 处理栈/队列观察是否能容纳所有数据 |
| Configuration Test | 配置测试 | 多个用户 |
| Compatibility Test | 兼容性测试 | 与大型数据库进行通信 |
| Regression Test | 回归测试 | 替代已存在的系统 |
| Security Test | 安全性测试 | 安全性要求 |
| Timing Test | 计时测试 | 执行函数的用户响应时间 |
| Environment Test | 环境测试 | Installation Site |
| Quality Test | 质量测试 | Reliability, Maintainability, Availability |
| Recovery Test | 恢复测试 | 错误或数据丢失的反应 |
| Maintenance Test | 维护测试 | 诊断工具 |
| Documentation Test | 文档测试 | All document compliance |
| Human Factor Test | 人为因素测试 | User Interfaces |

#### 可靠性、可用性、可维护性的定义及度量方法

> Reliability, Availability, Maintainability

* MTTF: Mean Time To Failure 平均失效时间
* MTTR: Mean Time To Repair 平均修复时间
* MTBF: Mean Time Between Failure  平均故障间隔时间

---

* Reliability 可靠性

> The probability that a system will operate without failure  
>   under given conditions for a given time interval.
>
> 在给定条件下对于一个给定的时间间隔，系统操作没有失败的概率。

度量方法：

** R = MTTF/\(1+MTTF\)**

---

* Availability 可用性

> The probability that a system is operating successfully according to specification at a given point of time.
>
> 根据规范，在给定的时间点系统操作成功的概率。

度量方法：

** A = MTBF/\(1+MTBF\)**

---

* Maintainability 可维护性

> The probability that , for a given condition of use, a maintenance activity can be carried out within a stated time interval and using stated procedures and resources.
>
> 在给定条件下，维护活动能够在规定的时间间隔和使用所述过程和资源的概率。

度量方法：

** M = 1/ \(1+MTTR\)**

---

#### 验收测试的基本方法

* Benchmark Test\(基准测试\)
* Pilot Test \(试验性测试\)
* alpha Test 属于内部测试\(即我们常说的内测\)
* beta Test 属于给用户进行的测试（即我们常说的beta版\)
* Parallel Test\(并行测试\)



