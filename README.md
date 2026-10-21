# WW2-Frontline-Command-C-SDL2-and-ImGui
基于 C++、SDL2 和 Dear ImGui 开发的硬核二战实时战术与丧尸坚守模拟游戏（支持纯鼠标操作、阶梯抽奖与本地存档）。WW2 Real-Time Tactical Game built with C++, SDL2, and Dear ImGui. Features mouse-only controls, tier-based unit gacha, zombie defense mode, and local save system.

# ⚔️ 二战前线指挥官 (WW2 Frontline Command) v1.0.0 正式发布！

🎉 **【绿色免安装版】无需配置任何开发环境，下载解压即可畅玩！**

---

### 🎮 游戏下载与运行说明
1. 下载下方 Assets 区域的 `WW2-Frontline-Command-Windows-x64.zip`。
2. 解压到本地任意文件夹。
3. 双击运行 `game.exe` 即可直接进入游戏。

---

### ✨ 核心游戏特色
* **🖱️ 纯鼠标直观交互**：右键拖拽平移视角，左键直观点选部队与下达推进、占领、冲锋及掩体建造指令。
* **🎰 阶梯稀有度军需处抽奖**：消耗战功金币可抽取普通兵种（60%）、精锐重火力（30%）与传说王牌机甲/巨兽（10%）。
* **💾 本地持久化存档系统**：自动读写本地 `save_game.dat`，金币与兵种解锁状态永久保存。
* **🔥 多种战役与坚守模式**：支持 1v1 经典战役、2v2 集团军会战、大乱斗以及 10 波波次递进的丧尸坚守模式。
* **🎵 真实战地音效**：集成 Windows 多媒体 API，实现枪炮开火、轰炸打击与抽取王牌兵种的音效反馈。

---

### 🛠️ 开发者指南 (如果您想自行编译)
* **开发语言**：C++ (Visual Studio 2022 / x64)
* **图形与 UI 依赖**：SDL2, Dear ImGui (SDLRenderer2 后端)
* **运行环境要求**：包含 `SDL2.dll` 与 `simhei.ttf` 字体文件即可运行。
