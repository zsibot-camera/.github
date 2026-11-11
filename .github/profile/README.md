<p align="center">
  <img src="https://raw.githubusercontent.com/zsibot-camera/.github/main/assets/banner.png" alt="智身科技 GENISOM AI" width="100%">
</p>

# 欢迎来到智身科技-视觉传感器 👋

智身科技（GENISOM AI）专注于智能机器人系统的研发。相机模块团队负责机器人视觉感知硬件的驱动、标定与配套 SDK，覆盖 NVIDIA Jetson / Orin、RDK S600 / S100P 等计算平台，以及 MIPI CSI、GMSL2、R-LinC 等相机接口。

我们把相机驱动、SDK 与工具交付出来，帮助开发者在自己的机器人或视觉项目中快速接入智身科技的相机模组。

## 支持的平台

- **NVIDIA Jetson / Orin / AGX Thor**：GMSL2 / MIPI CSI 相机模组驱动
- **D-Robotics RDK S600 / S100P**：相机模组驱动
- **统一 SDK（ZSCamera_sdk）**：C++17，覆盖 RV1126B / Orin NX / AGX Thor；UVDP v2、标定、深度与编码
- **上位机工具（ZSViewer）**：RGB-D 查看、点云、抓图、录像；支持 Linux / Windows

## 开源仓库

| 仓库 | 说明 |
| --- | --- |
| [nvidia-jetson-camera-drivers](https://github.com/zsibot-camera/nvidia-jetson-camera-drivers) | NVIDIA Jetson 相机驱动、深度 SDK 与 ROS2（Thor GMSL 双目 OG02D10） |
| [d-robotics-camera-drivers](https://github.com/zsibot-camera/d-robotics-camera-drivers) | D-Robotics RDK S600 / S100P 相机驱动与 SDK（整理中） |
| [ZSCamera_sdk](https://github.com/zsibot-camera/ZSCamera_sdk) | 统一相机与双目深度 SDK 二进制交付：C++ 头文件、预编译库、模型、协议/标定文档（不含源码） |
| [ZSViewer-delivery](https://github.com/zsibot-camera/ZSViewer-delivery) | 上位机 ZSViewer 工具独立交付：Linux / Windows 安装包、AI-INSTALL 与一键安装脚本 |

## 交付包

- **Thor 深度 SDK 0.1.0**：[下载](https://github.com/zsibot-camera/nvidia-jetson-camera-drivers/releases/tag/thor-depth-sdk-v0.1.0)
- **ZSViewer 2.1.0**：[下载](https://github.com/zsibot-camera/ZSViewer-delivery/releases/tag/v2.1.0)
- **Thor 驱动 + SDK + ROS2 完整包**：[交付包](https://github.com/zsibot-camera/nvidia-jetson-camera-drivers/tree/main/Jetson%20AGX%20Thor%20Devkit/GMSL/双目og02d10)
- 客户侧 AI 助手：直接阅读 [README-AI.md](https://github.com/zsibot-camera/nvidia-jetson-camera-drivers/blob/main/README-AI.md)，按里面的命令校验并一键安装。

## 联系我们

- 🌐 公司官网：[zsibot.com](https://www.zsibot.com/)
- 📫 邮箱：_待补充_
- 📍 中国
