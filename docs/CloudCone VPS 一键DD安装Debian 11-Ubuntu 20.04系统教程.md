# CloudCone VPS 一键DD安装Debian 11-Ubuntu 20.04系统教程

很多用户在使用CloudCone VPS时发现，直接DD安装Linux系统后会出现无法正常重启的问题。本文将详细介绍如何通过简单命令完成系统重装，并以Debian 11为例演示完整操作流程。

## 准备工作
- 确保已购买CloudCone VPS并获取root权限
- 准备SSH连接工具（如Putty或Xshell）
- 建议先备份重要数据

## 一键DD安装步骤

1. 通过SSH连接到您的CloudCone VPS
2. 执行以下命令下载安装脚本：

bash
wget -N --no-check-certificate https://down.vpsaff.net/linux/dd/network-reinstall-os.sh && \
chmod +x network-reinstall-os.sh && ./network-reinstall-os.sh

3. 根据提示选择系统版本（本文以Debian 11为例）
4. 等待安装完成（通常需要10-30分钟）

👉 [【点击查看】2025年最新CloudCone优惠码及特价云服务器方案汇总](https://bit.ly/Cloudcone)

## 常见问题解决方案

### 引导界面卡住问题
安装完成后可能会卡在引导选择界面，按以下步骤解决：

1. 选择第一个"Grub 2"选项
2. 按"c"键进入命令行
3. 输入"exit"后回车

### 系统启动后配置
成功进入系统后，还需执行以下命令完成最终配置：

bash
ln -s /boot/grub /boot/grub2

## 注意事项
- 建议在低峰期进行操作
- 确保网络连接稳定
- 不同系统版本安装时间可能有所差异
- 如遇问题可通过VNC查看安装进度

通过本教程，您应该已经成功在CloudCone VPS上安装了纯净的Debian 11系统。如需安装其他Linux发行版，只需在脚本中选择对应版本即可。