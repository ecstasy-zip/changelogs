# Ecstasy Changelogs

This document contains all notable changes across the Ecstasy components.

## [1.2.1] - 2025-05-18

### 🔨 Build System
- **[CLIENT]** Updated to v1.2.1
- **[BACKEND]** Updated to v1.2.1

## [1.2.0] - 2025-05-18

### 🔨 Build System
- **[CLIENT]** Updated to v1.2.0
- **[WEB]** Updated to v1.2.0

## [1.1.4] - 2025-05-09

### 🐛 Bug Fixes
- **[WEB]** *(dashboard)* Status spacing

### 🔨 Build System
- **[CLIENT]** Updated to v1.1.4
- **[WEB]** Updated to v1.1.4
- **[BACKEND]** Updated to v1.1.4

### 🚀 Features
- **[WEB]** *(home)* Full modern restyle

## [1.1.0] - 2025-05-09

### 🔨 Build System
- **[CLIENT]** Updated to v1.1.0

## [1.0.1] - 2025-05-02

### 🐛 Bug Fixes
- **[CLIENT]** *(initialization)* Fixed offline bug while initializing

### 🔨 Build System
- **[CLIENT]** Updated to v1.0.1
- **[WEB]** Updated to v1.0.1
- **[BACKEND]** Updated to v1.0.1

## [1.0.0] - 2025-05-01

### 🐛 Bug Fixes
- **[CLIENT]** *(crash)* Fixed a crash that sometimes happened when aiming
- **[WEB]** Always dark notifications
- **[WEB]** *(dashboard)* Prevent downloading when user expired
- **[BACKEND]** Infinity license not redeeming on account creation

### 🔨 Build System
- **[CLIENT]** Updated to v1.0.0
- **[WEB]** Updated to v1.0.0
- **[BACKEND]** Updated to v1.0.0

### 🚀 Features
- **[CLIENT]** Added ecstasy infinity support
- **[CLIENT]** Optimized memory aim with 0 smoothing
- **[CLIENT]** *(core)* Cpu optimization
- **[CLIENT]** *(menu)* Added ecs infinity border
- **[CLIENT]** *(watermark)* Added ecs infinity watermark
- **[CLIENT]** *(menu)* Hide clean button for infinity sessions
- **[WEB]** Added ecstasy infinity support
- **[WEB]** *(pricing)* Added infinity subscription
- **[WEB]** *(style)* Updated infinity style on dashboard
- **[WEB]** *(dashboard)* Disabled clean button for infinity sessions
- **[WEB]** *(tos)* Added infinity terms of service
- **[WEB]** *(home)* Added read tos requirement on get buttons
- **[WEB]** *(dashboard)* Updated pricing plans preview
- **[BACKEND]** Added ecstasy infinity support
- **[BACKEND]** *(internal)* Added infinity status support

## [0.6.1] - 2025-04-17

### 🐛 Bug Fixes
- **[CLIENT]** *(crash)* Fixed crash after game initialized

### 🔨 Build System
- **[CLIENT]** Updated to v0.6.0
- **[CLIENT]** Updated to v0.6.1
- **[WEB]** Updated to v0.6.1
- **[BACKEND]** Updated to v0.6.1

### 🚀 Features
- **[CLIENT]** *(clean)* Improved cleaning process
- **[CLIENT]** *(clean)* Improved cleaning process 2

## [0.6.0] - 2025-04-17

### 🐛 Bug Fixes
- **[BACKEND]** *(hv)* Disabled hypervisor check
- **[BACKEND]** Fixed initializing and offline right after bug

### 🔨 Build System
- **[WEB]** Updated to v0.6.0
- **[BACKEND]** Updated to v0.6.0

### 🚀 Features
- **[WEB]** *(dashboard)* Updated pricing plans preview

## [0.5.0] - 2025-04-01

### 🌳 Quality of Life Improvements
- **[BOOT-AGENT]** *(msg)* Changed "try again later" to "open a ticket"

### 🐛 Bug Fixes
- **[WEB]** *(home)* Fixed showcase video not playing on IOS

### 🔨 Build System
- **[CLIENT]** Updated to v0.5.0
- **[WEB]** Updated to v0.5.0
- **[BACKEND]** Updated to v0.5.0

### 🚀 Features
- **[CLIENT]** Proper physical memory page collector
- **[CLIENT]** *(clean)* Added driver unload
- **[BACKEND]** *(download)* Generate size, timestamp and hash on the fly
- **[BOOT-AGENT]** *(security)* Anti virustotal & MS defender detection

## [0.4.1] - 2025-03-29

### 🐛 Bug Fixes
- **[CLIENT]** *(core)* Fixed head markers colors

### 🔨 Build System
- **[CLIENT]** Updated to v0.4.1
- **[WEB]** Updated to v0.4.1
- **[BACKEND]** Updated to v0.4.1

### 🚀 Features
- **[CLIENT]** *(core)* Prevent file recovery

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
