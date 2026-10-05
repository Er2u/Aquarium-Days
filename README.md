# Aquarium Days

> A cozy 2D aquarium-management game about caring for fish, balancing a small ecosystem, and building a team of magical companions.
>
> 一款治愈系 2D 水族箱经营游戏：照顾鱼群、平衡小型生态，并搭配魔法伙伴构筑自己的鱼缸。

| 平台 / Platform | 最新下载 / Download | 版本 / Version |
|---|---|---|
| Windows x64 | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261005-tutorial03/Aquarium-Days-Windows64-20261005-tutorial03.zip) | **2026-10-05 tutorial03 · 测试版** |
| macOS Apple Silicon | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261005-tutorial03/Aquarium-Days-macOS-ARM64-20261005-tutorial03.zip) | **同内容 tutorial03 · 新包待实机测试** |

[本版更新与启动说明 / Release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261005-tutorial03) · [历史版本 / All releases](https://github.com/Er2u/Aquarium-Days/releases) · [问题反馈 / Issues](https://github.com/Er2u/Aquarium-Days/issues)

第一章 · 简体中文 · 键盘鼠标 / Chapter 1 · Simplified Chinese · Keyboard and mouse

## 本次更新

- 教程讲界面入口，投喂、放置、收币与等待期间自由经营。提示泡泡右上角“×”可关闭，任务详情可继续带路；百科首次介绍后可关闭，不反复弹出。
- 任务栏收起仅一行，标题可拖动、点任务名开详情；展开正文半透明、点击穿透、可滚动。任务指路随当前状态更新。
- “自家鱼苗喂丽鱼”改为接取后累计 **10 条自繁鱼被丽鱼捕食＋1800 对应金币实收**，不限时、不倒退，奖励仍为 3 颗珍珠。
- 修复造景拖回库存/出售途中取消，整理任务详情百科链接及任务栏阴影；统一适合取整的数字显示。

第一章包含鱼类成长、繁殖、捕食、出售、氧气与水质、魔法伙伴与支援、召唤、探险、库存、造景和三星任务。

## 下载、启动与旧进度

**Windows：** 完整解压到新文件夹，运行 `Aquarium Days.exe`，保留全部附带文件。已有玩家可继续原槽，新玩家选空槽新建。

**Mac：** M 系列芯片、macOS 12.0+，不适用于 Intel Mac，无需 Unity 或 Rosetta。完整解压后按包内 `README_M2_Playtest.md` 使用 `Launch_Playtest.command`。脚本和直接打开应用共用常规存档位置；包旁 `PlaytestData` 用于诊断/日志。应用未做 Developer ID 签名或公证，首次启动见包内说明。

早期 Mac 脚本进度在旧包旁：先退出游戏，运行新版 `Import_Old_Playtest.command`，选择旧 `PlaytestData`，再选来源槽和空目标槽导入。原件保留，不合并进度；不要删除旧目录或覆盖已有槽位。

历史旧档已做读取、续玩、保存和再读检查。**旧版进行中的 F3 会按新规则换算保留记录，进度可能不同；待领奖和已领奖不变。** 新版 Mac 实机升级仍待玩家测试。保留升级前备份；回退安装包不会自动回退存档，旧程序不保证完整识别新版保存的进度。

左键交互；数字键/小键盘 1–6 选择快捷栏；右键/Esc 取消或返回；菜单→设置→音频调整音量。当前不支持手柄。

## 测试与反馈

这是预发布测试版。已完成定向教程/任务/旧档验证，不能代替完整人工通关、长时间运行或新版 Mac 实机测试。F3 的 10 条／1800 金币仍是首测值；小海龟动画本次未改。历史窗口 X 退出异常尚未确认根因修复，建议保存后从游戏内菜单退出。

欢迎反馈提示关闭/继续、入口是否好找、任务栏遮挡、F3节奏及Mac同档/导入问题。请在[反馈页](https://github.com/Er2u/Aquarium-Days/issues)附 `20261005-tutorial03`、系统、复现步骤和截图。Mac启动问题可附 `PlaytestData` 内诊断/Player日志，公开前检查个人路径信息。

## English

Raise, breed, feed and sell fish; balance oxygen and water quality; configure magical companions and support abilities; summon, send expeditions and progress through three stars.

The latest **tutorial03** Windows and Apple Silicon Mac packages share the same content. Tutorials now explain UI entrances without restricting aquarium operations or waits. Teaching prompts are dismissible, the task HUD is compact with a click-through body, and the home-bred cichlid task uses cumulative goals without a time limit.

Fully extract the ZIP. Run `Aquarium Days.exe` on Windows; follow the bundled README on Apple Silicon/macOS 12+. The Mac app has no Developer ID signing or notarization. **This new Mac build still needs hardware testing.** Keep pre-upgrade backups; reverting the app does not revert your saves.

See [release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261005-tutorial03) for changes, import instructions and validation limits. Report your version, OS, steps and screenshots through [Issues](https://github.com/Er2u/Aquarium-Days/issues).

## 文件校验 / Integrity

- [Windows SHA-256](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261005-tutorial03/Aquarium-Days-Windows64-20261005-tutorial03.zip.sha256)
- [Mac SHA-256](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261005-tutorial03/Aquarium-Days-macOS-ARM64-20261005-tutorial03.zip.sha256)

每版使用独立 Release，旧版说明与安装包保留在[发布历史](https://github.com/Er2u/Aquarium-Days/releases)。Each version has its own release; older downloads remain available.

## License / 许可证

Repository-authored content is available under the [MIT License](LICENSE) unless otherwise noted. Packaged Unity runtime and third-party components remain subject to their respective licenses.

除另有说明外，仓库作者创作的内容按 [MIT License](LICENSE) 提供。Unity Runtime 与第三方组件仍受其各自许可证约束。
