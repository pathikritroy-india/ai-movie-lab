# PROJECT HANDOFF BRIEF — "Sui Dhaaga Se Desh Tak"

**One-Minute AI-Generated Short Film | Handoff date: July 14, 2026**

This document summarizes \~1.5 hours of concept development done in Claude chat. Cowork should pick up from "CURRENT STATUS & NEXT STEPS" below.

---

## 1\. THE CONCEPT (LOCKED)

**Working title:** Sui Dhaaga Se Desh Tak (सुई धागे से देश तक — "From Needle and Thread to the Nation") **Tagline used on poster:** "A Journey from Needle and Thread across the Country"

**Story:** A father-son tailor duo travels across India in a vintage mobile-tailoring van ("Tailors on Wheels"). At each of the four corners of India they collaborate with a local father-son craftsman pair and collect one signature craft element. All four elements come together in a single fusion garment, revealed at the end.

**The four stops and crafts:**

1. **North — Srinagar, Kashmir:** Sozni embroidery (Dal Lake, snow peaks, pheran-clad locals)  
2. **West — Bhuj, Kutch, Gujarat:** Mirror work / bandhani (White Rann salt desert)  
3. **East — Shantiniketan/Bishnupur, Bengal:** Kantha stitch (red earth, green paddy, monsoon)  
4. **South — Kanchipuram, Tamil Nadu:** Kanjeevaram zari silk border (temple gopuram, loom)

**The two lead characters (must remain visually consistent in every asset):**

- **Father:** elderly Indian man, mid-60s, wrinkled kind face, spectacles, white kurta, measuring tape around neck, works at a black vintage Singer sewing machine  
- **Son:** Indian man, late 20s, short beard, indigo Nehru jacket over rolled-up jeans

**The van (a recurring "character"):** weathered teal-green 1970s Indian van, hand-painted folk motifs, "TAILORS ON WHEELS" signage, number plate "DL 04 1974" (1974 \= year father started tailoring — adopted as story lore). Rear opens into a warm-lit mobile tailoring studio.

---

## 2\. THE POSTER (LOCKED — FINAL MASTER REFERENCE)

Created in Google Gemini (free tier) through 3 refinement rounds. Final version includes:

- Both characters, van, Singer machine on an open highway at golden hour  
- Four-corner sky blend: Himalayan peaks, cracked white Rann of Kutch salt desert, South Indian gopuram, green Bengal paddy fields  
- The garment in the son's hands shows all four crafts: sozni on one sleeve, mirror-work chest, kantha stitching, golden zari hem border  
- Devanagari title rendered correctly \+ English subtitle \+ tagline  
- Known accepted imperfection: van door signage reads cut-off "STITCHIN JOURNE" — decision was to leave it (reads as natural perspective) or patch later in Canva. Do NOT burn generations trying to fix it.

**This poster is the character/style reference for ALL future generations.** Every new scene prompt must instruct the image model to keep the two men, their clothing, and the van identical to this reference.

---

## 3\. THE ONE-MINUTE FILM STRUCTURE (LOCKED)

Workflow per scene: **still image in Gemini (using poster as reference) → review → animate via image-to-video (Kling) → review → next scene.** All scene stills in 16:9 horizontal (poster was 2:3 vertical).

| \# | Scene | Time | Content |
| :---- | :---- | :---- | :---- |
| 1 | The Departure | 0:00–0:08 | Dawn; father bids farewell to his old shop ("दर्ज़ी — Since 1974"); son loads fabric into van; brass diya on doorstep |
| 2 | The Map | 0:08–0:14 | Night, van interior, lamplight; hand-drawn India map with 4 empty swatch corners; father's finger traces route |
| 3 | North: Kashmir | 0:14–0:22 | Dal Lake mist; local father-son pair teaches sozni; four hands on one sleeve; swatch 1 pinned |
| 4 | West: Kutch | 0:22–0:30 | White salt desert; mirror-work on chest panel; mirrors scatter sunlight; swatch 2 pinned |
| 5 | East: Bengal | 0:30–0:38 | Red earth, paddy, gentle rain, veranda; kantha stitch on other sleeve; tea glasses; swatch 3 pinned |
| 6 | South: Kanchipuram | 0:38–0:46 | Gopuram at golden hour; loom with golden zari threads; border added at hem; swatch 4 pinned — map complete |
| 7 | The Final Stitch | 0:46–0:54 | Dusk, back at van (mirrors poster); father sews final stitch; son reveals finished garment in the wind |
| 8 | Title Card | 0:54–1:00 | Father dresses the son in the garment; wide shot; title fades in |

Repeating rhythm at each stop: arrive → learn → stitch → pin swatch. No dialogue needed.

**Scene 1 still prompt was already written and delivered** (dawn lane, old shop, diya, father's hand on doorframe, son pausing mid-load, 16:9). It may or may not have been generated yet — check with Pathikrit.

---

## 4\. TOOL DECISIONS & CONSTRAINTS (IMPORTANT)

**User context:** Pathikrit is in Kolkata, India, on a MacBook, using free tiers only (no subscriptions).

- **Google Gemini (free):** stills engine. Works well; \~20 images/day. Video (Veo) is NOT available on his free tier — confirmed by checking model dropdown and \+ menu (only "Create image" and "Create music" exist). Do not pursue Veo.  
- **Dreamina/CapCut (Seedance 2.0):** BLOCKED in India ("Coming up soon..." wall after DOB entry; ByteDance apps banned in India). Abandoned.  
- **Kling AI (kling.ai, free):** chosen animation engine. Account created. **66 free monthly credits** (expire Aug 14, 2026). Settings locked for economy: model **Video 1.6**, Standard, 720p, 5s, 1 output \= **20 credits/clip** (Video 3.0 with native audio cost 45 — rejected). So \~3 clips/month free.  
- **First test clip:** poster animated with slow push-in motion prompt; was submitted and sitting in the busy free-track queue at handoff time (an upsell popup appeared — no purchase made or needed). **Status unknown — first thing to check.**  
- **Backup free engines if Kling credits run out:** Hailuo AI (hailuoai.video), Luma Dream Machine (lumalabs.ai). Not yet signed up.  
- **Warned-off scam sites:** seedance2.ai, seedance2.app, seedance.tv, and a fake "Seedance GitHub installer" — avoid.

**Standard motion prompt pattern used (adapt per scene):** "Cinematic slow push-in... \[scene-specific natural motion\]... The men and the van stay in place; only natural motion and slow camera movement. Photorealistic, film grain, no distortion of faces." Negative prompt: "distorted faces, warped bodies, extra limbs, cartoon look, morphing."

**Prompting conventions that worked:**

- Poster edits: "STRICT IMAGE EDIT — NOT A NEW GENERATION" framing, explicit preserve-list, numbered edits only, built-in fallbacks ("if it cannot be done cleanly, leave unchanged")  
- New scenes: upload poster as reference \+ "characters must appear IDENTICAL, do not redesign"

---

## 5\. CURRENT STATUS & NEXT STEPS FOR COWORK

**Immediate:**

1. Check Kling queue result (Assets tab): did the poster test clip render? Evaluate: (a) faces stable? (b) garment motion natural? (c) any unwanted invented movement? Credits should show 46 remaining if the 20-credit job committed.  
2. Confirm whether Scene 1 still has been generated in Gemini yet; if not, generate using the Scene 1 prompt (regenerate from Section 3 details if needed).

**Then the production loop, scene by scene (1 → 8):** still in Gemini (16:9, poster as reference) → review → animate in Kling (20-credit settings) → review → next.

**Budget note:** 66 Kling credits ≈ 3 clips. Eight scenes will require either waiting for monthly renewal, adding Hailuo/Luma free tiers, or the user choosing to pay. Plan the sequencing accordingly (suggest: validate quality with test clip first, then prioritize Scenes 1, 7, 8 — the emotional pillars).

**Later stages (not yet planned in detail):** editing/stitching the 8 clips (CapCut is banned in India — suggest DaVinci Resolve free, or iMovie on his MacBook), music/sound, title cards, final export.

---

## 6\. FILES TO UPLOAD INTO COWORK ALONGSIDE THIS BRIEF

1. **FINAL LOCKED POSTER (essential)** — the third/latest Gemini version: the one WITH the "DL 04 1974" number plate and the cracked salt desert. This is the master character/style reference for everything.  
2. **Round-2 poster (optional backup)** — the version saved in Downloads before the final edit round (salt desert fixed, but plate still read "94 9").  
3. **The Kling test clip (when ready)** — download from Kling Assets and upload so Cowork can assess animation quality.  
4. **Scene 1 still (if already generated in Gemini)**.

Only item 1 is strictly required to continue; the rest add context.  
