# M3406-ADJ降压模块

本模块采用国产芯片[M3406-ADJ](https://item.szlcsc.com/84388.html)设计，旨在为各种电子设备提供高效、稳定的直流-直流(DC-DC)转换器。该模块具有输入电压范围广、输出电压稳定、效率高等优点，适用于电池供电、汽车电子、工业控制等领域。

## 特性

- 输入电压范围：2.0V - 6.0V
- 开关频率：1.5MHz
- 最大输出电流：800mA
- 内置同步整流，无需外部肖特基二极管
- 输出电压稳定，可以低至0.6V
- 轻载切换为PFM以达到更高效率
- 高效率，最高96%
- 100%占空比压降模式
- 低静态电流，典型20uA
- 良好的输入和输出瞬态响应
- 浪涌限制和软起动
- 关断电流小于1uA
- 短路保护，热保护
- 超小封装，易于使用

## 使用说明

本仓库包含2个PCB工程。

一个是降压模块，贴片设计，同时还有2.54mm排针孔，既可以方便的贴片焊接到其它电路板上，也可以采用直插方式作为快速可插拔模块电源。

![M3406降压模块](./IMG/M3406降压模块.png)

另一个是设计为贴片方式的测试底板。

![测试底板](IMG/测试底板.png)

### 准备

在使用之前，请确保已经完成以下步骤：

1. 确认模块的输入和输出接口以及相应的电路连接方式。
2. 确保模块已经正确接地或接到电源地线上。
3. 确保模块的工作环境符合要求，如温度、湿度等。

### 步骤

1. 将模块的输入端和输出端分别连接到相应的电路板上。请注意极性和正确的连接方式。
2. 将模块的电源正极接到电源线上，负极接到地线上。请注意极性和正确的连接方式。
3. 在需要使用模块时，根据实际需求设置输入和输出电压值以及其他相关参数。具体设置方法请参考模块的数据手册。
4. 在系统启动后，模块会自动开始工作并输出稳定的直流电压。如果出现异常情况，请迅速断开电源。

### 部分测试结果

![测试结果](IMG/长江微电电感.jpg)

测试详情参见：

1. [博客文章](https://blog.boringhex.top/posts/0fe68ed1b68a/)
2. [公众号文章](https://mp.weixin.qq.com/s/rMwLUHA0_VftLfn3x-7HMQ)

### 注意事项

- 在安装和使用模块时，请务必遵守相关的安全规定和操作规程，以免造成人身伤害或财产损失。
- 在接线和设置模块时，请勿随意更改模块的输入和输出参数，否则可能会导致设备损坏或失效。
- 如果您需要对模块进行维修或升级，请先了解相关的技术知识和操作方法，以免造成不必要的损失。
