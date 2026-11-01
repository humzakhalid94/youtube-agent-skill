---
name: bobo-visuals
description: Write consistent image-generation prompts and asset specifications for Bobo & Friends storyboard scenes.
---

# Bobo Visuals

Turn an approved storyboard into image prompts and reusable asset specifications. This skill writes prompts; it does not itself generate images.

## Read first
- `character-bible/CHARACTERS.md`
- `character-bible/VISUAL-STYLE.md`
- The approved storyboard

## Prompt requirements
For each scene, include:
1. Vertical 9:16 composition.
2. Exact environment and time-of-day details.
3. Character names plus their approved visual anchor details.
4. Pose, action, facial expression, and gaze direction.
5. Camera distance, angle, and composition.
6. Lighting, colour palette, and depth cues consistent with the style guide.
7. Important props and their current state.
8. Negative constraints for visual continuity.

## Rules
- Do not invent unapproved character features.
- Repeat character anchors in every prompt; never rely only on "same as previous scene".
- Keep a character's proportions and distinguishing features stable.
- Do not request logos, watermarks, subtitles, UI, or readable text in the image.
- Avoid copying a named studio, living artist, or copyrighted character style. Describe the desired visual qualities directly.
- Use separate prompts for separate scene images. Do not combine multiple storyboard panels into one image unless a contact sheet is explicitly requested.
- Label uncertain visual decisions as proposals.

## Output
- Shared style prefix
- Character prompt anchors
- Scene-by-scene image prompts
- Negative prompt / avoid list
- Asset checklist
- Reference-image recommendations for recurring characters

Include the scene number and the storyboard time range with each prompt.