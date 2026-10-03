# Aquarium Days

> A cozy 2D aquarium-management game about caring for fish, balancing a small ecosystem, and building a team of magical companions.
>
> 一款治愈系 2D 水族箱经营游戏：照顾鱼群、平衡小型生态，并搭配魔法伙伴构筑自己的鱼缸。

[**Download the latest Windows playtest / 下载最新 Windows 试玩版（反馈修复版，77.6 MB）**](https://github.com/Er2u/Aquarium-Days/releases/download/v0.1.0-demo/Aquarium-Days-Windows64-20261003-feedback.zip)

[**Download the Mac playtest / 下载 Mac 试玩版（Apple Silicon，64.6 MiB）**](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip)

Mac playtest tested on M2 and now open to players. Requires Apple Silicon and macOS 12+.

**Mac 版已通过 M2 实机测试，现已开放试玩。适用于 M 系列芯片及 macOS 12.0 以上；不适用于 Intel Mac。**

Current playtests: **Windows 2026-10-03 / Mac 2026-10-02 · Matching stable content · Chapter 1 · Simplified Chinese**

当前试玩：**Windows 2026-10-03 / Mac 2026-10-02 · 稳定内容已对齐 · 第一章 · 简体中文**

[Windows release / Windows 发布页与历史版本](https://github.com/Er2u/Aquarium-Days/releases/tag/v0.1.0-demo) · [SHA-256 checksum / 校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/v0.1.0-demo/Aquarium-Days-Windows64-20261003-feedback.zip.sha256)

[Mac release and launch instructions / Mac 发布页与启动说明](https://github.com/Er2u/Aquarium-Days/releases/tag/mac-playtest-20261002) · [Mac SHA-256 / Mac 校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip.sha256)

---

## English

### About the game

Aquarium Days is a modern take on classic aquarium-management games. Feed and raise fish, collect coin bubbles, balance oxygen and water quality, and choose plants and aquatic creatures that help maintain the tank. Magical companions and support abilities add different ways to shape your aquarium.

### Feedback fixes and platform alignment

The October 3 Windows package now includes the same eight player-feedback fixes as the October 2 Mac package: summon layout, oxygen advice, capacity navigation, fish details, automatic-collection notices, fish state colours, selection outlines and the initial breeding target. Music and previous UI/performance improvements are retained. The new tutorial, eight-tier coin visuals, quick-bar restoration and air/water presentation are still in development and are not part of either stable download.

### Audio update

Background music, core gameplay/UI sounds, expedition-return notifications and persistent volume settings are now included. Use Menu → Settings → Audio. The continuous ambient loop is disabled; its slider remains available. Two independent Windows processes passed audio-rendering and settings-recovery checks. Previous UI/performance validation below is retained evidence, not a new full playthrough.

### Current playtest content

- Chapter 1 progression from a new game through three stars, with tutorials, main tasks and optional tasks.
- Fish growth, breeding, predation and selling, alongside oxygen and water-quality management.
- Manual coin collection and collection abilities provided by aquatic creatures and plants.
- Magical companions, support loadouts, summoning and exchanges.
- Expeditions that bring back fish for your aquarium.
- Shop, inventory, quick bar, aquarium editing and three save slots.

### Download and play

#### Windows x64

1. Download [Aquarium-Days-Windows64-20261003-feedback.zip](https://github.com/Er2u/Aquarium-Days/releases/download/v0.1.0-demo/Aquarium-Days-Windows64-20261003-feedback.zip).
2. Extract the entire ZIP into a **new folder**. Do not run the game inside the ZIP or overwrite an older installation.
3. Open the extracted folder and launch `Aquarium Days.exe`. Keep the executable, `Aquarium Days_Data`, and all other extracted files together.
4. For your first playthrough, select an empty save slot and start a new game.

No installation or special launch arguments are required.

#### macOS · Apple Silicon

1. Download the [Mac playtest ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip) and extract everything into a new writable folder.
2. Run `Launch_Playtest.command`. No Unity or Rosetta installation is needed.
3. Use this launcher every time. Saves, audio settings and logs stay in the adjacent `PlaytestData` folder. For your first playthrough, start in an empty save slot.

Tested on an M2 Mac, with no issues reported (October 3, 2026). Requires macOS 12 or later and an M-series Mac; this package does not support Intel Macs. The app is not Developer ID signed or notarized; see the [Mac release page](https://github.com/Er2u/Aquarium-Days/releases/tag/mac-playtest-20261002) for first-launch guidance and the updated test status.

### Saves and compatibility

For a first playthrough, start in an empty slot. New-save restart recovery and a current schema 18 / content 5 test save were verified. Migration from older public builds was not tested; cross-version progress is not guaranteed. Older save files are preserved; do not manually replace or move them into another save folder.

### Controls

Keyboard and mouse only; controller input is disabled in this version.

- **Left mouse button:** interact, collect coin bubbles, select, place, and confirm.
- **1–6 / Numpad 1–6:** select a quick-bar slot.
- **Right mouse button or Esc:** cancel the current tool; Esc also goes back through panels or opens the menu when the tank is unobstructed.
- Use the on-screen buttons and menus to access management features; follow the task prompts to unlock additional systems.

### Known limitations and feedback

This playtest includes the revised task, shop, collection, companion, summon, expedition and menu UI. Fish purchases go directly into the tank, while scenery purchases enter placement. Collector-shrimp movement has been fixed; the hermit crab can walk along the sand without new walk animation. Art, animation and balance remain in development. Prior validation: the performance playtest Windows x64 release build and isolated startup/extraction checks passed. A separate QA Player from the same production source passed automated Wiki/directional-navigation, roughly four minutes of gameplay, and save/restart recovery checks. These are background checks, not a new full-chapter human playthrough or physical keyboard/mouse acceptance.

This update reduces repeated gameplay calculations, UI rebuilding and camera searches. Controller mappings have been removed to prevent unwanted navigation; keyboard and mouse only. Performance improvements do not guarantee that every intermittent stutter is eliminated. Routine notices can still refresh densely during clustered feeding. A previous window-close exit produced a native shutdown exception; this is not confirmed fixed. Save manually, then use the in-game menu to quit.

Please include the version date, a screenshot, what you wanted to do, and what actually happened in [feedback or bug reports](https://github.com/Er2u/Aquarium-Days/issues). For stutters, include your tank and companion setup. Full-chapter feedback on tutorial clarity, ease of use, and when the game becomes fun or repetitive is especially helpful.

The Windows ZIP is attached to the existing `v0.1.0-demo` release page; the Mac ZIP has its own release linked above. The retained Windows tag identifies the release page, not the build's source revision. Older ZIPs remain available; choose the current download for your platform above.

---

## 中文

### 游戏介绍

《Aquarium Days》是一款现代水族箱经营游戏。喂养鱼群、收集金币泡泡、维持氧气与水质，并选择植物和水中生物帮助鱼缸运转。魔法本体与支援能力提供不同的搭配方式，让玩家经营自己的小型生态。

### 反馈修复与平台对齐

10 月 3 日的 Windows 包现已补齐 Mac 包已有的八项反馈小修：召唤布局、缺氧建议、扩容入口、鱼详情、自动收币提示、状态色、选中轮廓与首次一星繁殖目标。两平台稳定内容已对齐，音乐和此前 UI／性能修复保留。正在开发的新教程、八档金币、快捷栏与水面空气补齐尚未包含在这两个稳定包中。

### 音频更新

现已加入背景音乐、主要玩法/UI 音效、探险归来提示，以及重启保留的音量设置。通过菜单 → 设置 → 音频调节。持续环境循环已关闭，环境滑块保留。两个独立 Windows 进程的音频渲染和音量恢复已验证；下文 UI/性能验证是沿用此前证据，不代表重新完成整章试玩。

### 当前试玩内容

- 第一章从正常新局推进到三星，包含教学、主线和可选任务。
- 鱼类成长、繁殖、捕食与出售，以及氧气和水质管理。
- 手动收集金币，以及由生物和植物提供的收集能力。
- 魔法伙伴、本体与支援配置、召唤和兑换。
- 派遣伙伴探险，获得可投入鱼缸的普通鱼。
- 商店、库存、快捷栏、鱼缸编辑与三个存档槽。

### 下载与运行

#### Windows 64 位

1. 下载 [Aquarium-Days-Windows64-20261003-feedback.zip](https://github.com/Er2u/Aquarium-Days/releases/download/v0.1.0-demo/Aquarium-Days-Windows64-20261003-feedback.zip)。
2. 将 ZIP 完整解压到一个**新文件夹**，不要在压缩包内运行，也不要覆盖旧版游戏文件夹。
3. 进入解压后的文件夹，双击 `Aquarium Days.exe`。请保持 exe、`Aquarium Days_Data` 和其他运行文件的相对位置。
4. 首次试玩请选择空存档槽，新建游戏。

无需安装或添加启动参数。

#### macOS · Apple Silicon

1. 下载 [Mac 试玩 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip)，完整解压到一个可写的新文件夹。
2. 双击 `Launch_Playtest.command`，无需安装 Unity 或 Rosetta。
3. 每次都用此脚本启动，存档、音量设置和日志保存在包旁的 `PlaytestData` 文件夹。首次试玩请选择空存档槽。

2026-10-03 已在 M2 Mac 上完成实机测试，反馈正常。需要 M 系列芯片和 macOS 12.0 或更新版本，此包不适用于 Intel Mac。应用尚未做 Developer ID 签名或公证；首次启动提示与最新测试状态请看 [Mac 发布页](https://github.com/Er2u/Aquarium-Days/releases/tag/mac-playtest-20261002)。

### 存档兼容

首次试玩建议选择空槽新建。此前已验证新局保存后重启恢复，以及当前 schema 18 / content 5 测试存档读取；未验证旧公开版本存档升级，不承诺跨版本继承。旧存档文件保留，请勿手动替换或搬入存档目录。

### 操作方式

当前只支持键盘鼠标，已关闭手柄输入。

- **鼠标左键：** 交互、收集金币泡泡、选择、放置和确认。
- **数字键 1–6 / 小键盘 1–6：** 选择快捷栏槽位。
- **鼠标右键或 Esc：** 取消当前工具；Esc 也可逐层返回界面，在鱼缸主界面打开菜单。
- 通过画面中的按钮和菜单进入管理功能，按任务提示逐步解锁其他系统。

### 已知问题与反馈

本次包含新版任务、商店、收藏、伙伴、召唤、探险及菜单 UI；买鱼默认直接入缸，造景进入摆放。寻金虾寻路已修复，寄居蟹可以贴沙地走动，暂未新增行走动画。美术、动画和平衡仍在迭代。此前验证：性能版 Windows64 构建通过（0 错误、18 条警告），发行包隔离启动和解压启动通过；同一生产源码的独立 QA Player 完成 Wiki/合成方向导航、约四分钟正常经营、保存后独立重启读取检查。存档身份、金币、鱼和主要任务状态恢复一致。以上为后台自动检查，不等同于整章人工试玩或物理键鼠验收。

本次减少了经营逻辑的重复计算、界面重建与镜头查找，并移除了干扰 UI 导航的手柄映射，当前仅支持键盘鼠标。性能改善不代表所有偶发卡顿均已消失；集中进食时常规提示仍可能密集刷新。此前测试有一次点击系统窗口 X 后出现原生退出异常，本次未确认修复；建议先手动保存，再从游戏内菜单退出。

欢迎[提交问题或建议](https://github.com/Er2u/Aquarium-Days/issues)。请附上版本日期、截图、当时想做的事和实际遇到的问题；卡顿反馈请补充鱼缸与伙伴配置。也欢迎完整试玩第一章，反馈是否清楚下一步、操作是否顺手，以及哪里有趣或开始无聊。

Windows 新版沿用 `v0.1.0-demo` 发布页，该历史标签不代表本次源码版本；Mac 使用上方独立发布页。旧 ZIP 保留，请按平台选择主页顶部的当前试玩包。

---

## File integrity / 文件校验

### Windows

File / 文件：`Aquarium-Days-Windows64-20261003-feedback.zip`

Size / 大小：77,624,984 bytes（约 77.6 MB）

```text
SHA-256: e318bb33ec905857bdc2b5079776623e1901d03b882ce5f14dc6f02e8c389daf
```

[Download checksum file / 下载校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/v0.1.0-demo/Aquarium-Days-Windows64-20261003-feedback.zip.sha256)

### macOS · Apple Silicon

File / 文件：`Aquarium-Days-macOS-ARM64-20261002-experimental.zip`

Size / 大小：67,696,940 bytes（约 64.6 MiB）

```text
SHA-256: c333d545df07164e5dfb48f2e65aab42e774a0cafc6e441880f800bd79f9d9e9
```

[Download Mac checksum / 下载 Mac 校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip.sha256)

## License / 许可证

Repository-authored content is available under the [MIT License](LICENSE) unless otherwise noted. Packaged Unity runtime and third-party components remain subject to their respective licenses.

除另有说明外，仓库作者创作的内容按 [MIT License](LICENSE) 提供。打包内的 Unity Runtime 与第三方组件仍受其各自许可证约束。



