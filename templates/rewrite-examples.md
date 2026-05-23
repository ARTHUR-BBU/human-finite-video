# Mode B & Mode C 改编示例

实战演示：怎么把已有Prompt和脚本改编成人类有限视频版本。

---

## Mode B 示例：改编已有Prompt

### 原始Prompt（典型ChatGPT生成版）

```
A woman in her 30s sitting in a modern office, being interviewed. 
Cinematic lighting, shallow depth of field, ultra realistic, 8K quality. 
The camera slowly pushes in as she speaks about her childhood. 
She becomes emotional, tears form in her eyes. 
The lighting creates a beautiful rim light effect. 
Smooth camera movement, professional color grading. 
Background is softly blurred with warm bokeh.
```

### 诊断

```
问题清单：
☑ "cinematic lighting" → 塑料高级感，删除
☑ "ultra realistic, 8K" → 越堆越假，删除
☑ "camera slowly pushes in" → 没有心理动机的机械运镜
☑ "beautiful rim light effect" → 世界在为主角服务
☑ "softly blurred with warm bokeh" → 完美虚化=无菌环境
☑ "smooth camera movement" → 太丝滑=没有人在操作
☑ 她哭了→反应太直接，没有延迟和犹豫
☑ 没有前景遮挡→上帝视角
☑ 没有环境干扰→封闭世界
☑ 没有沉默时间→情绪被填满
```

### 升级版Prompt

```
10s documentary interview footage, single continuous shot. Not cinematic.

OBSERVER: A documentary cameraman, 15 years experience, standing at the 
far end of the conference table. He's done hundreds of these interviews 
but occasionally still gets caught off guard. He's holding the camera 
at shoulder height, slightly lower than ideal because he's sitting on 
a stool that's too short. The table edge is visible at the bottom of frame.

SUBJECT: Woman, mid-30s, wearing a slightly rumpled linen shirt. 
Real skin — pores, slight unevenness under the eyes from poor sleep. 
Hair not perfectly arranged. Glasses that catch the window light.

CAMERA: Shoulder-mounted, handheld. The camera breathes with the operator.
When she starts talking about childhood, he doesn't push in immediately — 
he waits, listening, and only after a beat does he begin a very slow, 
almost imperceptible drift forward. Not a dolly move. A human leaning in.
Focus was on her hands (she's been fidgeting with a pen). It takes a moment 
to find her eyes, and the pull is not perfectly smooth.

LIGHTING: Late afternoon window light from camera left. Not controlled. 
There's a slightly hot spot on her left cheek. As a cloud passes outside, 
the light dims for 2 seconds, then returns. The window reflects internal 
office lights — you can see vague rectangles of fluorescent on the glass.

WORLD CONTAMINATION:
- The conference room door is slightly ajar — hallway light bleeds in
- Someone's coffee cup sits in the foreground, out of focus but present
- The HVAC clicks on at one point, barely audible
- A phone vibrates on the table (not hers — the interviewer's)

TIMELINE:
00:00–00:03 She's talking, gesturing casually. Camera is stable, 
  watching. Focus on her hands and the pen she's turning over.
  The table edge anchors the bottom of frame — this camera has a position.
00:03–00:05 She says "childhood." Her voice changes, almost imperceptibly. 
  The cameraman notices — camera begins its slow, hesitant drift forward. 
  Not a decision. An instinct.
00:05–00:07 She pauses. Processing something. Lips press together. 
  The camera doesn't move. The focus pulls from her hands to her eyes — 
  slow, not confident, like the operator is deciding whether this is real.
00:07–00:09 Her eyes get wet. She blinks. A quick, controlled blink — 
  she's trying not to cry. The camera holds. It doesn't push closer. 
  It respects the moment by not intruding.
00:09–00:10 She smiles, small and sad. The cloud outside passes, 
  light brightens for a second. Camera stays. No cut. 
  The interviewer's pen clicks softly off-screen.

NEGATIVE: No cinematic grading. No 8K sharpness. No rim lighting. 
No smooth dolly movement. No shallow bokeh that erases the room. 
No instant emotional reactions. No world that waits for her.
No score. No color grade that makes sadness look beautiful.

GOAL: A moment that feels like it happened in a real room, 
captured by a real person who was there and chose not to look away.
```

### 改动说明

```
1. 删除 cinematic/8K/ultra realistic → 替换为 "documentary, not cinematic"
2. 删除 "smooth camera" → 替换为操作者的呼吸节奏和本能前倾
3. 删除 "beautiful rim light" → 替换为未控制的自然窗光+过曝+云层变化
4. 删除 "warm bokeh" → 替换为前景咖啡杯、桌沿、门缝光线
5. 哭泣加延迟：不是说哭就哭→先声音变化→停顿→眨眼→控制→才湿了
6. 加世界污染：门缝光、空调声、采访者的手机振动
7. 加观察者心理：他"没决定推近，是本能"，"犹豫是不是真的在哭"
8. 结尾留白：0.7s不切，让笑容和光线变化自然发生
```

---

## Mode C 示例：改编剧本片段

### 原始剧本

```
INT. OFFICE - NIGHT

陈默坐在空荡的办公室里，屏幕的光打在他脸上。桌上散落着文件和一个没吃完的外卖盒。

他盯着手机里的一条消息："我们还是不要再联系了。"

手指停在屏幕上，没有打字。

沉默了十秒，他把手机翻过来扣在桌上。

站起来，走到窗边。城市灯火密密麻麻。

他深吸一口气，呼出来的时候，玻璃上凝出一小片雾。
```

### 视频化分析

```
场景：深夜办公室，只有屏幕光。空间大但空。
人物：陈默，30s左右，疲惫，独自一人。
动作：看手机→停顿→翻手机→站起→走到窗边→呼气。
情绪弧线：麻木→被击中→压抑→试图释放→微小的脆弱暴露。
潜台词：他不是在"悲伤"，他是在"忍住不在办公室崩溃"。
```

### 观察者设定

```
Observer: 不存在的第三者——这个场景本质上没有旁观者。
决策：使用"监控摄像头"式的固定机位 + 偶尔的缓慢呼吸感位移，
暗示这是一个被"无意记录"的私人时刻，而不是被拍摄的表演。

备选：如果是叙事短片，可以定义为"同事手机忘在桌上偶然录到"——
这样就有手持感、距离远、画质一般、角度受限（被桌面挡住一部分）。
以下用备选方案。
```

### 人类有限视频Prompt

```
12s, late night office, single phone camera. Security-cam adjacent. Not cinematic.

OBSERVER: A phone left face-up on a nearby desk, propped slightly against 
a stapler. Recording accidentally — maybe a voice memo that was never stopped. 
The angle is low and slightly tilted. The phone's owner left hours ago.
This is surveillance-by-accident. No one chose this frame.

SUBJECT: Man, early 30s, office clothes slightly disheveled — tie loosened, 
sleeves rolled unevenly. Face lit only by his monitor's blue-white glow. 
Real fatigue: slight bags under eyes, skin not perfect, hair messed from 
running his hand through it earlier.

CAMERA: Static phone camera, slight tilt (3-4 degrees). 
It does not move. It does not follow. It does not care.
It's a phone — it captures whatever's in its fixed field of view.
The edge of the desk cuts across the bottom of frame. 
A coffee mug sits in the foreground, half in frame.
Autofocus is slow in this light — when he stands up, focus hunts for 0.5s.

LIGHTING: Monitor light only. Blue-white, flat, unflattering. 
The rest of the office is dark — shapes of desks, chairs, 
but no detail. When he moves toward the window, 
the city glow starts to illuminate him from behind.
No fill light. No backlight. No one set this up.

WORLD CONTAMINATION:
- The HVAC is running — the office never turns it off
- A monitor in the background is on sleep mode, occasionally blinking
- The city outside has its own rhythm — a red light blinks on a tower, 
  cars move on a distant road. The city doesn't know he's there.
- His desk has the chaos of a real workday: stacked papers, 
  a cold takeout container, a charger cable snaking across

TIMELINE:
00:00–00:03 He's sitting. Staring at his phone. Not moving. 
  The phone-camera watches from its tilted angle. 
  His face is half in monitor-light, half in shadow.
  His thumb hovers over the screen but doesn't move.
  The office hums.
00:03–00:05 A stillness. He's not acting — he's processing.
  His jaw tightens, almost invisible. 
  The focus is still, but the phone's sensor noise is visible 
  in this low light. Real grain.
00:05–00:07 He flips the phone. Screen down on the desk. 
  The sound is sharp in the quiet room. 
  His hand stays there for a beat — like he's pressing it down, 
  keeping the message contained.
00:07–00:09 He stands. Not suddenly — slowly, heavily. 
  The camera's autofocus briefly loses him, hunts, finds him again. 
  He walks toward the window. The camera can't follow — 
  he moves partly out of frame. We see him from behind, 
  through the gap between two office chairs.
00:09–00:11 At the window. City lights behind him. 
  He breathes in. A long breath. Then out — 
  and a small patch of fog appears on the glass, 
  lit by the city behind it. It fades.
00:11–00:12 Hold. He doesn't move. The city doesn't care. 
  The fog on the glass evaporates. 
  The office hums. The recording continues.

NEGATIVE: No music. No cinematic wide shot. No slow motion. 
No color grade. No beauty lighting. No emotional camera movement. 
No camera that follows him like it understands. 
This is a phone on a desk. It captures what it can. 
It misses most of it. That's the point.

GOAL: A private moment that was never meant to be recorded, 
captured by accident, by a device that doesn't know 
what it's seeing. The most honest footage is the footage 
no one chose to take.
```

### 脚本→视频翻译说明

```
1. "屏幕的光打在他脸上" → 不写face lit by screen（太描述性）
   → 写monitor-light only, blue-white, flat, unflattering（光的质感）
2. "盯着一条消息" → 不拍手机屏幕内容（AI做不到那么精细）
   → 拍拇指悬在屏幕上不动（动作比内容更动人）
3. "手指停在屏幕上，没有打字" → 这就是延迟——他还没处理完
   → 保留这个停顿，加长到3秒，让观众自己感觉他在忍
4. "沉默了十秒" → 视频里十秒太长，但3秒的绝对静止就够了
   → 用环境音填充沉默（空调声、远处电梯声）→ 留白不是真空
5. "把手机翻过来扣在桌上" → 加一个细节：手没有立刻离开
   → "keeping the message contained"——物理动作暗示心理状态
6. "站起来，走到窗边" → 镜头跟不上（它是固定手机）
   → 他部分出画，只透过椅子的缝隙看到他→物理限制=有限性
7. "深吸一口气，玻璃上凝出雾" → 这是全场景最脆弱的瞬间
   → 雾气出现又消失——情绪也是，来了又走了
   → 不切镜头，让雾气自己蒸发
8. 整个场景的核心：没有任何人选择记录这个瞬间
   → "无意记录的私人时刻"比"精心拍摄的情绪戏"更可信
```

---

## 快速改编检查清单

改编任何已有内容时，过一遍这个清单：

```
□ 删掉所有"完美词"：cinematic, 8K, masterpiece, ultra realistic, perfect, smooth
□ 加一个观察者（即使原始内容没有→必须推断一个）
□ 镜头运动有没有心理动机？（没有→加）
□ 反应有没有延迟？（没有→加0.3-0.5s处理时间）
□ 世界有没有在自运行？（没有→加1-2个环境干扰）
□ 有没有"有逻辑的缺陷"？（没有→加1个物理原因的不完美）
□ 情绪有没有被说完整？（完整了→砍掉最后30%，留余味）
□ 前景有没有遮挡？（没有→加物理障碍）
□ 结尾有没有沉默时间？（没有→加0.5-1s留白）
□ 对焦是不是一步到位？（是→加犹豫对焦路径）
□ 背景是不是完美虚化？（是→加背景细节和杂乱信息）
```
