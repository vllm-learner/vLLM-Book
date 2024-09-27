# vLLM 深入浅出(vLLM Demystified)
最近几个月在使用 vLLM 推理语言模型、多模态大模型。涉及到添加 out of tree 的语言模型、多模态模型，还需要在 ray + vllm 场景下跑通。初期看着报错堆栈一头雾水，然后一步步利用打印大法调试，在此学习过程中有不少抓耳挠腮的时刻，也有不少收获，所以想借着十一期间7天假期，系统性地总结成一个系列。既然写了就分享出来，希望能对大家有所帮助。另外也希望借助这个系列，让国内做 vLLM 相关开发的同学，能够互相认识，形成社区，一起学习、交流。

## 本书集面向的人群

## 内容提要

### vLLM 概述
是什么，发展历史

### vLLM 如何使用
环境搭建，配置与测试

### 基础概念
架构、核心组件介绍
#### 模型推理的极简流程

#### 调度策略

#### 显存管理

### 进阶
如何定位问题
性能调优三板斧
### 开发实战
新增模型加载方法、新增模型、新增通信过程

### vLLM 对工作的帮助
想要一个通信组网的测试？