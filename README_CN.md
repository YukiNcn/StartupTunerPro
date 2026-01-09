# StartupTunerPro
开机自动优化手机的 Magisk 模块

语言/Language:[中文](README_CN.md)/[English](README.md)

## 📖 模块描述
StartupTunerPro 是一款功能全面的 Magisk 模块，可在开机后首次解锁屏幕时自动优化您的 Android 设备。它在后台静默运行，增强系统安全性、清理系统残余文件并自动启动必要服务。

## 📝 开发历史
本 Magisk 模块改编自酷安用户 @Yz堕仙 的帖子：  
https://www.coolapk.com/feed/65005997?s=YjdmY2UzYzAyM2ExNDg4ZzY5NjBmZDRjega1591

## ✨ 功能特性

### 原始功能
- SDK 接口修复：开机后首次解锁时自动修复 SDK 接口异常
- 安全加固：自动关闭 USB 调试和开发者选项
- 系统清理：删除 TWRP 文件夹以清除 Recovery 残留文件
- SELinux 强化：启用 SELinux 严格模式（enforcing）提升安全性
- 服务管理：自动启动黑阈 (BlackDomain) (app) 实现后台应用管控
- 序列号管理：仅支持手动执行 action.sh 生成新的序列号，重启后不会生成新序列号

### 新增功能
- 动态序列号生成：开机后首次解锁时自动生成新的随机序列号（依然支持手动生成新的序列号）
- 音频服务启动：自动启动 HxAudio (app) 音频增强服务

## ⚙️ 可选项配置
刷入模块时可通过音量键选择是否启用以下功能：
- 随机序列号生成
- 黑阈 (BlackDomain) 自启动
- HxAudio 自启动

## 🛠️ 系统要求
- Magisk 24.0+ 或 KernelSU 或 APatch 已安装（理论仅支持Magisk24.0+）
- Android 8.0+（API 级别 26+）
- 已获取 Root 权限

## ⚠️ 重要提示
- **语言支持**：模块刷入页面目前仅支持中文，后续版本将添加多语言支持
- **首次解锁触发**：所有优化功能仅在开机后首次屏幕解锁后触发
- **兼容性说明**：可能不适用于所有自定义 ROM 或重度修改的系统

## 🤝 参与贡献
欢迎提交问题反馈和建议！报告问题时请提供设备型号、Android 版本和框架版本信息。

## 🙏 致谢
- 原创概念与实现：@Yz堕仙（酷安）
- 社区反馈与测试用户
- Magisk 与 KernelSU 开发团队
