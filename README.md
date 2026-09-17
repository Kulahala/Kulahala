# Hi there, I'm Kulahala 👋

🎮 **Unreal Engine Gameplay C++ 开发者** | 专注于 **动作战斗 3C 系统**、**GAS 架构** 与 **AI-Native 高效工程协作**。

热衷于解构硬核动作游戏的打击感与底层机制，并以工业级代码质量（生命周期防御、内存安全、自动化测试门禁）将其还原至虚幻引擎。

---

## 🛠️ 技术专精 (Tech Stack & Core Skills)

### 核心引擎与架构
[![C++](https://img.shields.io/badge/C%2B%2B-20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-5.8-0E1128?style=flat-square&logo=unrealengine&logoColor=white)](https://www.unrealengine.com/)
[![GAS](https://img.shields.io/badge/Architecture-GAS_(Gameplay_Ability_System)-FF6B6B?style=flat-square)](https://docs.unrealengine.com/)
[![StateTree](https://img.shields.io/badge/AI-StateTree-4ECDC4?style=flat-square)](https://docs.unrealengine.com/)
[![Enhanced Input](https://img.shields.io/badge/3C-Enhanced_Input-45B7D1?style=flat-square)](https://docs.unrealengine.com/)
[![Automation](https://img.shields.io/badge/Quality-UE_Automation_Testing-2ECC71?style=flat-square)](https://docs.unrealengine.com/)

- **战斗与 3C 体系**：
  - **GAS (Gameplay Ability System)**：基于 ASC 唯一权属构建技能、消耗、打断与属性体系，杜绝状态机并行与非法状态透支。
  - **精准打击管线**：多帧 Sweep Trace、Hit Stop 顿帧、相机 Shake/FOV Punch 震屏分级反馈、三级受击反应分类（Small / Big / Launch）。
  - **动画与位移控制**：Motion Warping 动态位移配准、处决吸附对齐、托管动作蒙太奇速率窗口与取消窗口。
  - **敌人行为 AI**：UE 5.8 原生 **StateTree** 驱动的宏观战斗决策，结合感知记忆、协同攻击队列与环绕机动。
- **外围系统与工程化**：
  - **持久化与交易**：单魂账本与死亡光球掉落回收架构、动态武器装备多槽位快照、异步写盘看门狗与无缝重载。
  - **工程严谨性**：构建 50+ 领域分层（AI、Combat、Player、Projectile 等）的自动化测试套件；对异步委托、定时器、回调实施严格生命周期守卫（Callback Guards）。

### 工具链与协作
[![Rider](https://img.shields.io/badge/IDE-JetBrains_Rider-red?style=flat-square&logo=rider&logoColor=white)](https://www.jetbrains.com/rider/)
[![Git](https://img.shields.io/badge/VCS-Git_&_Git_LFS-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![AI-Native](https://img.shields.io/badge/Workflow-AI--Native_Pair_Programming-9B59B6?style=flat-square)](https://github.com/)
[![Steam](https://img.shields.io/badge/Steam-8000+_Hours_Gamer-000000?style=flat-square&logo=steam&logoColor=white)](https://steamcommunity.com/profiles/76561198410377548/)

---

## 🎮 重点项目 (Featured Projects)

### ⚔️ [PolyQuest](https://github.com/Kulahala/PolyQuest) · *旗舰项目*
> **基于 UE 5.8 与 GAS 架构深度构建的单人第三人称风格化动作 RPG 原型**

- **系统设计与权属权威**：
  - 彻底以 GAS 作为战斗运行时唯一权威，承载近战连段、格挡蓄力、弹反破防与处决机制。
  - 接入双代理研发流（Main 规划架构 + Executor 实施与自审），以严格契约（`plan.md` / `ARCHITECTURE.md`）驱动复杂战斗与系统交付。
- **智能化敌人与打击反馈**：
  - 敌人宏观决策由 UE 5.8 StateTree 承载，细颗粒度动作由 GAS 控制，配合动态感知、脱战巡逻与远程风起限速瞄准。
  - 全流程视听反馈：根据攻击强弱分级触发材质叠加闪烁（Overlay Flash）、相机视场震颤与音效调度。
- **自动化测试保障网**：
  - 原生自研 50+ 项覆盖 AI 状态树、投射物弹道预判、生命周期重入、体力衰竭门禁、装备换装一致性的自动化测试套件，杜绝隐蔽 Bug 与回归。

---

### 🛡️ [UE5-Soulslike-Combat](https://github.com/Kulahala/UE5-Soulslike-Combat)
> **基于纯 Gameplay C++ 从零构建的第三人称类魂动作战斗原型（技术沉淀基线）**

- **核心动作流转**：通过 C++ 有限状态机严格控制翻滚、轻重攻击、盾牌格挡与弹反窗口，探索动作互斥与回调安全。
- **判定与硬直**：BoxTrace Sweep 逐帧检测防漏刀，实现 Hit Stop 顿帧与架势破防（Stance Break）处决。
- *（已作为探索基线，核心战斗设计已全面重构升级至 PolyQuest 的 GAS 体系）*

---

## 💡 关于我与开发理念 (About Me)

- 🎮 **资深硬核动作玩家**：[Steam 资深用户](https://steamcommunity.com/profiles/76561198410377548/)（游戏库 250+ 款，累计游戏时长 8000+ 小时，主攻黑魂、艾尔登法环、只狼、怪猎等），擅长将优秀动作手感解构为数学与引擎状态逻辑。
- 🤖 **AI-Native 高效工程实践者**：深度拥抱 AI 辅助研发，将大语言模型与 IDE MCP 工具链、图分析、自动化回归测试紧密结合，具备极高的需求拆解、架构把控与全流程闭环交付能力。
