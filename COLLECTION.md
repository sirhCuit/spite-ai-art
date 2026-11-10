# SPITE — AI Art Collection Index

The collection as a whole is named **SPITE** (named by Sirhc 2026-11-09; born from the anti-AI "theft" debates: copyright infringement, plagiarism, and theft are three distinct things, and ultimately a human problem). Two series under it, started 2026-11-08. Labels on every piece: all-caps Kaushan Script, hollow embossed outline (border only, art shows through the glyph interiors), typeset deterministically with PIL at 3840×3840, never AI-redrawn. Framing standard (from Pastel): subject ~84% of frame, centred at 49.7% across, 48.3% down.

## CORE SERIES — motherboard / circuitry / custom-PC-lighting feel
Icy silver-cyan label outline.

- **#001 (official, approved 2026-11-08)** — `core-series-001-4k.jpg` (same file as `core-series-001-reborn-4k.jpg`)
  - Perfectly circular concentric circuit disc, cyan + violet neon, subtle smoke wisps baked into the art. Circle-check proof: `core-series-001-reborn-circle-check.jpg`.
  - Generation prompt: "Futuristic circuit mandala artwork: a single PERFECTLY CIRCULAR disc made of concentric glowing rings like a round portal, intricate motherboard circuitry in cyan and violet neon on dark metal, flawless radial symmetry in every direction, the outline is one smooth true circle with no corners, no angles, no square or polygonal shapes anywhere, no towers, no spires, no protruding points, the disc floats perfectly centered with black space around all its edges, faint cyan and purple nebula smoke wisps curling softly around the rim, ultra detailed, dark background, no text, no letters"
  - Source generation: `~/workspace/imagine_media/media-generation-core-series-001-regen-a-0-0d2822c0-a492-448f-ad3c-7a3fceee4d34.webp` (candidate A of 3)
  - Superseded: the original petal/tower circuit mandala (`mandala-001-circuit-core-4k.jpg`) and all roundness-warp attempts (`core-series-001-round*.jpg`, `-true-round-`, `-circle-`, `-wisps-`, `-zoomed-`). Its outer band read as a rounded square no matter the warp (gestalt: diagonal towers + straight chords), so Sirhc chose regeneration over more warping.

## PASTEL SERIES — lighter tones, candy textures, whimsical
Warm cream label outline.

- **#001 (official)** — `pastel-series-001-4k.jpg`
  - Smooth pastel nebula-bloom mandala ("Nebula Bloom"), peach/teal/pink, wispy smoke, no hard linework.
  - Source generation: `~/workspace/imagine_media/media-generation-futuristic-mandala-002-0-b4c67fbf-c321-4324-b7d8-e5974c30d858.webp` (originally generated as piece #002 of the unified collection, renumbered when the series split; the generator's burned-in "PIECE #002" text was removed by diffusion fill confined to the bottom label band, pixel-diff verified).

## Posting versions (2080)
- `core-series-001-2080.jpg` / `pastel-series-001-2080.jpg` — clean 2080×2080 downscales of the 4K masters (light sharpening), EXIF Artist / Copyright / ImageDescription embedded. Masters untouched.
- `core-series-001-2080-watermarked.jpg` / `pastel-series-001-2080-watermarked.jpg` — same 2080s plus an incognito watermark: `@circuit_research` in Kaushan Script, diagonal across the centre, white ~30% opacity with a faint dark shadow, so it reads on close look without wrecking the art. Full EXIF added (Artist, Copyright, ImageDescription, Software, DateTime, DateTimeOriginal, UserComment). Verified 2026-11-09: watermark delta is confined to the diagonal band (max 98 Core / 66 Pastel on 0-255); outside the band only JPEG re-encode noise, max 19 Core / 10 Pastel. Clean 2080s kept alongside for comparison.

## Standing rules for future pieces
- Check every generated image before presenting it; never ship on a first-piece check.
- For shape claims, verify with a drawn reference shape over the rendered pixels, not detector numbers alone.
- Change only exactly what was asked; typeset exact text with PIL, never via the image model.
- Wisps on Core pieces stay subtle like Pastel: faint translucent smoke at the rim, no bright opaque puffs.

## Launch
- 2026-11-09: SPITE publicly launched on Threads (@circuit_research) with both #001s, using the watermarked 2080 posting versions, alt text on both images, ending question "Core or Pastel, which one wins?", paired with Juice WRLD & benny blanco "Real Shit".
