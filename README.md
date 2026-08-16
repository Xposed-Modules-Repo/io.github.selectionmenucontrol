# 文本选择菜单控制

面向 ColorOS 16 的 Modern LibXposed 模块，用于管理文字选择菜单中的“处理文本”扩展项。选择需要隐藏的项目后，它会从系统和应用的文字选择菜单中消失，让菜单保持简洁。

[下载最新版](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases/latest) · [源码与问题反馈](https://github.com/TheKingBucket001/txtoi)

## 功能

- 自动列出已安装的文字处理扩展项。
- 按需隐藏指定项目，规则立即作用于全局文字选择菜单。
- 支持一键恢复全部显示，随时还原菜单。
- 规则会持续保留，重启、更新模块或结束应用后台后仍然生效。
- 已隐藏的项目仍会显示在配置列表中，可直接重新启用。
- 内置运行环境检测，确认模块与 Root 状态就绪后再配置规则。
- 支持启动时自动检查更新，也可以在关于页面关闭该选项。

模块不会读取选中文字，也不会修改系统 APK 或其他应用。

## 安装

1. 从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases) 下载 APK 并安装。
2. 在 LSPosed 中启用模块，作用域选择 `system`。
3. 重启设备后，打开“文本选择菜单控制”。

## 使用

1. 在“文字处理扩展项”列表中勾选需要隐藏的项目。
2. 长按任意可编辑文本，已勾选的项目会从菜单中隐藏。
3. 需要恢复时，点击“恢复全部显示”。

## 更新

新版本会发布在本仓库的 [Releases](https://github.com/Xposed-Modules-Repo/io.github.selectionmenucontrol/releases) 页面，也会同步至 LSPosed 模块仓库。