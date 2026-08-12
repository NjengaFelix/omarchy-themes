# omarchy-themes

Extra background images for [Omarchy](https://omarchy.org/).

## Usage

Omarchy looks for user-supplied wallpapers in `~/.config/omarchy/backgrounds/<theme-name>/`,
where `<theme-name>` matches the name in `~/.config/omarchy/current/theme.name`
(e.g. `tokyo-night`, `catppuccin`, `hackerman`).

Any image placed there is merged into that theme's background rotation
alongside its stock wallpapers — no theme files are modified.

1. Clone this repo:
   ```bash
   git clone https://github.com/NjengaFelix/omarchy-themes.git
   ```
2. Copy an image into whichever theme's folder you want it to show up in
   (not tied to any specific theme — pick your own, creating the folder if it doesn't exist):
   ```bash
   mkdir -p ~/.config/omarchy/backgrounds/<your-theme-name>
   cp omarchy-themes/backgrounds/audi-quattro-intense.jpg ~/.config/omarchy/backgrounds/<your-theme-name>/
   ```
3. Apply it:
   ```bash
   # Set it directly
   omarchy theme bg set ~/.config/omarchy/backgrounds/<your-theme-name>/audi-quattro-intense.jpg

   # Or cycle through backgrounds until it comes up
   omarchy theme bg next
   ```

## Backgrounds

| File | Description |
|------|--------------|
| `backgrounds/audi-quattro-intense.jpg` | Synthwave-style Audi Quattro rally car at sunset — works well with any neon/retro-leaning theme, but drop it into whichever theme folder you like |
| `backgrounds/quattro-mouton-ghibli.jpg` | Ghibli-style illustration of a rally driver beside an Audi Sport livery car at sunset — same retro rally aesthetic, any theme folder works |
