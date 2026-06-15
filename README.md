# Kulahala | Unreal Engine Gameplay C++

我现在主要做 Unreal Engine Gameplay C++，重点关注动作战斗、输入分发、状态机、动画通知、Trace 命中、敌人 AI、HUD 反馈和 DataAsset 驱动配置。

## Featured Project

### [UE5-Soulslike-Combat](https://github.com/Kulahala/UE5-Soulslike-Combat)

UE5.7 C++ 第三人称类魂动作战斗原型，目标是把输入、动作状态、动画事件、命中检测、伤害反馈和敌人 AI 串成一个可演示、可扩展的 Gameplay 闭环。

- 状态驱动的攻击、翻滚、格挡、弹反、喝药、受击、死亡流程。
- AnimNotifyState + BoxTrace sweep 实现武器有效帧和命中检测。
- 格挡、弹反、韧性、破防、击退、相机震动和 Hit Stop 反馈链路。
- DataAsset 配置玩家连招、特殊/蓄力攻击、敌人招式和 Motion Warping 参数。
- 敌人巡逻、搜索、追击、战斗局部子状态、攻击冷却和队友攻击协调。
- Lock-on、HUD、调试开关、Niagara 反馈、Chaos 破坏物和 PCG 场景辅助。

## Current Focus

- UE5 Gameplay C++
- Action combat systems
- Animation-driven hit detection
- AI combat behavior
- Data-driven gameplay configuration
- Debugging and gameplay-system documentation

## Other Projects

- [MixGame](https://github.com/Kulahala/MixGame): 微信小游戏合集，使用纯前端 Canvas 架构实现数独、数字华容道、扫雷、2048、记忆翻牌等玩法，包含场景宿主、输入分发、本地成绩和浏览器调试壳。
- [Smoke-VueProject](https://github.com/Kulahala/Smoke-VueProject): Vue 3 + Vite 产品展示站，包含中英文目录、响应式页面、SEO、Decap CMS 内容管理、Netlify 部署和图片 WebP 自动转换流程。

## Tech Stack

- **Game / Engine**: Unreal Engine 5, C++, Blueprint, Enhanced Input, UMG, Niagara, Motion Warping, NavMesh
- **Programming**: C/C++, Java, Python, JavaScript
- **Web / Tools**: Vue 3, Vite, Git, Visual Studio, Unreal Editor
