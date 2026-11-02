# Install FM Dugout Template

A plain USS skin for **FM27 Launch Preview**. No build step, BepInEx or
FM Dugout application is required.

1. Extract `FM-Dugout-Template.zip`.
2. Move the extracted **FM Dugout Template** folder into your FM27 user-data
   `skins` folder. Create `skins` if it does not exist.
3. Check that `skin.json`, `main.uss`, `theme.uss`, `styles/`, `fonts/` and
   `assets/` sit directly inside `skins/FM Dugout Template/`. Avoid an extra
   nested `skin` or `FM Dugout Template` folder.
4. Open FM27 Preferences, choose **FM Dugout Template** in the skin selector
   and apply it. If it does not appear, check the user-data location and folder
   nesting, then reopen Preferences or restart the game.

Typical locations:

- macOS: `~/Library/Application Support/Sports Interactive/Football Manager 27/skins/`
- Windows: `Documents/Sports Interactive/Football Manager 27/skins/`

Use your custom user-data location if you moved it. Windows Documents may be
redirected to OneDrive. Back up an existing skin and any personal edits before
replacing its folder.

## Editing

Start with `theme.uss` for shared appearance or `custom.uss` for personal
overrides. Save, then reload or reapply the skin in FM. The included
[editing guide](README.md) explains the theme tokens and component files.

Dark is the default. The optional Light palette is incomplete: some native
embedded links remain white and some data colours need better light-surface
contrast. Competition scoreboards reference the game's native fonts; extracted
UEFA fonts are not included. Poppins is supplied with its licence in
[fonts/OFL-Poppins.txt](fonts/OFL-Poppins.txt).

Updates and source: [FM Dugout skin repository](https://github.com/lotsgon/fm27-dugout-skin-public).
