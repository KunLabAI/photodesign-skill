---
name: photography-scene-design
description: "专业摄影器材、参数和案例配方指南，用于角色、道具、场景的 AI 图像生成。使用于需要把相机机身、镜头品牌、焦距、光圈、色温、光照角度、布光模式、景深、焦外、胶片或电影镜头质感转写成提示词的任务，适用于 GPT-image-2、nanobanana2、nanobananapro、seedream 5.0 等文生图/图生图模型。"
---

# 摄影场景设计（角色·道具·场景）

**目的**：为AI图像生成注入真实摄影器材参数，通过指定相机机身、镜头品牌、焦距与光圈，精确控制画面质感、景深、透视与氛围，提升角色/道具/场景设计的专业度与真实感。

## 使用场景

- 生成角色立绘、人像写真、时尚摄影
- 道具细节特写、产品摄影
- 场景氛围图、概念设计、环境渲染
- 需要特定摄影器材质感的图像（胶片感、中画幅质感、电影镜头风格等）

## 核心原则

1. **器材服务画面**：选择器材参数是为了实现特定视觉效果，不是堆砌品牌名
2. **参数协调**：焦距、光圈、机身、色温、光照角度五者搭配需合理，避免不可能的组合
3. **一句一器材**：提示词中明确一套器材参数即可，不混用多套
4. **适配模型特性**：针对不同图像模型（GPT-image-2、nanobanana 系列、seedream 5.0），器材描述融入自然语言
5. **优先使用案例配方**：遇到具体生成需求时，先查案例索引选择相近配方，再替换主体、场景、光线、色温和风格变量
6. **色温匹配情绪**：暖色温（2700-3400K）传达亲密温暖，冷色温（6500-7500K）传达疏离清冷，根据画面情绪选择
7. **光照角度塑造立体感**：正面光平柔、侧光立体、逆光梦幻，光照角度决定主体的体积感和氛围

---

## 一、相机机身品牌速查

### 全画幅/中画幅（高画质优先）

| 品牌 | 代表机型 | 画面特征 | 适用场景 |
|------|----------|----------|----------|
| Canon | EOS R5 / R6 Mark II | 肤色讨喜、色彩饱和、暗部纯净 | 人像、时尚、商业摄影 |
| Nikon | Z8 / Z9 | 色彩真实、锐度极高、高动态范围 | 风光、产品、纪实 |
| Sony | A7R V / A7 IV | 高解析力、对焦精准、宽容度大 | 全场景通用、人像、街拍 |
| Fujifilm | GFX 100S / X-T5 | 独特胶片色彩模拟、中画幅质感 | 人文、肖像、胶片风格 |
| Leica | M11 / Q3 | 德味色彩、过渡细腻、氛围独特 | 街拍、人文、艺术摄影 |
| Hasselblad | X2D 100C | 中画幅超高细节、色彩科学顶级 | 时尚、商业广告、精细产品 |
| Phase One | IQ4 150MP | 1.5亿像素、极致细节、色彩精准 | 高端商业、艺术品复制 |

### 电影/视频机身（电影质感）

| 品牌 | 代表机型 | 画面特征 | 适用场景 |
|------|----------|----------|----------|
| ARRI | ALEXA 35 / Mini LF | 自然肤色、电影级宽容度、柔和高光 | 电影感角色、叙事场景 |
| RED | V-RAPTOR / KOMODO | 高分辨率、锐利细节、科技感 | 科幻、动作、高细节场景 |
| Blackmagic | URSA Mini Pro 12K | 高动态范围、Raw色彩空间 | 独立电影、概念场景 |

### 胶片相机（复古质感）

| 品牌 | 代表机型 | 画面特征 | 适用场景 |
|------|----------|----------|----------|
| Contax | T2 / G2 | 蔡司镜头、温暖色调、柔和过渡 | 复古人像、日系写真 |
| Mamiya | RZ67 / 7II | 中画幅胶片、奶油虚化、立体感强 | 肖像、时尚胶片感 |
| Pentax 67 | 6x7 | 大底胶片、景深极浅、影调丰富 | 人像、风光、文艺 |
| Rolleiflex | 2.8F | 双反结构、方画幅、古典韵味 | 古典肖像、街头人文 |

---

## 二、镜头品牌速查

### 顶级光学品牌

| 品牌 | 特征 | 代表镜头 | 适用搭配 |
|------|------|----------|----------|
| Zeiss | 极致锐度、色散控制、3D立体感 | Otus 55/1.4、Milvus 85/1.4 | 高端人像、产品 |
| Leica | 德味渲染、焦外旋转、过渡细腻 | Summilux 50/1.4、Noctilux 75/1.25 | 人文、艺术、氛围 |
| Canon L | 红圈标识、肤色优化、对焦快速 | RF 85/1.2L、RF 50/1.2L | 商业人像、婚礼 |
| Nikon S | 纳米涂层、抗眩光、高解析 | Z 50/1.2S、Z 85/1.2S | 全场景、高锐度需求 |
| Sony GM | 高MTF、极速对焦、轻量化 | FE 85/1.4GM II、FE 50/1.2GM | 人像、运动、街拍 |

### 专业副厂/艺术镜头

| 品牌 | 特征 | 代表镜头 | 适用搭配 |
|------|------|----------|----------|
| Sigma Art | 极高锐度、大光圈、性价比 | 35/1.4 Art、85/1.4 Art | 全场景锐利画质 |
| Voigtlander | 手动对焦、复古焦外、紧凑 | Nokton 50/1.2、40/1.2 | 文艺、街拍、氛围 |
| Helios | 旋转焦外（旋焦）、苏联镜头 | Helios 44-2 58/2 | 梦幻旋焦、复古人像 |
| Petzval | 漩涡焦外、中心锐利边缘柔和 | Lomography Petzval 85/2.2 | 戏剧性肖像、奇幻 |
| Cooke | 电影镜头、Cooke Look柔和渲染 | S7/i 75mm T2.0 | 电影质感、叙事场景 |
| ARRI/Zeiss | Master Prime系列、电影级 | Master Prime 50/T1.3 | 电影布光、专业场景 |

---

## 三、焦距详解

### 焦距与透视关系速查

| 焦距范围 | 类型 | 透视效果 | 角色场景应用 |
|----------|------|----------|--------------|
| 14-20mm | 超广角 | 强烈透视畸变、空间极度夸张 | 建筑内景、环境全貌、压迫感场景 |
| 24-28mm | 广角 | 适度透视、前景突出 | 环境人像、街拍全身、场景氛围 |
| 35mm | 小广角 | 接近人眼、自然不变形 | 纪实、街拍、环境肖像 |
| 50mm | 标准 | 最接近人眼视角、无畸变 | 通用人像、日常场景、产品 |
| 85mm | 中长焦 | 轻微压缩、面部比例最佳 | 人像黄金焦段、半身特写 |
| 105-135mm | 长焦 | 明显压缩、主体突出背景虚化 | 特写肖像、道具细节、情绪渲染 |
| 200-400mm | 超长焦 | 极度压缩、前后景叠加 | 远景人物、空间压缩、梦幻氛围 |
| 100mm Macro | 微距 | 1:1放大、极致细节 | 道具特写、珠宝、微观世界 |

### 焦距选择指南

| 设计目标 | 推荐焦距 | 原因 |
|----------|----------|------|
| 角色全身+环境交代 | 24-35mm | 能容纳环境信息，建立角色与空间关系 |
| 角色半身/四分之三 | 50-85mm | 面部比例自然，景深适中突出主体 |
| 角色面部特写 | 85-135mm | 面部压缩最佳，避免鼻子变形 |
| 道具/饰品细节 | 90-105mm Macro | 放大细节，背景完全虚化 |
| 宏大场景/建筑 | 14-24mm | 视角宽广，建立空间感 |
| 多角色群像 | 35-50mm | 自然透视，多人同框不变形 |

---

## 四、光圈详解

### 光圈与景深关系速查

| 光圈值 | 景深效果 | 画面特征 | 适用场景 |
|--------|----------|----------|----------|
| f/1.0-f/1.2 | 极浅景深 | 仅眼睛锐利，其余全化为奶油焦外 | 极致氛围人像、梦幻特写 |
| f/1.4-f/1.8 | 很浅景深 | 面部锐利，背景大面积虚化 | 标准人像、角色立绘、情绪渲染 |
| f/2.0-f/2.8 | 浅景深 | 上半身锐利，背景柔和分离 | 半身人像、产品摄影、道具特写 |
| f/4.0-f/5.6 | 适中景深 | 全身锐利，背景轻微虚化 | 全身人像、时尚、环境肖像 |
| f/8.0-f/11 | 大景深 | 全画面清晰锐利 | 场景设计、建筑、群像、风光 |
| f/16-f/22 | 极大景深 | 从前景到无穷远全部清晰 | 宏大场景、全景、产品目录 |

### 焦外（Bokeh）风格

| 类型 | 特征 | 来源 |
|------|------|------|
| 奶油焦外 | 过渡平滑无二线性，圆润光斑 | Canon RF 85/1.2L、Sony 85/1.4GM |
| 旋转焦外 | 焦外呈漩涡状旋转 | Helios 44-2、Petzval 85 |
| 硬焦外 | 光斑边缘锐利、有洋葱圈纹 | 反射镜头、部分老镜头 |
| 柔化焦外 | 整体朦胧、梦幻 | 柔焦镜头、Leica Thambar |
| 星芒 | 点光源呈放射状星芒 | 小光圈 f/11-f/16 |

---

## 五、色温详解

### 色温速查表

| 色温值 | 名称 | 视觉效果 | 适用场景 |
|--------|------|----------|----------|
| 2000K | 烛光/火光 | 极暖橙红色调 | 温馨室内、烛光、篝火、复古暖调 |
| 2700-3200K | 钨丝灯/暖白 | 暖黄色调 | 室内暖光、酒吧、复古场景、黄昏室内 |
| 3400K | 摄影钨丝灯 | 暖白色调 | 影棚暖色布光、电影感室内 |
| 4000-4500K | 荧光灯/晨暮光 | 中性偏暖 | 办公场景、清晨/黄昏过渡、自然室内 |
| 5000-5500K | 日光/闪光灯 | 标准白色 | 影棚标准、商业产品、中性肤色还原 |
| 5600K | 日光白平衡 | 自然白色 | 户外日光、标准商业摄影、准确色彩 |
| 6000-6500K | 阴天/阴影 | 微冷色调 | 阴天户外、阴影区域、清冷情绪 |
| 7000-7500K | 阴影/冷调 | 冷蓝白色调 | 雪景、冷调情绪、科幻场景、极地 |
| 8000K+ | 极冷调 | 明显蓝色调 | 极地夜景、超现实冷调、赛博朋克 |

### 色温选择指南

| 设计目标 | 推荐色温 | 原因 |
|----------|----------|------|
| 温暖亲密人像 | 2700-3200K | 暖色营造亲密感，肤色偏暖讨喜 |
| 自然写实肤色 | 5000-5500K | 接近标准日光，肤色还原最准确 |
| 电影叙事暖调 | 3200-3400K | 模拟室内钨丝灯，电影感温暖 |
| 清冷孤独情绪 | 6500-7500K | 冷调传达疏离感、忧郁氛围 |
| 赛博朋克/科幻 | 4000K 混合 7000K+ | 暖冷混合光源制造科技感冲突 |
| 雪景/极地冷调 | 7000-7500K | 强化环境冷感，白色层次分明 |
| 黄金时刻户外 | 3200-4000K | 模拟日落低色温暖光 |
| 商业产品准确色 | 5000-5500K | 中性色温确保色彩无偏移 |

### 色温与白平衡配合

- **匹配光源色温**：将白平衡设为与环境光源一致的色温，获得准确色彩还原
- **刻意偏暖**：白平衡设高于实际光源色温（如日光下设 6500K），画面整体偏暖
- **刻意偏冷**：白平衡设低于实际光源色温（如钨丝灯下设 3200K），画面整体偏冷
- **混合光源**：暖冷光源同时存在时（如室内钨丝灯+窗外日光），选择强调一方，保留另一方色温差营造层次

---

## 六、光照角度详解

### 光照角度速查表

| 角度 | 名称 | 视觉效果 | 适用场景 |
|------|------|----------|----------|
| 0° 正面光 | 平光（Front Light） | 面部均匀照亮、阴影极少 | 美妆特写、证件照、清新高调人像 |
| 15-30° | 蝶形光/蝴蝶光（Butterfly/Paramount） | 鼻下蝶形阴影、颧骨高光突出 | 时尚女性肖像、glamour 风格、复古好莱坞 |
| 30-45° | 伦勃朗光（Rembrandt） | 面颊倒三角光、立体感强烈 | 戏剧人像、电影感肖像、油画质感 |
| 45-60° | 环形光（Loop Lighting） | 鼻影短小不连通、自然立体 | 通用商业人像、自然感肖像、婚纱 |
| 90° 侧光 | 分割光/侧光（Split/Side Light） | 面部明暗对分、雕塑感 | 男性硬朗肖像、低调情绪、产品质感 |
| 120-135° | 侧逆光/轮廓光（Rim/Back-Side） | 边缘轮廓光勾勒、正面偏暗 | 发丝光、主体与背景分离、氛围肖像 |
| 180° 逆光 | 逆光（Backlight） | 主体边缘光晕、正面需补光 | 剪影、梦幻光晕、透光材质、逆光人像 |
| 顶部光 | 顶光（Top Light） | 眼窝深影、下方阴影重 | 正午户外、舞台顶光、戏剧压迫感 |
| 底部光 | 底光（Under Light） | 不自然、恐怖感 | 恐怖题材、戏剧效果、特殊照明 |

### 光照角度选择指南

| 设计目标 | 推荐角度 | 原因 |
|----------|----------|------|
| 柔美无瑕美妆 | 0° 正面光 + 大柔光 | 均匀照明消除瑕疵，皮肤干净 |
| 时尚魅力肖像 | 15-30° 蝶形光 | 颧骨高光立体，鼻影优雅 |
| 电影叙事立体感 | 30-45° 伦勃朗光 | 面部三角光创造戏剧深度 |
| 自然通用商业 | 45-60° 环形光 | 立体但不极端，适用面广 |
| 硬朗男性/反英雄 | 90° 侧光 | 明暗分割强化骨骼和质感 |
| 发丝轮廓分离 | 120-135° 侧逆光 | 轮廓光将主体从背景剥离 |
| 梦幻逆光氛围 | 180° 逆光 | 光晕、透光感、浪漫氛围 |
| 产品材质质感 | 45-90° 侧光/侧逆光 | 斜射光突显表面纹理和浮雕 |

### 布光模式速查

| 布光模式 | 构成 | 适用场景 |
|----------|------|----------|
| 三点布光 | 主光 + 辅光 + 轮廓光 | 通用商业、人像、产品 |
| 伦勃朗布光 | 45°主光 + 弱补光 | 戏剧人像、电影感 |
| 蝶形光 | 正高位主光 + 下方反光 | 时尚、glamour、美妆 |
| 分割布光 | 90°单侧主光 | 男性肖像、低调情绪 |
| 蛤壳光 | 上方主光 + 下方反光板 | 美妆、护肤、柔和无瑕 |
| 全暗调 | 单光源无补光 | 低调肖像、黑色背景产品 |

---

## 七、提示词模板库

### 角色设计——人像特写
```
Shot on Canon EOS R5 with RF 85mm f/1.2L USM at f/1.4, 3200K warm color temperature, 45° loop lighting, a young woman with silver hair gazes into the lens, soft window light illuminating her face, extremely shallow depth of field with creamy bokeh dissolving the background into warm golden tones, skin texture and iris details rendered with exceptional clarity.
```

### 角色设计——全身立绘
```
Captured with Sony A7R V and Sigma 35mm f/1.4 Art at f/2.8, mixed 4000K/7000K neon color temperature, 135° side-back rim lighting, a cyberpunk warrior stands in a rain-soaked neon alley, full body visible from head to boots, ambient neon reflections on wet surfaces, medium depth of field keeping the character sharp while the background glows with colorful bokeh.
```

### 角色设计——电影感肖像
```
Filmed on ARRI ALEXA 35 with Cooke S7/i 75mm T2.0, 3200K warm practical color temperature, 120° Rembrandt lighting, cinematic portrait of a detective in a dimly lit office, warm practical lighting from a desk lamp, the Cooke Look rendering skin with gentle halation and smooth tonal transitions, shallow depth of field isolating the subject from the noir background.
```

### 道具设计——细节特写
```
Shot on Hasselblad X2D 100C with Zeiss Otus 100mm Macro at f/4, 5500K studio color temperature, 120° rim lighting, extreme close-up of an ornate mechanical pocket watch, every gear tooth and engraving rendered in extraordinary detail, dark velvet background completely dissolved into pure black, studio rim lighting accentuating metallic textures.
```

### 场景设计——宏大环境
```
Captured with Nikon Z8 and Nikkor Z 14-24mm f/2.8S at 16mm f/8, 4000K twilight color temperature, 15° low-angle sunlight, a vast cyberpunk cityscape at twilight, towering megastructures receding into atmospheric haze, deep depth of field rendering every architectural detail from foreground market stalls to distant skyscrapers, dramatic perspective lines converging at the horizon.
```

### 场景设计——氛围内景
```
Shot on Fujifilm GFX 100S with GF 80mm f/1.7 at f/2.0, 3400K warm golden-hour color temperature, 45° side window light, a quiet Japanese tea room in late afternoon, golden hour light streaming through shoji screens, medium format rendering delivering exceptional tonal gradation and three-dimensionality, gentle bokeh on background elements.
```

### 复古胶片——角色写真
```
Shot on Contax T2 with Zeiss Sonnar 38mm f/2.8, 4000K warm daylight color temperature, 60° natural available light, Kodak Portra 400 film, a woman in a summer dress walking through a sunlit garden, characteristic warm color palette with soft highlight rolloff, natural film grain adding organic texture, the timeless Contax rendering style.
```

### 产品/道具——商业级
```
Photographed with Phase One IQ4 150MP and Schneider 120mm LS f/4 Macro, 5500K studio standard color temperature, 90° side lighting, a luxury perfume bottle on reflective black acrylic surface, 150 megapixel resolution capturing every crystal facet and light refraction, controlled studio lighting with precise specular highlights, absolute color accuracy.
```

---

## 八、快速意图匹配指南

| 设计意图 | 推荐器材组合 | 推荐色温 | 推荐光照角度 |
|----------|--------------|----------|--------------|
| 梦幻人像/氛围感 | Canon R5 + RF 85/1.2L @ f/1.2 | 3200K 暖 | 180° 逆光或 45° 环形光 |
| 锐利角色立绘 | Sony A7RV + 85GM II @ f/1.8 | 5500K 标准 | 45° 环形光 |
| 电影叙事感 | ARRI ALEXA 35 + Cooke 75mm T2.0 | 3200K 暖 | 30-45° 伦勃朗光 |
| 胶片复古风 | Contax T2 / Mamiya RZ67 + Portra 400 | 4000K 暖白 | 60° 自然光 |
| 道具微距细节 | Hasselblad X2D + Zeiss 100mm Macro | 5500K 标准 | 120° 侧逆光 |
| 宏大场景 | Nikon Z8 + 14-24/2.8S @ f/8 | 4000K 暮光 | 15° 低角度日光 |
| 德味人文 | Leica M11 + Summilux 50/1.4 | 5000K 日光 | 45-60° 自然侧光 |
| 日系清新 | Fujifilm X-T5 + 56/1.2 (Classic Chrome) | 5500K 日光 | 45° 窗光 |
| 科幻/高科技 | RED V-RAPTOR + Sigma 35 Art | 4000K/7000K 混合 | 90° 顶光+侧光 |
| 奇幻/戏剧性 | Petzval 85/2.2（旋涡焦外） | 3200K 暖 | 180° 舞台逆光 |

---

## 九、与图像模型集成方式

在生成提示词时融入器材参数：

1. **GPT-image-2**：直接在提示词中以自然语言描述器材和参数
   - 示例：`Photo taken with a Canon EOS R5, 85mm f/1.2 lens, shallow depth of field, creamy bokeh background`

2. **nanobanana 2.0 / nanobanana pro**：将器材信息作为画面质感描述的一部分
   - 示例：`shot on Hasselblad medium format, 80mm lens at f/2, cinematic lighting, ultra-detailed skin texture`

3. **seedream 5.0**：适合把摄影风格关键词、器材、布光和景深合并成完整画质描述
   - 示例：`professional photography, Canon EOS R5, 85mm f/1.2L lens, f/1.4 aperture, 3200K warm color temperature, 45° loop lighting, natural window light, extremely shallow depth of field, creamy bokeh, warm golden tones, high detail skin texture`

4. **通用格式**：`[器材信息] + [色温] + [光照角度] + [主体描述] + [光线环境] + [景深/焦外描述]`

### 注意事项

- 器材参数为画质提示，模型不会真的模拟光学物理，但能引导风格方向
- 可组合使用本技能与「电影镜头语言」技能，前者控制静态画质，后者控制动态运镜
- 光圈值与焦距搭配需合理：超广角 f/1.2 镜头现实中极少存在
- 案例配方中的主体、职业、材质和场景都可替换；优先保留器材、焦距、光圈和画面结果之间的关系

---

## 参考资料与案例库

上方速查表提供快速选型。每种器材组合的**详细参数说明**和**可直接使用的完整提示词模板**，请参阅：

👉 [摄影器材完整参考手册](./references/full_photography_guide.md)

需要根据意图快速挑选案例时，先阅读：

👉 [结构化案例索引](./references/case_index.md)

使用方式：
1. 从速查表或案例索引中根据设计意图选定器材组合
2. 打开对应案例文件，读取适用、画面结果、可替换变量和避免项
3. 根据具体角色/道具/场景需求微调后融入生成提示词
