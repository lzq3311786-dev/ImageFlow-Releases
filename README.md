# ImageFlow Releases

ImageFlow 的官方 Windows 二进制发布仓库。源码位于私有仓库，本仓库只提供安装包、自动更新元数据和可选运行时组件。

## 支持平台

- Windows 10/11 x64
- Intel/AMD CPU
- NVIDIA、AMD、Intel 显卡，以及无独显电脑

基础安装包包含 CPU 运行时，可在所有支持的电脑上运行。兼容 NVIDIA GPU 的电脑可以另行安装 CUDA 12.6 加速组件；加速不可用时 ImageFlow 会回退到 CPU。

## 下载

请在 [Releases](../../releases) 页面下载最新版 `ImageFlow-Setup-<version>.exe`。应用内自动更新同样使用本仓库，无需 GitHub 账号或 Token。

首版安装包未进行代码签名，Windows SmartScreen 可能显示“未知发布者”。

本仓库不包含源码、配置包、API Key、云存储密钥或个人数据。
