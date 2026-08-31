# Final Spark — Pitch Deck

Live at **https://jackwdharris.github.io/FinalSparkPitch/**

11 slides. Trimmed from the recruitment deck by cutting its slides 2–13
(the personal history: playtime, the 2D demo, Guildrun, the 3D prototype).

| Key | Action |
| --- | --- |
| `→` `↓` `Space` / tap right | Next step or slide |
| `←` `↑` / tap left | Back |
| `Home` / `End` | First / last slide |
| `F` | Fullscreen |

Click-through reveals: **3** The Patterns (3), **8** The World (4, enters empty), **9** (1).

## Slides

1. Title
2. Games I Love
3. The Patterns
4. Plays Like
5. But It Feels Like
6. What If It Looked Like This?
7. Secrets inside an autobattler
8. The World — four beats
9. Final Spark is… — second sentence on a click
10. The Team We're Building
11. Close — QR

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
