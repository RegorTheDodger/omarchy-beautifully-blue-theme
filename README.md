# Beautifully Blue — Omarchy theme

Beautifully Blue is a calm, modern theme for Omarchy with a blue-focused color palette and readable contrast. It aims to be pleasant for long sessions while keeping UI elements clear and consistent.

![Preview screenshot](https://github.com/user-attachments/assets/c581cc99-b8c4-44fe-b8b9-916f355b1dda)

## Highlights
- Soothing blue palette with readable contrast
- Clean, minimal UI treatment for windows, panels, and lists
- Small CSS footprint; light Lua integrations where needed

## Demo / Screenshots
- Add additional screenshots or an animated GIF in this section to show:
  - Main desktop with theme active
  - App lists / menus
  - Focused vs unfocused window states

## Installation
### Pick one:

#### TERMINAL (recommended)
- Install directly from this repository:
  omarchy-theme-install https://github.com/dxrkinfuser44/omarchy-beautifully-blue-theme.git

#### WALKER MENU
1. Copy this link: `https://github.com/dxrkinfuser44/omarchy-beautifully-blue-theme.git`
2. Open Walker: SUPER+ALT+SPACE
3. Navigate: Install → Style → Theme
4. Paste (CTRL+SHIFT+V) and press Enter

## Uninstall
- Use your theme manager or remove the theme folder from Omarchy's themes directory.
- If you installed via omarchy-theme-install, consult Omarchy docs for removal steps.

## Compatibility
- Tested with Omarchy version: (add tested version here)
- Should work with other recent Omarchy versions; report any incompatibilities.

## Color palette
### Primary:
- Deep Ocean: #0B3D91
- Sky Accent: #2F80ED
### Secondary / UI:
- Soft Blue: #58A6FF
- Muted Slate: #233D66
### Neutral:
- Paper: #F6F9FF
- Ink (text): #0F172A

(Replace these with the exact hex values used by your CSS if different.)

## Files & Structure
- styles/ (or root)
  - theme.css (main CSS — variables, layout, UI styling)
  - colors.css (palette variables)
  - widgets.lua (Lua hooks for dynamic elements)
- assets/
  - screenshots/ (recommended place for images used in README)

## Customize
To tweak colors or fonts:
1. Open the theme CSS file (e.g., `theme.css`, `colors.css`) and edit the CSS variables at the top:
   - --primary, --accent, --bg, --text, etc.
2. Save and re-apply the theme in Omarchy (restart or reload theme if supported).
If the theme uses a Lua file for runtime variables, update the corresponding values there (e.g., `theme_colors = { ... }`).

### Activate the theme
- After installation, open Walker → Style → Theme and select "Beautifully Blue" (or restart Omarchy if needed).

## Troubleshooting
- If some UI elements remain unstyled:
  - Check for conflicting user themes or overrides.
  - Look for missing CSS selectors in your Omarchy version — UI element class names can change across versions.
- For runtime errors, check Omarchy logs and the Lua files included in the theme.

## Contributing
- Contributions welcome — fork the repo, make changes, and open a PR.
- Please include:
  - Clear description of changes
  - Screenshots for visual changes
  - If adding or changing colors, include a small rationale (accessibility, contrast)

## Credits & Inspiration
- Based on ideas from:
  - omarchy-ayaka-theme — https://github.com/abhijeet-swami/omarchy-ayaka-theme
  - omarchy-bauhaus-theme — https://github.com/somerocketeer/omarchy-bauhaus-theme
### TERMINAL
`omarchy-theme-install https://github.com/RegorTheDodger/omarchy-beautifully-blue-theme.git`
### WALKER MENU
1. Copy this link: `https://github.com/RegorTheDodger/omarchy-beautifully-blue-theme.git`
2. Open Walker, `SUPER+ALT+SPACE`, navigate to: Install < Style < Theme
3. Paste: `CTRL+SHIFT+V`, then press enter/return.