# 观察者Prompt模板集

直接复制改写即可。每个模板已内置有限性五维注入。

---

## 模板A：纪录片访谈（人味最重的类型）

```
[时长] documentary interview footage. Not cinematic. Not a film.

OBSERVER: A documentary cameraman, moderately experienced, standing at the side 
of a conference table. The space is narrow — the interviewer's shoulder is 
partially in frame on the left edge, slightly blocking the view. The cameraman 
is curious but restrained. When the subject says something that hits hard, he 
leans in almost imperceptibly, causing a very controlled Z-axis shift.

SUBJECT: [人物描述 — 保留真实皮肤纹理、不对称、疲态]

CAMERA: Handheld, shoulder-mounted. Not stabilized.
- Focus starts on the subject's hands for 0.3s, then slowly pulls to eyes
- Slight focus breathing throughout
- Camera wanders briefly to coffee cup, window reflection, then back to face
- When subject pauses, camera doesn't cut — it waits, breathing with the moment

LIGHTING: Natural window light only. Slight overexposure from window. 
Light fluctuates as clouds pass. Not controlled. Not pretty.

WORLD CONTAMINATION:
- Window reflections shift as cars pass outside
- Background glass shows hallway activity
- Table surface has water ring marks, scattered papers
- HVAC hum is present in the room's atmosphere

TIMELINE:
00:00–00:03 Subject starts speaking. Camera settles from slight adjustment.
  Focus finds hands first, drifts to face.
00:03–00:07 Subject says something important. Observer leans in slightly.
  Camera has subtle forward drift. Focus tightens on eyes.
00:07–00:09 Subject pauses. Processing. Lips press together. 
  Camera doesn't move. Holds the silence.
00:09–00:11 Subject resumes, but voice has changed. 
  Camera follows naturally. 0.5s delay before reframing.
00:11–00:12 Hold. No cut. Subject blinks, looks down. 
  The moment isn't over — it's just quiet.

NEGATIVE: No cinematic grading. No 8K sharpness. No perfect exposure. 
No instant focus. No world that pauses for the subject. No dramatic music. 
No cut that's too clean.

GOAL: Feel like a real person was in that room, holding a camera, 
limited by where they could stand, capturing something they didn't fully control.
```

---

## 模板B：街头偶遇（手机随拍感）

```
[时长] casual street footage. Phone camera quality. Not professional.

OBSERVER: A regular person holding their phone, standing on the sidewalk.
They noticed something interesting 3-5 meters away. A bit nervous — 
not wanting to be obvious. Phone is held at chest height, slightly tilted.

SUBJECT: [人物/场景描述]

CAMERA: Phone camera, handheld at chest level.
- Slight constant micro-movement from breathing and hand tremor
- Occasional reframing when observer shifts weight
- Not smooth — has the uneven rhythm of a human body standing still
- When something happens, phone lifts slightly (observer's instinct)

LIGHTING: Whatever's there. Street. Shop windows. Neon. 
Sometimes blown out, sometimes too dark. Not adjusted.

WORLD CONTAMINATION:
- Pedestrians walk through frame without caring
- Cars pass, headlights sweep across
- Someone's arm enters frame from the side
- Wind catches the observer's hair/finger on lens

TIMELINE:
00:00–00:02 Observer notices. Camera slowly points at subject. 
  Not centered. Finding the subject.
00:02–00:05 Watching. Camera drifts slightly — observer gets distracted 
  by something else for a beat, then returns to subject.
00:05–00:07 Something happens. Camera lifts instinctively. 
  Slightly late — already started when phone comes up.
00:07–00:09 Observer lowers phone slightly, almost stops recording.
  Then decides to keep going. Moment of hesitation visible in camera movement.
00:09–00:10 Hold for one more second. Then the recording would end naturally.

NEGATIVE: No stabilization. No cinematic framing. No shallow DOF. 
No perfect timing. No clean composition. Not an ad. Not a film.
Phone camera aesthetics: slight noise, imperfect white balance, 
occasional focus hunting.

GOAL: Feel like someone's phone recording that they almost didn't take.
```

---

## 模板C：新闻/现场（专业但受限）

```
[时长] on-location news footage. Broadcast quality but field conditions.

OBSERVER: A TV news cameraman, experienced, shoulder-mounted professional camera.
Been shooting since 6am. Tired but alert. Jostled by the crowd — 
can't get the perfect angle. Making the best of limited position.

SUBJECT: [事件/人物描述]

CAMERA: Professional broadcast camera, shoulder-mounted.
- Stable but not perfect — fatigue shows in slight irregular drift
- Quick, professional reframing, but occasionally a beat late when 
  something unexpected happens
- Zoom pulls are deliberate but sometimes overshoot slightly
- White balance slightly off from mixed lighting

LIGHTING: Mixed. Whatever the location provides. 
Fluorescent + natural + whatever lights are there. 
Color temperature shifts across the frame.

WORLD CONTAMINATION:
- Other reporters' mics and cameras visible at edges
- Crowd noise is real and continuous
- Weather doesn't care about the broadcast
- Someone's elbow appears in frame periodically

TIMELINE:
00:00–00:03 Establishing. Camera finds subject through crowd. 
  Not a clean establishing shot — obstructed, searching.
00:03–00:06 Subject speaks/moves. Camera follows professionally 
  but physically constrained by crowd position.
00:06–00:08 Something unexpected happens off to the side. 
  Camera swings 0.3s late — professional reflex, but still human.
00:08–00:10 Camera pulls back to wider shot. 
  Realizes the wider context matters. Deliberate choice.
00:10–00:11 Hold. Broadcast hold. Let the moment exist before cutting.

NEGATIVE: Not a studio. Not controlled lighting. Not clean audio.
Not perfectly framed. Not a press kit. Not color graded.
Real field conditions. Real fatigue. Real crowd.

GOAL: Look like footage that a tired professional cameraman shot 
in imperfect conditions because that's exactly what happened.
```

---

## 快速注入片段（可以粘贴到任何现有Prompt里）

### 加入犹豫
```
Observer's attention drifts: focus briefly lands on [次要元素] for 0.3s 
before finding [主要目标]. Camera overshoots slightly, corrects gently. 
Not a search — a hesitation.
```

### 加入延迟
```
Reactions are not instant. 0.3-0.5s processing delay before visible response.
Understanding travels through the body: eyes first, then face, then posture.
Emotion doesn't arrive on time — it's always a beat late.
```

### 加入被污染
```
The world doesn't serve the subject. Background continues its own business:
[环境元素1 continues], [环境元素2 happens without regard for camera], 
[前景遮挡 from 空间限制]. The frame is slightly dirty with reality.
```

### 加入留白
```
After [关键时刻], hold the frame for 0.7s. No cut. Let the silence exist.
The emotion hasn't finished — it's still arriving. 
The subject blinks, looks down, breathes. Don't interrupt this.
```

### 加入不完美
```
Technical imperfections from real conditions: [逆光导致slight overexposure], 
[玻璃反光momentarily obscures], [对焦hunts briefly before settling].
These are not flaws — they're evidence that a real camera was in a real space.
```
