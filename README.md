# Crime-Scene-Investigation---CSI-AiO-Fix
It fixes all the issues i found in CSI and makes it compatible with windows 11

This is my CSI All-in-One compatibility fix, addressing several issues identified during debugging and testing.

# Windows 10/11 compatibility

Fixed the startup crash caused by the legacy runtime’s handling of modern graphics-driver information.

Restored working keyboard input on Windows 11.

Removed the need to download or separately install the discontinued Shockwave Player in certain instances.

# Three display options

Original: retains the original 800×600 presentation and resolution with applied fixes.

Desktop Fit: enlarges the complete picture to desktop resolution while preserving its 4:3 proportions, with borders where needed.

Desktop Fill: stretches the complete picture across the desktop resolution without cropping the scene or interface.

# Native graphics support

Fixed corruption when entering the first panorama after launching the Fill version.

Fixed an issue that caused the game to fall back to software rendering when DirectX or OpenGL was selected.

Fixed and Confirmed active DirectX 7 rendering through diagnostic logs in all three versions.

OpenGL also works in the tested Fit and Fill builds.

No external scaling application is required for the AiO.

# Shockwave runtime fixes

Fixed a crash in the bundled Shockwave 3D component when detecting modern graphics drivers (RTX 5080 Tested).

Resolved the “Shockwave Player 8.5 is not installed” launch problem in certain instances.

Corrected rendering and scaling problems within the bundled runtime.

Keeps the fix self-contained, without requiring a separate (defunct) Shockwave Player installation.

# Corrected mouse and tool effects

Maintains alignment between the pointer, interface controls, scene objects and exits when scaling.

Fixed tool effects appearing in the wrong position or being restricted to a small area.

Corrected effect size, tool movement limits and clipping at scene boundaries.

Prevents effects drawing outside the scene onto surrounding borders.

# Audio fix

Audio now plays correctly

Fixed a bug that continued playing main-menu music after loading a saved game.

# Saves Fix

New save Location C:\Users\YOURUSERNAME\AppData\Local\VirtualStore\Program Files\Ubisoft\369\CSI\SavedGames

Older saves were successfully restored by moving them to the new save location with correct write permissions.

# Resolution testing

Fit and Fill have been tested at multiple resolutions, from 800×600 to 2560×1440 (See Screenshots for 1440).

Mouse mapping remained correct, with no reported rendering issues in my diagnostic logs.

Compatibility with every GPU, resolution and scene has not been exhaustively tested.

# Original presentation preserved

Scales the existing artwork rather than replacing textures or adding new scene content.

Fit preserves proportions; Fill deliberately stretches the picture to match the screen.

# Release packages

Includes Original, Fit and Fill versions.

Each executable must be used with its matching scripts.cxt file.

# Original game required

This is a compatibility and fix patch, not a complete game distribution.

Back up existing game files and saves before installing.

# No Source code
I did create this fix but most of the code belongs to the game so i will not be providing it
