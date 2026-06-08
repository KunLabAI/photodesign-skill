# Photography Scene Design Skill

> Professional photography equipment & parameter guide for AI image generation, designed for document-driven Agent systems.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Models](https://img.shields.io/badge/Models-GPT--image--2%20%7C%20nanobanana2%20%7C%20nanobananapro%20%7C%20seedream5.0-blue)](#supported-models)
[![KunFlix](https://img.shields.io/badge/Platform-KunFlix-purple)](https://github.com/KunLabAI/KunFlix)

[简体中文](./README.md) | English

---

## 📚 Introduction

**Photography Scene Design Skill** is a professional photography scene design skill that injects real photography equipment parameters into AI image generation. By specifying camera bodies, lens brands, focal lengths, and apertures, it precisely controls image texture, depth of field, perspective, and atmosphere — enhancing the professionalism and realism of character/prop/scene designs.

This Skill is designed for ✨**document-driven Agent systems**✨, enabling AI agents to reference professional photography parameters when calling image generation tools, automatically producing expert-level photography prompts.

### What Can This Skill Do?

- 📷 **Equipment Parameter Injection** — Incorporate real camera, lens, and aperture parameters into prompts to enhance image quality
- 🎬 **Multi-Style Coverage** — From commercial portraits to cinematic, vintage film, macro close-ups, and more
- 🎨 **Smart Intent Matching** — Automatically recommend the best equipment combo based on design intent
- 📝 **Structured Case Library** — 53 searchable photography-grade prompt recipes with replaceable variables

---

## 🤖 Supported Models

This Skill is compatible with the following cutting-edge text-to-image / image-to-image models:

| Model | Type | Equipment Description Integration |
|-------|------|-----------------------------------|
| **GPT-image-2** | Text-to-Image / Image-to-Image | Describe equipment and parameters directly in natural language |
| **nanobanana2** | Text-to-Image / Image-to-Image | Incorporate equipment info as part of image quality description |
| **nanobananapro** | Text-to-Image / Image-to-Image | Incorporate equipment info as part of image quality description |
| **seedream 5.0** | Text-to-Image / Image-to-Image | Rich photography style descriptions with equipment + lighting + DOF combined |

---

## 📦 Installation & Usage

### Using with KunFlix

This Skill is a companion photography skill for the [KunFlix](https://github.com/KunLabAI/KunFlix) platform. Place `SKILL.md` in the KunFlix Skills directory to activate:

```bash
# Clone this repository
git clone https://github.com/KunLabAI/photodesign-skill.git

# Copy Skill files to KunFlix Skills directory (English version)
cp photodesign-skill/skill_en/SKILL.md <your-kunflix-path>/backend/skills/photography_scene_design/SKILL.md
cp -r photodesign-skill/skill_en/references <your-kunflix-path>/backend/skills/photography_scene_design/
```

### Using with Other Agent Systems

This Skill uses standard Markdown format and can be easily integrated into any document-driven Agent system:

- **Qoder / Cursor** — Import `SKILL.md` as a custom Skill
- **Other Agent Frameworks** — Provide the content as System Prompt or reference documentation for your Agent

---

## 📂 Project Structure

```
photodesign-skill/
├── skill_zh/                            # Chinese version
│   ├── SKILL.md                         # Core Skill file (equipment quick ref + case entry)
│   └── references/
│       ├── full_photography_guide.md    # Full photography equipment reference (25 templates)
│       ├── case_index.md                # Structured case index
│       └── cases_*.md                   # 53 case recipes
├── skill_en/                            # English version
│   ├── SKILL.md                         # Core Skill file (equipment quick ref + case entry)
│   └── references/
│       ├── full_photography_guide.md    # Full photography equipment reference (25 templates)
│       ├── case_index.md                # Structured case index
│       └── cases_*.md                   # 53 case recipes
├── LICENSE                              # MIT License
├── README.md                            # 中文说明
└── README_EN.md                         # English README (this file)
```

---

## 🚀 Quick Start

### Skill Contents

| Module | Description |
|--------|-------------|
| Camera Body Reference | Canon, Nikon, Sony, Fujifilm, Leica, Hasselblad, Phase One, ARRI, RED, etc. |
| Lens Brand Reference | Zeiss, Leica, Canon L, Nikon S, Sony GM, Sigma Art, Voigtlander, Helios, etc. |
| Focal Length Guide | Full focal range 14mm-400mm with applicable scenes and perspective effects |
| Aperture Guide | f/1.0-f/22 depth of field control and bokeh styles |
| Structured Case Library | 53 case recipes with applicability, equipment, settings, image result, variables, and avoid notes |
| Intent Matching Guide | Quickly select equipment combos based on design intent |

### Example: From Intent to Prompt

**Intent**: Generate a dreamy atmospheric portrait close-up

**Skill Recommended Equipment**: Canon EOS R5 + RF 85mm f/1.2L @ f/1.2

**Generated Prompt**:
```
Shot on Canon EOS R5 with RF 85mm f/1.2L at f/1.2, dreamy close-up portrait 
of a young woman with flowing auburn hair, single eye in critical focus, 
background completely dissolved into large circular bokeh orbs of golden 
afternoon light, natural rim lighting on hair.
```

---

## 🎬 About KunFlix

<div align="center">

**🌟 [⭐ KunFlix - AI-Driven Film & Advertising Creation Platform](https://github.com/KunLabAI/KunFlix) 🌟**

</div>

This Skill is part of the [**KunFlix**](https://github.com/KunLabAI/KunFlix) open-source ecosystem. KunFlix is an AI content creation Agent platform focused on film and advertising, integrating scriptwriting, character design, video/audio generation, asset management, and intelligent editing into a seamless end-to-end pipeline.

### KunFlix Core Features

| Feature | Description |
|---------|-------------|
| 🎭 Infinite Canvas | Human-AI collaboration or fully autonomous agent creation |
| 🤖 Multi-Agent Collaboration | Conversation-driven multi-agent cooperation for complex tasks |
| 🔧 Skills System | Built-in specialized Skills with custom extension support (like this Photography Skill) |
| 🎨 Full-Pipeline Multimodal | Script → Character → Video/Audio → Final production seamless transformation |

👉 **Try it now**: https://github.com/KunLabAI/KunFlix

---

## 🤝 Contributing

All forms of contributions are welcome!

- 💬 Submit new equipment combo templates
- 🐛 Report issues or suggest improvements
- 🌍 Translation and localization
- 📸 Add adaptation guides for new models

```
Fork → Branch → Commit → Push → Pull Request
```

---

## 📞 Contact

| Channel | Address |
|---------|---------|
| 📧 Email | zack@kunpuai.com |
| 💬 GitHub Issues | [Submit an issue](https://github.com/KunLabAI/photodesign-skill/issues) |
| 🌟 KunFlix Project | [github.com/KunLabAI/KunFlix](https://github.com/KunLabAI/KunFlix) |

---

## 📄 License

This project is open-sourced under the [AGPL3.0](./LICENSE).

Copyright © 2026 [KunLabAI](https://github.com/KunLabAI)

---

<div align="center">

Made with ❤️ by [KunpuAI](https://github.com/KunLabAI)

**If this Skill helps you, please give it a ⭐ Star!**

[⭐ Star this project](https://github.com/KunLabAI/photodesign-skill) · [🌟 Star KunFlix](https://github.com/KunLabAI/KunFlix)

</div>
