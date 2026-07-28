# 🏝️ 我岛 · WordIsle

> 一款专注于写作记录的桌面应用。数据完全本地存储，离线可用。

![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey)
![License](https://img.shields.io/badge/license-Custom%20(see%20LICENSE)-blue)

## 📥 下载安装

从 [Releases](https://github.com/vodkaangel07/wordisle/releases/latest) 页面下载对应平台的安装包：

| 平台 | 文件 | 说明 |
|------|------|------|
| macOS (Apple Silicon) | `WordIsle-1.1.0-arm64.dmg` | M1 / M2 / M3 / M4 芯片 Mac |
| Windows (x64) | `WordIsle-1.1.0-win32-x64.zip` | Win10 / Win11 64 位 |

### macOS 安装步骤

1. 下载 `.dmg` 文件，下载完成后**先不要打开，若已经打开请先关闭**
2. 打开「终端」应用，输入：`sudo xattr -cr `（注意末尾空格），然后把 DMG 文件拖进终端，回车后终端会显示 `Password: `，输入密码后回车即可
3. **打开 DMG 文件**，在弹出的窗口中**双击 WordIsle 图标** → 弹窗点「安装」
4. 应用会自动复制到 `/Applications/` 并启动
5. ***在进行上述操作之前若直接打开并运行下载的`.dmg`文件，会弹窗报错「文件已损坏」，请关闭该dmg窗口，在「访达」中左侧栏内「位置」处找到「我岛·WordIsle」，右键选择「推出」，然后执行上述2-4步操作***

> ⚠️ 第 2 步必需：浏览器下载的 DMG 会被 macOS 标记 quarantine 隔离属性，不清除会显示「文件已损坏」。本应用未经过 Apple 开发者签名，这是 macOS 对未签名应用的硬性限制，不影响安全性。

### Windows 安装步骤

1. 下载 `.zip` 文件并解压
2. 进入解压后的文件夹，双击 `WordIsle.exe` 启动
3. 首次启动可能被 SmartScreen 拦截，点击「更多信息」→「仍要运行」

## ✨ 主要功能

- **文档管理**：文档/文件夹多层嵌套 + 拖拽排序 + 全文搜索
- **5 类预置标签** + 自定义标签 + 多选 AND 筛选（类 Steam 游戏库）
- **标签管理**：体裁/题材分类可右键重命名 / 删除预置标签
- **实时字数统计**（含标点，英文按单词）+ 字数日历热力图（5 档颜色）
- **6 维度看板**（日 / 周 / 月 / 年 / 总计 / 自定义）+ 趋势图表
- **码字计划** + 当日备忘与心情
- **段落对齐**（左/中/右）+ **粗体 / 斜体** + **撤回 / 重做**
- **一键排版**（保留空行）+ 首行缩进
- **14–22px 字号** / 3 款中文字体 / 字符间距调节
- **侧栏可拖拽调整宽度** + 响应式工具栏
- **专注模式** + **夜间模式**
- **5 秒自动保存** + Ctrl/Cmd+S 手动保存 + 顶部保存按钮
- **单实例锁**防止多开冲突
- **数据完全本地存储**，零上传，零遥测

> 📌 「🏝️ 岛屿」与「🏆 成就」为持续开发中的游戏化模块，目前为占位状态。

## 🔒 数据与隐私

- **完全本地存储**：所有数据保存在你的电脑上，不上传任何用户数据
- **数据位置**：默认保存在「文档」文件夹下的 `wordisle/data.myisland`，可在应用内「偏好设置」中自定义为任意目录
- **导入/导出**：应用内可导出 `.myisland` 备份文件，换机迁移用导入功能恢复
- **联网检查更新**：启动时会访问 GitHub 查询是否有新版本（仅读取版本号，不上传任何数据），离线时自动跳过
- **无遥测**：不收集任何使用数据

## 📜 致谢

本应用使用了以下开源项目与资源：

- [Electron](https://www.electronjs.org/) — 跨平台桌面应用框架（MIT）
- [霞鹜文楷](https://github.com/lxgw/LxgwWenKai) — 开源中文字体（OFL 1.1）
- [Noto Serif SC](https://fonts.google.com/noto/specimen/Noto+Serif+SC) — 思源宋体（OFL 1.1）

## 📄 许可证

详见 [LICENSE](./LICENSE)。

**简而言之**：本应用为闭源软件，安装包可免费下载使用。品牌名「我岛 / WordIsle」、应用图标等归作者所有，未经授权禁止用于衍生项目。

## 🐛 反馈

遇到 bug 或有建议，请到 [Issues](https://github.com/vodkaangel07/wordisle/issues) 提交反馈。