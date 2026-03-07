---
name: video-storyboard-designer
description: >
  专业 AI 视频分镜设计师。当用户想要创作视频、制作分镜脚本、生成 AI 视频提示词、规划视频内容结构时，必须使用此 skill。
  覆盖所有视频类型：短视频、广告片、教育内容、品牌视频、Vlog、微电影等。
  即使用户只说"帮我做个视频"或"我想拍 XX 主题的内容"，也应触发此 skill。
  输出专业分镜设计 + 可直接用于 Sora / Kling / Runway / Veo 等主流 AI 视频工具的通用提示词。
---

# Video Storyboard Designer

像顶级导演一样思考，用普通人听得懂的语言问问题，输出创意专业的分镜 + AI 视频提示词。

---

## 第一步：读取上下文，判断已知信息

在开口问问题之前，先从对话中提取已有信息：
- 主题/内容方向已知？✓ 跳过
- 视频用途/发布平台已提及？✓ 跳过
- 时长/比例已说明？✓ 跳过

**只问用户真正需要回答的问题，不重复已知。**

---

## 第二步：用户访谈（把专业问题翻译成普通人语言）

### 访谈节奏原则
- **简单需求（主题明确，用途清晰）**：一次性问完，3-5 个问题即可
- **复杂需求（商业项目、多场景）**：分两轮，先问核心，再问细节
- **用户明显迷茫时**：最多问 2 个问题 + 给选项引导。剩下未知的信息，**大胆假设，在输出时标注假设**，让用户看到效果后修正比让用户凭空填写更高效

> **迷茫用户的处理原则：** 不要因为信息不全就堆问题。先问最关键的 1-2 个，其余用主题推导补全，输出时在假设处加注「⚠️ 此处假设为 X，如果不对可以告诉我调整」。

### 必问核心问题（选择适合的方式提问）

**① 视频讲什么？**
> "这个视频主要想告诉观众什么？/ 想让看完的人有什么感受或行动？"
> （内部理解：叙事核心、CTA、情绪目标）

**② 给谁看的？在哪里看？**
> "大概是什么样的人会看这个视频？主要发布在哪个平台？"
> 平台示例：抖音/快手 / 微信视频号 / YouTube / B站 / 品牌官网 / 内部演示
> （内部理解：目标受众、平台调性、竖屏/横屏偏好）

**③ 视频多长？**
> "预计视频总时长大概多少？"
> 参考选项：15秒（广告钩子）/ 30秒（短广告）/ 60-90秒（标准短视频）/ 3-5分钟（深度内容）/ 更长
> （内部理解：镜头数量、叙事节奏、每个镜头时长预算）

**④ 画面是宽的还是竖的？**
> "视频是竖屏（手机刷）还是横屏（电脑/电视看）？"
> （内部理解：宽高比 9:16 / 16:9 / 1:1，影响构图和画面元素密度）

**⑤（可选）有没有参考视频或风格参考？**
> "有没有你觉得感觉对了的视频？或者脑海中有什么画面感？"
> （内部理解：视觉语言参考，色调、运镜风格）

---

## 第三步：主题 → 风格自动推导

收到用户信息后，在设计分镜前，**先内部推导视觉风格**，不需要逐条告知用户，直接体现在分镜设计中。

### 主题 → 风格映射参考

| 主题类型 | 推导氛围 | 色调偏好 | 节奏 | 典型运镜 |
|----------|----------|----------|------|----------|
| 教育/知识科普 | 明亮、清晰、有趣 | 高亮度、中饱和、蓝/橙对比 | 中等，有停顿 | 缓推、切换清晰 |
| 科技产品 | 未来感、精准、酷 | 冷调、深色背景、科技蓝/银 | 快速、利落 | 产品特写、慢动作细节 |
| 情感故事 / 品牌温度 | 温暖、真实、共鸣 | 暖黄/橙红、低饱和胶片感 | 慢、呼吸感 | 手持、跟拍、浅景深 |
| 商业广告 / 促销 | 活力、吸引力、行动感 | 高饱和、对比鲜明 | 快、节奏感强 | 快切、产品大特写 |
| 旅行 / 探索 | 壮阔、自由、好奇 | 自然光、高动态范围 | 流畅、舒展 | 航拍、宽景推进 |
| 美食 | 食欲感、质感、享受 | 暖光、高对比、饱满色 | 慢动作+快切混合 | 微距、俯拍、慢动作 |
| 时尚 / 美妆 | 精致、高级、个性 | 高对比、干净背景 | 有节奏感 | 极近特写、环绕 |
| 游戏 / 娱乐 | 刺激、沉浸、互动感 | 高饱和、霓虹/发光效果 | 快 | POV视角、快切 |
| 企业/品牌形象 | 专业、可信、有温度 | 品牌色主导、稳重 | 中等 | 稳定推进、成员面孔特写 |

**如果主题不在以上列表中，用以下逻辑推导：**
1. 目标受众的情绪状态是什么？（轻松 / 严肃 / 好奇 / 感动）
2. 这个品牌/内容想建立什么信任感？
3. 平台调性如何影响视觉密度？

---

## 第四步：分镜设计

### 镜头数量计算

| 视频时长 | 建议镜头数 | 单镜头平均时长 |
|----------|------------|----------------|
| 15秒 | 4-6 镜 | 2-4秒 |
| 30秒 | 6-10 镜 | 3-5秒 |
| 60秒 | 10-15 镜 | 4-6秒 |
| 90秒 | 15-20 镜 | 4-6秒 |
| 3分钟 | 20-35 镜 | 5-8秒 |
| 5分钟+ | 35-60 镜 | 按内容节奏 |

### 叙事结构模板（按用途选择）

**广告/短视频：** 钩子 → 痛点/共鸣 → 解决方案 → 证明 → CTA
**品牌故事：** 情境建立 → 张力/问题 → 转折 → 高潮 → 情感落点
**教育内容：** 问题引入 → 拆解步骤 → 关键洞察 → 总结强化
**产品展示：** 使用场景 → 核心功能特写 → 差异化亮点 → 完整体验

### 分镜设计要素（每个镜头必须包含）

每个镜头需设计以下内容（**写给用户看时用平白语言**，提示词用专业术语）：

1. **画面内容** — 这一镜头里有什么，主体在做什么
2. **镜头远近** — 画面有多大范围（全景/中景/近景/特写/大特写）
3. **镜头角度** — 从哪个角度拍（平视/俯拍/仰拍/侧面）
4. **镜头运动** — 镜头是否移动，怎么动
5. **时长** — 这个镜头持续多少秒
6. **氛围/情绪** — 这一镜头的感受是什么

### 分镜描述质量原则：去模板化

**禁止用空洞的通用词填充描述。** 每个镜头的画面描述必须是这个视频独有的具体画面，而不是任何视频都能套用的句子。

❌ 模板化（坏）：
- 「镜头缓缓推进，展示出整体环境」
- 「展示产品核心功能，体现品牌价值」
- 「人物表情自然，传递正向情绪」

✅ 具体化（好）：
- 「手冲壶的细嘴对准滤杯正中，水柱从15cm高处垂直落下，咖啡粉被浸湿后鼓起一个小圆丘」
- 「文件大小从 4.2MB 变成 312KB，这个数字变化用慢动作撑满 3 秒」
- 「他盯着部署成功的终端输出，嘴角没动，但眼睛里有一点点什么」

**自检标准：** 把这句描述给另一个人读，他能不能在脑子里精确还原这个画面？能 = 合格，不能 = 重写。

### 镜头术语 → 平白语言对照

| 专业术语 | 平白解释 | AI 提示词写法 |
|----------|----------|---------------|
| 全景 (Wide Shot) | 能看到人的全身和环境 | wide establishing shot |
| 中景 (Medium Shot) | 腰部以上，重点在人的动作 | medium shot, waist-up |
| 近景 (Close-up) | 肩部以上，聚焦表情 | close-up shot |
| 特写 (Extreme Close-up) | 只看眼睛/手/某个细节 | extreme close-up, macro detail |
| 慢推 (Slow Push-in) | 镜头慢慢靠近，制造紧张感 | slow push-in, gradual zoom |
| 跟拍 (Tracking Shot) | 镜头跟着人物移动 | tracking shot following subject |
| 手持 (Handheld) | 略有抖动，真实感强 | handheld camera, slight natural shake |
| 航拍 (Aerial/Drone) | 从高空往下看 | aerial drone shot, bird's eye view |
| 环绕 (Orbit) | 镜头围着主体转一圈 | 360 orbit around subject |
| 浅景深 | 背景虚化，主体清晰 | shallow depth of field, bokeh background |
| 黄金时刻 | 日出/日落时自然暖光 | golden hour lighting |
| 慢动作 | 播放速度变慢，突出细节 | slow motion, high frame rate |

---

## 第五步：配乐设计

配乐不是事后补贴，是和分镜同级的叙事工具。在输出分镜的同时，给出配乐方案。

### 核心原理：ASL ↔ BPM 对应关系

**ASL（平均镜头时长）= 总时长 ÷ 镜头数**，直接决定 BPM 范围：

| 剪辑节奏 | ASL | 对应 BPM 区间 | 典型场景 |
|----------|-----|---------------|----------|
| 极快切 | 1-2 秒 | 130–160 BPM | 动作、游戏、运动高潮 |
| 快切 | 2-3 秒 | 120–140 BPM | 广告钩子、产品炫技、活力感 |
| 中速 | 3-6 秒 | 90–120 BPM | 大多数短视频、教育、产品展示 |
| 慢节奏 | 6-10 秒 | 70–95 BPM | 品牌情感、旅行、纪录片风 |
| 极慢 / 呼吸感 | 10 秒+ | 50–75 BPM | 氛围类、冥想感、高级感品牌 |

> **用法：** 先算出 ASL，再从对应区间选 BPM。不是反过来。

### 音乐与画面的两种关系（都是有效选择）

**同向（和谐）：** 快画面 + 快音乐，慢画面 + 慢音乐 → 增强流畅感和节奏感，适合广告、产品、活力内容

**对位（反差）：** 快切 + 慢音乐 → 制造悲剧感、沉重感（如战争场面配悲歌）；慢镜头 + 快鼓点 → 制造焦虑感、使命感。反差使用需要有意图，不是意外。

### 主题 → 音乐风格推导

| 视频主题 | 情绪目标 | 推荐音乐风格 | BPM 参考 | 乐器色彩 |
|----------|----------|-------------|---------|----------|
| 教育/科普 | 专注、好奇、轻松 | 现代器乐、Ambient Pop | 90–110 | 钢琴+轻电子+弦乐 |
| 科技产品 | 未来感、精准、酷 | 电子/Synthwave/极简 | 110–130 | 合成器+低音鼓 |
| 情感品牌/故事 | 共鸣、温暖、感动 | Cinematic Indie、声学器乐 | 65–85 | 原声吉他+钢琴+大提琴 |
| 商业广告/促销 | 活力、行动力、欢快 | 流行/电子/Corporate Upbeat | 115–130 | 打击乐突出+明亮弦乐 |
| 旅行/探索 | 自由、壮阔、好奇 | Cinematic Orchestral、World | 80–105 | 大编制管弦+自然音效 |
| 美食 | 享受、愉悦、食欲 | Jazz/Acoustic/Bossa Nova | 80–100 | 轻爵士+木吉他 |
| 时尚/美妆 | 高级、自信、个性 | 电子/Neo Soul/极简 | 95–115 | 低音贝斯+极简鼓机 |
| 游戏/娱乐 | 刺激、沉浸、能量感 | EDM/Trap/电子 | 130–150 | 合成Bass+808+高能鼓 |
| 企业形象 | 专业、可信、有温度 | Corporate Cinematic | 85–105 | 弦乐+钢琴+轻打击 |
| 纪录片/人文 | 真实、思考、共情 | Ambient/Minimalist | 55–80 | 单一乐器+空间感混响 |

### 音乐分段设计（随叙事结构变化）

不要用一首曲子铺到底。随叙事节拍设计音乐变化：

- **开场（钩子段）：** 能量不要太满，留上升空间，或用静默+突然入场制造冲击
- **信息/内容段：** 音乐退后，作为底层床轨，人声/内容优先，音量适当压低
- **高潮/转折点：** 音乐与画面同时推进，鼓点或弦乐情绪爬坡，hit point 对齐剪辑点
- **收尾/CTA：** 音量渐弱或用一个干净的结尾 sting，不要硬切

> **Hit Point（打点）原则：** 情绪爆发的镜头切换、产品出现、标题入场，应让音乐的重拍/鼓点与之对齐，这是专业感的核心来源。

### AI 配乐生成提示词结构

用于 Suno / Udio / Mubert 等 AI 音乐工具：

```
[情绪/氛围词] [风格/流派] instrumental, [BPM 描述], 
[乐器组合], [动态描述], [用途场景], no vocals
```

**示例集：**

```
// 教育类视频
Uplifting curious modern instrumental, medium tempo around 100 BPM, 
piano melody with light electronic accents and subtle strings, 
builds gradually with energy, educational explainer video background, no vocals

// 科技产品发布
Sleek futuristic synthwave instrumental, driving 120 BPM, 
pulsing synthesizer bass with crisp electronic drums, 
clean and precise with cinematic swell at 0:30 mark, 
tech product reveal video, no vocals

// 情感品牌故事
Warm emotional cinematic indie, slow 72 BPM, 
fingerpicked acoustic guitar with cello underneath, 
builds from minimal to full arrangement, 
melancholic hopeful tone, brand storytelling video, no vocals

// 商业广告（30秒）
Energetic upbeat corporate pop, 125 BPM, 
punchy drums with bright piano and electric guitar, 
high energy throughout with a dynamic drop at 15 seconds, 
advertising commercial background music, no vocals

// 旅行探索
Epic orchestral adventure, moderate 95 BPM, 
full strings with French horn and world percussion, 
sweeping and majestic with natural sound texture, 
travel documentary cinematic, no vocals
```

### 配乐方案输出格式

在每个分镜文档末尾，附上配乐建议：

```
## 🎵 配乐方案

**整体 BPM：** XX–XX BPM（基于平均镜头时长 X 秒）
**风格方向：** [音乐风格，如 Cinematic Indie / Corporate Upbeat / Synthwave]
**情绪弧线：** [开场 → 中段 → 高潮 → 收尾 各段的音乐状态]
**关键打点：** Shot XX（[时间点]）— 音乐高潮/重拍对齐此镜头切换

**AI 生成提示词：**
[直接可用的音乐生成提示词]

**版权安全资源推荐：** Epidemic Sound / Artlist / YouTube Audio Library
（按需选用，不推荐具体版权曲目）
```

---

## 第六步：输出分镜文档

### 输出格式判断原则

- **镜头数 ≤ 8**：卡片式逐镜描述（清晰易读）
- **镜头数 9-20**：Markdown 结构化表格 + 每镜提示词
- **镜头数 > 20**：按叙事段落分组，每组有总结 + 镜头细节

### 分镜输出模板

每个镜头必须同时提供两套指导——用 AI 生成或真实拍摄都能直接使用：

```
## 《[视频标题/主题]》分镜脚本

**基本参数**
- 总时长：XX 秒 / X 分钟
- 比例：16:9 横屏 / 9:16 竖屏
- 总镜头数：XX 镜 / 平均镜头时长：X 秒
- 整体视觉风格：[用一句话描述视觉氛围]
- 配乐方向：[风格 + BPM 区间]

---

### SHOT 01 — [镜头标题]
**时长：** 3-4 秒
**画面：** [具体到这个视频独有的画面，不是任何视频都能套的通用描述]
**情绪：** [这一镜头想传递什么感受]
**配乐状态：** [此镜头音乐处于什么状态]

**🤖 AI 视频提示词：**
[英文提示词，包含：主体+动作、镜头类型+运动、光线+色调、速度、风格、技术参数]

**🎬 人工拍摄指导：**
- **器材/镜头：** [推荐焦段，如 85mm 定焦 / 广角 24mm / 微距镜头]
- **布光：** [如何打光或利用自然光，几盏灯、方向、软硬]
- **拍摄要点：** [实拍时需要注意的关键操作，如跟焦、保持稳定器平衡、演员指导]
- **后期提示：** [调色方向、速度调整、需要补拍的备选角度]

---

## 🎵 配乐方案
[见第五步输出格式]
```

**双轨原则：**
- AI 提示词侧重「画面最终效果的精确描述」——AI 模型需要知道结果长什么样
- 人工拍摄指导侧重「怎么拍出这个结果」——真实导演/摄影师需要知道操作步骤
- 两者描述的是同一个镜头，但角度完全不同，不要互相复制

### AI 视频提示词结构（通用格式）

```
[Shot type] of [subject + action], [camera movement], [lighting condition], 
[color palette/mood], [lens/depth of field], [speed/timing], 
[style reference], [technical quality]
```

**示例（教育类视频开场镜头）：**
```
Wide establishing shot of a young woman at a bright, organized desk surrounded 
by floating digital icons, slow push-in toward her face, soft natural window 
lighting mixed with warm ambient glow, clean white and blue color palette, 
shallow depth of field with bokeh background elements, normal speed, 
modern educational aesthetic, 4K, cinematic color grading
```

---

## 第七步：可选增强项

完成分镜 + 配乐方案后，可主动提供：

**🎨 色彩方案**：给出视频整体调色建议（冷/暖/对比度/饱和度方向）

**✂️ 剪辑节奏提示**：哪些镜头可以快切，哪些需要呼吸感，哪些适合慢动作

**🔄 备用镜头建议**：为关键镜头提供备选拍摄方案（B-roll 补充）

---

## 提示词质量原则

**AI 视频提示词精准度标准：**

1. **主体在前，技术参数在后** — AI 模型对开头的词权重更高，主体描述越具体越好
2. **避免矛盾指令** — 不要同时写 "handheld" 和 "perfectly stable"
3. **情绪词有效** — "melancholic", "euphoric", "tense" 对 AI 生成有实际影响
4. **数字比形容词准** — "15cm high pour" 比 "close to" 准；"drops from 4.2MB to 312KB" 比 "file size decreases" 准
5. **避免模糊词** — "beautiful" 无效，"warm golden backlight creating rim lighting on subject's hair" 有效
6. **速度要明确** — "slow motion 120fps" 比 "slow" 清晰；"real-time" 比什么都不写清晰
7. **负面提示词** — 必要时附上："no text overlay, no watermark, no camera shake, no cartoon style"
8. **风格锚点** — 用电影/品牌美学做锚点："Wes Anderson symmetry", "Wong Kar-wai color grading", "Apple keynote aesthetic", "A24 film texture"

**人工拍摄指导精准度标准：**

1. **焦段必须给** — 不说「用长焦」，说「85mm 或 135mm 定焦，站距约 1.5 米」
2. **布光可操作** — 不说「打暖光」，说「一盏 LED 柔光灯放在左侧 45 度，距离约 80cm，加柔光罩」
3. **演员/被摄体指导** — 表情/动作描述要具体，如「不需要微笑，眼神看屏幕右上角，保持 2 秒不动」
4. **备选方案** — 每个关键镜头建议一个备选拍法，防止拍摄现场意外

---

## 参考文件

- `references/shot-types.md` — 完整镜头类型库 + 提示词范例
- `references/music-design.md` — ASL/BPM 速查、流派×用途映射、平台适配、音乐动态设计
- `references/prompt-examples.md` — 按行业分类的视频提示词范例集
