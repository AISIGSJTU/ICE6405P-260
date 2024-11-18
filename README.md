2024年秋云计算课程网站

* TOC
{:toc}

## 课程通知 / News
- 2024/9/23：欢迎开始**云计算（ICE6405P-260）**的学习！

## 课程材料 / Material

| 章节            | 课件                                                         |
| --------------- | ------------------------------------------------------------ |
| 云计算概论 & 机器学习概论 | [Lecture 1](./slides/lec1-intro.pdf) |
| 联邦学习概论 | [Lecture 2](./slides/lec2-FL.pdf) |
| 联邦学习研究 | [Lecture 3](./slides/lec3-FL Research.pdf) |
| 虚拟化 | [Lecture 4](./slides/lec4-virtualization.pdf) |
| 高级虚拟化 | [Lecture 5](./slides/lec5-advanced virtualization.pdf) |

## 动手实践 / Hands-on

| 章节            | 课件                                                         |
| --------------- | ------------------------------------------------------------ |
| 联邦学习实操课（1） | [FL-handson-1](./slides/FL-handson-1.pdf) |
| 联邦学习实操课（2） | [FL-handson-2](./slides/FL-handson-2.pdf) |
| 云计算实操课（1） | [Cloud-handson-1](./slides/Cloud-handson-1.pdf) |

## 作业 / Homework

### Federated Learning Lab (DDL: 2024年12月8日23:59)

在课上讲的五种FedAvg的拓展算法（FedDyn, MOON, KT-pFL, FedMA, SageFlow）的基础上，进行以下研究：

- 复现论文代码（FedDyn和MOON需要实现不少于两种的联邦学习实现方式），实现方式不限于：
  - 串行模拟并行，多线程，多进程，多虚拟机，多容器，多机
- 在不少于两个数据集上进行运行，总结实验结果，可用数据集不限于：
  - MNIST，Fashion-MNIST，Cifar10，Cifar100
- 在不少于两种模型上进行运行，总结实验结果，可用模型不限于：
  - LeNet，ResNet，VGG，GoogleNet
- 对算法中的各个超参数进行实验测试，可测试超参数不限于：
  - 客户端数量，客户端参与率，学习率，Batch size，Local epoch
- (bonus) 尝试对于论文方法进行改进，并实验验证方案的可行性。

作业提交：实验报告+源代码+必要的实验log数据+答辩ppt