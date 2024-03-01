# proj321-ArceOS-Hypervisor-Porting
# 移植 ArceOS Hypervisor到瑞芯微RK3588，实现虚拟化功能

## 项目描述
当前机器人领域应用和智能控制多部署在两台独立硬件设备上，虽然在部署上互相有充足的灵活性，不互相影响，但也存在以下缺点：
1）不同的硬件平台造成了一定的资源浪费；
2）部署和装配问题，机器人腔体空间有限，在有限的空间内，部署多个硬件平台存在一定的困难。
为解决以上问题，北京朴津智能科技有限公司做了集中部署尝试，在同一台设备上通过虚拟化技术实现应用和智能控制部署在同一硬件平台同时运行，这也是本题目的来源。

借助安全、模块化、可扩展的虚拟化技术ArceOS Hypervisor，实现RK3588 arm核虚拟化，在单一CPU上同时运行多操作系统。

## 预期目标

### 初级目标

移植 ArceOS Hypervisor到瑞芯微RK3588，运行Nimbos。

### 中级目标

1. ArceOS Hypervisor支持在瑞芯微RK3588上双Linux操作系统独立运行，互不影响；
2. 应用演示。

### 高级目标

1. 支持网络接口和USB接口；
2. 虚拟机占用CPU核数可配置，默认4核；
3. 应用演示。

## 特征

1. 文档、代码、问题、答疑交互过程都开放和开源的
2. 支持各种硬件
	- 基于目前量产的处理器和开发板：
		- 朴津智能CCM-300A中央计算平台（基于瑞芯微 RK3588 ARM CPU）

## 已有参考资料

- [ArceOS](https://cicvedu.com/course/112)
- [Hypervisor](https://github.com/arceos-hypervisor/2023-virtualization-campus)
		
## 赛题分类

2.3 操作系统内核大类 -->  2.3.1 虚拟化

## 参赛要求

1. 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
2. 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
3. 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等

## License

GPL-3.0 License

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

姓名：臧义昌
单位：北京朴津智能科技有限公司
email： zangyichang@chinapji.com

姓名：郭伟康
单位：国家智能网联汽车创新中心
github ID： https://github.com/guoweikang
email： guoweikang@china-icv.cn
