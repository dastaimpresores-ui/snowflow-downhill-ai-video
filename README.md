# SnowFlow Downhill — AI Video Workflow

**SnowFlow Downhill** is a storyboard-to-video AI workflow for creating a 15-second cinematic downhill snow action scene using Seedance 2.0.

The project follows three young riders descending a snowy mountain:

- One green snowboarder
- One blue skier
- One red snowboarder

The sequence includes:

- Downhill acceleration
- Slalom turns
- Snow jump
- Freeze-time moment
- 360° camera orbit
- Landing
- Final downhill push

This repository contains the full storyboard prompt, the final Seedance 2.0 video prompt, camera planning, timing structure, negative prompts, and YouTube Shorts copy.

---

## Project Goal

The goal of this experiment is to test how much control can be achieved in AI video generation through:

- storyboard planning
- action timing
- camera direction
- subject consistency
- movement continuity
- negative prompting
- cinematic structure

AI video tools can create strong visuals, but without structure they often lose continuity, change characters, break movement logic, or create chaotic camera motion.

This workflow uses a structured storyboard and a detailed motion prompt to reduce those issues.

---

## Tools

Main video generation target:

- Seedance 2.0

Creative direction:

- Manga-inspired sports action
- Cinematic downhill camera language
- Storyboard-to-video workflow
- Freeze-time 360° camera orbit

---

## Sequence Summary

| Time | Action |
|---|---|
| 0:00–0:02 | Three riders start at the top of the slope |
| 0:02–0:04 | Group accelerates downhill |
| 0:04–0:06 | First slalom section |
| 0:06–0:07.5 | Green snowboarder approaches jump |
| 0:07.5–0:09.5 | Freeze-time midair 360° orbit |
| 0:09.5–0:11 | Landing and regroup |
| 0:11–0:13 | Advanced coordinated slalom |
| 0:13–0:15 | Final downhill push |

---

# Storyboard Prompt y Seedance 2.0 Prompt

Use this prompt to generate the visual storyboard reference.

```text
Create a single vertical storyboard poster in a clean editorial motion-study layout.

The format should look like a professional cinematic storyboard sheet, not a comic page.

Layout:
A vertical A4-like poster with a white background, thin grey divider lines, black typography, red accent numbers, and lots of white space.

Use this structure:
- Left information column with project title and technical notes.
- Middle column with 9 stacked horizontal storyboard frames.
- Narrow text strip beside each frame with shot number, shot title, short description, and duration.
- Right column with simple black camera/movement diagrams for each shot.

Do not use a 3x3 grid.
Do not make it look like a comic page.
Make it look like a professional motion storyboard sheet.

Project title block on the left:
Top small line: "MOTION STORYBOARD"
Main title: "SnowFlow"
Brush-script secondary title: "Downhill"

Info sections on the left:
GENRE: "SPORT / ACTION / MANGA"
FORMAT: "VERTICAL • 4:4 FRAMES"
DURATION: "~ 20–30 SECONDS"
VISUAL LANGUAGE: "SNOW ACTION / SLALOM / FREEZE TIME / 360 ORBIT / ANIME ENERGY"

DIRECTOR’S NOTE:
"Three young riders descend a snowy mountain. Two snowboarders and one skier perform a fast, fluid run with slalom turns, a jump, a freeze-time orbit shot, and a final downhill push."

KEY:
Use tiny icons for:
- Direction / camera move
- Movement path
- Timing / duration
- Impact / highlight

Footer:
"MOTION • SNOW • ENERGY • CAMERA • IMPACT"
"STORYBOARD / MOTION STUDY"

Central storyboard content:
Use colorful cartoon manga / anime sports style, crisp lines, dynamic poses, vibrant snow lighting, blue sky, alpine mountains, pine trees, and action snow spray.

The scene follows the same three young riders throughout all 9 shots:
1. Green-and-black snowboarder with green helmet, goggles, and green-black snowboard.
2. Blue-and-black skier with blue helmet, goggles, blue skis, and ski poles.
3. Red-and-black snowboarder with red helmet, goggles, and red-black snowboard.

Keep the characters consistent across all frames:
same outfits,
same helmets,
same goggles,
same equipment,
same body proportions,
same visual identity.

Do not switch equipment between riders.
The skier must remain a skier.
The snowboarders must remain snowboarders.

Storyboard rows:

1. START LINE
Description: Three riders at the summit, ready to begin.
Duration: 02.5s
Central frame: wide establishing shot of the three riders at the top of the snowy slope.
Right camera note: "CAM: LOW WIDE"
Right icon: upward arc or low-angle camera arrow.

2. ACCELERATION
Description: The group begins descending together, gaining speed.
Duration: 02.5s
Central frame: all three riders accelerate downhill, snow spray behind them.
Right camera note: "CAM: TRACK DOWNHILL"
Right icon: straight horizontal tracking arrow.

3. SLALOM ENTRY
Description: The trio starts slalom turns between course gates.
Duration: 03.0s
Central frame: the riders carve between red and blue slalom gates.
Right camera note: "CAM: FOLLOW TURN"
Right icon: curved turn arrow.

4. JUMP APPROACH
Description: The green snowboarder approaches the jump ramp while the other two follow behind.
Duration: 02.5s
Central frame: green snowboarder moves toward a snow jump ramp, blue skier and red snowboarder behind.
Right camera note: "CAM: PUSH IN"
Right icon: dashed push-in arrow.

5. FREEZE AIR 01
Description: The green snowboarder is frozen midair at the peak of the jump.
Duration: 02.5s
Central frame: green snowboarder suspended in the air over the snowy mountain.
Right camera note: "CAM: 360 ORBIT"
Right icon: circular orbit arrow.

6. FREEZE AIR 02
Description: Same airborne moment from a new orbit angle, continuing the 360 move.
Duration: 02.5s
Central frame: green snowboarder still in the air, seen from another angle as the camera orbit continues.
Right camera note: "CAM: ORBIT CONTINUE"
Right icon: second circular orbit arrow.

7. LANDING
Description: The green snowboarder lands and rejoins the descent.
Duration: 02.0s
Central frame: landing impact with snow spray, the other two riders regrouping.
Right camera note: "CAM: FOLLOW LANDING"
Right icon: downward follow-through arrow.

8. ADVANCED SLALOM
Description: All three riders carve aggressively in a coordinated slalom.
Duration: 03.0s
Central frame: all three riders carve in dynamic coordinated slalom lines.
Right camera note: "CAM: WIDE / WEAVE"
Right icon: S-curve weaving arrow.

9. FINAL RUN
Description: Dynamic closing frame of the three riders charging downhill together.
Duration: 03.0s
Central frame: final downhill push, all three riders moving fast toward camera with snow spray.
Right camera note: "CAM: EXTREME WIDE"
Right icon: radial burst or wide outward arrows.

Visual style:
Professional storyboard sheet.
Clean Swiss editorial layout.
White background.
Thin grey dividers.
Black typography.
Red accent numbers.
Minimalistic motion-study design.
Central action frames should be vivid, colorful, manga-inspired, and cinematic.

Restrictions:
No messy layout.
No comic page grid.
No extra characters.
No duplicated riders.
No inconsistent outfits.
No equipment switching.
No broken anatomy.
No extra limbs.
No unreadable text.
No random arrows inside the central action frames.
No urban background.
No night scene.
No crowd.
No fantasy elements.
No weapons.
No unrelated props.

#Seedance 2.0 Final Prompt

OBJECTIVE:
Create one continuous 15-second cinematic downhill snow-action video in vertical 9:16.

The scene follows three young riders descending a bright alpine mountain: two snowboarders and one skier.

The sequence must feel fast, fluid, dynamic, and coherent, with slalom turns, one jump, a freeze-time 360° orbit in midair, landing, and a final coordinated downhill push.

SUBJECT:
Three young athletic riders wearing winter sports gear:

Rider A:
Green-and-black snowboarder.
Green helmet.
Goggles.
Green-black snowboard.

Rider B:
Blue-and-black skier.
Blue helmet.
Goggles.
Blue skis.
Ski poles.

Rider C:
Red-and-black snowboarder.
Red helmet.
Goggles.
Red-black snowboard.

All three riders must remain visually consistent throughout the full video.

Keep the same outfits, helmets, goggles, body proportions, and equipment from beginning to end.

Rider A must always be the green snowboarder.
Rider B must always be the blue skier.
Rider C must always be the red snowboarder.

Do not switch equipment between riders.
Do not turn the skier into a snowboarder.
Do not turn the snowboarders into skiers.

SCENE / ENVIRONMENT:
Bright alpine ski mountain under a vivid blue sky.

The environment includes:
wide snowy slope,
bright white snow,
pine trees,
distant mountain peaks,
slalom gates,
groomed snow texture,
snow spray,
natural jump ramp,
crisp winter sunlight.

The environment should feel clean, cinematic, premium, open, and energetic.

No urban background.
No crowds.
No text.
No storyboard panels.
No arrows.
No poster layout.

ACTION:
The video must evolve as one continuous downhill sequence.

0:00–0:02
The three riders start at the top of the slope and launch into the descent together.

They push off with energy and immediately begin moving downhill.

0:02–0:04
The group accelerates downhill in formation.

Rider B, the blue skier, stays near the center.
Rider A, the green snowboarder, rides slightly to one side.
Rider C, the red snowboarder, balances the opposite side.

Snow sprays behind them.
The camera should communicate speed and direction clearly.

0:04–0:06
The three riders enter a slalom section.

They weave between red and blue slalom gates with aggressive but controlled turns.

The movement must feel synchronized, fluid, and readable.

0:06–0:07.5
Rider A, the green snowboarder, breaks slightly ahead and approaches a snow jump ramp.

The blue skier and the red snowboarder continue descending behind him.

Build anticipation for the jump.

0:07.5–0:09.5
Rider A launches into the air.

At the peak of the jump, time freezes.

The camera performs a smooth 360-degree orbit around Rider A at rider height while snow particles hang in the air.

The freeze-time orbit must feel cinematic, stable, elegant, and clean.

The rider should remain readable in silhouette.

Avoid chaotic spinning.
Avoid camera jitter.
Avoid motion breaking.

0:09.5–0:11
Time resumes.

Rider A completes the aerial movement and lands cleanly with a burst of snow.

He rejoins the group and continues descending.

0:11–0:13
All three riders carve through a more advanced coordinated slalom section.

Their movement lines can cross visually in a dynamic way, but they must not collide.

The skier remains centered.
The two snowboarders flank him.

0:13–0:15
Final downhill push.

All three riders charge toward camera with speed, confidence, and strong snow energy.

Snow blasts outward.
The shot ends with a powerful cinematic closing image of the trio descending together.

CAMERA:
Use cinematic action-sports camera language.

Lens feel:
24mm to 28mm wide-angle.
Immersive downhill perspective.
Dynamic but controlled movement.
Strong sense of speed.

Camera progression:

0:00–0:02
Low-angle wide establishing tracking shot.

0:02–0:04
Forward downhill tracking camera moving with the group.

0:04–0:06
Follow-cam with lateral drift as the trio performs slalom turns.

0:06–0:07.5
Push in toward Rider A approaching the jump.

0:07.5–0:09.5
Freeze-time orbital camera move:
smooth 360-degree orbit around Rider A at midair height.
Maintain clean framing.
Keep the rider centered.
Keep the silhouette readable.

0:09.5–0:11
Follow the landing with a slight downward sweep and momentum recovery.

0:11–0:13
Wide weaving camera capturing all three riders during the advanced slalom.

0:13–0:15
Dynamic frontal or slightly low-angle downhill shot as the three riders charge toward camera.

Camera motion should feel:
smooth,
cinematic,
controlled,
athletic,
fast,
clear,
not shaky,
not chaotic.

LIGHTING / COLOR:
Bright daylight mountain lighting.

Use:
crisp sunlit snow,
cool blue shadows,
vivid blue sky,
natural alpine contrast,
subtle bloom on snow highlights,
realistic snow sparkle,
clean atmospheric clarity.

Color palette:
white snow,
blue sky,
green rider,
blue rider,
red rider,
dark winter gear contrast.

The snow should glow cleanly in sunlight.
Shadows should remain cool and slightly blue.
Avoid overexposure.
Avoid muddy colors.

STYLE:
Premium stylized cinematic manga-inspired sports action.

The result should feel like a finished animated action video, not a storyboard sheet.

Use:
dynamic poses,
clean silhouettes,
strong speed sensation,
readable movement,
energetic snow-action style,
cinematic framing,
clear sports choreography.

Not childish.
Not goofy.
Not flat comic panels.
Not static illustration.
Not cheap animation.
Not realistic documentary footage.
This is a polished stylized action sequence.

RHYTHM / TIME:
Total duration: 15 seconds.

The motion must feel continuous, not like disconnected clips.

Rhythm:
clear start,
acceleration,
slalom rhythm,
jump anticipation,
dramatic freeze-time midair orbit,
strong landing,
advanced coordinated slalom,
final downhill drive.

Use speed variation:
fast downhill flow,
brief suspended freeze-time moment during the jump,
renewed acceleration after landing,
energetic closing finish.

AUDIO / DIALOGUE:
No dialogue.

Optional sound design:
ski and snowboard scraping on snow,
wind rush,
carving whooshes,
snow spray impacts,
subtle cinematic bass rise during jump approach,
suspended ambient hush during freeze-time orbit,
strong landing thump,
energetic downhill rush at the end.

CONSISTENCY:
Keep all three riders consistent throughout the full video.

Rider A = green snowboarder.
Rider B = blue skier.
Rider C = red snowboarder.

Keep:
same outfit colors,
same helmets,
same goggles,
same gear,
same equipment,
same body proportions,
same visual identity.

Do not switch equipment between riders.
Do not duplicate characters.
Do not replace the skier with a snowboarder.
Do not replace a snowboarder with a skier.
Do not add extra riders.
Do not add crowds.
Freeze-time orbit must happen only for Rider A, the green snowboarder.

RESTRICTIONS / NEGATIVES:
No text.
No numbers.
No typography.
No logo.
No watermark.
No storyboard panels.
No comic page borders.
No poster layout.
No arrows.
No UI elements.
No captions.
No extra riders.
No crowd.
No duplicated characters.
No duplicated snowboards.
No duplicated skis.
No missing skis.
No missing snowboard.
No changing outfits.
No mismatched helmets.
No equipment switching.
No skier turning into snowboarder.
No snowboarder turning into skier.
No extra limbs.
No broken anatomy.
No warped legs.
No floating disconnected limbs.
No distorted hands.
No melted faces.
No unrealistic body twisting.
No camera chaos.
No jittery motion.
No random jump cuts.
No broken continuity.
No inconsistent environment.
No blizzard.
No night scene.
No muddy snow.
No urban buildings.
No fantasy weapons.
No unrelated visual effects.
No collisions between riders.
No chaotic orbit during freeze-time.

OUTPUT:
15 seconds.
Vertical 9:16.
24 fps or 30 fps.
High detail.
Smooth continuous motion.

---

# Important Note

This prompt is designed for a single 15-second generation.

That is technically demanding because the scene includes:

- three characters
- fast downhill motion
- skis and snowboards
- slalom gates
- one jump
- freeze-time
- 360° camera orbit
- character consistency
- equipment consistency

For better control, the same sequence can be split into three 5-second clips:

1. Start + acceleration + first slalom
2. Jump + freeze-time 360 orbit
3. Landing + final slalom + downhill push

This usually gives better continuity and fewer motion errors.
Premium cinematic action.
Final frame: the three riders descending together with strong speed and snow energy.
