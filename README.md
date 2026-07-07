# Photography Scene Design Skill

> 专为 AI 图像生成打造的专业摄影器材与参数指南，适用于文档驱动的 Agent 系统。

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL3.0-yellow.svg)](./LICENSE)
[![Models](https://img.shields.io/badge/Models-GPT--image--2%20%7C%20nanobanana2%20%7C%20nanobananapro%20%7C%20seedream5.0-blue)](#%E6%94%AF%E6%8C%81%E6%A8%A1%E5%9E%8B)
[![KunFlix](https://img.shields.io/badge/Platform-KunFlix-purple)](https://github.com/KunLabAI/KunFlix)

简体中文 | [English](./README_EN.md)

---

## 📚 项目简介

**Photography Scene Design Skill** 是一个专业的摄影场景设计技能（Skill），为 AI 图像生成注入真实摄影器材参数。通过指定相机机身、镜头品牌、焦距与光圈，精确控制画面质感、景深、透视与氛围，提升角色/道具/场景设计的专业度与真实感。

本 Skill 专为✨**文档驱动的 Agent 系统**✨设计，可供智能体在调用生图工具时参考，自动生成专业级摄影参数提示词。

### 这个 Skill 能做什么？

- 📷 **器材参数注入** — 将真实相机、镜头、光圈参数融入提示词，提升画面质感
- 🎬 **多风格覆盖** — 从商业人像到电影感、胶片复古、微距特写等多种风格
- 🎨 **智能意图匹配** — 根据设计意图自动推荐最佳器材组合
- 📝 **结构化案例库** — 53 套可检索、可替换变量的摄影级提示词案例配方

---

## 🤖 支持模型

本 Skill 适配以下前沿文生图/图生图模型：

| 模型 | 类型 | 器材描述融入方式 |
|------|------|------------------|
| **GPT-image-2** | 文生图 / 图生图 | 直接在提示词中以自然语言描述器材和参数 |
| **nanobanana2** | 文生图 / 图生图 | 将器材信息作为画面质感描述的一部分 |
| **nanobananapro** | 文生图 / 图生图 | 将器材信息作为画面质感描述的一部分 |
| **seedream 5.0** | 文生图 / 图生图 | 支持丰富的摄影风格描述，融入器材+光线+景深综合描述 |

---

## 📦 安装与使用

### 在 KunFlix 中使用

本 Skill 是 [KunFlix](https://github.com/KunLabAI/KunFlix) 平台的配套摄影技能。将 `SKILL.md` 放置到 KunFlix 的 Skills 目录即可启用：

```bash
# 克隆本仓库
git clone https://github.com/KunLabAI/photodesign-skill.git

# 复制 Skill 文件到 KunFlix Skills 目录（中文版）
cp photodesign-skill/skill_zh/SKILL.md <your-kunflix-path>/backend/skills/photography_scene_design/SKILL.md
cp -r photodesign-skill/skill_zh/references <your-kunflix-path>/backend/skills/photography_scene_design/
```

### 在其他 Agent 系统中使用

本 Skill 采用标准 Markdown 格式，可轻松集成到任何支持文档驱动的 Agent 系统：

- **Qoder / Cursor** — 将 `SKILL.md` 作为自定义 Skill 导入
- **其他 Agent 框架** — 将内容作为 System Prompt 或参考文档提供给 Agent

---

## 📂 项目结构

```
photodesign-skill/
├── skill_zh/                            # 中文版
│   ├── SKILL.md                         # 核心 Skill 文件（器材速查 + 案例入口）
│   └── references/
│       ├── full_photography_guide.md    # 完整摄影器材参考手册（25套模板）
│       ├── case_index.md                # 结构化案例索引
│       └── cases_*.md                   # 53套案例配方
├── skill_en/                            # 英文版
│   ├── SKILL.md                         # Core Skill file (equipment quick ref + case entry)
│   └── references/
│       ├── full_photography_guide.md    # Full photography equipment reference (25 templates)
│       ├── case_index.md                # Structured case index
│       └── cases_*.md                   # 53 case recipes
├── LICENSE                              # MIT License
├── README.md                            # 中文说明
└── README_EN.md                         # English README
```

---

## 🚀 快速上手

### Skill 包含内容

| 模块 | 说明 |
|------|------|
| 相机机身速查 | Canon、Nikon、Sony、Fujifilm、Leica、Hasselblad、Phase One、ARRI、RED 等 |
| 镜头品牌速查 | Zeiss、Leica、Canon L、Nikon S、Sony GM、Sigma Art、Voigtlander、Helios 等 |
| 焦距详解 | 14mm-400mm 全焦段适用场景与透视效果 |
| 光圈详解 | f/1.0-f/22 景深控制与焦外风格 |
| 色温详解 | 2000K-8000K+ 色温速查、选择指南与白平衡配合 |
| 光照角度详解 | 0°-180° 光照角度速查、布光模式（伦勃朗、蝶形光、分割光等） |
| 结构化案例库 | 53 套带适用场景、器材、参数（含色温与光照角度）、画面结果、变量和避免项的案例配方 |
| 意图匹配指南 | 根据设计意图快速选定器材组合、色温与光照角度 |

### 示例：从意图到提示词

**意图**：生成一张梦幻氛围的人像特写

**Skill 推荐器材**：Canon EOS R5 + RF 85mm f/1.2L @ f/1.2

**生成提示词**：
```
Shot on Canon EOS R5 with RF 85mm f/1.2L at f/1.2, dreamy close-up portrait 
of a young woman with flowing auburn hair, single eye in critical focus, 
background completely dissolved into large circular bokeh orbs of golden 
afternoon light, natural rim lighting on hair.
```

---

## 🎬 关于 KunFlix

<div align="center">

**🌟 [⭐ KunFlix - AI驱动的影视广告创作平台](https://github.com/KunLabAI/KunFlix) 🌟**

</div>

本 Skill 是 [**KunFlix**](https://github.com/KunLabAI/KunFlix) 开源生态的一部分。KunFlix 是一款专注于影视广告的 AI 内容创作 Agent 平台，将剧本写作、角色设计、视音频生成、资产管理和智能剪辑全链路打通。

### KunFlix 核心特性

| 特性 | 说明 |
|------|------|
| 🎭 无限画布 | 人机协作或由智能体创作，无需人工干预 |
| 🤖 多 Agent 协作 | 对话驱动的多智能体协作，复杂任务化繁为简 |
| 🔧 Skills 系统 | 内置专用 Skills，支持自定义扩展（如本摄影 Skill） |
| 🎨 全链路多模态 | 剧本 → 角色 → 视音频 → 成片的无缝转化 |

👉 **立即体验**：https://github.com/KunLabAI/KunFlix

---

## 🤝 参与贡献

欢迎各种形式的贡献！

- 💬 提交新的器材组合模板
- 🐛 报告问题或建议优化
- 🌍 翻译与本地化
- 📸 补充新模型的适配指南

```
Fork → Branch → Commit → Push → Pull Request
```

---

## 📞 联系我们

| 渠道 | 地址 |
|------|------|
| 📧 邮件 | zack@kunpuai.com |
| 💬 GitHub Issues | [提交问题](https://github.com/KunLabAI/photodesign-skill/issues) |
| 🌟 KunFlix 项目 | [github.com/KunLabAI/KunFlix](https://github.com/KunLabAI/KunFlix) |

---

## 📄 许可证

本项目基于 [AGPL3.0](./LICENSE) 开源。

Copyright © 2026 [KunLabAI](https://github.com/KunLabAI)

---

<div align="center">

Made with ❤️ by [KunpuAI](https://github.com/KunLabAI)

**如果这个 Skill 对你有帮助，请给个 ⭐ Star 支持一下！**

[⭐ Star 本项目](https://github.com/KunLabAI/photodesign-skill) · [🌟 Star KunFlix](https://github.com/KunLabAI/KunFlix)

</div>
