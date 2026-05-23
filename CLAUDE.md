# CLAUDE.md

# Human Finite Video — 人类有限视频方法论

让AI视频从"无限电影"变成"有限的人拍的真实瞬间"。

## 核心公式

```
真实感 = 有限性留下的痕迹
```

AI越追求无限，越像梦。人类越暴露有限，越像现实。

## 这个项目是什么

一套可执行的AI视频方法论，包含：
- 五维有限性框架（不完美/延迟/犹豫/被污染/留白）
- 观察者身份定义系统
- 三种工作模式（从零生成 / 改编已有Prompt / 改编剧本）
- 完整的Prompt模板和快速注入片段
- 实战改编示例

## 五维有限性

| 维度 | 本质 | 对应的人类有限性 |
|------|------|----------------|
| 不完美 | 画面不能完全受控 | 设备有限、环境有限 |
| 延迟 | 反应不能瞬间完成 | 神经有限、理解有限 |
| 犹豫 | 判断不能一次正确 | 注意力有限、经验有限 |
| 被污染 | 世界不服务主体 | 空间有限、现场不可控 |
| 留白 | 情绪不能被立刻解释 | 语言有限、表达有限 |

五个词都指向同一个母概念：**有限性**。

## 三种工作模式

| 模式 | 输入 | 产出 |
|------|------|------|
| A. 从零生成 | 场景描述/概念 | 完整的人类有限视频Prompt |
| B. 改编Prompt | 已有AI视频Prompt | 升级版（注入有限性+观察者） |
| C. 改编剧本 | 影视脚本/剧本/场景描写 | AI视频Prompt（注入有限性+镜头语言） |

## 关键原则

1. **定义观察者**：每次生成前必须回答"镜头背后站着谁"——身份、状态、物理限制、注意力模式、经验水平
2. **删除塑料词**：cinematic, 8K, masterpiece, ultra realistic, perfect — 越堆越假
3. **世界不配合主角**：主动注入环境干扰和自运行元素
4. **情绪慢慢渗出来**：不是爆发，是延迟→犹豫→微表情→身体跟上
5. **留30%没说完**：不要把情绪填满，给观众进入的门

## 文件结构

```
├── CLAUDE.md                    — 本文件（渐进式披露）
├── README.md                    — 项目说明
├── methodology.md               — 完整方法论文档
├── templates/
│   ├── observer-prompt-templates.md  — 三种场景完整Prompt模板 + 快速注入片段
│   └── rewrite-examples.md           — Mode B & Mode C 实战改编示例
├── .github/
│   └── copilot-instructions.md  — Copilot/Codex 兼容
└── LICENSE                      — MIT
```

## 与其他项目的关系

- **[ai-video-director](https://github.com/ARTHUR-BBU/ai-video-director)** — 技术框架（10层控制系统），本方法是它的哲学层（Layer 11）
- **[weight-thinking](https://github.com/ARTHUR-BBU/weight-thinking)** — 同源方法论：锚点=边界，权重=倾向，有限性=天然锚点

## 使用方式

### 作为 Hermes Agent Skill

放在 `~/.hermes/skills/creative/human-finite-video/` 下即可自动加载。

### 作为独立参考

直接读 `methodology.md` 获取完整理论，用 `templates/` 里的模板直接改写。

### 作为 Custom GPT 系统提示词

取 `methodology.md` 核心部分 + `templates/observer-prompt-templates.md` 的模板，精简后灌入系统提示词。

---

*真实感不是技术问题，是存在论问题。不是"看起来真实"，而是"感觉真实"。*
