# Ecstasy Changelogs

This document contains all notable changes across the Ecstasy components.

## [0.4.0] - 2025-03-25

### 🌳 Quality of Life Improvements
- **[WEB]** *(dashboard)* Added "hp" after the health value

### 🐛 Bug Fixes
- **[CLIENT]** *(menu)* Popups hierarchy (including color pickers)
- **[CLIENT]** *(core)* Health & armour value approximation
- **[CLIENT]** *(menu)* Weapon exploits values rounded to two decimal places
- **[CLIENT]** *(menu)* Fixed sliders transparent bug
- **[CLIENT]** *(core)* Streamproof now only enables if desired
- **[WEB]** *(dashboard)* Fixed color pickers
- **[WEB]** *(home)* Centered pricing section
- **[WEB]** *(dashboard)* Fixed recoil, spread & reload_time values
- **[WEB]** *(dashboard)* Weapon exploits values rounded to two decimal places
- **[BACKEND]** *(stream)* Temp fix for timecheck

### 🔨 Build System
- **[CLIENT]** Updated to v0.4.0
- **[WEB]** Updated to v0.4.0
- **[BACKEND]** Updated to v0.4.0

### 🚀 Features
- **[CLIENT]** Support for windows 24H2
- **[CLIENT]** *(security)* Added security clamp to health & armour values
- **[CLIENT]** *(menu)* Disable health & armour sliders if not in game
- **[CLIENT]** *(core)* Prevent shadowplay from stopping recording with streamproof
- **[WEB]** *(tos)* Added windows 11 below 23h2
- **[WEB]** *(tos)* Added windows 11 24H2
- **[WEB]** *(home)* Updated free trial FaQ
- **[WEB]** *(home)* Added Revolut payment method
- **[WEB]** *(home)* Added specific supported winvers to FaQ
- **[WEB]** *(dashboard)* Increased max online users graph to 64
- **[WEB]** *(home)* Updated showcase video to v0.4.0
- **[BACKEND]** Support for windows 24H2

## [0.3.2] - 2025-03-16

### 🐛 Bug Fixes
- **[WEB]** *(dashboard)* Fixed some sections descriptions

### 🔨 Build System
- **[CLIENT]** Updated to v0.3.2
- **[WEB]** Updated to v0.3.2
- **[BACKEND]** Updated to v0.3.2

### 🚀 Features
- **[CLIENT]** Clean & unload with game closed
- **[BACKEND]** Clean & unload with game closed

## [0.3.1] - 2025-03-16

### 🐛 Bug Fixes
- **[WEB]** *(dashboard)* Fixed skeletons color
- **[BACKEND]** *(streamsock)* Ecp packets reliability

### 🔨 Build System
- **[CLIENT]** Updated to v0.3.1
- **[WEB]** Updated to v0.3.1
- **[BACKEND]** Updated to v0.3.1

### 🚀 Features
- **[CLIENT]** *(ecp)* Communication packets reliability
- **[BOOT-AGENT]** *(ecp)* Communication packets reliability

## [0.3.0] - 2025-03-13

### ⚡ Performance
- **[CLIENT]** Draw manager optimization, closed #36

### 🌳 Quality of Life Improvements
- **[CLIENT]** Updated keybinds names to match the web dashboard
- **[WEB]** *(home)* Enhanced features section
- **[WEB]** *(home)* Capitalized Q in "FaQ"

### 🐛 Bug Fixes
- **[CLIENT]** *(core)* Fixed npc feature, closed #31
- **[CLIENT]** *(menu)* Fixed slider flickering, closed #35
- **[CLIENT]** *(render)* Radar now renders on top of everything
- **[WEB]** *(download)* Removed file system access api support, closed #18
- **[WEB]** *(dashboard)* Fixed win, shift, ctrl & alt keybinds
- **[WEB]** *(dashboard)* Correct players online count
- **[BACKEND]** *(dashboard)* Correct players online count

### 🔨 Build System
- **[CLIENT]** Updated to v0.3.0
- **[WEB]** Updated to v0.3.0
- **[BACKEND]** Updated to v0.3.0

### 🚀 Features
- **[CLIENT]** *(menu)* Decreased aim fov min value, closed #34
- **[CLIENT]** *(ecp)* New ecstasy protocol packer, closed #38
- **[CLIENT]** *(graphics)* Restyled players around feature, fixed #37
- **[CLIENT]** *(boot-agent)* Hwid setup now runs in a anonymous browser
- **[WEB]** *(dashboard)* Decreased aim fov min value, closed #19
- **[WEB]** *(ecp)* New ecstasy protocol packer, closed #21
- **[BACKEND]** *(download)* Random exe name, closed #8
- **[BACKEND]** *(ecp)* New ecstasy protocol packer, closed #9
- **[BACKEND]** *(stream)* Stream client component (auto-update)
- **[BOOT-AGENT]** *(stream)* Stream client component (auto-update)

<!-- © Ecstasy 2025. All rights reserved. -->
