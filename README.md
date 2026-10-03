# Aquarium Days

> A cozy 2D aquarium-management game about caring for fish, balancing a small ecosystem, and building a team of magical companions.
>
> 一款治愈系 2D 水族箱经营游戏：照顾鱼群、平衡小型生态，并搭配魔法伙伴构筑自己的鱼缸。

| Platform / 平台 | Current download / 当前下载 | Version / 内容版本 |
|---|---|---|
| Windows x64 | [Download ZIP / 下载试玩包](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261003-tutorial01/Aquarium-Days-Windows64-20261003-tutorial01.zip) | **2026-10-03 tutorial01 · 新教程测试版** |
| macOS Apple Silicon | [Download ZIP / 下载试玩包](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip) | **2026-10-02 · 先前稳定内容，不含本次教程改版** |

[New Windows release / 新版 Windows 说明](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261003-tutorial01) · [Mac release / Mac 启动说明](https://github.com/Er2u/Aquarium-Days/releases/tag/mac-playtest-20261002) · [All versions / 全部历史版本](https://github.com/Er2u/Aquarium-Days/releases) · [Feedback / 问题反馈](https://github.com/Er2u/Aquarium-Days/issues)

Chapter 1 · Simplified Chinese · Keyboard and mouse / 第一章 · 简体中文 · 键盘鼠标

## 中文

### 最新 Windows 测试版

这次更新重点帮助新玩家理解任务和系统：

- 从任务栏和按钮开始，逐步带着玩家完成第一章的新机制；阅读和指定操作时暂停鱼缸，需要观察结果时恢复。
- 任务栏默认展开，目标更清楚；详细计数规则和奖励集中放在任务详情。重写 19 项任务文字，补齐伙伴百科和术语解释。
- 商店购买旁直接设置快捷栏，浏览时底栏保持可见；六槽均可配置，空槽不再误报锁定。
- 金币按面值区分八档外观，水面泡泡轻微浮动，小海龟与寻金虾能收取水面金币。
- 补齐水面空气表现、真实素材放置预览，并修正提示气泡的位置与遮挡。

第一章仍包含鱼类成长、繁殖、捕食、出售、氧气与水质、魔法伙伴与支援、召唤、探险、库存、造景和三星任务。音乐、音效及可保存的音量设置保留。

### 下载与运行

**Windows：** 完整解压到一个新文件夹，再双击 `Aquarium Days.exe`。保留 exe、`Aquarium Days_Data` 和其他文件的相对位置，不在 ZIP 内运行。首次试玩选空槽新建；上一稳定版玩家可以直接继续原槽，无需重新开局。

**Mac：** 现有包已通过用户 M2 实机测试，要求 Apple Silicon 和 macOS 12.0+，不支持 Intel Mac。完整解压到可写的新文件夹，每次通过 `Launch_Playtest.command` 启动；存档、音量设置和日志位于旁边的 `PlaytestData`。无需 Unity 或 Rosetta，应用尚未签名或公证，首次启动说明见 [Mac 发布页](https://github.com/Er2u/Aquarium-Days/releases/tag/mac-playtest-20261002)。**此 Mac 包暂未包含 Windows 新教程更新，两平台目前内容不同。**

### 存档与操作

新版 Windows 已验证上一 `20261003-feedback` 稳定版四类旧档的读取、续玩、保存和再次读取，保持原存档目录与槽位。老档可能补一次繁殖介绍，可直接确认现有设置，不会因此收费。无需手动搬动存档，请勿手动替换存档文件。升级验证不代表旧程序可完整理解新版保存的进度。Mac 新版升级尚未验证。

- 左键：交互、收币、选择、放置与确认。
- 数字键 / 小键盘 1–6：选择快捷栏。
- 右键 / Esc：取消当前工具或返回；主界面 Esc 打开菜单。
- 菜单 → 设置 → 音频：调节音量，0 为静音。当前不支持手柄。

### 测试范围与反馈

本机独立 Windows Player 验证副本以 60 FPS 上限采样，最长单轮约 228 秒；持续经营与术语停留的 P99 帧时间约 16.7–16.9 毫秒。完成同一进程 48 次界面开关，预热后未见持续大幅内存累积或模拟故障。界面切换仍有偶发长帧：首次最高约 55 毫秒，热开关最高约 37 毫秒；不能保证所有设备、鱼缸规模和长时间运行都无卡顿。发布版的每帧分配计数器不可用，未把无效零值作为零分配证明。

已完成定向教程、任务/百科入口、交易和恢复检查，以及隔离 Player 的新局保存、旧档继承与发行包启动检查；这些不等于全设备或整章人工通关验收。美术、动画和平衡仍在迭代，寄居蟹尚无新的行走动画。集中进食时提示可能密集。历史测试曾出现窗口 X 退出阶段异常，尚未确认根因修复；建议先保存，再通过游戏内菜单退出。

请在[反馈页](https://github.com/Er2u/Aquarium-Days/issues)说明版本、步骤、期望与实际结果，并附截图。卡顿请补充电脑配置、鱼缸和伙伴配置；特别欢迎反馈教学卡点与整章体验。

## English

### Latest Windows playtest

The new Chapter 1 tutorial introduces the task panel and then guides real actions as systems unlock. The tank pauses for explanations and required actions, resuming for observation. This release also includes clearer task text and companion reference pages, hover explanations, direct shop-to-quick-bar assignment, eight coin appearance tiers, floating surface coins, surface collection fixes, and revised air/water presentation.

Raise, breed, feed and sell fish; balance oxygen and water quality; configure magical companions and support abilities; summon, send expeditions and progress through three stars. Music, gameplay sounds and persistent volume settings remain included.

### Play and continue your save

On Windows, fully extract the ZIP into a new folder and run `Aquarium Days.exe` with all accompanying files kept together. First-time players can start in an empty slot. Existing players can continue their original slot: four save scenarios from the previous `20261003-feedback` Windows stable build passed load, continued play, save and reload checks. Existing saves may show a one-time breeding introduction; confirming the current configuration has no fee. No manual save relocation is needed. Forward upgrade checks do not guarantee that older builds understand all newly saved progress.

The existing Mac download was tested on an M2 Mac and requires Apple Silicon/macOS 12+. Use `Launch_Playtest.command` every time; saves/settings/logs stay in the adjacent `PlaytestData` folder. See its release for unsigned-app launch guidance. **The Mac package still contains the earlier stable content, without this new Windows tutorial update.** A new Mac upgrade has not been verified.

Keyboard/mouse only: left-click to interact, 1–6 to select a quick-bar slot, right-click/Esc to cancel or go back. Audio settings are available from the menu.

### Validation and limitations

Instrumented standalone Windows Player copies were sampled at a 60 FPS cap, with the longest run lasting about 228 seconds. Sustained gameplay and term hover had approximately 16.7–16.9 ms P99 frame times. A 48-cycle UI open/close run showed no simulation fault or sustained large memory accumulation after warm-up. UI transitions still produced occasional long frames: about 55 ms on first creation and 37 ms when warm. This is bounded testing, not an all-device or long-session guarantee. Per-frame allocation counters were unavailable in the release Player; their zero values were excluded.

Targeted tutorial/UI/transaction/recovery checks and isolated Player startup, new-save and previous-save upgrade checks have been completed. These do not replace a full human Chapter 1 playthrough or testing on every device. Art, animation and balance remain in progress; clustered feeding can produce dense notices. A historical native exception on closing the window has not been confirmed fixed; save and exit through the in-game menu.

Report your version, steps, expected/actual behaviour and screenshots via [Issues](https://github.com/Er2u/Aquarium-Days/issues). Include hardware and tank/companion setup for stutters.

## File integrity / 文件校验

**Windows tutorial01:** 77,990,881 bytes（约 78 MB） · [SHA-256 file / 校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261003-tutorial01/Aquarium-Days-Windows64-20261003-tutorial01.zip.sha256)

```text
35f36cb2ba2f59c451188bac29337df638c2e06e338ca92c493d4d6c042fa216
```

**Mac 2026-10-02:** 67,696,940 bytes · [SHA-256 file / 校验文件](https://github.com/Er2u/Aquarium-Days/releases/download/mac-playtest-20261002/Aquarium-Days-macOS-ARM64-20261002-experimental.zip.sha256)

```text
c333d545df07164e5dfb48f2e65aab42e774a0cafc6e441880f800bd79f9d9e9
```

Each new version has its own release; older downloads remain available in [release history](https://github.com/Er2u/Aquarium-Days/releases). / 后续每版使用独立 Release；旧版说明与安装包继续保留。

## License / 许可证

Repository-authored content is available under the [MIT License](LICENSE) unless otherwise noted. Packaged Unity runtime and third-party components remain subject to their respective licenses.

除另有说明外，仓库作者创作的内容按 [MIT License](LICENSE) 提供。Unity Runtime 与第三方组件仍受其各自许可证约束。
