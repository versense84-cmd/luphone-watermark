# 鹿phone watermark

给照片添加透明白色苹果标志与机型文字的 iPhone 快捷指令，支持多张照片批量处理并保存副本。

## 下载

- [iPhone 18 Pro 快捷指令](https://github.com/versense84-cmd/luphone-watermark/releases/latest/download/iPhone18Pro-Batch.shortcut)
- [iPhone 18 Pro Max 快捷指令](https://github.com/versense84-cmd/luphone-watermark/releases/latest/download/iPhone18ProMax-Batch.shortcut)
- [AI 助手 Skill 包](https://github.com/versense84-cmd/luphone-watermark/releases/latest/download/xiaoou-iphone-watermark.zip)

普通 iPhone 用户下载对应快捷指令即可。Skill 包供支持 Skill 的 AI 助手使用。

## iPhone 使用方法

1. 下载对应 `.shortcut` 文件，在 iPhone 的文件 App 中打开，点“添加快捷指令”。
2. 在照片 App 中选择一张或多张原照片，点分享，选择 `iPhone18Pro-Batch` 或 `iPhone18ProMax-Batch`。
3. 首次出现照片权限提示时允许保存。带水印的 JPEG 副本保存到“最近项目”，原照片保留。

也可以直接运行快捷指令，再从照片选择器多选。分享菜单没有显示时，在“编辑操作”中寻找并加入，或检查快捷指令详细信息中的“在共享表单中显示”。

水印在照片下方居中，文字为 `Shot on iPhone 18 Pro` 或 `Shot on iPhone 18 Pro Max`。文字是自定义装饰，不读取或验证实际拍摄机型。请选择原照片，重复处理会叠加水印。

## Skill 使用方法

下载并解压 Skill 包，将 `xiaoou-iphone-watermark` 文件夹安装到 AI 助手的 Skill 目录（例如 Codex 的 `~/.codex/skills/`）。然后说：“使用 xiaoou-iphone-watermark，给我 18 Pro Max 批量水印快捷指令和安装方法。”

Skill 内含两个快捷指令文件。iPhone 快捷指令 App 不能直接导入 Skill ZIP，需要打开内附的 `.shortcut` 文件。

## 版本说明

内附快捷指令已在 macOS 签名。尚未覆盖所有 iOS 版本和设备；遇到问题可在本仓库 Issues 中提供系统版本、操作步骤和报错原文。

本项目为个人制作的摄影工具，与 Apple 无官方关联。
