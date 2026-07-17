# Project Hand-off: *Sui Dhaaga - The Road Trip Tailors*

**Project owner:** Pathikrit Roy  
**Project type:** 25-second, dialogue-free AI short film and teaching case study  
**Status:** Final film exported; V1.1 technical documentation complete  
**Last updated:** 17 July 2026

---

## 1. One-paragraph brief

Create a gentle, cinematic 25-second Indian road-film about an elderly tailor and his son taking their mobile tailoring studio across India. The story must be understood without dialogue. A weathered teal-green 1970s van, the father, the son, and the making of a garment are the visual anchors. The emotional arc is inherited craft becoming a shared future: departure, service across regions, pride in the finished work, and a quiet blue-hour departure into the distance.

**Final end text:** `the journey continues..`

---

## 2. Current final deliverables

- Final video export: `C:\Users\pathi\Downloads\Video Project1.mp4`
- Teaching guide V1.1 (Word): `C:\Users\pathi\Documents\Codex\2026-07-14\chrome-plugin-chrome-openai-bundled-file\outputs\Sui_Dhaaga_AI_Film_Lab_Guide_V1_1.docx`
- Teaching guide V1.1 (PDF): `C:\Users\pathi\Documents\Codex\2026-07-14\chrome-plugin-chrome-openai-bundled-file\outputs\Sui_Dhaaga_AI_Film_Lab_Guide_V1_1.pdf`

The film is approximately 25 seconds long and uses five five-second scenes.

---

## 3. Tool and model history

| Stage | Tool/model used | Decision and reason | Important outcome |
|---|---|---|---|
| Initial ideation | Claude Chat, Fable 5 | Used as a conversational development partner to propose four short-film concepts. | Audience-selected concept: **The Road Trip Tailors**. |
| Continued ideation/workflow | Claude Cowork, Fable 5 | Continued the same project after early ideation. | Work paused when the daily limit was reached. |
| Handoff and remaining production | ChatGPT Codex, 5.6 Terra | Chosen after the Claude Cowork limit; saved project briefs allowed continuation. | Continued image/video/edit guidance and created final documentation. |
| Still-image generation | Google Gemini | Used to create one 16:9 locked reference still for each scene. | Four approved stills are available locally; Scene 5 is represented in the final video and storyboard. |
| Image-to-video exploration | Kling considered, then stopped | Kling was not used further. | Avoided spending time/credits there. |
| Image-to-video final tool | Pika | Chosen as the viable free image-to-video option. | Five separate 5-second clips were generated. |
| Edit and sound | Microsoft Clipchamp | Chosen because it was available in the signed-in browser and could assemble/export the project. | Five clips assembled, title added, score added, final MP4 exported. |

### Core lesson from the hand-off

The project did **not** depend on one model. It depended on a saved brief containing the story, locked visual anchors, approved assets, exact prompts, current status, and next action. The brief is the source of truth; individual models and tools are interchangeable production workstations.

---

## 4. Story development and audience choice

The concept-selection exercise presented four directions:

1. **The Last Projectionist** - a fading cinema and shared family memory.
2. **The River Letter** - a letter travelling through landscapes to reconnect a family.
3. **The Road Trip Tailors** - a father-son mobile tailoring studio travelling across India.
4. **The Monsoon Postcard** - a young artist sending a visual message home through rain-soaked streets.

The selected idea was **The Road Trip Tailors** because it had:

- A memorable recurring prop/location: the teal mobile tailor van.
- Tactile actions suitable for animation: loading cloth, stitching, smoothing zari, lifting a garment, driving away.
- A clear father-son emotional arc without dialogue.
- Geographic variety while retaining visual continuity.

---

## 5. Locked continuity bible

Repeat these anchors in every new still-image or video prompt.

| Element | Locked specification |
|---|---|
| Van | Weathered teal-green 1970s van; folk-painted mobile tailoring studio; warm practical light inside when relevant. |
| Father | Elderly tailor, white kurta, yellow measuring tape, calm and observant. |
| Son | Young adult; practical, warm presence; blue/indigo waistcoat or jacket in the early scenes. |
| Materials | Colourful fabric bolts, thread, mirror-work, zari, completed patchwork garment. |
| Atmosphere | Dust, cloth movement, rain sheen, lantern light, fireflies, monsoon haze, or breeze - depending on scene. |
| Tone | Gentle, cinematic, restrained, realistic, dialogue-free. |
| Frame | 16:9 throughout. |
| Text rule | Do not rely on AI-generated text. Add the final title in Microsoft Clipchamp. |

---

## 6. Final five-scene structure

| Time | Scene | Story beat | Edit rule |
|---|---|---|---|
| 0:00-0:05 | Departure | Father watches his son load fabric into the van at dawn. | Hard cut in. |
| 0:05-0:10 | Threads of Kutch | Craft work in the salt desert. | Hard cut. |
| 0:10-0:15 | Temple Thread | Zari/saree repair outside a temple after rain. | Hard cut. |
| 0:15-0:20 | Bengal Finale | Father and son hold the completed garment by the glowing van. | Hard cut. |
| 0:20-0:25 | The Road Continues | Van drives away on a Bengal village road at blue hour. | Final visual fade-out only. |

### Final title specification

- **Text:** `the journey continues..`
- **Time:** 0:23-0:25
- **Placement:** lower-centre over Scene 5
- **Style:** small, warm white/soft ivory
- **Animation:** approximately 1-second fade-in on the text layer
- **Do not:** ask Pika to render readable title text

---

## 7. Approved still-image assets

| Scene | Local source still |
|---|---|
| 1 - Departure | `C:\Users\pathi\Downloads\Gemini_Generated_Image_d4.png` |
| 2 - Threads of Kutch | `C:\Users\pathi\Downloads\Gemini_Generated_Image_d5.png` |
| 3 - Temple Thread | `C:\Users\pathi\Downloads\Gemini_Generated_Image_d7.png` |
| 4 - Bengal Finale | `C:\Users\pathi\Downloads\Gemini_Generated_Image_d6.png` |
| 5 - The Road Continues | Use the final Pika output/final MP4 as reference; the replacement road scene was generated later. |

### Still-image prompts used/recommended

#### Scene 1 - Departure

```text
Cinematic dawn in a narrow Indian bazaar. An elderly tailor in a white kurta with a yellow measuring tape stands in his doorway while his son in a blue waistcoat loads folded colourful fabrics into a weathered teal-green 1970s folk-painted van marked TAILORS ON WHEELS. Warm dust, realistic skin, 16:9, no watermark.
```

#### Scene 2 - Threads of Kutch

```text
Cinematic late afternoon on the Kutch salt desert. The same teal-green tailoring van, the elderly tailor hand-stitching a red-and-indigo mirror-work garment, and the same son steadying the cloth. Distant women in traditional Kutch dress, warm wind, realistic Indian craft detail, 16:9, no watermark.
```

#### Scene 3 - Temple Thread

```text
Cinematic early evening outside a South Indian temple after rain. The same teal-green tailoring van; the elderly tailor smooths a gold zari border while the son holds a Kanjeevaram saree. Lanterns, wet stone reflections, temple gopuram, restrained wedding guests, 16:9, no watermark.
```

#### Scene 4 - Bengal Finale

```text
Cinematic blue-hour Bengal paddy fields after rain. The same father and son proudly hold a completed patchwork garment in front of their open, warmly lit teal-green tailoring van. Banyan tree, fireflies, wet path, 16:9, no watermark.
```

#### Scene 5 - The Road Continues

```text
Cinematic blue-hour Bengal village road after rain. The same weathered teal-green 1970s tailoring van drives away from camera between paddy fields; warm tail-lights recede into mist. Distant banyan silhouette, fireflies, locked-off wide 16:9 frame. No readable text, no logo, no extra vehicles.
```

---

## 8. Exact Pika image-to-video prompts

### Scene 1 - Departure

```text
A gentle cinematic dawn departure. The elderly tailor pauses at the shop doorway, softly turning his head toward his son with a warm, proud expression; the yellow measuring tape moves subtly in the breeze. The son slowly lifts and settles the colourful fabric bolts into the open teal-green van. Fine dust motes drift through golden morning light; faint breeze moves fabric and clothing. Slow, subtle camera push-in with natural human motion. Preserve faces, wardrobe, shop, van, and framing. No text, warping, or extra people.
```

### Scene 2 - Threads of Kutch

```text
Cinematic late-afternoon Kutch salt desert. The elderly tailor's hands guide the needle through the red-and-indigo mirror-work garment while his son gently steadies the fabric. A warm desert breeze lifts the garment's edge; fine salt dust drifts across the ground. The distant women remain respectfully soft and still. Slow, graceful camera arc and subtle push-in, natural human movement. Preserve faces, wardrobe, van, garment, and framing. No text, warping, or extra people.
```

### Scene 3 - Temple Thread

```text
Cinematic early evening temple street after rain. The elderly tailor delicately smooths the golden Kanjeevaram zari border while his son keeps the saree gently lifted so it catches the warm lantern light. A light breeze stirs the fabric; rain-slick stone reflects the temple lamps. The softly blurred wedding guests stay calm in the background. Slow rack focus from the shimmering gold border to the father's focused face, then a subtle push-in. Preserve faces, wardrobe, van, saree, temple, and framing. No text, warping, or extra people.
```

### Scene 4 - Bengal Finale

```text
Cinematic blue-hour Bengal paddy fields after rain. The elderly tailor and his son share a quiet proud smile as they slowly raise and hold the completed patchwork garment before the open, warmly lit teal-green van. Fireflies drift through the cool evening air; paddy leaves and the garment move gently in the breeze. Slow, wide tracking pull-back revealing the banyan tree and glowing mobile studio. Preserve faces, wardrobe, van, garment, field, and framing. No text, warping, or extra people.
```

### Scene 5 - The Road Continues

```text
Cinematic 16:9 blue-hour Bengal village road after rain. The same weathered teal-green 1970s tailoring van, with its warm interior light glowing, slowly drives away from camera along a narrow road between lush paddy fields beneath a distant banyan silhouette. Its warm red tail-lights recede gently into the misty blue evening. A few fireflies drift over the roadside; soft monsoon haze and a calm breeze move the paddy leaves. Slow locked-off wide shot, emotional and understated. Preserve the van's folk-painted character and authentic cinematic realism. No readable text, no logos, no watermark, no extra vehicles.
```

### Pika settings and operating notes

- Generate **one scene at a time**.
- Use **5 seconds per scene**.
- Keep the approved still as the image reference.
- Choose restrained movement rather than adding many simultaneous actions.
- Prompt pattern: **action + atmosphere + camera movement + preserve constraints + negative constraints**.
- At the time of production, Pika's free plan was used; 5-second 480p outputs consumed credits. Verify current free-plan limits before starting a new run.

---

## 9. Microsoft Clipchamp assembly recipe

1. Create a **16:9** project.
2. Import clips **one at a time** if batch imports remain at 0%. This was the successful workaround.
3. Place the five Pika clips in the five-scene order above.
4. Use **hard cuts** between scenes to preserve a 25-second total.
5. Do **not** use a Cross fade between scenes if exact runtime matters: it overlaps clips and reduces the overall timeline by its duration.
6. On Scene 5, apply a final fade-out of roughly **0.8-1.0 seconds**.
7. Add the final text layer from 0:23-0:25.
8. Add a free, non-premium instrumental track from **Content library > Music** (not SFX).
9. Start music at 0:00, trim it at the video end, set volume to approximately **15-20%**, and add a **1-second fade-out**.
10. Export at **1080p** and review the complete film full-screen.

### Music selection lesson

Avoid tracks marked with the gold diamond/premium marker. Also avoid a result labelled **SFX** when selecting a continuous score. Search terms used/recommended: `cinematic ambient`, `acoustic`, and `emotional`.

---

## 10. Technical decision log

| Decision point | Alternatives | Final decision | Why |
|---|---|---|---|
| Ideation | Claude Chat, Claude Cowork, ChatGPT Codex | Claude Chat on Fable 5, then Cowork | Strong conversational ideation and option development. |
| Daily-limit fallback | Wait for Claude Cowork reset vs switch models | Switch to ChatGPT Codex 5.6 Terra | Saved brief made continuation immediate. |
| Stills | Generate a full video directly vs lock images first | Lock 16:9 stills in Google Gemini | Easier continuity checking and controlled image-to-video input. |
| Video generator | Kling vs Pika | Pika | Usable free workflow for five separate image-to-video clips. |
| Edit design | Cross-fade-heavy timeline vs exact timed cuts | Hard cuts + final fade | Preserves the 25-second assignment constraint. |
| Typography | Ask video generator to make text vs editor text layer | Microsoft Clipchamp text layer | AI-generated readable text is unreliable. |
| Score | Premium/SFX selection vs free Music asset | Free Music asset | Avoids paid asset lock and supports a full-duration bed. |

---

## 11. Handoff protocol for another model or operator

Before leaving a tool or hitting a usage limit, create/update a hand-off packet with this schema:

```text
PROJECT: Sui Dhaaga - The Road Trip Tailors
CURRENT STAGE: [e.g., Scene 3 Pika generation / Clipchamp audio]
MODEL/TOOL: [product + model/version]
STORY: [one sentence]
LOCKED ANCHORS: [father, son, teal van, costume, palette]
APPROVED ASSETS: [full file paths and scene numbers]
PROMPTS USED: [exact text or document location]
EDIT TARGET: 16:9, 25 seconds, five scenes
KNOWN ISSUE: [e.g., daily cap, stalled import, unavailable free credits]
NEXT ACTION: [one concrete action]
DO NOT CHANGE: [continuity anchors, end-title wording, scene order]
```

### Resume instruction for a new assistant/model

```text
Read the project hand-off first. Restate the story, current stage, locked continuity anchors, assets available, and next action before generating, editing, or changing any prompt. Preserve the 16:9 five-scene / 25-second structure unless the project owner explicitly changes it.
```

---

## 12. Quality-control checklist

- [ ] Every scene is 16:9.
- [ ] The father, son, and teal van remain visually coherent.
- [ ] Motion is subtle and purposeful; there is no visible warping or unwanted extra people.
- [ ] No essential generated text appears inside the Pika output.
- [ ] Scene order is correct and the total remains approximately 25 seconds.
- [ ] End title appears only in Scene 5, from 0:23-0:25.
- [ ] Music is a non-premium Music asset, not an SFX asset.
- [ ] Music is quieter than the visual experience and fades out cleanly.
- [ ] Final export has been watched through once before sharing.

---

## 13. Authorship

The entire project was conceptualized, created, and implemented by **Pathikrit Roy**.

`the journey continues..`
