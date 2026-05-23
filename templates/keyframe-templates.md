# Mode D: Keyframe (Image) Prompt Examples

AI video workflow: keyframe/seed image first, then img2vid. If the seed frame is already "infinite cinema," the video inherits that plastic feel. Finiteness must start from the seed.

---

## D-Generate Example: Documentary Interview Keyframe

### Request

"I need a keyframe for an interview scene — a woman in an office."

### Human Finite Video Keyframe Prompt

```
A photographic still frame from a documentary interview. Not a portrait. Not a headshot.
Shot by a documentary cameraman holding a shoulder-mounted camera, standing at the 
side of a conference table, slightly lower than eye level because the room is cramped 
and his stool is too short.

OBSERVER PRESENCE:
- Camera position: side angle, past the interviewer's left shoulder (partially visible 
  at frame left edge, soft focus, fabric texture visible)
- Framing: subject is slightly right of center — the camera found her but didn't 
  perfectly center. The table edge cuts across the bottom third.
- Focus state: focus just landed on the subject's eyes after briefly resting on her 
  hands. Not a clean pull — you can feel the hesitation.

SUBJECT:
Woman, early 30s, wearing a slightly rumpled blue linen shirt with the top button undone. 
Real skin — visible pores on her nose, slight shine on her forehead, the beginning of 
expression lines around her eyes. Hair not perfectly arranged, a strand falling across 
her cheek that she hasn't noticed. Thin-framed glasses that catch the window light, 
creating a brief moment where her eyes are obscured by reflection.

MOMENT IN TIME:
She's mid-sentence, mouth slightly open, one hand raised in a gesture that hasn't 
completed yet. Her expression is in transition — something between conviction and 
vulnerability. She's looking past the camera, at the interviewer. Her eyes suggest 
she just said something she wasn't planning to say.

ENVIRONMENT AS WITNESS:
- The window behind her shows a slightly overexposed city view — not a beautiful 
  skyline, just an ordinary office building across the street. A reflection of the 
  conference room is faintly visible in the glass.
- The table in front of her has a scattering of real objects: a paper coffee cup 
  with a lid that's not quite on straight, a pen lying across a notebook, a phone 
  face-down, a water glass with a fingerprint smudge.
- The far wall has a whiteboard with partially erased writing — someone didn't 
  clean it properly after the last meeting.

TECHNICAL REALITY:
Late afternoon window light from camera left, creating a slightly hot spot on her 
left cheek and a subtle shadow across her right side. The light is not balanced — 
it's whatever the window gives at 4:30 PM. No fill light. No reflector. The room's 
overhead fluorescents are off (someone turned them off for the interview but forgot 
the one in the corner, which casts a faint cool wash on the background).
Lens shows natural vignetting at the edges. Slight chromatic aberration on the 
glasses frames. Not a perfect lens — a real broadcast zoom that's been used for years.

NEGATIVE: No perfect skin. No studio lighting. No cinematic color grade. 
No pristine environment. No centered subject. No perfectly sharp throughout.
No posed expression. No retouched portrait. No beauty lighting. No bokeh that 
erases the room. No real estate aesthetic.

GOAL: A frame that feels pulled from real documentary footage — not a photograph 
taken, but a moment caught by someone who was listening more than framing.
```

---

## D-Fix Example: Repairing an "Too Perfect" Keyframe

### Original Prompt

```
A professional woman in a modern office, beautiful natural lighting, 
shallow depth of field. Ultra realistic, 8K quality. She looks confidently 
at the camera. Cinematic composition, warm tones, soft bokeh background. 
Her skin is flawless, wearing a perfect blazer. The office is clean and modern.
```

### Diagnosis

```
Infinite cinema traces:
- "beautiful natural lighting" -> light serves her
- "ultra realistic, 8K" -> plastic quality words
- "looks confidently at camera" -> direct eye contact = omniscient view
- "cinematic composition" -> perfect framing = no operator
- "flawless skin" -> non-existent skin
- "perfect blazer" -> no wear marks
- "clean and modern office" -> showroom
- No foreground obstruction -> god's eye view
- No environmental detail -> world doesn't exist
- Expression is completed -> no in-transition authenticity
```

### Repaired Version

```
A documentary still of a woman in an actual office — not a showroom, 
the kind of office where people work. Shot by a cameraman standing at 
the doorframe, partially blocked by the door edge on the right side of frame.

She's mid-conversation, not posing. Her expression is shifting — she was 
about to say something but the interviewer's last question caught her off guard. 
Her mouth is slightly open, not in a composed way, but in a "wait, let me think" way. 
Her eyes are directed at someone off-frame left, not at the camera.

Skin is real: visible texture, slight unevenness, the kind of face that 
has been in a meeting since 9 AM and it's now 3 PM. Her blazer has a 
small crease across the lapel from leaning back in her chair. One button 
is done up, the other is not — asymmetry that real people have.

Light comes from the window behind the camera, not perfectly balanced — 
the left side of her face is brighter than the right. No fill. No reflector. 
The window behind her shows an ordinary street, not a beautiful vista. 
A passing car's reflection moves across the glass.

Her desk has the evidence of a real workday: a coffee cup ring on the surface, 
papers not stacked but scattered, a phone with a cracked screen protector, 
a pen that rolled to the edge. The whiteboard behind her has last week's 
notes still on it, partially erased.

Camera is slightly off-center, tilted 2 degrees — the operator was standing 
in the doorway, didn't have time to level. Focus is sharp on her eyes but 
the foreground door frame is soft and present. The frame has vignetting at 
the edges. No color grade. No HDR. This is what the sensor captured.

Not a portrait. Not a headshot. A moment in a real day, in a real room, 
caught by someone standing in a doorway.
```

### Fix Explanation

```
1. "professional woman" -> "woman in an actual office" (de-commodified)
2. Removed "beautiful natural lighting" -> window light, uneven, no fill
3. Removed "ultra realistic, 8K" -> no resolution/quality claims
4. "looks confidently at camera" -> "looking at someone off-frame" (observer present)
5. Removed "cinematic composition" -> doorway position, 2-degree tilt, no time to level
6. "flawless skin" -> real skin after a full day of meetings
7. "perfect blazer" -> creased, buttons asymmetric
8. "clean and modern office" -> coffee ring, scattered papers, cracked phone screen
9. Added foreground: door frame obstruction (operator standing in doorway)
10. Added world: ordinary street outside, passing car reflection
11. Expression from "confident completion" to "interrupted transition"
12. Closing definition: not a portrait, a real moment caught in a doorway
```

---

## Keyframe-to-Video Continuity Example

### Keyframe finiteness elements -> How video extends them

```
Keyframe: Door frame on right edge, 2-degree tilt
-> Video: Keep tilt and door frame for first 1-2 seconds, then operator 
   slowly adjusts stance (tilt recovers but not perfectly)

Keyframe: Her expression in transition, mouth slightly open
-> Video: Expression completes landing at 0.5s (she says the thing, 
   voice slightly hesitant)

Keyframe: Car reflection in window
-> Video: Reflection continues moving, light subtly shifts, 
   world didn't stop

Keyframe: Cluttered desk
-> Video: AC blows a paper edge slightly (world keeps running)

Keyframe: Focus on her eyes
-> Video: When she says the key line, focus briefly slides to her hands 
   (operator drawn to gesture), then returns to eyes
```

---

## Quick Keyframe Checklist

Run through this for any keyframe generation or repair:

```
[ ] Real skin texture? (No -> add pores/unevenness/fatigue)
[ ] Natural lighting defects? (No -> add overexposure/unevenness/shadow)
[ ] Composition too perfect? (Centered/balanced -> offset/crop/tilt)
[ ] Foreground obstruction? (No -> add shoulder/doorframe/plant/hand)
[ ] World exists in background? (No -> add window activity/wear marks/clutter)
[ ] Expression is "completed" or "in transition"? (Completed -> change to transition)
[ ] Focus sharp throughout? (Yes -> add hesitant focus/pull state)
[ ] Lens/camera physical traits? (No -> add vignetting/chromatic aberration/edge softness)
[ ] Looks like "photography" or "video frame grab"? (Photography -> downgrade to frame grab)
[ ] Can you state "who's shooting" in one sentence? (No -> need to define observer)
```
