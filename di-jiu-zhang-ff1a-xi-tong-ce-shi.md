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
|  | 配置测试 | 多个用户 |
|  | 兼容性测试 | 与大型数据库进行通信 |
|  | 回归测试 | 替代已存在的系统 |
|  | 安全性测试 | 安全性要求 |
|  | 计时测试 | 执行函数的用户响应时间 |
|  | 环境测试 | Installation Site |
|  | 质量测试 | Reliability, Maintainability, Availability |
|  | 恢复测试 | 错误或数据丢失的反应 |
|  | 维护测试 | 诊断工具 |
| Documentation Test | 文档测试 | All document compliance |
| Human Factor Test | 人为因素测试 | User Interfaces |

\(安装环境\) \|  
\| Quality Test  
 \| 质量测试 \| Reliability, Maintainability, Availability  
 \|  
\| Recovery Test  
 \| 恢复测试 \| 错误或数据丢失的反应 \|  
\| Maintenance  Test  
 \| 维护测试 \| 诊断工具 \|  
\| Documentation Test  
 \| 文档测试 \| All document compliance  
 \|  
\| Human Factor Test  
 \| 人为因素测试 \| User Interfaces  
 \|

#### 可靠性、可用性、可维护性的定义及度量方法

#### 验收测试的基本方法



