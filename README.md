# DoorNet2 OpenWrt / iStore Firmware

专为 **DoorNet2 / Rockchip RK3399** 定制的 OpenWrt 固件项目。

本项目在 OpenWrt / LEDE Rockchip 基础上进行定制，重点实现：

- TF 卡优先启动
- eMMC 自动回退
- TF / eMMC 双独立系统
- 安全在线升级
- TF 整卡容量支持
- iStore / OPKG 在线软件安装
- QuickStart 首页
- iStoreOS 风格界面
- DoorNet2 专用在线升级保护

---

# 当前状态

当前主系统：

```text
TF Card
OpenWrt R23
QuickStart + Argon
RootFS ≈ 29.2 GB
