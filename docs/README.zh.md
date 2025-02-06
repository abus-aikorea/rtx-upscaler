<!-- 
    title: RTX 升级器 - 基于 NVIDIA RTX 技术的 AI 视频增强
    description: 使用 NVIDIA Maxine SDK 转换低质量和老旧视频。利用 RTX 实时加速提供 AI 超分辨率和伪影消除功能。用户友好的 Gradio 界面实现无缝视频增强。
    keywords: 视频升级, NVIDIA RTX, AI 视频增强, 超分辨率, 伪影消除, 老旧视频修复, Maxine SDK, Gradio GUI, 视频处理
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: 视频增强软件
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: 商用
-->

# RTX 升级器：基于 NVIDIA RTX 技术的 AI 视频增强 📺

🌍 [English](../README.md) ∙ [한국어](README.kor.md) ∙ [日本語](README.jpn.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [Deutsch](README.de.md) ∙ [Español](README.es.md)

使用 NVIDIA RTX 技术提升低质量视频。RTX 升级器是一款基于 NVIDIA Maxine Video Effects SDK 的易用型 Gradio 图形界面程序，提供 AI 超分辨率和伪影消除功能。

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 主要特点

- **AI 画质提升**: 采用 NVIDIA 先进的超分辨率和伪影消除技术
- **实时 GPU 加速**: 利用 RTX 性能实现快速处理
- **直观界面**: 简单易用的 Gradio 图形界面
- **老旧视频修复**: 将老旧视频升级至现代画质标准
- **一键安装**: 便捷安装，支持便携式使用

## 🛸 演示视频
- [You Call It Love (from L étudiante)](https://youtu.be/HXomwoKS3V4)
- [A-ha • “Take On Me” • 1985 [Reelin' In The Years Archive]](https://youtu.be/cZPSTTsmHxI)

## 🎯 系统要求

- **操作系统**: 仅支持 Windows 10/11 (64位)
- **GPU**: NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX 或更高版本
- **NVIDIA 驱动程序**: NVIDIA 显示驱动程序版本 570 或更高版本
- **显存**: 最低 4GB (建议 8GB)
- **内存**: 最低 4GB
- **存储空间**: 20GB 可用空间
- **网络**: 安装和更新需要联网


## 🛠️ 安装指南

### 快速开始
1. 🚀 运行 `configure.bat` (首次使用)
   - 安装必需组件 (git, ffmpeg, CUDA)
   - 仅需首次运行，需要联网
   
2. 🚀 运行 `start.bat`
   - 启动带有网页界面的 RTX 升级器
   - 首次运行时会自动安装

### 更新
- 运行 `update.bat` 更新 Python 虚拟环境
- 推荐现有用户使用

### 卸载
- 运行 `uninstall.bat` 移除所有组件
- 或直接删除安装文件夹（便携式安装）

## 💻 功能介绍

### RTX 工作室界面
- 集成 YouTube 下载器
- AI 伪影消除
- 超分辨率画质提升
- 视频压缩工具
- 支持所有 ffmpeg 兼容格式
- 可自定义输出设置 (wav, flac, mp3)
- 可调节模式、缩放、CRF 和预设选项

## ⚠️ 注意事项

- **免费试用版限制**: 可处理最长 60 秒视频
- **GPU 兼容性**: NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX 或更高版本
- **NVIDIA 驱动程序**: NVIDIA 显示驱动程序版本 570 或更高版本
- **必需软件**:
  - [NVIDIA Graphics Driver](https://www.nvidia.com/en-us/drivers/)


## 🔧 故障排除

浏览器未自动启动时:
1. 使用 start.bat 重新启动
2. 手动访问显示的地址 (例如: http://127.0.0.1:7892)

Windows 安全警告处理:
- 点击"更多信息"然后选择"仍要运行"
- 必要时在文件属性中设置"解除锁定"

## 📬 联系与支持

- 电子邮件: abus.aikorea@gmail.com
- 官方网站: https://abuskorea.imweb.me
- 亚马逊购买: US, Japan, Singapore, UAE
- 产品演示: [YouTube 频道](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)

## 🙏 致谢

* NVIDIA Maxine SDK: <https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>

## ©️ 版权

<img src="images/ABUS-logo.jpg" width="100" height="100"> by [ABUS](https://abuskorea.imweb.me)