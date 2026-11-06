<div align="center">

# 毛蒙恩 · AI Product Manager & Builder

### 把模糊需求变成可验证、可运行、可发布的 AI 产品

我关注用户为什么需要、产品如何落地、结果怎样评估、失败如何兜底。<br>
从问题定义与 Agent 工作流，到交互、实现、测试和开源发布，我希望让 AI 真正成为可使用的产品。

[![Portfolio](https://img.shields.io/badge/个人作品集-1557FF?style=for-the-badge&logo=safari&logoColor=white)](https://maomengen888-maker.github.io/)
[![Featured Project](https://img.shields.io/badge/核心项目_简屿·灵动岛-07111F?style=for-the-badge&logo=apple&logoColor=54DDFF)](https://github.com/maomengen888-maker/trae-flow)
[![Email](https://img.shields.io/badge/联系我-FF5A45?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:1251548030@qq.com)

</div>

---

## 🚀 正在构建：简屿 · 灵动岛

> Mac 顶部的个人工作台与 AI 陪伴助手，把待办、随笔、需求资料和日常工具集中在一座岛里。

<p align="center">
  <a href="https://github.com/maomengen888-maker/trae-flow">
    <img src="https://raw.githubusercontent.com/maomengen888-maker/trae-flow/main/TraeFlow/Assets.xcassets/AppIcon.appiconset/icon_256x256.png" width="128" alt="简屿 · 灵动岛应用图标">
  </a>
</p>

这个项目基于开源 [TRAE Flow](https://github.com/ccsonicc333/trae-flow) 继续设计与开发。我把产品方向扩展为个人工作台与 AI 陪伴，围绕任务管理、可管理的记忆、资料检索和 Mac 顶部交互持续迭代。

| 核心体验 | 产品实现 |
| --- | --- |
| 🧭 今日工作台 | 四列任务看板、截止时间提醒、天气与带伞建议 |
| ✨ AI 陪伴 | 陪伴、复盘、建议、知识问答四种模式，支持 Dify、DeepSeek、OpenAI 与兼容服务 |
| 🧠 可管理的记忆 | 根据明确表达提取信息，查看来源、确认、修改、删除或设置禁止记忆规则 |
| 📚 资料库与隐私空间 | 本地资料检索；独立的 Touch ID 解锁加密空间 |
| 📝 随笔与需求管理 | Markdown 随笔；需求资料按 PRD → 原型 → 测试验收 → 上线组织 |
| 📸 桌面工具 | 截图置顶、快速录音与语音转写、音乐播放控制 |
| 🎬 抖音与置顶小窗 | 主界面/独立小窗切换，关闭时暂停音视频 |

AI 默认进入原生陪伴工作区，DeepSeek Harness 保留为可选的「开发者工作台」。项目目前处于个人开发与体验阶段，具体功能、数据处理方式与验证结果见项目仓库。

**我承担的工作：** 产品定义 · 交互设计 · SwiftUI/AppKit/WebKit 实现 · API 接入 · 测试迭代 · 文档与开源发布

[查看源码与完整功能 →](https://github.com/maomengen888-maker/trae-flow) · [查看验证记录](https://github.com/maomengen888-maker/trae-flow/blob/main/docs/verification-2026-09-28.md)

---

## 🧩 代表项目

### [章鱼时代智库 Agent](https://github.com/maomengen888-maker/zhangyu-knowledge-agent)

基于 Dify Chatflow、RAG 与 Next.js 的企业知识问答项目，围绕制度查询、流程指引、引用溯源和流式对话组织体验。模型连接通过服务端代理，API Key 由服务端环境变量管理。

**当前阶段：** 已有前端与 Dify 对话代理；标准评测集、人工转接和管理端评测看板仍在后续规划中。

`企业知识库` `RAG` `Dify` `Next.js`

### [梦象 Web PoC](https://github.com/maomengen888-maker/mengxiang-dream-trace)

围绕「记录 → 梦象确认 → 按需澄清 → 解析 → 结果卡片」设计的可追溯传统解梦原型，重点验证梦象修订、会话恢复与来源边界。

**当前阶段：** 解析与卡片使用演示数据，尚未接入真实模型或生产知识库；古籍条目保留待核验状态，避免把演示内容当作已核实结论。

`产品原型` `状态管理` `来源溯源` `Next.js`

### [AI Product Manager Skill](https://github.com/maomengen888-maker/PM--skill)

一套证据优先的 11 阶段 AI 产品工作流，把产品想法推进到机会定义、MVP、Agent 设计、PRD、评估、上线与迭代。

`产品策略` `MVP` `PRD` `评估与兜底`

### [Human Writing AI Skill](https://github.com/maomengen888-maker/max-writing-skill)

面向中文写作与改稿的 AI Agent，通过任务路由、材料边界、事实核验和渐进式上下文加载控制质量。

`Agent 设计` `任务路由` `事实核验` `质量控制`

### [Bango Agent Product Architecture](https://github.com/maomengen888-maker/runninghub-bango-architecture)

基于可观察证据拆解多 Agent 创作产品，覆盖用户旅程、Agent I/O、共享上下文、状态转换与平台架构。

`产品拆解` `Agent I/O` `状态建模` `产品架构`

---

## 🛠️ 我的工作方式

- **从用户问题开始：** 先厘清场景、约束和证据，再讨论功能与模型。
- **把假设说清楚：** 区分事实、判断、建议和待确认项，减少过早确定方案。
- **设计完整 Agent：** 明确输入输出、人机分工、工具调用、上下文和失败兜底。
- **亲手验证体验：** 用原型和可运行产品验证交互，不让 PRD 停在文档里。
- **让质量可衡量：** 定义正常/异常用例、验收标准、观测信号和迭代闭环。

## 🧠 能力组合

`AI 产品策略` `用户与场景研究` `Agent 工作流` `PRD` `原型`<br>
`SwiftUI / AppKit` `Web 产品` `API 集成` `模型评估` `产品写作`

---

<div align="center">

### 好 AI 产品，不是让模型“看起来很聪明”

而是帮助用户在明确场景里，更稳定、更可控地完成任务。

[访问个人作品集](https://maomengen888-maker.github.io/) · [查看简屿 · 灵动岛](https://github.com/maomengen888-maker/trae-flow) · [邮件联系](mailto:1251548030@qq.com)

</div>
