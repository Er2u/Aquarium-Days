# Aquarium Days

> A cozy 2D aquarium-management game about caring for fish, balancing a small ecosystem, and building a team of magical companions.
>
> 一款治愈系 2D 水族箱经营游戏：照顾鱼群、平衡小型生态，并搭配魔法伙伴构筑自己的鱼缸。

| 平台 / Platform | 最新下载 / Download | 版本 / Version |
|---|---|---|
| Windows x64 | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261004-tutorial02/Aquarium-Days-Windows64-20261004-tutorial02.zip) | **2026-10-04 tutorial02 · 测试版** |
| macOS Apple Silicon | [下载 ZIP](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261004-tutorial02/Aquarium-Days-macOS-ARM64-20261004-tutorial02.zip) | **同内容 tutorial02 · 新包待实机测试** |

[本版更新与启动说明 / Release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261004-tutorial02) · [历史版本 / All releases](https://github.com/Er2u/Aquarium-Days/releases) · [问题反馈 / Issues](https://github.com/Er2u/Aquarium-Days/issues)

第一章 · 简体中文 · 键盘鼠标 / Chapter 1 · Simplified Chinese · Keyboard and mouse

## 本次更新

这次重点修订教程中的操作限制和入口指引，两平台内容已对齐：

- 一星六项任务按顺序引导，强引导期间锁定当前追踪；可在新局初始跳过，不能中途跳过。
- 自动收币任务接受普通面值金币，观察时可以手收；手收不计自动目标。
- 从「更多→鱼缸管理」学习繁殖设置入口；一星后成长、支援和探险在后台等待，期间允许正常经营。
- 补齐教学恢复路径，修正部分遮挡与菜单状态问题；「收藏」改为「仓库」，补充植物食物来源和操作文案。
- Mac 普通脚本与直接打开应用统一存档位置，提供旧脚本进度导入，保留原件、不覆盖已有槽位。

第一章包含鱼类成长、繁殖、捕食、出售、氧气与水质、魔法伙伴与支援、召唤、探险、库存、造景和三星任务。保留此前任务文字/百科、商店快捷栏设置、金币面值外观与水面浮动、音频及水面空气更新。

## 下载、启动与旧进度

**Windows：** 完整解压到新文件夹，运行 `Aquarium Days.exe`，保留全部附带文件。已有玩家可继续原槽，新玩家选空槽新建。

**Mac：** 适用 M 系列芯片、macOS 12.0+，不适用于 Intel Mac，无需 Unity 或 Rosetta。完整解压，按包内 `README_M2_Playtest.md` 使用 `Launch_Playtest.command`。脚本和直接打开应用现在使用同一常规存档位置，包旁 `PlaytestData` 用于诊断/日志。应用未做 Developer ID 签名或公证，首次启动见包内说明。

旧 Mac 脚本的进度在旧包旁：先退出游戏，运行新版 `Import_Old_Playtest.command`，选择旧 `PlaytestData`，再选择来源槽和空目标槽确认导入。原件保留，不合并两份进度；设备设置另行确认。不要删除旧目录或为导入覆盖已有进度。

已完成 feedback 内容与 tutorial01 相关旧来源的读取、续玩、保存和再读检查。**Mac 历史迁移数据链在 Windows 验证，新版 Mac 实机升级仍待玩家测试。** 保留升级前备份；旧版程序不保证完整识别新版保存的进度，回退包不会自动回退存档。

左键交互；数字键/小键盘 1–6 选择快捷栏；右键/Esc 取消或返回；菜单→设置→音频调整音量。当前不支持手柄。

## 测试范围与反馈

这是供玩家验证的预发布版本，尚未完成整章人工验收。已做定向教程、任务事务、恢复与旧档检查。

两平台构建与 ZIP 完整性检查通过；Windows 最终解包的新局保存、以及保留原运行程序集的独立验证副本中的继续读档/再次存读/菜单退出检查通过。Mac 目前只有交叉构建和静态检查，实机启动、输入、音频与旧档导入仍待测试。

重点欢迎反馈一星卡点、真实菜单入口、一星后后台等待及 Mac 同档/导入问题。美术、动画和平衡仍在迭代，小海龟动画本次未改。此前窗口 X 退出异常尚未确认根因修复，建议保存后通过游戏内菜单退出。

请在[反馈页](https://github.com/Er2u/Aquarium-Days/issues)附版本 `20261004-tutorial02`、系统、复现步骤、期望/实际结果及截图；卡顿补充电脑与鱼缸配置。Mac 启动失败请附 `PlaytestData` 的诊断/Player 日志，公开前检查个人路径信息。

## English

Raise, breed, feed and sell fish; balance oxygen and water quality; configure magical companions and support abilities; summon, send expeditions and progress through three stars.

The latest **tutorial02** Windows and Apple Silicon Mac packages share the same game content. This playtest improves mandatory tutorials, real menu navigation, ordinary automatic coin collection and background waits after the first star. The new Mac launcher shares the regular save location with direct app launch and provides explicit import of older launcher saves into empty slots.

Fully extract the ZIP. Run `Aquarium Days.exe` on Windows; follow the bundled Mac README on Apple Silicon/macOS 12+. The Mac app has no Developer ID signing or notarization. **This new Mac package still needs hardware testing; previous M2 acceptance only covered the older release.** Existing save upgrade checks and targeted tests do not replace a full human playthrough or all-device testing. Keep pre-upgrade backups; older builds may not understand newly saved progress.

See [release notes](https://github.com/Er2u/Aquarium-Days/releases/tag/playtest-20261004-tutorial02) for import instructions and validation limits. Report your version, OS, steps and screenshots through [Issues](https://github.com/Er2u/Aquarium-Days/issues).

## 文件校验 / Integrity

- [Windows SHA-256](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261004-tutorial02/Aquarium-Days-Windows64-20261004-tutorial02.zip.sha256)
- [Mac SHA-256](https://github.com/Er2u/Aquarium-Days/releases/download/playtest-20261004-tutorial02/Aquarium-Days-macOS-ARM64-20261004-tutorial02.zip.sha256)

每版使用独立 Release，旧版说明与安装包保留在[发布历史](https://github.com/Er2u/Aquarium-Days/releases)。Each version has its own release; older downloads remain available.

## License / 许可证

Repository-authored content is available under the [MIT License](LICENSE) unless otherwise noted. Packaged Unity runtime and third-party components remain subject to their respective licenses.

除另有说明外，仓库作者创作的内容按 [MIT License](LICENSE) 提供。Unity Runtime 与第三方组件仍受其各自许可证约束。
