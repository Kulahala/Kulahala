# Hi there, I'm Kulahala 👋

Unreal Engine / Gameplay C++ 开发者。热衷于游戏 3C 系统、动作战斗系统开发，以及探索人机协作（AI-assisted coding）的高效开发流。

---

## 🛠️ Tech Stack & Tools

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Unreal Engine 5](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vue3](https://img.shields.io/badge/Vue3-4FC08D?style=flat-square&logo=vue&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
[![Steam](https://img.shields.io/badge/Steam-000000?style=flat-square&logo=steam&logoColor=white)](https://steamcommunity.com/profiles/76561198410377548/)

* **游戏开发**：Gameplay C++ 核心逻辑、Enhanced Input、Montage 动作控制、AnimNotify 机制、BoxTrace Sweep 物理检测、DataAsset 数据驱动、Motion Warping 动画配准、AIController & NavMesh 寻路。
* **开发工具**：Unreal Editor、Visual Studio 2022、Git、AI 编程协作工具 (Codex, Claude code, Gemini)。

---

## 🎮 Featured Projects

### ⚔️ [UE5-Soulslike-Combat](https://github.com/Kulahala/UE5-Soulslike-Combat)
> **基于纯 Gameplay C++ 从零构建的第三人称类魂（Soulslike）动作战斗原型。**
* **核心动作闭环**：通过 C++ 有限状态机控制攻击、格挡、弹反等多动作互斥流转；在定时器与物理伤害等异步回调路径实施严密的生命周期守卫（Callback Guards）以防死锁和悬空指针。
* **命中检测与反馈**：使用 BoxTrace Sweep 连接相邻帧插槽以防止漏判；实现统一解耦的物理伤害管线，支持击退、Hit Stop 顿帧、以及受击重定向至架势破防（Stance Break）大硬直的经典处决反馈。
* **AI 决策与招式**：构建外层 FSM 与局部子状态机，引入“协同攻击队列”（Coordinated Attack Queue）限制并发群攻决策；借助 AI 辅助 Review 修复了打断分流下的死锁问题。

### 🕹️ [MixGame](https://github.com/Kulahala/MixGame)
> **基于 HTML Canvas 的微信小游戏合集。**
* 独立开发并重构了经典扫雷、2048 等游戏，实现了统一的场景管理、输入分发和触控渲染优化。

### 🌐 [Smoke-VueProject](https://github.com/Kulahala/Smoke-VueProject)
> **基于 Vue3/Vite 构建的个人作品展示站。**
* 支持双语国际化，集成 CMS 动态发布内容，优化 SEO 指标并实现基于 Netlify 的自动化 CI/CD 部署。

---

## 💡 About Me & Hobbies

* 🎮 **核心游戏素养**：[Steam 资深用户](https://steamcommunity.com/profiles/76561198410377548/)（储备 250+ 游戏，累计游玩 8000+ 小时，主要涉猎动作、射击、生存沙盒等品类），善于解构各种核心玩法机制，并能逆向还原为 C++ 游戏逻辑。
* 🤖 **AI Native 编程习惯**：深度拥抱 AI 辅助编程，善于利用大模型快速进行符号定位、代码逻辑 Review、日志错误排查，拥有极高的自主探索与调试能力。

