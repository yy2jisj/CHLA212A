# CHLA 212A first draft coverage

The supplied 16-part brief is the checklist for this draft. [Unverified] I cannot verify alignment with the instructor’s project instructions, grading rubric, lecture slides, or assigned readings. The attachment, workspace, and targeted Drive searches did not yield these materials. Check the course’s terminology, expected numbering of Al-Farabi’s hierarchy, required passages, and permitted Western comparison against those materials.

| Brief | Deliverable and verification target |
| --- | --- |
| 1–2. Objective and academic requirements | Continuous presentation, one fictional AI case, all four Islamic perspectives, Western comparison, glossary, arguments, objections, and qualified findings. |
| 3. Opening | Human and machine imagery, four questions revealed in sequence, and a case dossier. |
| 4. Al-Farabi | First Cause, nine celestial associations, tenth Active Intellect, terrestrial world, separate human intellect sequence, interactive camera and rotation. |
| 5. Ikhwan al-Safa | Animated relations between metaphysical principles, cosmic and individual soul, faculties, and intellectual ascent. |
| 6. Ibn Sina | Four labeled adaptation stages, first-person imagery, optional fading audio, audience response, argument, objections, and AI application. |
| 7. Mulla Sadra | Side-by-side animation of changes in appearance and a metaphor for changes in mode of existence, followed by an argument and its application. |
| 8. Western comparison | Searle’s Chinese Room with an operable rulebook, Systems Reply and response, and direct comparison with all four Islamic frameworks. |
| 9. Courtroom | Scroll-controlled 3D camera from the roofline through opening walnut doors and down the aisle. Textured limestone, worn plaster, recessed windows, and an enlarged brass scales relief. Five inspectable arguments with sources and separate verdicts on three claims. |
| 10. Comparative analysis | Five positions across eight requested dimensions, plus cross-framework synthesis. |
| 11. Interview | Documentary player with local video and captions support, planned questions, and findings workspace. |
| 12–14. Navigation, design and technical | Progress and active navigation, keyboard, presentation mode, replay and skip, adaptive layout, reduced motion, WebGL fallback, optional audio, and single-file runtime. |
| 15. References | Inline notes keyed to an end bibliography, with course alignment flagged. |
| 16. Testing and delivery | Local HTTP and direct-file browser tests with motion, interaction, and responsive checks. |

## Open and present

From any PowerShell directory on this PC, run:

```powershell
Start-Process 'C:\Users\yaa49\Desktop\CHLA212A\index.html'
```

Use **Contents** to jump to an exhibit. Use **Present** for larger type and chapter controls. The page embeds Three.js, textures, exhibit artwork, and synthesized optional audio. Bibliography links use the internet. The video player opens the group’s local recording and optional WebVTT captions when those files are available.

For Vercel, put the single HTML file in the deployment root and use the **Other** framework preset with the build command disabled. [Vercel’s static build instructions](https://vercel.com/docs/builds/configure-a-build)

## Browser verification

- Chrome over localhost at 1440 × 960. Checked all 11 chapters, the 13 cosmology stops, 5 Ikhwan relations, all 4 Flying Man stages, the courtroom at 13 points along its path, navigation, replay, optional audio controls, the Chinese Room, the ballot, and the interview player with a temporary local test clip and captions.
- Offline direct-file test. Both WebGL scenes rendered with embedded assets. With WebGL blocked, each showed an illustrated view and retained its chapter controls.
- Chrome touch emulation at 820 × 1180 and 1180 × 820 and reduced-motion testing at 390 × 844. [Unverified] I cannot verify performance on a physical iPad or classroom projector.

## Artwork

Generated with the built-in ImageGen tool and embedded in `index.html`. The prompts requested opposing limestone and bronze-filament profiles for the opening, a first-person cedar-paneled study and isolated hands for the Flying Man, and flat scans of aged lime plaster and dark walnut. Four additional prompts used fixed 3D camera frames to request realistic weathered limestone and slate, hand-carved entrance doors, worn walnut courtroom pews with soft window light, and a judge’s bench with period woodwork. The 3D model includes the enlarged scales relief.
