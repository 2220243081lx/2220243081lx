# 你好，我是李想 👋

大连海事大学（211）· 测控技术与仪器（双一流学科）
专业排名 **9/86（前 1.7%）** · GPA **3.83/5.0** · CET-6 **535**

研究兴趣：**机器人感知与定位（视觉 SLAM / 多传感器融合）· 嵌入式控制 · 机械臂系统 · FPGA 数字系统设计**

> 🤝 **团队担当**：6 项国家级赛事获奖，5 次以**队长 / 负责人**身份带队，1 次以**主力队员**身份参与；
> 负责过机械、嵌入式、算法三方向的技术统筹与整机联调。

## 🔥 News

- **2026.11**：获睿抗机器人开发者大赛 **国家一等奖**（**队长**）
- **2026.08**：获 RoboCup 机器人世界杯中国赛「AI+智创未来」**国家二等奖**（**队长**）；中国大学生计算机设计大赛 **国家二等奖**（主力队员）
- **2025.11**：获全国大学生信息安全与对抗技术竞赛（ISCC）**国家三等奖**（**队长**）；立项国家级大创「**多模态医疗护理机器人**」并担任**项目负责人**
- **2025.10**：获 RoboCup 机器人世界杯中国赛 **国家三等奖**（**队长**）
- **2025.08**：获中国机器人及人工智能大赛 **国家三等奖**（**队长**）

## 🏆 荣誉奖项

| 时间 | 奖项 | 级别 | 我的角色 |
| --- | --- | --- | --- |
| 2026.11 | 睿抗机器人开发者大赛 · 智能配送与分拣赛道 | **国家一等奖** | **队长** |
| 2026.08 | RoboCup 机器人世界杯中国赛 · AI+智创未来 | **国家二等奖** | **队长** |
| 2026.08 | 中国大学生计算机设计大赛 · 软件开发与应用 | **国家二等奖** | 主力队员 |
| 2025.11 | 全国大学生信息安全与对抗技术竞赛（ISCC） | 国家三等奖 | **队长** |
| 2025.10 | RoboCup 机器人世界杯中国赛 | 国家三等奖 | **队长** |
| 2025.08 | 中国机器人及人工智能大赛 | 国家三等奖 | **队长** |
| — | 蓝桥杯 | 省二等奖 | **队长** |

- 国家级大学生创新创业训练计划 **项目负责人**（多模态医疗护理机器人，2025.11 立项）

---

## 🤖 项目经历

### 1️⃣ 多模态医疗护理机器人 · 国家级大创
**🏷 项目负责人 / 队长** ｜ 2025.11 至今 ｜ SolidWorks · STM32 · 视觉识别 · 多机协同

双机械臂 + 移动底盘形态，面向养老陪护场景：**SolidWorks** 完成整机、双臂与底盘建模装配及爆炸图渲染；**独立开发 STM32 底层电控**（电机驱动、传感器采集、运动控制）；统筹机械、算法两组分工，完成整机联调。

<table>
<tr>
  <td align="center"><img src="assets/eldercare/robot_render.png" width="300"><br><sub>整机三维建模与渲染</sub></td>
  <td align="center"><img src="assets/eldercare/robot_real.jpg" width="300"><br><sub>整机实物联调</sub></td>
  <td align="center"><img src="assets/eldercare/gripper.jpg" width="300"><br><sub>机械臂夹爪对比设计</sub></td>
</tr>
</table>

### 2️⃣ 基于 Webots 的虚实结合六轴协作机械臂 · 睿抗国赛
**🏷 队长** ｜ 国家一等奖 ｜ Webots · OpenCV · 单应性标定 · Client-Server 通信

省赛虚拟仿真 + 国赛实物联调：**HSV 颜色空间识别与轮廓检测**定位物块，基于**单应性矩阵标定**完成像素坐标到机械臂坐标映射；设计 **Client-Server 低延迟双向通信**与状态反馈闭环调度抓取流程；**九点标定**完成视觉-机械臂坐标拟合，真空气动夹爪实现传送带物料分拣。

<table>
<tr>
  <td align="center"><img src="assets/arm/arm_national.jpg" width="320"><br><sub>国赛实物六轴机械臂</sub></td>
  <td align="center"><img src="assets/arm/sorting_targets.jpg" width="320"><br><sub>传送带物料分拣目标</sub></td>
  <td align="center"><img src="assets/arm/calibration.jpg" width="320"><br><sub>九点标定与视觉-机械臂坐标拟合</sub></td>
</tr>
<tr>
  <td align="center" colspan="3"><img src="assets/arm/webots_arm.png" width="240"><br><sub>Webots 虚拟仿真环境</sub></td>
</tr>
</table>

### 3️⃣ 智慧药房自主配送小车 · CRAIC 国赛
**🏷 队长** ｜ 国家三等奖 ｜ ROS · 激光 SLAM · AMCL · OpenCV · 二维码/OCR

树莓派 + ROS 的 **EPRobot** 小车平台：单线激光雷达 **SLAM 建图**、**AMCL 定位**与 **move_base 路径规划**；OpenCV 轮廓定位 + 二维码/OCR 识别；**有限状态机**调度「扫码-取药-配送-语音播报」全流程，支持多窗口自主配送与双车协同。

<table>
<tr>
  <td align="center"><img src="assets/car/robot_body.png" width="320"><br><sub>EPRobot 小车硬件组成</sub></td>
  <td align="center"><img src="assets/car/system_arch.png" width="320"><br><sub>整车软硬件系统架构</sub></td>
  <td align="center"><img src="assets/car/slam_map.png" width="320"><br><sub>激光 SLAM 建图与路径规划</sub></td>
</tr>
</table>

### 4️⃣ ROSMan 人形机器人 · 智能安全挑战（ISCC）
**🏷 队长** ｜ 国家三等奖 ｜ ROS · Docker · AprilTag · 视觉伺服 · 舵机步态

24 自由度人形机器人（树莓派 5 + Docker + ROS）：**LAB 颜色阈值 + 三段 ROI 视觉检测**、**AprilTag 引导与抗视觉欺骗**、分段 P 控制视觉伺服巡线；**自研跨栏/上下台阶/沙包投掷**舵机步态动作组，Gazebo 仿真验证后真机联调。

<table>
<tr>
  <td align="center"><img src="assets/rosman/gazebo_sim.png" width="320"><br><sub>Gazebo 仿真：视觉检测与步态联调</sub></td>
  <td align="center"><img src="assets/rosman/hardware.jpg" width="320"><br><sub>24 自由度人形机器人本体与配件</sub></td>
</tr>
</table>

### 5️⃣ 像素生息 · FPGA 动态音画窗景
**🏷 队长** ｜ 嵌入式芯片与系统设计竞赛 · FPGA 创新设计赛道 ｜ Verilog · SPI/SDRAM/HDMI

以安路 **EG4S20 FPGA** 为核心的桌面音画设备：自主实现 **TF 卡 SPI 读取、FAT32 扫描与 BMP 解析、DDA 定点双线性缩放、SDRAM 三 bank 背景缓存、800×600 HDMI 输出与 48kHz PCM 音画同步**；红外遥控 + 环境光自适应；自主拓展 **PCB 与 3D 打印外壳**完成整机集成，**六时钟域时序零违例**。

<table>
<tr>
  <td align="center"><img src="assets/fpga/device.jpg" width="320"><br><sub>整机实拍：HDMI 音画输出与红外遥控</sub></td>
  <td align="center"><img src="assets/fpga/poster.jpg" width="240"><br><sub>作品海报</sub></td>
  <td align="center"><img src="assets/fpga/enclosure.png" width="320"><br><sub>自研 3D 打印外壳建模</sub></td>
</tr>
</table>

### 6️⃣ 无人车导航 · 视觉导航开发
**🏷 主要开发者** ｜ 基于双目相机的视觉 SLAM 与多传感器融合

基于双目相机搭建**视觉 SLAM 定位系统**；融合 **IMU 与轮速里程计**抑制定位漂移；开发**可行驶区域分割、障碍物检测**算法；完成算法轻量化与实车多模块联调。

---

## 📖 教育背景

**大连海事大学（211）** · 测控技术与仪器（双一流学科）
专业排名 9/86（前 1.7%）· GPA 3.83/5.0
核心课程：高等数学（95）、电路原理（92）、FPGA 可编程逻辑器件（93）

## 🛠️ 技能

- **嵌入式**：51/STM32 单片机开发、电机驱动与运动控制、PCB 绘制（含自主拓展 PCB 设计）
- **机器人**：ROS 节点编写、激光/视觉 SLAM、多传感器融合、move_base 导航、手眼标定与坐标变换、人形机器人步态控制、Webots/Gazebo 仿真
- **FPGA/数字设计**：Verilog、SPI/SDRAM/HDMI 接口开发、多时钟域时序设计
- **工具**：SolidWorks 建模仿真、3D 打印
- **语言**：CET-6（535）

## 📮 联系方式

- 邮箱：3163079468@qq.com
- GitHub：[@2220243081lx](https://github.com/2220243081lx)
