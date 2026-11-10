# AdGuardHome for Root · Liancan Edition

[![Android](https://img.shields.io/badge/Android-Root%20Only-3DDC84?logo=android&logoColor=white)](#)
[![Architecture](https://img.shields.io/badge/Architecture-ARM64-607D8B)](#)
[![UI](https://img.shields.io/badge/UI-Celadon%20%2F%20Ink-78A99A)](#)
[![License](https://img.shields.io/badge/License-Upstream%20terms-lightgrey)](https://github.com/twoone-3/AdGuardHomeForRoot)

基于 [twoone-3/AdGuardHomeForRoot](https://github.com/twoone-3/AdGuardHomeForRoot) 的 Android Root DNS 广告拦截模块二次开发版。

**Liancan Edition** 以青瓷雾色为浅色主题，以青墨色为夜间主题，在保留原有 AdGuardHome 服务管理、DNS 与 iptables 机制的基础上，优化 Web 管理界面和使用说明。

> 本仓库用于 Liancan 二次开发版本的项目说明与更新记录。请在发布页获取正式安装包；在正式 Release 上传前，请勿将本仓库文档页视为可安装模块。

## 主要特性

- **青瓷浅色主题**：低饱和青釉、雾青与瓷灰背景，避免纯白刺眼。
- **青墨夜间主题**：独立深色配色，不使用简单的颜色反转。
- **Web 管理界面**：保留服务状态、启停、日志、维护与密码相关入口。
- **规则源快捷参考**：提供常用过滤规则源地址，便于复制后在 AdGuardHome 原生面板中添加。
- **使用指南**：集中说明服务管理、规则配置与常见操作。
- **Root-only**：面向具备 Root 权限的 Android 设备。

## 规则管理说明

当前版本的规则快捷库用于展示和复制规则订阅地址。添加、启用、停用和更新过滤器仍通过 AdGuardHome 原生管理面板完成。不会通过覆盖整个 YAML 配置的方式重置用户已有过滤器或白名单。

## 安装前须知

1. 设备需要可用的 Root 环境。
2. 安装或升级前请备份现有模块及 AdGuardHome 配置。
3. 不建议同时运行多个会争用 DNS 端口或修改相同 iptables 规则的 DNS/代理模块。
4. 首次安装后请检查模块日志、DNS 解析和实际广告拦截效果。
5. 当前版本尚未公布真机兼容性矩阵；不同 Root 管理器、Android 版本及网络环境可能存在差异。

## 项目来源

- 上游项目：[twoone-3/AdGuardHomeForRoot](https://github.com/twoone-3/AdGuardHomeForRoot)
- 二次开发仓库：[yunyu614/AdGuardHomeForRoot](https://github.com/yunyu614/AdGuardHomeForRoot)
- 二次开发署名：**Liancan**

请遵循上游项目及所包含组件各自的许可证与版权声明。此版本不代表上游作者发布或背书。

## 更新记录

版本详情见 [CHANGELOG.md](CHANGELOG.md)。安装包发布状态以 GitHub Releases 页面为准。

## 反馈

欢迎通过 GitHub Issues 提交问题。请附上 Android 版本、Root 管理器版本、模块日志及可复现步骤；提交日志前请先移除设备标识、账号、IP 等隐私信息。
