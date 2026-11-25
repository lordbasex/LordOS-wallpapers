# Still wallpapers

150 pictures for every LordOS theme, in three sections of 50: `abstract/` (soft 3D shapes, glass and pastel gradients),
`epic/` (LordOS's own mythology: warriors in leather armour, duels, dark and light scenes) and `anime/` (sakura, in
day and night scenes). LordOS lists them from `catalog.json` at the root of this repository, which gives each file's
size and SHA-256; a copy of that catalog ships in LordOS's signed system package.

- **Author:** generated with ChatGPT (OpenAI) for LordOS, from prompts written by the LordOS project, on 2026-11-25.
  Every picture is **AI-generated**: no photograph, real person, logo or readable text was used or asked for.
- **License:** [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). OpenAI's terms assign the output
  to the user; the LordOS project dedicates these pictures to the public domain. Use them for anything, with no credit
  required (a mention of LordOS is welcome).
- **Files:** each folder `<section>/<id>/` holds `thumb.jpg` (320×180), `1080.jpg` (1920×1080) and `2160.jpg`
  (3840×2160), JPEG quality 90 with 4:4:4 chroma (the thumbnail quality 85), centre-cropped to 16:9.
- **Upscaling:** the generator gives 1672×941. `abstract/` and `anime/` are upscaled ×4 with Real-ESRGAN
  (`realesrgan-x4plus`, and `realesrgan-x4plus-anime` for anime), then resized with Lanczos. `epic/` is resized with
  Lanczos and a light unsharp mask, which keeps its fine textures (fur, leather, stone) natural.
