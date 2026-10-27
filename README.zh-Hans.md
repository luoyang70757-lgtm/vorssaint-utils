<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/logo-dark.svg">
    <img src="docs/assets/readme/logo.svg" width="220" alt="Vorssaint 标志">
  </picture>
</p>

<h1 align="center">Vorssaint</h1>

<p align="center">
  <a href="README.md">English</a> · <a href="README.zh-Hans.md">简体中文</a>
</p>

<p align="center">
  一个菜单栏图标，替代十几个付费 Mac 应用。<br>
  只安装你用得到的功能。
</p>

<p align="center">
  <a href="https://vorssaint.com">官网</a> ·
  <a href="#安装">安装</a> ·
  <a href="#功能一览">功能</a> ·
  <a href="#默认保护隐私">隐私</a> ·
  <a href="CHANGELOG.md">更新日志</a> ·
  <a href="mailto:hello@vorssaint.com">联系</a> ·
  <a href="https://discord.gg/M6BwWH4BJp">Discord</a>
</p>

<p align="center">
  <a href="https://github.com/vorssaint/vorssaint-utils/releases"><img src="https://img.shields.io/github/v/release/vorssaint/vorssaint-utils?label=release&color=4c8dff" alt="最新版本"></a>
  <a href="https://github.com/vorssaint/vorssaint-utils/releases"><img src="https://img.shields.io/github/downloads/vorssaint/vorssaint-utils/total?color=4c8dff" alt="下载量"></a>
  <a href="https://github.com/vorssaint/vorssaint-utils/actions/workflows/ci.yml"><img src="https://github.com/vorssaint/vorssaint-utils/actions/workflows/ci.yml/badge.svg?branch=main&event=push" alt="CI 状态"></a>
  <a href="#系统要求"><img src="https://img.shields.io/badge/macOS-14%2B%20Apple%20Silicon%20%7C%20Intel-black" alt="macOS 14 及更新版本，Apple Silicon 或 Intel"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0--or--later-blue" alt="许可证 GPL 3.0 或更新版本"></a>
</p>

<p align="center">
  <a href="https://buymeacoffee.com/vorssaint">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="217" height="60" alt="请我喝咖啡">
  </a>
</p>

<p align="center">
  如需私下联系，请发邮件至
  <a href="mailto:hello@vorssaint.com"><strong>hello@vorssaint.com</strong></a>。
</p>

<p align="center">
  <a href="https://trendshift.io/repositories/53716?utm_source=repository-badge&amp;utm_medium=badge&amp;utm_campaign=badge-repository-53716" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/repositories/53716" alt="vorssaint/vorssaint-utils | Trendshift" width="250" height="55"></a>
  <a href="https://trendshift.io/repositories/53716?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-53716" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/trendshift/repositories/53716/weekly?language=Swift" alt="vorssaint/vorssaint-utils | Trendshift 周榜" width="250" height="55"></a>
  <a href="https://trendshift.io/repositories/53716?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-53716" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/trendshift/repositories/53716/monthly?language=Swift" alt="vorssaint/vorssaint-utils | Trendshift 月榜" width="250" height="55"></a>
</p>

<p align="center">
  <img src="docs/assets/readme/panel-mixer.png" width="196" alt="音量混音器，每个应用一个滑块，其中一个应用提升到 100% 以上">
  <img src="docs/assets/readme/panel-system.png" width="196" alt="系统标签页，显示温度、使用率曲线和内存压力">
  <img src="docs/assets/readme/panel-controls.png" width="196" alt="窗口控制，包含应用切换器和 Dock 功能">
  <img src="docs/assets/readme/panel-utilities.png" width="196" alt="实用工具，包含清理器、Homebrew、媒体工具和剪贴板">
</p>

按应用调节音量、真正的系统监控、更好用的应用切换器、窗口吸附、Dock 预览、剪贴板历史、文本片段、文件架、卸载器。Mac 用户常常要逐个购买的这些工具，如今集中在同一个菜单栏图标里，无需账号、无遥测、无订阅。

## 只安装你用得到的功能

可以逐个选择功能，也可以从预设方案开始。卸载的功能会停止加载并从界面消失；重新安装会恢复原有设置。设置流程只会请求你的选择真正需要的权限。

<p align="center">
  <img src="docs/assets/readme/features-hub.png" width="720" alt="设置中的功能中心，可整体安装和卸载功能">
</p>

面板分区可以重新排序或隐藏，支持紧凑布局，还能把设置导出到另一台 Mac。应用支持十多种语言。

## 功能一览

### 声音

- **音量混音器。** 按应用设置音量，把偏小的声音提升到 100% 以上，收藏或重新排序常用应用。无需音频驱动。
- **按应用指定输出。** 音乐走扬声器，通话走耳机。
- **输出切换器。** 用快捷键切换音频输出，耳机断开时自动降低音量。
- **麦克风工具。** 选择首选输入设备，在支持的设备上调整电平，用一个快捷键静音所有麦克风。
- **音乐应用拦截。** 在检测到播放键按下后，阻止 Music 被意外启动。需要辅助功能权限。

### 了解 Mac 的运行状态

- **系统监控。** CPU、GPU、内存、温度、电池健康和功耗，带历史曲线和高耗能应用视图。
- **风扇控制（Beta）。** 设置手动转速或温度曲线，实时查看 RPM。
- **菜单栏读数。** 把你关心的读数、占用条、电池时间或风扇转速直接放进菜单栏。
- **网络。** 查看实时流量、本次会话总量和本机 IP，或运行测速。
- **告警。** 在 CPU 持续高负载、温度过高、内存压力、磁盘空间不足或电量过低时通知你。

### 窗口与 Dock

- **应用切换器。** 在应用和窗口之间切换，支持实时预览、搜索和显示器筛选。不想授予屏幕录制时，可用更简单的图标模式。
- **窗口布局。** 用快捷键、屏幕边缘或按住修饰键拖动，把窗口吸附成各种布局、移到其他显示器，或恢复之前的位置。
- **Dock 预览。** 鼠标悬停 Dock 图标即可预览各个桌面的窗口，并可直接切换、关闭、移动或吸附。
- **Dock 点击。** 点击当前应用的 Dock 图标，最小化、隐藏或在它的窗口间循环。
- **最大化窗口。** 用绿色按钮填满屏幕，而不新建一个 Space。
- **固定 Space 顺序。** 让 Space 保持你设定的顺序，而不是按最近使用自动重排。关闭后恢复系统原有设置。
- **关闭时退出。** 当所选应用的最后一个窗口关闭时退出该应用。
- **退出与关闭保护。** 按应用设置长按、双击或额外修饰键，防止误触 ⌘Q 或 ⌘W。

<p align="center">
  <img src="docs/assets/readme/quit-protection-hold.png" width="300" alt="长按确认提示，在 Command-Q 退出快捷键下方显示进度">
</p>

<p align="center">
  <img src="docs/assets/readme/window-switcher.gif" width="540" alt="窗口切换器显示已打开窗口的实时缩略图">
</p>

### 键盘与鼠标

- **文本片段。** 把简短触发词展开成带剪贴板、日期和时间变量的文本，或从可搜索菜单插入片段。
- **平滑滚动。** 让鼠标滚轮顺滑滑动，速度和响应可调。
- **指针加速。** 关闭鼠标加速，关闭该功能时恢复你之前的设置。
- **线性滚动。** 无论滚轮转得多快，每一格都滚动相同的行数。
- **焦点跟随鼠标。** 指针停留一段时间后，把指针下的窗口提到前面。
- **滚动方向。** 独立于触控板反转鼠标的垂直和水平滚动。
- **按住按键横向滚动。** 按住指定按键时，把滚轮垂直滚动变成横向滚动。
- **侧键。** 在 Finder、浏览器和兼容应用中使用鼠标的前进/后退键。
- **鼠标按键快捷键。** 为额外按键和侧滚轮分配按键，或用按键拖拽手势触发 Spaces 和调度中心。
- **中键点击。** 把触控板三指按压变成中键点击。
- **例外应用。** 让指定应用不参与鼠标增强。
- **额外点击过滤。** 忽略老旧鼠标按键产生的快速误触，同时不影响正常点击。
- **按键去抖。** 过滤老旧键盘产生的重复字母。
- **Super 键。** 把 Caps Lock 或右侧修饰键用作快捷键组合，支持单独的轻按动作和应用例外。
- **键盘快捷键。** 在一个地方管理所有功能快捷键，包括功能激活时可选接管受支持的 macOS 快捷键。

### 剪贴板、文件与链接

- **剪贴板历史。** 搜索本地的文本、图片和文件历史，收藏常用条目，预览并用快捷键粘贴。
- **自动清空剪贴板。** 延迟一段时间、睡眠或锁屏后清空系统剪贴板，同时保留已保存的历史。
- **纯文本粘贴。** 粘贴时去掉格式，同时保留剪贴板原内容。
- **文件架。** 拖动时把文件、文本和链接暂存在光标附近，之后再放置或分享。
- **Finder 快捷键。** 用 ⌘X 和 ⌘V 移动文件，用 F2 重命名，或把复制的图片粘贴成 PNG 文件。
- **链接清理。** 手动或自动移除链接中的跟踪参数。
- **磁盘映像安装器。** 从挂载的磁盘映像安装应用并推出，可选清理下载文件。

### 日常工具

- **灵动岛。** 让音乐、通知、日历、计时器、下载和常用控制围绕摄像头开孔显示，在其他 Mac 上也可用模拟开孔。可自定义分区和快捷键，可选歌词、实时均衡器、摄像头预览和文件工具。
- **AI 智能体。** 在灵动岛里跟踪 Claude、Codex、OpenCode 和 GitHub Copilot：计划限额及重置时间（在可用时）、Token、API 价值、模型、项目和实时工作状态，长任务完成时通知你。Codex 的存量重置也可在这里使用，每个额外的 Codex 账号（`CODEX_HOME`）都可以有自己的限额卡片。Copilot 使用本地 CLI/应用会话日志；Token 总量在关机指标到达时更新，API 价值估算使用基础费率。
- **命令栏。** 用一个输入框搜索应用、窗口、文件、剪贴板历史、文本片段和应用菜单命令；还能计算、换算单位、查找 emoji 或运行已保存的脚本。
- **快捷面板。** 用 ⌃⌘V 打开常用工具的浮动面板。
- **快捷开关。** 切换外观、隐藏桌面图标、推出磁盘、清空废纸篓、锁定屏幕等。
- **径向菜单。** 在指针周围打开可自定义的应用、文件、快捷键和工具轮盘，支持配置文件和子菜单。
- **便签。** 在标签页中保存自动保存的笔记，支持 Markdown 预览和导出，可放在浮动窗口或灵动岛里。
- **清洁模式。** 清洁时锁定键盘输入，可显示黑屏或小型提示。

### 截图与创作

- **屏幕捕捉。** 在一个选择器里切换截图、录制、文字识别和取色，带像素放大镜。
- **截图。** 捕捉区域、窗口、屏幕或滚动页面；可标注、裁剪、打码、添加背景和水印、固定截图、通过分享菜单发送，或生成限时链接。
- **屏幕录制。** 分别录制系统声音和麦克风音轨；可裁剪、剪切、自动缩放、模糊隐私内容，导出视频或 GIF，或生成限时链接。
- **摄像头预览。** 通话前在浮动镜像或灵动岛里检查摄像头。
- **从屏幕取字。** 离线识别任意屏幕区域的文字，或读取二维码。
- **取色器。** 把屏幕颜色复制为 HEX、RGB、HSL 或 SwiftUI 代码。
- **媒体工具。** 全部在本地压缩和编辑视频、批量转换图片、添加水印、制作 GIF 和提取文字。

### 应用管理

- **应用更新。** 在一个列表里检查商店应用、包管理器应用和受支持的开发者更新源；可批量安装受管理的更新，或打开应用自带的更新器。
- **清理器。** 手动或按计划清理缓存、日志和应用残留。
- **通讯软件下载整理。** 用保留规则检查、整理或把通讯软件的下载文件移到废纸篓。
- **卸载器。** 移除应用前先查看相关缓存、偏好设置和辅助程序。
- **Homebrew 管理器。** 无需打开终端即可搜索、安装和移除 formula 与 cask。
- **端口管理器。** 查找监听网络端口的进程，安装 Kill Process 后可直接结束它们。

### 能源与显示

- **保持唤醒。** 按计时器、合盖时，或在指定应用、电源、外接显示器存在时让 Mac 继续工作。
- **显示器。** 分别控制各个显示器和亮度；支持的硬件使用硬件控制，亮度键支持半格/四分之一格调节，可选在显示器最低亮度以下继续压暗，并提供软件调光作为后备。
- **超级亮度。** 利用 MacBook Pro XDR 屏幕的 HDR 余量，突破普通最高亮度。
- **睡眠时断开蓝牙。** 睡眠时断开蓝牙，唤醒后仅当是 Vorssaint 断开时才恢复。

## 安装

本分支（含 Intel 适配）建议从源码构建：

```sh
git clone https://github.com/luoyang70757-lgtm/vorssaint-utils.git
cd vorssaint-utils
./build.sh --dev            # 构建独立的 Developer 版本
./build.sh --dev --install  # 安装并启动
```

上游官方版可通过 [Homebrew](https://brew.sh) 安装：

```sh
brew install --cask vorssaint
```

也可从[发布页面](https://github.com/vorssaint/vorssaint-utils/releases)下载磁盘映像，把 Vorssaint 拖入「应用程序」。

官方构建使用 Apple Developer ID 签名并公证，macOS 可直接打开，权限也能在更新后保留。

## 卸载

Homebrew 安装的版本：

```sh
brew uninstall --cask vorssaint
```

要彻底移除 Vorssaint（包括设置和权限）：

```sh
./Tools/uninstall.sh
```

## 默认保护隐私

Vorssaint 以本地为先，没有账号、分析和跟踪。只有你能看到的功能会访问网络：检查更新、测速、Homebrew 操作、可选的在线歌词查询、临时的截图/录制分享链接，以及你主动发送的反馈。完整说明见[隐私说明](docs/PRIVACY.md)。

权限也是如此。每一项都是可选的，应用会用通俗的语言解释每项权限，展示哪些功能真正使用它，甚至会在你授予的权限已不再被任何功能需要时提醒你，并提供撤销入口。

<p align="center">
  <img src="docs/assets/readme/permissions.png" width="720" alt="权限页面，显示每项权限的作用、使用它的功能，以及未使用权限的提醒">
</p>

各功能需要哪些权限、不授权时还能用什么，见[权限指南](docs/PERMISSIONS.md)。

## 系统要求

- Apple Silicon 或 Intel Mac
- macOS 14 Sonoma 或更新版本

> 说明：上游项目仅支持 Apple Silicon。本分支已适配 Intel 构建与 SMC 温度传感器，包括 CPU/GPU/电池温度、风扇转速和功耗读取。

### 自行构建

```sh
git clone https://github.com/luoyang70757-lgtm/vorssaint-utils.git
cd vorssaint-utils
./build.sh --dev            # 构建独立的 Developer 版本
./build.sh --dev --install  # 安装并启动
```

只需要 Xcode Command Line Tools。[贡献指南](CONTRIBUTING.md)介绍了目录结构和约定。官方构建只由原维护者发布：GPL 覆盖源代码，而 Vorssaint 名称、图标和外观由 [TRADEMARKS.md](TRADEMARKS.md) 单独保护，因此分支需要自己的品牌标识。

## 出问题时

启动问题、权限和预览缺失见[故障排查](docs/TROUBLESHOOTING.md)，其他帮助见[支持](SUPPORT.md)。

## 文档

- [隐私](docs/PRIVACY.md)：什么会离开你的 Mac，什么不会
- [权限](docs/PERMISSIONS.md)：用通俗语言解释每一项 macOS 权限
- [故障排查](docs/TROUBLESHOOTING.md)：常见问题的处理
- [贡献](CONTRIBUTING.md)：构建、目录结构和约定
- [支持](SUPPORT.md)：在哪里获得帮助
- [安全](SECURITY.md)：如何报告漏洞

## 社区

Vorssaint 从第一个提交到登上 GitHub Trending 首页只用了三天，之后一直位居 Swift 榜单前列；每一个版本都受到 issue 和 pull request 的影响。欢迎提交 bug、功能想法和翻译，从[贡献指南](CONTRIBUTING.md)开始。

Vorssaint 免费，并将一直免费。如果它在你的菜单栏里赢得了一席之地，点个 star 能帮助更多人发现它；[请一杯咖啡](https://buymeacoffee.com/vorssaint)则能让维护者保持清醒——无论有没有开启「保持唤醒」。

## 致谢

- 应用图标由 [@divisionseven](https://github.com/divisionseven) 设计
- Intel 适配与简体中文 README：[luoyang70757-lgtm](https://github.com/luoyang70757-lgtm)

## 许可证

[GPL 3.0 或更新版本](LICENSE)，版权所有 2026 Vorssaint。许可证覆盖源代码；Vorssaint 名称、标志和外观在 [TRADEMARKS.md](TRADEMARKS.md) 中单独说明。

<p align="center">
  <sub>由 <a href="https://x.com/vorssaint">@vorssaint</a> 制作</sub>
</p>
