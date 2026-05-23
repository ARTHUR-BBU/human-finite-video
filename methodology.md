---
name: human-finite-video
description: "人类有限视频方法论 — 让AI视频从'无限电影'变成'有限的人拍的真实瞬间'。五维有限性注入：不完美、延迟、犹豫、被污染、留白。核心公式：真实感=有限性留下的痕迹。"
version: 1.0.0
metadata:
  hermes:
    tags: [ai-video, human-traces, finiteness, prompt-engineering, methodology]
    category: creative
  related_skills:
    - ai-video-director
    - weight-thinking
---

# 人类有限视频 — Skill

让AI视频从"无限电影"变成"有限的人拍的真实瞬间"。

## When to Use

- 用户在做AI视频（Seedance/Kling/Veo/Sora/Runway）时想要"人味"而不只是"好看"
- 用户的AI视频被反馈"太假""塑料感""不像人拍的"
- 用户要写视频Prompt时，想让镜头背后有一个"人"
- 用户在讨论AI视频真实感、工业化AI视频制作
- 用户提到"纪录片感""手持感""真人感"但又说不清到底缺什么
- 用户在做AI视频内容创作（X/YouTube）需要这个方法论框架
- **用户拿来一个已有的视频Prompt，想升级成带人味的版本**
- **用户提供了一段影视脚本/剧本片段，想改编成人类有限视频版本**
- **用户说"帮我把这个Prompt改得更有纪录片感/更真/更像人拍的"**
- **用户有剧本场景描述，想转成AI视频生成用的Prompt**
- **用户要生成AI视频的关键帧/参考图（seed image），需要带人味的图片Prompt**
- **用户有一张已有的关键帧图/Prompt，想修复成更像人拍的效果**
- **用户在做AI视频工作流（先用图生视频），想让起始帧就具备有限性**
- **用户说"帮我调一下这张参考图/关键帧"**

## 三种工作模式

本 skill 支持三种模式，根据用户输入自动判断：

| 模式 | 触发条件 | 产出 |
|------|---------|------|
| **A. 从零生成** | 用户描述一个场景/概念，没有现成素材 | 完整的人类有限视频Prompt |
| **B. 改编已有Prompt** | 用户提供了一个已有的AI视频Prompt | 升级版Prompt（注入有限性+观察者） |
| **C. 改编脚本/剧本** | 用户提供影视脚本、剧本片段、分镜描述、场景描写 | 转译为AI视频Prompt（注入有限性+观察者+镜头语言）|
| **D. 关键帧（图）** | 用户要生成或修复AI视频用的关键帧/参考图Prompt | 带有限性痕迹的图片Prompt（作为视频的种子帧）|

## 核心公式

```
真实感 = 有限性留下的痕迹
```

AI越追求无限，越像梦。人类越暴露有限，越像现实。

AI的破绽不是不够强，而是太不受限制。

## 核心判断

1. AI视频的问题不是"不够真实"，而是缺少"镜头背后的人类痕迹"
2. AI在"生成"画面，人类在"观察"世界——这个鸿沟极大
3. 手持抖动只是浅层，真正重要的是"镜头为什么会那样动"——注意力漂移和判断痕迹
4. 观察者即媒介：观察者的状态本身就是内容的一部分

## 五维有限性框架

每次生成或优化AI视频Prompt时，必须检查这五个维度是否被注入：

### 1. 不完美（Imperfection）— 设备有限、环境有限

不是粗制滥造，是**有逻辑的缺陷**：
- 逆光导致脸部对比度略微下降
- 玻璃反射让眼镜片有一瞬间看不清
- 对焦先落在前景肩膀，再慢慢回到人物脸
- 皮肤保留毛孔、细纹、疲态
- 背景不是完美虚化，有一些说不清的杂乱

**Prompt注入关键词**：`natural skin texture`, `slight backlight overexposure`, `imperfect focus pull`, `realistic glass reflection`, `unpolished background detail`

**绝对禁止**：`cinematic`, `8K`, `masterpiece`, `ultra realistic`, `perfect` — 这些词越堆越推向塑料高级感

### 2. 延迟（Latency）— 神经有限、理解有限

延迟不是慢，是身体层面的传导时间差：
- 人听到话→理解→被击中→脸上出现反应，中间有真实时间差
- 半秒后眼神才开始变，又过半秒笑容才消失
- 观众在这个过程中会紧张——因为看到"理解正在发生"

**Prompt注入策略**：
- 在Timeline Blocks里加入微小的"处理时间"：`0.3s pause before reaction`, `delayed blink`
- 动作分解：不是一步到位，而是先眼神→停顿→嘴角→身体
- 不要让角色反应"准时"——准时到像程序就是破绽

### 3. 犹豫（Hesitation）— 注意力有限、经验有限

犹豫是意识层面的不确定（和延迟不同，延迟是身体层面）：
- 摄影师发现表情有意思：先慢半拍，推过去时稍微过头，又轻轻修回来
- 镜头在"找"——先落到咖啡杯、手、玻璃反光，随后才回到说话者脸上
- 这种"找不到重点"恰恰是人类感知的真实状态

**Prompt注入策略**：
- 镜头运动加入轻微overshoot和correction：`camera slightly overshoots then gently corrects`
- 对焦路径设计：`focus wanders briefly to hands/coffee cup before settling on eyes`
- 避免镜头一步到位找到完美构图

### 4. 被污染（Contamination）— 空间有限、现场不可控

世界不服务于主角——这是最大架构级缺陷：
- 窗外车经过，反光扫过玻璃，画面亮了一下
- 前景有人身体微动，挡住画面一角
- 过肩镜头的肩膀是物理障碍，不是构图元素
- 空调吹得纸轻轻翘起
- 隔壁有人倒水的声音

**Prompt注入策略**：
- 主动加入"世界自运行"元素：`occasional window reflection from passing car`, `background activity continues naturally`
- 前景遮挡：`partial obstruction from interviewer's shoulder`, `narrow shooting position`
- 环境干扰：`ambient HVAC hum`, `natural light fluctuation from clouds`

### 5. 留白（Negative Space）— 语言有限、表达有限

AI剪辑最常犯的错：太急。说完话立刻切，表情出现立刻给特写：
- 一句话说完后的沉默才是情绪真正发生的地方
- 一个人转身之前的迟疑
- 镜头没马上走，继续看那个人重新把自己收拾好

**Prompt注入策略**：
- Timeline末尾加入沉默块：`hold 0.7s after speech ends`, `let moment breathe`
- 不要把每个情绪都表达完整——留"没说完"的空间
- `preserve the silence`, `don't cut immediately`, `let expression fade naturally`

## 观察者身份定义（核心新增层）

这是本方法论最重要的新增：**定义镜头背后的人**。

每次生成Prompt前，必须先回答：

```
镜头背后的人是谁？
- 身份：纪录片摄影师？手机路人？疲惫的记者？紧张的新人？
- 状态：从容的？紧张的？好奇的？不耐烦的？被吸引的？
- 物理位置：站在哪里？被什么限制？能移动多少？
- 注意力模式：在找什么？被什么吸引？什么时候会反应？
- 经验水平：老手（克制、精准但有人味）还是新手（笨拙但真诚）？
```

这些答案会决定：
- 镜头运动的幅度和节奏
- 对焦的路径和迟疑程度
- 构图的"错误"类型
- 留白的长度
- 被污染的程度

## Prompt生成流程

### Step 1: 定义观察者（必做）

```
Who is behind the camera?
→ 身份 + 状态 + 物理限制 + 注意力模式 + 经验水平
```

### Step 2: 场景有限性分析

```
这个场景里，人的身体/设备/空间/时间/注意力各被什么限制？
→ 列出具体限制条件
```

### Step 3: 五维检查

```
□ 不完美：画面里有没有有逻辑的缺陷？
□ 延迟：反应有没有身体传导的时间差？
□ 犹豫：镜头/人物有没有找不到重点的瞬间？
□ 被污染：世界有没有不配合主角的元素？
□ 留白：有没有情绪还没被说完的沉默时间？
```

### Step 4: 注入到Prompt结构

参考 ai-video-director 的10层框架，但升级：
- Layer 2 (Reality Goal)：加入"镜头背后是什么人"
- Layer 3 (Camera System)：镜头运动有心理动机
- Layer 7 (Timeline Blocks)：注入延迟和留白的时间块
- Layer 9 (Negative Constraints)：不只禁止AI化，主动注入有限性痕迹
- **新增 Layer 11 (Observer Identity)**：观察者身份层

### Step 5: 输出Prompt

## Mode B：改编已有Prompt

当用户提供了一个现成的AI视频Prompt（无论是自己写的、ChatGPT生成的、还是从别处拿来的），执行以下流程：

### Step B1：诊断原始Prompt

逐项检查原始Prompt的问题：

```
诊断清单：
□ 是否包含"cinematic/8K/masterpiece/ultra realistic"？→ 标记为"塑料高级感词"，必须删除
□ 镜头运动是否有心理动机？→ 没有=机械运镜，需要加观察者
□ 世界是否为主角服务？→ 光为主打/背景为主虚/路人为让路=无限电影，需要注入世界惯性
□ 反应是否太准时？→ 瞬间反应=程序感，需要加延迟
□ 剪辑是否太急？→ 每个情绪都表达完整=没有余味，需要加留白
□ 有没有"有逻辑的缺陷"？→ 没有任何不完美=无菌感，需要注入有限痕迹
□ 有没有前景遮挡/空间限制？→ 完美构图=上帝视角，需要物理限制
```

### Step B2：确定升级策略

根据诊断结果，选择主导注入维度（不要五个全上）：

| 原始Prompt类型 | 主导注入维度 | 原因 |
|---------------|------------|------|
| 产品广告/商业片 | 被污染 + 不完美 | 广告最缺"世界不配合"和"有逻辑的缺陷" |
| 访谈/对话/纪录片 | 犹豫 + 延迟 + 留白 | 人物互动最需要反应时间和沉默空间 |
| 动作/运动/体育 | 延迟 + 被污染 | 动作片最缺身体传导延迟和环境干扰 |
| 风景/空镜 | 被污染 + 不完美 | 风景最缺"有人在这里拍"的痕迹 |
| 剧情短片 | 犹豫 + 留白 + 延迟 | 剧情最需要情绪的"慢慢渗出来" |
| MV/舞蹈 | 被污染 + 不完美 | MV最缺现场感和设备限制 |

### Step B3：定义观察者

即使用户没要求，也必须推断一个合理的观察者：

```
从原始Prompt推断：
- 场景类型 → 观察者身份（办公室→同事/会议记录者/纪录片摄影师）
- 氛围 → 观察者状态（正式→克制/随意→放松/紧张→警觉）
- 构图暗示 → 观察者位置（远景→远距离旁观/中景→参与者距离/特写→亲密/入侵）
```

### Step B4：执行改编

对原始Prompt逐部分改造：

1. **删除所有塑料高级感词**：cinematic, 8K, masterpiece, ultra realistic, perfect, pristine, flawless
2. **替换为有限性等价词**：
   - `cinematic lighting` → `natural available lighting with slight imperfection`
   - `ultra realistic` → `documentary-real, captured by a real person`
   - `perfect focus` → `focus with brief hesitation before settling`
   - `smooth camera` → `handheld with observer's breathing rhythm`
3. **注入OBSERVER层**（加在开头）
4. **改造TIMELINE**：在关键情绪点注入延迟和留白
5. **注入WORLD CONTAMINATION层**
6. **升级NEGATIVE CONSTRAINTS**
7. **保留原始Prompt的有效内容**（场景、人物、动作描述不删不改，只升级控制层）

### Step B5：对比输出

输出格式：
```
--- 原始Prompt ---
[用户提供的原始]

--- 诊断 ---
[发现了什么问题]

--- 升级版Prompt ---
[改编后的人类有限视频版]

--- 改动说明 ---
[逐项列出改了什么、为什么改]
```

## Mode C：改编脚本/剧本

当用户提供影视脚本、剧本片段、分镜描述、小说场景描写等叙事性文本时，执行以下流程：

### Step C1：拆解原始文本

从叙事文本中提取视频生成所需的元素：

```
提取清单：
□ 场景：在哪里？什么空间？什么光线？
□ 人物：谁？什么状态？什么关系？
□ 动作：发生了什么？先后顺序？
□ 情绪：情感弧线？转折点？
□ 对话：有没有说出口的话？
□ 潜台词：没说出来的东西是什么？（这是留白的素材来源）
```

### Step C2：确定视频化策略

脚本和视频是不同的语言，需要"翻译"：

| 脚本元素 | 翻译为视频语言 |
|---------|--------------|
| "他感到震惊" | 不直接拍震惊→拍延迟的反应：先没反应→0.5s后眼神变→再0.3s后身体才有动作 |
| "她犹豫了" | 镜头先到别处（手、桌面、窗）再慢慢回到她的脸，对焦迟疑 |
| "气氛紧张" | 不用音乐渲染→用留白：话说完后0.7s沉默，只有环境音 |
| "阳光明媚" | 不写sunny→写自然光的缺陷：过曝、窗影晃动、云层偶尔遮住 |
| "他走近" | 不是smooth dolly→是观察者身体前倾导致的微小Z轴位移 |
| "她笑了" | 不是标准笑容→先嘴角动→停一下→眼睛才跟上（延迟的笑更真实） |
| "两人对视" | 不是正反打→是观察者在两人之间犹豫不知道看谁好，镜头在找 |
| "背景是咖啡馆" | 不写coffee shop→写世界的自运行：咖啡机声、服务员走动、窗外行人 |
| 内心独白 | 不能直接念→用留白+微表情+手部动作让观众自己读到 |

### Step C3：定义观察者

脚本是"全知叙事"，但视频必须是"有限观察"。需要主动选择一个视角：

```
选择策略：
- 脚本有明确的"谁在看" → 用那个角色的视角
- 脚本没有明确视角 → 创造一个合理的在场观察者
- 脚本是客观叙事 → 选择"纪录片摄影师"作为默认观察者
- 脚本有情绪基调 → 匹配观察者状态（紧张的场景=紧张的摄影师）
```

### Step C4：构建Timeline

把叙事的时间线转化为视频的时间块：

```
原则：
1. 脚本里的每个情绪转折点 → 必须有延迟反应时间（不早于0.3s）
2. 脚本里的每个"重要的话" → 话说完后必须有留白（0.5-1s）
3. 脚本里的每个"沉默" → 是最重要的时刻，镜头不能走
4. 脚本里的环境描写 → 全部变成世界污染素材
5. 脚本里的"内心活动" → 翻译为微表情+延迟，不翻译为旁白
```

### Step C5：输出

输出格式：
```
--- 原始脚本 ---
[用户提供的文本]

--- 视频化分析 ---
[提取的场景/人物/动作/情绪/潜台词]

--- 观察者设定 ---
[推断或选择的观察者身份]

--- 人类有限视频Prompt ---
[完整的视频生成Prompt，含OBSERVER/CAMERA/WORLD CONTAMINATION/TIMELINE/NEGATIVE]

--- 脚本→视频翻译说明 ---
[逐条解释：这个情绪怎么翻译、那个动作怎么延迟、环境怎么变污染]
```

### Mode C 特殊场景处理

**对话场景**（最常见的脚本类型）：
- 不要让两个人都完整说出台词→AI视频吃不下长对话
- 只保留最后一句关键台词→前面的用情绪铺垫代替
- 镜头在两人之间犹豫→不是正反打，是观察者"不知道该看谁"
- 说话者的微动作比台词更重要→手指、眼神、嘴唇

**动作场景**：
- 不要写"激烈的打斗"→分解为具体动作块+每个块的物理反应
- 身体的延迟：被打后不是立刻飞出去→先停顿→再反应
- 镜头跟不上动作→这是好事，让镜头晚半拍到（犹豫的观察者）

**情绪场景**（哭/笑/震惊/释然）：
- 绝对不要让情绪完整表达→永远留30%没说完
- 反应前必须有空白时间→"理解正在发生"
- 眼睛比嘴巴重要→嘴可能伪装，眼睛不会
- 手比脸更能暴露情绪→手指摩挲、握紧、松开

**群戏场景**：
- 不要让所有背景演员完美配合→他们各有各的事
- 背景人物的自运行就是最好的世界污染
- 镜头被人群限制→只能从缝隙中拍→这就是有限性

## Mode D：关键帧（图）Prompt构建与修复

AI视频工作流通常是：先生成关键帧图片（seed image / reference frame），再用图生视频（img2vid）。如果起始帧就是"无限电影"风格，后面视频怎么加人味都打折扣。**有限性必须从种子帧就开始注入。**

### 关键帧 vs 视频Prompt的区别

| 维度 | 视频Prompt | 关键帧Prompt |
|------|-----------|-------------|
| 时间性 | 有Timeline，可以表现延迟/留白 | 只有单帧，延迟和留白要用"痕迹"暗示 |
| 运动暗示 | 可以写镜头运动 | 通过模糊/残影/对焦状态暗示"刚动过"或"正在动" |
| 犹豫表现 | 镜头overshoot+correction | 通过不完全居中的构图、轻微倾斜暗示 |
| 被污染 | 世界在后续帧自运行 | 单帧内必须有污染元素存在 |
| 留白 | 沉默时间 | 构图里的负空间、未完成的眼神、没关上的门 |

### Step D1：判断是生成还是修复

```
用户输入判断：
- "帮我生成一个关键帧" / "我要一张参考图" → Mode D-Generate
- "帮我改一下这个关键帧" / "这张图太假了" / 用户给了一个图片Prompt → Mode D-Fix
```

### Step D2：关键帧五维注入

五维有限性在单帧图片中的具体表现：

#### 1. 不完美 — 图片版

```
必须包含的视觉元素：
- 皮肤：毛孔、细纹、不对称、疲态、出油、干裂（不是磨皮后的塑料）
- 光线：轻微过曝区域、色温不均匀、窗影、灯影
- 环境：桌面杂物、没对齐的物品、使用痕迹、水渍、灰尘
- 镜头：轻微色散、边缘暗角、不是完美锐利、景深过渡自然

Prompt关键词：
`natural skin texture with visible pores`, `uneven lighting from window`, 
`slight chromatic aberration at edges`, `lens vignetting`, 
`lived-in environment with daily clutter`, `water ring on table`

绝对禁止：
`flawless skin`, `perfect lighting`, `pristine`, `studio quality`, 
`professional color grading`, `airbrushed`
```

#### 2. 延迟 — 图片版（用痕迹暗示时间）

```
延迟在单帧中表现为"动作正在发生但还没完成"：
- 人物：眼神比身体慢半拍（身体已经转向但眼睛还留在原处）
- 手部：动作中间态（手正在放下杯子但还没完全放下）
- 表情：情绪正在到达但还没到位（嘴角开始动但笑还没完成）
- 对焦：正在从A点到B点的过程中（前一个焦点在虚，新焦点还没实）

Prompt关键词：
`mid-action freeze`, `expression in transition`, `gaze not yet aligned with body`, 
`focus mid-pull between foreground and subject`, `reaction still arriving`
```

#### 3. 犹豫 — 图片版（用构图暗示判断过程）

```
犹豫在单帧中表现为"构图不是一步到位"：
- 主体不在画面中心（偏左或偏右，像摄影师在犹豫要不要居中）
- 轻微倾斜（不是故意 Dutch angle，是手持的自然歪斜1-3度）
- 部分裁切（头顶或下巴被裁掉一点，像"还没来得及调好"）
- 注意力锚点不明确（画面里有多个看点，没有明确的视觉引导线）

Prompt关键词：
`slightly off-center composition`, `natural handheld tilt of 2 degrees`, 
`subject partially cropped at frame edge`, `unresolved framing`, 
`multiple attention points competing in frame`
```

#### 4. 被污染 — 图片版（单帧内的世界存在）

```
被污染在单帧中表现为"世界在这个瞬间仍然在运行"：
- 窗外：有东西在发生（车、人、鸟、云）
- 前景：有遮挡物（肩膀、门框、植物、别人的手）
- 反射面：玻璃/镜子/桌面反射出画面外的东西
- 环境痕迹：空调出风口的飘带、被风吹动的纸、不完全静止的物体

Prompt关键词：
`reflection in glass showing activity outside frame`, 
`foreground shoulder partially blocking view`, 
`wind-blown paper on desk`, `passing car reflection in window`, 
`environment continuing its own rhythm`
```

#### 5. 留白 — 图片版（未完成的情绪）

```
留白在单帧中表现为"情绪没有被完整表达"：
- 眼神：看向画面外（没看镜头也没看画面内的任何东西，在看"别处"）
- 表情：介于两种情绪之间（不是笑也不是不笑，正在从一种过渡到另一种）
- 空间：画面里有大量"没用"的空间（空的椅子、没关的门、空走廊）
- 沉默感：画面让人感觉"声音刚消失"或"声音还没开始"

Prompt关键词：
`gaze directed outside frame`, `expression suspended between emotions`, 
`empty space that suggests absence`, `the silence after a sentence`, 
`door left slightly ajar`, `unread letter on the table`
```

### Step D3：关键帧Prompt模板

#### 模板D-1：人物关键帧

```
A photographic still frame from [视频类型]. Not a portrait. Not a headshot.
Shot by a [观察者身份] with [设备类型].

OBSERVER PRESENCE:
- Camera position: [物理位置，暗示受限]
- Framing: [slightly off-center / partial crop / natural handheld feel]
- Focus state: [mid-pull / settled on X after hesitating / breathing]

SUBJECT:
[人物描述 — 保留真实皮肤纹理、不对称、疲态、衣服的自然褶皱和穿戴痕迹]

MOMENT IN TIME:
[动作中间态] — not before, not after, but during.
Expression is [in transition / suspended / still arriving].
Gaze is [directed slightly away / caught mid-shift / focused on something outside frame].

ENVIRONMENT AS WITNESS:
- [污染元素1: 窗外反射/前景遮挡/环境痕迹]
- [污染元素2: 桌面杂物/没整理的物品/使用痕迹]
- [污染元素3: 不完美的光线/色温不均/过曝区域]

TECHNICAL REALITY:
Natural [light source] with [缺陷: overexposure / uneven color temp / shadow cast].
Lens shows [vignetting / slight softness at edges / chromatic aberration].
No retouching. No studio lighting. No color grade.
This is a frame that was captured, not composed.

NEGATIVE: No perfect skin. No studio quality. No cinematic grading. 
No pristine environment. No centered subject. No sharp throughout.
No posed expression. No controlled lighting.

GOAL: A frame that feels like it was pulled from real footage — 
not a photograph that was taken, but a moment that was caught.
```

#### 模板D-2：场景/空镜关键帧

```
A photographic establishing frame from [视频类型]. Not a real estate photo.
Shot by a [观察者身份] positioned [受限位置].

OBSIVER PRESENCE:
- The camera is [物理限制: squeezed in corner / through a doorway / partially blocked by furniture]
- The frame includes [intrusion: edge of a coat / someone's shoulder / a plant leaf]
- Composition is [slightly tilted / off-balance / searching]

SCENE:
[场景描述 — 强调使用痕迹和生活感，不是样板间]

LIVING WORLD:
- [世界自运行元素1: 水杯里的水有涟漪/纸被吹动/窗帘在动]
- [世界自运行元素2: 窗外有模糊的活动/灯光有微小变化]
- [时间痕迹: 灰尘在光柱里/使用过的物品/没关上的抽屉]

LIGHTING:
Natural [light source]. [自然缺陷]. Not set up.
The light falls where it falls. Shadows exist where they shouldn't for a "good" photo.
There's a [hot spot / dark corner / flare] that a DP would eliminate but a real person couldn't.

TECHNICAL REALITY:
[设备特征: phone camera grain / DSLR noise at high ISO / slight motion blur].
Depth of field is [imperfect / focusing on the "wrong" thing first].
The frame has the energy of being there, not the perfection of being staged.

NEGATIVE: No architectural photography. No perfect symmetry. No clean surfaces.
No HDR. No studio lighting. No staged minimalism. No real estate aesthetic.

GOAL: A frame that feels like someone walked into this space, 
raised their camera, and pressed the shutter before they had time to compose.
```

### Step D4：关键帧修复流程（Mode D-Fix）

当用户拿来一个已有的关键帧Prompt要修复：

```
修复检查清单：
□ 有没有"perfect/flawless/pristine"等无限词？→ 删除替换
□ 皮肤是不是太干净？→ 加真实纹理描述
□ 光线是不是太完美？→ 加过曝/不均匀/自然缺陷
□ 构图是不是太居中/太平衡？→ 加偏移/裁切/倾斜
□ 前景有没有遮挡？→ 没有就加
□ 背景有没有世界存在的证据？→ 没有就加
□ 人物表情是不是"完成态"？→ 改为"过渡态"
□ 对焦是不是全程锐利？→ 加对焦犹豫/中间态
□ 有没有使用痕迹/杂乱？→ 没有=样板间，必须加
□ 整体是不是像"摄影作品"？→ 降级为"视频截帧"感
```

修复输出格式：
```
--- 原始关键帧Prompt ---
[用户提供的]

--- 诊断 ---
[发现了什么无限电影痕迹]

--- 修复版Prompt ---
[注入有限性后的版本]

--- 修复说明 ---
[逐条列出改了什么]
```

### 关键帧与视频的衔接原则

关键帧是视频的种子——它决定了视频生成的起点。衔接原则：

```
1. 关键帧里已有的有限性元素，视频Prompt必须继承并延续
   - 关键帧有过曝区域 → 视频里光线要有波动
   - 关键帧有前景遮挡 → 视频里遮挡要继续存在（甚至轻微移动）
   - 关键帧人物表情在过渡 → 视频里让这个过渡完成

2. 关键帧暗示的观察者，视频Prompt必须保持一致
   - 关键帧是手机拍的 → 视频也是手机视角
   - 关键帧有倾斜 → 视频开头保持倾斜，可以慢慢修正（观察者在调整）

3. 关键帧留的"白"，视频要去填（但要慢慢填）
   - 关键帧眼神看向画面外 → 视频里让视线慢慢回来
   - 关键帧门没关 → 视频里门可以被风吹动或有人经过
   - 关键帧情绪在两种之间 → 视频里让它落到其中一种
```

## Prompt模板

### 人类有限视频版模板

```
[时长] [视频类型]. [真实感目标].

OBSERVER: A [身份] standing [物理位置], [状态]. 
[经验水平] — [注意力模式].
Limited by: [具体物理限制].

SUBJECT: [人物锁定]

CAMERA SYSTEM: [镜头类型], operated by a [身份].
Lens behavior reflects observer's attention:
- [注意力起点] → [漂移路径] → [最终焦点]
- Subtle overshoot and correction when [触发条件]
- Focus breathing, not mechanical precision

LIGHTING: [光源]. [自然缺陷 — 过曝/反光/变化]. Not controlled.

WORLD CONTAMINATION:
- [世界自运行元素1]
- [世界自运行元素2]
- [前景遮挡/空间限制]

TIMELINE:
00:00–00:03 [动作] — [观察者注意力和镜头行为]
00:03–00:07 [动作] — [延迟反应/犹豫对焦]
00:07–00:10 [动作] — [情绪处理时间]
00:10–00:11 [留白 — 沉默/呼吸/未完成的情绪]

NEGATIVE: Not cinematic. Not 8K. Not perfect. No CGI. No game. No plastic skin. 
No instant reactions. No world that serves the subject. No overdramatic lighting.

GOAL: Feel like a real person, in a real space, captured by another real person 
who was limited, hesitant, and present.
```

## 与 ai-video-director 的关系

| 维度 | ai-video-director | human-finite-video |
|------|-------------------|-------------------|
| 层级 | 技术框架（10层控制系统） | 哲学层（有限性方法论） |
| 解决 | "像什么系统" | "镜头背后站着谁" |
| 产出 | 完整视频Prompt | 观察者定义 + 有限性注入 |
| 关系 | human-finite-video是ai-video-director的Layer 11 | 可以独立使用，也可以升级ai-video-director |

**最佳工作流**：先用human-finite-video定义观察者和有限性策略，再用ai-video-director组装完整10层Prompt。

## 与 weight-thinking 的关系

同一个哲学内核在不同领域的表达：

```
权重思维：锚点=边界 → 权重=倾向 → 输出=带约束的中间态
有限视频：身体/空间/注意力=边界 → 人类状态=倾向 → 画面=带约束的不完美
```

AI无限电影 = 没有锚点 = 权重无限大 = 不可信。
人类有限性 = 天然锚点 = 权重被约束 = 输出有"人味"。

可信度 = 有结构的高熵。AI视频太低熵。人类有限性注入的是有因果关系的高熵。

## 典型场景的观察者定义示例

### 纪录片访谈
```
Observer: 纪录片摄影师，中等经验，站在会议桌侧后方
Position: 空间狭窄，前景有采访者肩膀形成部分遮挡
State: 好奇但克制，被受访者的某些话吸引时会身体前倾
Attention: 先注意到手部微动作，然后才回到眼睛
Limits: 不能绕到另一侧，被桌子限制，被前景人限制
```

### 街头随拍
```
Observer: 手机用户，普通路人，偶然拍到
Position: 站在人行道边，距离被拍者3-5米
State: 有点紧张（偷拍感），不敢靠太近
Attention: 被主体吸引但会被周围环境分散
Limits: 手持手机稳定性有限，来不及对焦，随时可能被路人挡住
```

### 新闻现场
```
Observer: 电视台摄影师，经验丰富，扛着专业摄像机
Position: 被其他记者挤在角落，机位受限
State: 疲惫但警觉，已经拍了一天
Attention: 本能地寻找最有信息量的画面，偶尔被无关细节吸引
Limits: 身体疲劳导致镜头有轻微不规则晃动，空间被人群压缩
```

### 演唱会
```
Observer: 粉丝，手持手机，激动
Position: 看台远端，距离舞台很远
State: 情绪被卷入，不自觉跟着节奏动，镜头跟着身体晃
Attention: 跟着偶像走，但会被旁边突然尖叫的粉丝分散
Limits: 距离远画质差，手臂会酸，旁边人一直在动
```

## Pitfalls

- **不要只加手持抖动就完事**：抖动只是结果，关键是"镜头为什么那样动"——必须先定义观察者
- **不要把五个维度平均注入**：根据场景选择2-3个主导维度。纪录片重在犹豫和被污染，演唱会重在延迟和被污染
- **不要追求"所有视频都需要人味"**：产品广告、科幻特效、MV舞蹈可能不需要——人味是给需要"可信度"的场景用的
- **"不完美"不等于粗制滥造**：有逻辑的缺陷≠随便加噪点。每个"缺陷"必须有物理或心理原因
- **留白不是拖时间**：留白是给观众进入的门，不是无聊的等待。必须有情绪"正在发生但还没完成"的张力
- **世界惯性是架构级问题**：当前AI视频模型（Sora/Kling/Veo）都是"围绕当前任务"生成，世界只有任务相关元素在动。这不是Prompt能完全解决的——但可以在Prompt里主动注入"世界自运行"元素来部分补偿
- **观察者身份必须一致**：定义了"疲惫的记者"就不能突然出现"精准的斯坦尼康运动"——观察者的能力边界必须贯穿始终

## Obsidian 参考

- `01-AI技术/AI-Video/镜头后面有没有一个人——AI视频的人味方法论.md` — 完整方法论
- `01-AI技术/AI-Video/人类有限视频——不是AI无限电影.md` — 概念宣言
- `01-AI技术/AI-Agent/权重系统与中间层架构.md` — 同源理论
- `01-AI技术/场论工程——从铁轨思维到场域引导.md` — 场论哲学根基

完整溯源见 `references/source-materials-and-outputs.md`。
