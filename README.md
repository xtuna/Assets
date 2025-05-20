# Cozy Cuisine Game Assets

A comprehensive collection of game assets for our food-themed game "Cozy Cuisine", including UI elements, characters, animations, and more.

<p align="center">
  <img src="./Logo/logo-with-animation.gif" alt="Cozy Cuisine Logo" width="300">
</p>

## Overview

This repository contains all visual assets required for Cozy Cuisine (Game Version 1.0), organized into logical folders for easy access and implementation. These assets include UI elements, character sprites, animations, backgrounds, and more.

## Asset Structure

```
📁 MC and Customers        # Main character and customer sprites
📁 NPC and Player          # Non-playable characters and player assets
📁 Animation of UI Elements # Animated UI components 
📁 Logo                    # Game logo in various formats and sizes
📁 Stall                   # Food stall graphics and variations
📁 UI Elements             # Static UI components (buttons, panels, icons)
📁 Dish with Ingredients   # Food items and ingredient sprites
📁 Loading Screen Background # Loading and splash screen backgrounds
```

## UI Style Guide

Our game follows a cohesive pixel art style designed to create an inviting and cozy food game experience. The complete UI Style Guide (updated May 19, 2025) is included in this repository.

[View UI Style Guide PDF](https://drive.google.com/file/d/1fOJoxY6x8QCD1p5PvecIPoEuSveo0Pb5/view?usp=drive_link)

## Component Behavior Guide

For detailed information on how UI components should behave in-game, please refer to the Component Behavior Guide (updated May 20, 2025):

[View Component Behavior Guide PDF](https://drive.google.com/file/d/1QLIbIqsd2to-YCy0_4GF9Z2XsdIX5Yw1/view?usp=drive_link)

### Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Light Beige | #FFEAC5 | Backgrounds |
| Peach Cream | #FFDBB5 | UI Containers, Tooltips |
| Dark Brown | #6C4E31 | Primary Text, Icons |
| Deep Brown | #603F26 | Buttons, Borders |
| Accent Orange | #D1763C | Active states, highlights |

### Typography

- **Press Start 2P**: Titles, Buttons (16-20px, Uppercase)
- **ByteBounce**: In-game Labels (12-14px, Regular)
- **Pixel Arial 11pt**: Tooltips, Subtext (10-12px, Regular)

## Asset Usage Guidelines

### UI Elements

- All UI buttons come in three states: normal, hover, and pressed
- Icons are provided in both outlined and filled variants
- Modal backgrounds use a semi-transparent dark overlay (#000000 at 60% opacity)

### Characters

- Player and NPC sprites are organized with consistent naming: `[character]_[action]_[direction].png`
- All character animations use 8 frames at 12fps

### Food Items

- Food items are separated into base dishes and ingredients for mix-and-match gameplay
- Each dish has 4 preparation states: raw, cooking, cooked, and burnt

## Implementation Notes

### Animation

- UI animations use sprite sheets with frame data in accompanying JSON files
- Character animation sequences are provided as individual frames
- Loading animations should run at 24fps for smooth experience

### Characters

- Player and NPC sprites are organized in the "MC and Customers" and "NPC and Player" folders
- All character animations use consistent framing for smooth gameplay experience

### Food Items

- Food items are located in the "Dish with Ingredients" folder
- Items are separated for mix-and-match gameplay mechanics

## Implementation Notes

### Interaction Patterns

- Hover Effects: All interactive UI elements respond visually
- Pop-Ups: Animate from scale 0.8 → 1.0, duration: 200ms
- Transitions: Fade in/out (200ms) when switching menus or scenes
- Loading: Includes animated sign + progress bar with cat animation

### Accessibility

- Minimum contrast ratio for text: 4.5:1
- Text labels or tooltips for all icon-only buttons
- Avoid red/green-only indicators – include icons or text hints

### Export & File Naming Convention

| Asset Type | Format | Naming Example |
|------------|--------|----------------|
| UI Buttons | PNG | btn_[name]_idle.png, btn_[name]_hover.png |
| Icons | PNG | icon_[name].png |
| Pop-up Panels | PNG | popup_[name].png |
| Sprite Sheets | PNG/GIF | anim_[element]_sheet.png, anim_[element].gif |

### Loading Screen

Loading screen components found in the "Loading Screen Background" folder include:
- Background that fades in
- Progress bar that grows from 0% to 100% width with ease-in curve
- Cat sprite that loops idle animation during loading
- Sign element that hangs and swings subtly

## Credits

All assets designed and created by Ma. Cristina S. Velasco (UI/UX Designer)

## License

These assets are All Rights Reserved - see LICENSE.md file for details.

## Contact

For questions or support regarding these assets, please contact:
- Email: unlibugs938@gmail.com
