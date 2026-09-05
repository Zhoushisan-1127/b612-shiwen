# B612·拾文：Markdown 转 Word / WPS 工具

> 替你省下繁琐排版的时间，把时间留给真正热爱的事。

B612·拾文是一款 Windows 桌面文档工具，用于编辑和整理 AI 生成的 Markdown 内容，将排版后的文字、图片、表格和公式复制到 Microsoft Word、WPS Office，或导出为 Word 文档。

A Windows desktop app for converting Markdown and LaTeX content to Word documents with editable equations.

## 下载与安装

当前版本：**v1.5.10** · 支持 **Windows 10/11 64 位（x64）**

- [下载安装包](https://github.com/Zhoushisan-1127/b612-shiwen/releases/download/v1.5.10/B612-Shiwen-Setup-v1.5.10.exe)
- [下载 SHA-256 校验文件](https://github.com/Zhoushisan-1127/b612-shiwen/releases/download/v1.5.10/B612-Shiwen-Setup-v1.5.10.exe.sha256)
- [查看版本更新说明](https://github.com/Zhoushisan-1127/b612-shiwen/releases/tag/v1.5.10)

下载后双击安装包，按提示选择安装位置，安装完成后启动 B612·拾文。

安装包暂未进行代码签名，Windows 可能显示“未知发布者”或 SmartScreen 提醒。请从本仓库下载，并核对页面下方的 SHA-256 校验值。

## 主要功能

- **编辑与预览**：打开、编辑和保存 Markdown 文档，实时查看排版效果。
- **大纲导航**：按标题层级展开、折叠大纲，快速跳转到对应内容。
- **复制到 Office**：复制全部或选中内容，保留文字、图片、表格及可编辑公式。
- **导出 Word**：生成可继续编辑的 Word 文档，图片随文档保存。
- **插入图片**：支持插入、粘贴和拖放图片，保存 Markdown 时一并保存所需图片。
- **调整视图**：切换编辑与预览布局，选择浅色、深色或跟随系统的主题。

## 使用方法

1. 将 Markdown 内容粘贴到左侧编辑区，或通过“文件 → 打开文档”打开已有的 Markdown 文件。
2. 在左侧修改内容，右侧会同步显示排版预览。
3. 打开“设置 → 复制目标”，选择 Microsoft Word 或 WPS Office。
4. 点击“复制全部”，或在右侧预览中选中内容后点击“复制选中部分”，再到对应的 Word/WPS 文档中按 **Ctrl+V** 粘贴。
5. 需要独立的 Word 文件时，选择“文件 → 导出为 Word”。导出完成后，可通过“文件 → 打开 B612 文档舱”查看文件。

在 Word 中粘贴时，选择 **“保留源格式”** 可保留原文的字体和加粗范围；“合并格式”会采用目标文档的格式。

## 保存与图片

- 使用“文件 → 保存为 MD”保存可继续编辑的 Markdown 文档。未保存的临时内容不会在下次启动时恢复。
- 保存含本地图片的 Markdown 时，会在文档旁生成同名的 `文档名.assets` 图片文件夹。移动或发送文档时，请将两者放在一起。
- 导出的 Word 文档会嵌入图片，无需另带图片文件夹。
- 网络图片默认不加载。如需显示，可开启“设置 → 自动加载网络图片”；开启后会访问图片来源网站。完整隐私说明可在“帮助 → 隐私说明”中查看。

## 兼容性说明

- 支持复制到桌面版 Microsoft Word 和 WPS Office；不同版本的粘贴效果可能有所差异。
- 带框公式粘贴后保留公式内容，外框不保留；多行推导的对齐位置可能与预览不同。
- 向 WPS 复制含公式的内容时，暂不支持跨行合并的表格；图片支持 PNG、JPEG、GIF，且需先正常加载。
- Microsoft Word 和 WPS Office 需自行安装，不随本软件提供。

## 下载校验

v1.5.10 安装包的 SHA-256：

```text
C0AE54348D48566B3873D5D2B58E3012E0715F027784AE6A1FA4C0A612576B4C
```

## 版权与许可

Copyright © 2026 Shisan Zhou. All rights reserved.

B612·拾文是专有软件，不是开源软件。本仓库仅用于发布官方安装包和用户文档，不包含软件源代码。

未经版权所有者书面许可，不得修改、反编译、重新打包、转售或以其他名义二次发布本软件。第三方组件适用各自许可证，详见安装包随附的第三方组件声明。
