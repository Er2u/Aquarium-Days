# Aquarium Days

> A cozy 2D aquarium-management game about caring for fish, balancing a small ecosystem, and building a team of magical companions.
>
> 一款治愈系 2D 水族箱经营游戏：照顾鱼群、平衡小型生态，并搭配魔法伙伴构筑自己的鱼缸。

| 平台 / Platform | 最新下载 / Download | 版本与验证 / Version & validation |
|---|---|---|
| Windows x64 | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261015-chapter01-rc1/Aquarium-Days-Windows64-20261015-chapter01-rc1.zip) | **20261015-chapter01-rc1 · 第一章更新试玩版，最终包已运行验证** |
| macOS Apple Silicon | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261015-chapter01-rc1/Aquarium-Days-MacARM64-20261015-chapter01-rc1.zip) | **同内容 rc1 · 尚未 Mac 实机验证，未 Developer ID 签名或公证** |

[本版更新与启动说明 / Release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261015-chapter01-rc1) · [完整更新日志](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261015-chapter01-rc1/CHANGELOG.md) · [历史版本 / All releases](https://github.com/Er2u/Aquarium-Days/releases) · [问题反馈 / Issues](https://github.com/Er2u/Aquarium-Days/issues)

第一章 · 简体中文 · 键盘鼠标 / Chapter 1 · Simplified Chinese · Keyboard and mouse

## 本次更新

- **从一条小金鱼接手老水族馆。** 新增开场 CG、女声助手、二星联络员和三星开放日，配有第一章主干语音；字幕可在设置中开关。
- **赚钱有了更清楚的目标。** 「更多 → 小馆发展」整合四笔转让款与协会许可，逐步开放商店、伙伴和探险。没有期限、利息或欠款惩罚；星级仍靠实际经营任务推进。
- **轻提示，自己探索。** 开局不再先选教程路线，气泡可随时关闭；百科不自动弹出，找到过入口后再给快捷方式。入门主线减为五项，捕食体验改为可选支线。
- **新增翠纹灯鱼与水芋丛。** 适合植物喂养的中档鱼与产食造景，随第三笔转让款开放。
- **整个鱼缸换装。** 九种普通生物、八件造景、小海龟、叶羊与寄居蟹更新形象和动作；水体、沙床、岩石、透光、水线统一呈现。
- **操作与收泡更顺手。** 点击范围和选中高光更新，空气层也能收币、投食；手动与自动收取采用新版音色，可关闭捡金币升调。修复零价值金币泡泡和部分动作衔接问题。

第一章包含鱼类成长、繁殖、捕食、出售、氧气与水质、魔法伙伴与支援、召唤、探险、库存、造景和三星任务。

## 下载、启动与旧进度

**Windows：** 完整解压到新文件夹，运行 `Aquarium Days.exe`，保留全部附带文件。已有玩家可继续原槽，新玩家选空槽新建。

**Mac：** M 系列芯片、macOS 12.0+，不适用于 Intel Mac，无需 Unity 或 Rosetta。完整解压后按包内 `README_M2_Playtest.md` 使用 `Launch_Playtest.command`。脚本和直接打开应用共用常规存档位置；包旁 `PlaytestData` 用于诊断/日志。**本版本尚未在 Mac 上实际运行，没有 Developer ID 签名或公证。** 首次启动按包内说明操作，不要移除隔离属性或关闭系统安全保护。

早期 Mac 脚本进度在旧包旁：先退出游戏，运行新版 `Import_Old_Playtest.command`，选择旧 `PlaytestData`，再选来源槽和空目标槽导入。原件保留，不合并进度。

本版支持 tutorial03 等 V18/content5–8 进度承接到 content9，保留已有资产和已获得的资格；不要求老玩家一律重交转让款。旧目录原件保留，旧程序不保证读取本版新增内容。V17 及以前进度不在本次兼容范围内。

左键交互；数字键/小键盘 1–6 选择快捷栏；右键/Esc 取消或返回；菜单 → 设置 → 音频调整音量。当前不支持手柄。

本次发布的是验证完成的原版 rc1 文件。包内“本地候选／尚未发布”是冻结时的记录，当前发布状态以 Release 页面为准。

## 试玩数据

「分享试玩数据」默认开启，可以在 **设置 → 试玩数据** 关闭，重启后保留选择。收集有限的进度、功能使用、性能摘要与错误诊断，帮助定位卡点；不上传完整存档、自定义鱼名、账号或本机路径，使用随机安装与会话标识。

数据低频记录、后台上传，断网不阻止经营、保存或退出。关闭后停止采集与上传并清理本地待传队列，已送达的数据不会自动撤回。

## 测试与反馈

Windows 最终包已检查启动、新局、首期经营、保存重进和正常退出，并完成有限 tutorial03 旧档承接检查。两平台构建与内容一致性已检查，Mac 仍待实机测试。整章玩法、美术和配音复用此前验收，不代表所有硬件、网络或长期平衡已验证。

重进阶段仍可能出现短时卡顿，日志有既有任务类型序列化深度警告。历史窗口 × 退出异常根因未单独确认修复，本次原包检查通过。性能证据和采集补验边界见 Release 附件。

欢迎反馈发展节奏、入口指引、新美术与声音、存读和跨设备问题。请在[反馈页](https://github.com/Er2u/Aquarium-Days/issues)附 `20261015-chapter01-rc1`、系统、复现步骤和截图。公开日志前请检查个人路径信息。

## English

Raise, breed, feed and sell fish; balance oxygen and water quality; configure magical companions and support abilities; summon, send expeditions and progress through three stars.

The **20261015-chapter01-rc1** playtest adds Chapter 1 story scenes and voice-over, an installment-based development ledger, association permits, lighter guidance, a new fish and plant, refreshed sprites and animation, aquarium lighting, and new coin-collection audio. Windows and Apple Silicon Mac packages share the same content.

Fully extract the ZIP. Run `Aquarium Days.exe` on Windows; follow the bundled README on Apple Silicon/macOS 12+. **The Mac build has not been tested on hardware and has no Developer ID signing or notarization.** Supported V18/content5–8 progress migrates to content9; older applications may not read new progress.

Optional playtest statistics and diagnostics are enabled by default and can be turned off together in Settings. Collection is bounded and uploads run in the background; offline play, saving and quitting do not wait for uploads. Full saves, custom fish names, accounts and local paths are not uploaded.

See [release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261015-chapter01-rc1) for the complete changes and validation limits. Report your version, OS, steps and screenshots through [Issues](https://github.com/Er2u/Aquarium-Days/issues).

## 文件校验与历史版本 / Integrity & history

- [SHA256SUMS.txt](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261015-chapter01-rc1/SHA256SUMS.txt)
- [上一公开版 tutorial03](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261005-tutorial03)
- [全部发布历史](https://github.com/Er2u/Aquarium-Days/releases)

每版使用独立 Release，旧版说明与安装包保留。Each version has its own release; older downloads remain available.

## License / 许可证

Repository-authored content is available under the [MIT License](LICENSE) unless otherwise noted. Packaged Unity runtime and third-party components remain subject to their respective licenses.

除另有说明外，仓库作者创作的内容按 [MIT License](LICENSE) 提供。Unity Runtime 与第三方组件仍受其各自许可证约束。
