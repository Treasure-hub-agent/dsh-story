<div align="center">

# 📖 dsh-story

**DSH 互动小说插件 · DeepSeek Harness Interactive Fiction**

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![DSH](https://img.shields.io/badge/DeepSeek%20Harness-plugin-8A2BE2)](https://github.com/deepseek-ai/deepseek-harness)
[![Skills](https://img.shields.io/badge/skill%20base-v10.0.0-blue)](https://github.com/Treasure-hub-agent/interactive-fiction-skill)

</div>

---


本插件基于 interactive-fiction-skill 开发

> ### [📚 interactive-fiction-skill](https://github.com/Treasure-hub-agent/interactive-fiction-skill) 
>
> 选项驱动的沉浸式互动小说创作规范，**一个 skill 达到收费平台级别的体验**。
>
> - **铁律级规则引擎**：每轮必出选项、视角一致性、字数区间（500-1200）、自由输入优先、自检清单
> - **完整玩法体系**：穿越 / 自创 / 创世 / 随机开局、角色卡体系、场景卡、事件回响与后果回收
> - **双路存档**：运行时 JSON 状态 + 章节进度，多作品并存
> - **多 Agent 支持**：子 Agent 模式、沉浸模式、双文模式、主线性模式

**dsh-story 把这份规则引擎从「文本指令」升级为「代码级 UI 体验」** —— 规则注入不再靠模型自觉，而是插件接缝强制执行；选项从打字变成点按钮；状态从文本条变成悬浮窗。

---

## ✨ 目标能力

- **全量 UI 叙事面板**：正文排版、选项按钮（A/B/C/D/E）、章节卡片，内嵌于 DSH 聊天流
- **悬浮窗信息层**：角色状态、当前场景、关键道具等常驻悬浮展示，不打断对话
- **代理叙事**：子代理生成正文（skill 同款机制），后续扩展子代理职能（场景渲染/角色台词/多线并行），不拆分双 AI
- **存档系统**：`ctx.storage` 持久化章节进度，关窗不丢剧情
- **规则注入**：skill 规则原生复用（DSH `ctx.skills` 加载，与 Hermes 体验一致）+ UI 接管交互

## 🗺️ 路线图

| 阶段 | 内容 | 状态 |
|---|---|---|
| 0 | 仓库初始化 + 规划 | ✅ |
| 1 | UI 全量叙事面板 MVP（选项按钮 + 正文卡片） | ⏳ |
| 2 | 悬浮窗信息层 | ⏳ |
| 3 | 代理叙事增强（子代理职能扩展）+ 存档 + 玩法升级 | ⏳ |


## 🛠️ 相关项目

- [interactive-fiction-skill](https://github.com/Treasure-hub-agent/interactive-fiction-skill) —— 同题材 skill 版（规则引擎已沉淀）
- [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) —— 本插件运行平台

## 📄 License

MIT
