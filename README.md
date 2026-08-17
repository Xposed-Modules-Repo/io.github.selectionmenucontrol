<div align="center">

# 文本选择菜单控制

**为 ColorOS 16 精简文字选择菜单。**

[![Release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/io.github.selectionmenucontrol?display_name=tag&label=release&color=brightgreen)](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases/latest)
[![CI](https://github.com/TheKingBucket001/txtoi/actions/workflows/android.yml/badge.svg?branch=main)](https://github.com/TheKingBucket001/txtoi/actions/workflows/android.yml)
[![License](https://img.shields.io/badge/license-GPL--3.0--only-blue.svg)](https://github.com/TheKingBucket001/txtoi/blob/main/LICENSE)
[![ColorOS](https://img.shields.io/badge/ColorOS-16-1677FF.svg)](https://github.com/TheKingBucket001/txtoi)

[下载模块](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases/latest) · [查看源码](https://github.com/TheKingBucket001/txtoi) · [提交反馈](https://github.com/TheKingBucket001/txtoi/issues)

</div>

---

## 项目简介

长按文字时，菜单里常会出现一串用不到的“处理文本”项目。文本菜单控制将这些项目集中列出，勾选后即可从文字选择菜单中隐藏；想恢复时，一键还原即可。

模块只处理文字选择菜单中的扩展项，不读取选中文字，也不修改系统 APK 或其他应用。

## 模块功能

- 扫描并列出已安装的文字处理扩展项。
- 按项目隐藏，改动会作用于系统和应用内的文字选择菜单。
- 一键恢复全部显示。
- 隐藏规则会保留，重启、更新模块或结束应用后台后仍然生效。
- 已隐藏项目不会从配置列表消失，随时可以重新启用。
- 启动时检查模块和 Root 状态，避免在环境未就绪时写入规则。
- 可在关于页面关闭自动检查更新。

## 下载模块

- [Latest Release](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases/latest)
- [全部版本](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases)

## 使用说明

1. 下载并安装 APK。
2. 在 LSPosed 中启用模块，作用域选择 `system`。
3. 重启设备，打开“文本选择菜单控制”。
4. 在“文字处理扩展项”中勾选不想看到的项目。
5. 长按任意可编辑文字，确认对应项目已经隐藏。

需要还原时，打开模块并点击“恢复全部显示”。

## 项目链接

| 链接 | 地址 |
| --- | --- |
| 主页 | [TheKingBucket001/txtoi](https://github.com/TheKingBucket001/txtoi) |
| 源代码 | [TheKingBucket001/txtoi](https://github.com/TheKingBucket001/txtoi) |
| 问题反馈 | [Issues](https://github.com/TheKingBucket001/txtoi/issues) |
| 模块发行 | [Xposed Modules Repository](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases) |