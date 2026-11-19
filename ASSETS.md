# Final Spark — Pitch Deck

Live at **https://jackwdharris.github.io/FinalSparkPitch/**

21 slides, restructured Nov 2026 from Dean's notes: slides 1-6 unchanged, then
the pitch (7-8), a Game Design section (9-13), an Art section (14-20) and a
closing roles slide with the big QR (21).

| Key | Action |
| --- | --- |
| `→` `↓` `Space` / tap right | Next step or slide |
| `←` `↑` / tap left | Back |
| `Home` / `End` | First / last slide |
| `F` | Fullscreen |

Click-through reveals: **3** The Patterns (3), **7** What is it? (1 — the
closing sentence), **8** Narrative Overview (4, enters empty).

## Slides

1. Title
2. Games I Love
3. The Patterns
4. Plays Like
5. But It Feels Like
6. Secrets inside an autobattler
7. What is it? — pitch copy + Anubis / Itzpapalotl / Morrigan portraits
8. Narrative Overview — the four story beats
9. Gameplay Overview — Guildrun + Blue Prince
10. Auto-Battler — two points + TFT board / augments
11. Auto-Battler — two Unity demo clips
12. Secrets and Puzzles — two points + Animal Well / Blue Prince references
13. Secrets and Puzzles — two design-concept images
14. Visual Pillars — five pillars + the three god portraits
15. Character Concept Art — four pieces in two size-matched pairs
16. Environment Concept — sky islands + night island
17. Target Fidelity — Stylized Realism — four 3D model sheets, 2 x 2
18. Environment Models — island painting + five models, two justified rows
19. VFX and Tech Art — Status VFX / Attack VFX clips
20. UI Art — Art Deco copy + class card / god-select UI
21. Open Roles — role cards + big QR

## New asset slots (Nov 2026)

Until a file exists the slot shows a labelled placeholder with its path.

| Slide | Basename(s) in `assets/` |
| --- | --- |
| 7, 14 | `god-anubis`, `god-itzpapalotl`, `god-morrigan` |
| 9 | `gameplay-guildrun`, `gameplay-blueprince` |
| 10 | `autobattler-tft-board`, `autobattler-tft-augments` |
| 11 | `demo-autobattler-1`, `demo-autobattler-2` (clips) |
| 12 | `secrets-animalwell`, `secrets-blueprince` |
| 13 | `secrets-concept-1`, `secrets-concept-2` |
| 15 | `concept-character-1` … `concept-character-4` |
| 16 | `concept-environment-1`, `concept-environment-2` |
| 17 | `model-anubis`, `model-itzpapalotl`, `model-morrigan`, `model-ame` |
| 18 | `env-model-1` … `env-model-6` |
| 19 | `vfx-status` (heal clip), `vfx-attack` (clips) — cropped to the Unity game view |
| 20 | `ui-art-1`, `ui-art-2` |
| 21 + corner | `qr` |

## Assets

Every slot names a path **without an extension**; the deck probes
`mp4 → webm → mov → gif → png → jpg → webp` and uses the first that loads.
Drop a replacement in under the same basename and it just works. A clip or GIF
beats a still of the same name.

Slides load their own media on arrival with the neighbours warmed, so first
paint is only the HTML — this is what keeps it working on phones.

## Scaling

Authored on a fixed 1600 × 900 canvas, scaled as a unit to fit the window. In a
portrait viewport the stage rotates onto the long axis so it fills a phone
screen rather than becoming a thin strip. Work in plain pixels against that
canvas if you edit sizes — `vw`/`vh` would measure the window, not the canvas.

## Publishing

```bash
cd ~/Documents/FinalSpark_Pitch
git add -A && git commit -m "your message" && git push
```

The previous pitch deck (the 16.7MB single-file version from May) is still in
this repo's git history — `git log -- index.html` to find it.

Sibling site: the full 23-slide recruitment deck at
https://jackwdharris.github.io/FinalSparkRecruitment/
(`~/Documents/FinalSpark_RecruitmentDeck`).
