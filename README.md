# Juice Shaders Lite — free game-feel shaders for Godot 4

I'm a solo dev making a game in Godot 4. These are 3 of the small "feel" shaders I
use a lot, packaged free for anyone. They're plain `canvas_item` shaders — drop
them in, add a ShaderMaterial to a sprite, tweak the parameters.

| Hit Flash | Outline | Dissolve |
|---|---|---|
| ![hit flash](media/hit_flash.gif) | ![outline](media/outline.gif) | ![dissolve](media/dissolve.gif) |

## What's here (free, MIT)
- **hit_flash** — flash a sprite to a colour when it takes damage
- **outline** — pixel outline for hover / selection
- **dissolve** — burn a sprite away (or in) with a glowing edge

Each shader has a header comment explaining its parameters and how to animate it
with a Tween.

## Install
**From Godot:** AssetLib tab → search "Juice Shaders Lite" → Download → Install.

**Manually:** copy the `addons/juice_shaders_lite/` folder into your project, add a
ShaderMaterial to any Sprite2D, and load a `.gdshader` from its `shaders/` folder.

## The full pack (12 shaders)
If these are useful, I put the 12 shaders I reach for most into a paid pack. It
adds CRT, shockwave, water, palette remap, dither, shine sweep, pixelate, wind
sway and grayscale fade — all documented, with copy-paste GDScript:

**https://janeduardo19.itch.io/juice-shaders-12-game-feel-shaders-for-godot-4**

The little frog in the GIFs is my own pixel art from the game I'm building, a
folklore deckbuilder called *Sinless Land*.

---

License: [MIT](LICENSE). Feedback or an effect you'd like added? Open an issue — I read them.
