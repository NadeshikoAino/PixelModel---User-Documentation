# PixelModel---User-Documentation

## Overview

**Model Name:** PixelModel  
**Creator:** Nadeshiko Aino
**Compatibility:** Live2D Cubism 5.0+, VTube Studio (PC / Steam)

This document describes **model-specific behavior, presets, parameters, and limitations**. It does **not** cover general VTube Studio usage.

---

## Before You Buy (Important)

This model is intended for **experienced VTube Studio users**.

Please review the following before purchasing:

- Paid premade Live2D model, not a beginner template
    
- Parameters are exposed and adjustable via sliders; however, presets are intentionally provided as the primary control method to avoid invalid layer combinations and ensure predictable results.
    
- Color customization uses **integer-stepped parameters**, not freeform selection
    
- Expressions are **not automatically mutually exclusive** due to VTube Studio limitations
    
- Users are expected to assign/manage their own hotkeys
    

---

## Product Page Summary

**Fully rigged, paid Live2D premade model for experienced VTube Studio users.**  
Features multiple outfits, preset-based appearance switching, integer-stepped color customization, and expression files with documented limitations based on VTube Studio behavior.

---

## Background Knowledge

Users should know how to:

- Load models
    
- Assign/manage hotkeys
    
- Enable/disable expressions
    
- Use Model Settings panel
    

---

## Installation

1. Load the model into VTube Studio
    
2. Verify expressions, presets, and color parameters respond correctly
    
3. Assign hotkeys or import provided presets if available
    

---

## Expressions / Emotions

All emotions are **toggle expressions** with a **0.2s fade time**, except Neutral Expression.

### Global Control

|Action|Hotkey|Notes|
|---|---|---|
|Unset all expressions|LeftCtrl + Alt + Num0|Immediately disables all active expressions|

### Emotions

| Expression         | Hotkey | Fade | Behavior / Notes                                  |
| ------------------ | ------ | ---- | ------------------------------------------------- |
| Neutral Expression | Num0   | 0s   | Baseline state; visually overrides other emotions |
| Speechless         | Num1   | 0.2s | Replaces pupil artmesh                            |
| Surprised          | Num2   | 0.2s | Replaces pupil artmesh                            |
| Love               | Num3   | 0.2s | Replaces pupil artmesh                            |
| Angry              | Num4   | 0.2s | Modifies pupil color only                         |
| Confused           | Num5   | 0.2s | Replaces pupil artmesh                            |
| Speaking           | Num6   | 0.2s | Sticker-only expression                           |

**Notes:**

- Multiple emotions can be active simultaneously
    
- Neutral overrides emotions visually but does not hard-reset them
    
- Unused expression (**Disgusted**) modifies pupil color like Angry; not assigned to hotkeys
    

---

## Appearance Presets

### Outfit Presets

|Preset|Hotkey|Notes|
|---|---|---|
|Default Outfit|F1|Baseline outfit|
|Outfit Preset 1|F2|Alternate outfit|
|Outfit Preset 2|F3|Alternate outfit|
|Outfit Preset 3|F4|Alternate outfit|
|Outfit Preset 4|F5|Alternate outfit|
|Outfit Preset 5|F6|Alternate outfit|
|Outfit Special|F7|Special-use outfit|

### Appearance Presets

|Preset|Hotkey|Notes|
|---|---|---|
|Default Appearance|Alt + Num1|Baseline appearance|
|Appearance A|Alt + Num2|Variant appearance|
|Appearance B|Alt + Num3|Variant appearance|
|Appearance C|Alt + Num4|Variant appearance|
|Appearance D|Alt + Num5|Variant appearance|
|Appearance E|Alt + Num6|Variant appearance|

---

## Expressions Without Hotkeys

### Outfit Parameters

|Parameter|Range|Notes|
|---|---|---|
|Outfit Color|1–5|Derived from outfit presets but adjustable separately|
|Outfit Style|1–5|Derived from outfit presets but adjustable separately|

### Appearance Parameters

| Parameter  | Range | Notes                                                     |
| ---------- | ----- | --------------------------------------------------------- |
| Hair Color | 1–5   | Derived from appearance presets but adjustable separately |
| Hair Style | 1–5   | Derived from appearance presets but adjustable separately |
| Eye Color  | 1–5   | Derived from appearance presets but adjustable separately |

### Layer Logic Notes

- Tops are split into **innerwear** (shirt/blouse/dress) and **outerwear** (jacket/hoodie/suit)
    
- The **Suit** preset uses a dedicated layer and does not respond to any color parameter
    

---

## Creating Your Own Presets

Users may create **custom presets** to suit personal preferences:

1. Adjust desired parameters (outfit, appearance, colors) in the Model Settings panel
    
2. Save a new preset with a unique name
    
3. Assign a hotkey if desired
    

**Tips:**

- Always test custom presets to ensure correct layering
    
- Avoid creating conflicting hotkeys with core expressions or existing presets
    
- Document custom presets for your own reference
    

---

## Hotkeys & Control Philosophy

- Preset-driven approach prevents invalid layer combinations
    
- Expressions are toggle-based for consistent visual behavior
    
- Users are encouraged to customize hotkeys to fit workflow
    

---

## Known Limitations / Design Decisions

> Documented against **VTube Studio v1.32.x (current public release at time of writing)**. Behavior may change in future updates.

- VTube Studio does not support true parameter cycling via hotkeys
    
- Expressions do not enforce automatic priority or exclusivity
    
- Expression states must be manually toggled off
    
- Integer-stepped parameters cannot be displayed as discrete UI buttons
    
- Sliders for stepped color parameters are not natively supported
    

Presets provide stable, predictable results.

---

## Troubleshooting

- **Expression does not reset:** Toggle the expression off directly, or toggle Neutral off/on again
    
- **Colors do not change:** Ensure correct integer index; check if active outfit ignores color (e.g., Suit)
    
- **Unexpected layering:** Verify the active preset
    

---

## License, Usage, and Refund Policy

### Included License

- Commercial streaming/content creation license included
    
- Permitted: Monetized streaming, monetized videos, ad revenue, memberships, donations
    
- Not permitted: Merchandise, NFTs, redistribution, resale, model packs, sublicensing
    

### Refund Policy

- Digital asset delivered as-is; no refunds after download
    
- Review product page and documentation carefully before purchase
    
- Compatibility issues caused by unsupported software versions or user workflow preferences are not grounds for refund
    

---

## Support Scope

- Supported: Missing/broken files, incorrect preset behavior, model errors
    
- Not Supported: General VTube Studio usage, hotkey layout, third-party plugins, software update changes
    
