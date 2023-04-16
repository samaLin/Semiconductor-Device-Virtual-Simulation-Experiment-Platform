# Semiconductor-Device-Virtual-Simulation-Experiment-Platform
半导体器件虚拟仿真实验平台，包含PN结，BJT，MOSCAP，能带，迁移率五大仿真模块。

## 介绍
半导体器件虚拟仿真实验平台是一种新型的教育手段，具有广阔的应用前景和发展潜力。但是目前该领域还存在一些问题和挑战，如平台功能过于复杂、界面不够友好、硬件配置要求过高、不能贴合课程内容等。因此，在未来需要进一步完善平台设计、优化用户体验、提高课程贴合度等方面，以更好地服务于教育事业。

本平台是一个针对本校微电子与集成电路专业课程需求而设计的半导体器件虚拟仿真平台。该平台具有以下优点：

(1) 小体量：该平台采用轻量级编程语言开发，在任何设备上都可以快速加载。
(2) 易于使用：该平台提供了简洁明了的操作界面和指导手册，用户只需按照步骤进行输入和选择，即可完成仿真实验。
(3) 贴合课程内容：该平台涵盖了本专业课程中涉及的主要半导体器件类型和参数，如二极管、晶体管、场效应管等，并提供了与课程教材相一致的理论模型。
(4) 动态显示仿真结果：该平台不仅可以给出最终器件的仿真结果，还可以通过拖动滑块来显示中间过程中仿真曲线随着偏置电压的变化而变化的曲线图，帮助用户更好的理解偏置电压对器件各种分布曲线的影响。

## 程序架构
半导体器件虚拟仿真实验平台的整体架构如下图所示
![仿真平台架构](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/%E4%BB%BF%E7%9C%9F%E5%B9%B3%E5%8F%B0%E6%A8%A1%E5%9D%97%E6%9E%B6%E6%9E%84.png)

## 功能特点
- PN结模块：实现了一维PN结的稳态仿真。其主要功能是计算PN结中的能带图，电势分布，电场分布，载流子浓度分布，净电荷分布，电流分布和I-V特性曲线。
- BJT模块：实现了NPN和PNP型BJT的稳态仿真。其主要功能是计算BJT中的能带图，电势分布，电场分布，载流子浓度分布，净电荷分布，电流分布以及I-V特性曲线和β-V特性曲线。
- MOSCAP模块：实现了MOSCAP的稳态仿真。其主要功能是计算MOSCAP中的能带图，电势分布，电场分布，载流子浓度分布和净电荷分布。
- 能带模块：实现了对Si, Ge, GaAs等材料的不同晶向的能带仿真。
- 迁移率模块：利用蒙特卡洛法实现了对迁移率的仿真。

## 使用
程序主界面如下图所示
![程序主界面](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/%E7%A8%8B%E5%BA%8F%E4%B8%BB%E7%95%8C%E9%9D%A2.png)
点击相应按钮进入对应仿真模块

- PN结模块
![PN结模块](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/PN%E7%BB%93%E6%A8%A1%E5%9D%97.png)
- BJT模块
![BJT模块](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/BJT%E6%A8%A1%E5%9D%97.png)
- MOSCAP模块
![MOSCAP模块](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/MOSCAP%E6%A8%A1%E5%9D%97.png)
- 能带模块
![能带模块](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/%E8%83%BD%E5%B8%A6%E6%A8%A1%E5%9D%97.png)
- 迁移率模块
![迁移率模块](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/%E8%BF%81%E7%A7%BB%E7%8E%87%E6%A8%A1%E5%9D%97.png)

设置仿真参数后，点击开始仿真按钮，等待仿真结束后，点击曲线图，选择需要显示的仿真结果曲线图
![选择仿真结果](https://github.com/samaLin/Semiconductor-Device-Virtual-Simulation-Experiment-Platform/blob/main/%E9%80%89%E6%8B%A9%E4%BB%BF%E7%9C%9F%E7%BB%93%E6%9E%9C.png)
