🌌 Infinite Stream (无限流) 3.0 - AI Architect Engine

Infinite Stream 是一个纯前端、零后端 (Zero-Backend)、基于大语言模型驱动的无限流文字沙盒游戏引擎。
通过 BYOK (Bring Your Own Key) 模式，玩家可以自主构建世界法则，AI 将化身为严谨的“地下城主 (Dungeon Master)”，根据玩家的特质和行动，进行逻辑自洽的长链推演。

✨ 核心特性 (Features)

🧠 深度逻辑引擎集成 (DeepSeek R1 & MiMo)

内置对 DeepSeek-Reasoner (R1) 的特殊适配，支持在 UI 前端可视化展示 AI 的“思维链 (Chain of Thought)”。

动态多模型路由，玩家可随时在“高级推理 (Pro/R1)”与“极速响应 (Flash/V3)”间切换。

🎶 AI 程序化情感 BGM (Procedural Audio)

无需加载庞大的音频文件！基于 Tone.js 纯代码合成。

AI 引擎会根据当前剧情的走向（如暗黑、宏大、战斗、宁静），实时输出 [MOOD] 指令，前端瞬间演算并无缝切换环境音乐。

🛠️ 架构师热重载系统 (System Assistant)

彻底解决长文本 AI 容易“吃书”的痛点。

玩家拥有最高权限，可在侧边栏随时修改【底层法则】和【角色状态】，强制 AI 在下一回合对齐新设定。

🌐 极致轻量的去中心化架构

单个 index.html 文件即包含所有逻辑。

无数据库、无服务器成本，极致的高并发潜力，非常适合用于展示大规模 Multi-Agent 和长文本推演的商业化可能。

🚀 快速上手 (Quick Start)

本项目无需复杂的 Node.js 环境或构建工具。

克隆仓库 或直接下载压缩包：

git clone [https://github.com/YourUsername/Infinite-Stream.git](https://github.com/YourUsername/Infinite-Stream.git)



运行游戏：
直接在浏览器（推荐 Chrome 或 Edge）中双击打开 index.html 文件。

建立连接：
在初始登录界面，选择你的模型供应商（DeepSeek 或 Xiaomi），填入你个人的 API KEY，设定世界观，敲击回车即可开启创世。

📸 界面预览 (Screenshots)

(建议在此处上传 1-2 张你本地运行时的炫酷截图，比如带有绿色思维链、侧边栏和深色背景的游戏界面)

![登录界面](./assets/login.png)
![推演界面](./assets/gameplay.png)

⚙️ 技术栈 (Tech Stack)

UI & 逻辑: HTML5 + CSS3 (Glassmorphism & CRT 特效) + Vanilla JavaScript

音频引擎: Tone.js (Web Audio API)

大模型接口: 标准化 REST API (/v1/chat/completions 格式)

🗺️ 未来规划 (Roadmap)

[x] 多模型路由适配 (DeepSeek / 小米 MiMo)

[x] AI 程序化环境音效 (Tone.js)

[x] R1 思维链前端可视化

[ ] 导出/导入“世界观记忆存档” (JSON 格式)

[ ] 接入前端向量数据库 (如 Web-Milvus) 实现超长文本 RAG 记忆

[ ] 允许玩家上传本地知识库 (TXT/PDF) 作为世界观背景

📜 协议 (License)

本项目采用 MIT License 开源协议，欢迎随意 Fork、修改并用于你的创意之中！如果你用它搭建了有趣的世界，欢迎在 Issues 中与我们分享。

“在无限流的宇宙里，唯一的限制是你的算力与想象。”
