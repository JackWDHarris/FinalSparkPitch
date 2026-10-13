# Final Spark — Pitch Deck

Live at **https://jackwdharris.github.io/FinalSparkPitch/**

23 slides. Trimmed from the recruitment deck by cutting its slides 2–13
(the personal history: playtime, the 2D demo, Guildrun, the 3D prototype).
Slides 9–22 are the art-recruitment deck (Fall recruitment 2026), restyled to
match. Dropped from it: the title slide, "What is Final Spark?" (restates slide
8), the hidden "3D Art" slide, the thank-you slide, and the QR on its closing
slide.

| Key | Action |
| --- | --- |
| `→` `↓` `Space` / tap right | Next step or slide |
| `←` `↑` / tap left | Back |
| `Home` / `End` | First / last slide |
| `F` | Fullscreen |

Click-through reveals: **3** The Patterns (3), **7** The World (4, enters empty), **8** (1).

## Slides

1. Title
2. Games I Love
3. The Patterns
4. Plays Like
5. But It Feels Like
6. Secrets inside an autobattler
7. The World — four beats
8. Final Spark is… — second sentence on a click
9. Style Overview — who we're looking for
10. Style Overview — key details
11. Style Overview — inspirations (Ori, Hades, League of Legends)
12. 3D Art Roles
13. What We Already Have — Anubis 3D
14. What We Already Have — 3D props
15. 2D Art
16. 2D Art Roles — concept / portrait / landscape
17. What We Already Have — 2D
18. Tech Art
19. Tech Art Roles
20. UI Art Roles — Art Deco
21. UI Art Roles — references (Minimal, Crown Gambit, Sultan's Game)
22. Closing — didn't see your role? Let us know!
23. Close — QR

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
