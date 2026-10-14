---
name: Vix Personal Video Creator By BK Han
description: Create HeyGen personal videos with your own face and voice, using hook, founder-story, and offer variations reviewed before posting.
---

# Vix Personal Video Creator By BK Han

> **v0.1 draft**

## 1. Connect HeyGen

- The Creator plan is enough.
- Connect via an assistant's HeyGen connector or a private API key.
- Check credits before rendering.

## 2. Photo

- Sharp, front-facing, plain background, good light, head and shoulders.
- Your own face only.

## 3. Voice

- Record 1–2 minutes of natural talking in a quiet room.
- Clean it:

  ```bash
  ffmpeg -i raw.m4a -af "highpass=f=80,afftdn=nf=-25,loudnorm=I=-16" clean.m4a
  ```

- Listen back.

## 4. Build once

- Create a photo avatar and a voice clone.
- Do the HeyGen consent yourself.
- Reuse the same avatar and voice in every video.

## 5. Prompt the Video Agent

Include: avatar, voice, 9:16, length, captions, brand tag, CTA link.

**Variations:**

| Variation | Length | Structure |
|---|---|---|
| Hook | 20–30s | Bold claim, why now, link |
| Founder story | 40–60s | Past to now, turning point, lesson, link |
| Offer | 15–20s | Product, price, one benefit, urgency, link |

Real claims only.

## 6. Review before posting

- Watch the full video.
- Check face, lip sync, captions, price, and link.
- Test the link.
- Save clearly named files.
- Post only after approval.
- Add AI disclosure where required.

## Checklist

- [ ] Clear photo
- [ ] Clean voice
- [ ] Consent
- [ ] Credits
- [ ] Captions
- [ ] Link tested
- [ ] Approved
