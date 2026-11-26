Dethrace – PlayStation 3 Native Port

Project overview

This project aims to bring the original 1997 Carmageddon to PlayStation 3 as a native homebrew application using Dethrace and the open-source PSL1GHT SDK, without relying on DOS or Windows emulation.

The game is now booting successfully on real PS3 hardware, with working menus, 3D rendering, sound effects and video playback.

Development progress – November 26, 2026

Completed work

PS3 platform integration

Native PowerPC64 compilation.

PS3 platform backend implementation.

CMake cross-compilation configuration.

PSL1GHT SDK integration.

EBOOT.BIN generation.

Installable PS3 PKG packages.

Successful launch from the PS3 XMB.

Testing on real PlayStation 3 hardware.

File system and game data

PS3-specific file system implementation.

Working directory handling.

Relative and absolute path support.

Case-insensitive file lookup.

Directory enumeration fixes.

Original Carmageddon game data loading.

PSL1GHT runtime library compatibility fixes.

Graphics and rendering

Native RSX display initialization.

1280 × 720 video output.

Double-buffered framebuffer.

Vertical synchronization.

Indexed 8-bit to 32-bit colour conversion.

Palette handling.

Aspect ratio preservation.

Software-rendered 3D graphics.

Texture rendering fixes.

Lighting and shading fixes.

BRender 64-bit PowerPC compatibility fixes.

Big-endian rendering fixes.

Framebuffer synchronization and graphical artifact fixes.

Working in-game 3D rendering.

Audio

Native PS3 audio backend.

PSL1GHT libaudio integration.

Miniaudio software mixing.

Dedicated audio processing thread.

48 kHz stereo audio output.

Sound effects playback.

Menu sound effects.

In-game sound effects.

Audio volume, panning and pitch handling.

WAV big-endian compatibility fixes.

Smacker video audio playback.

Video audio stuttering fix.

Video playback

Smacker video decoding.

Intro and cutscene playback.

Video palette updates.

Video audio playback.

Redundant framebuffer swap fix.

Controller support

Native DualShock 3 initialization.

Controller detection.

Working menu navigation.

Button-to-keyboard input mapping.

Initial analog stick and trigger input implementation.

Debugging and development

Real-time UDP logging over LAN.

Startup diagnostics.

Game initialization diagnostics.

BRender rendering diagnostics.

Audio backend diagnostics.

Comparison with PC builds.

Development milestone backups.

Work in progress

Full analog steering.

Analog acceleration using R2.

Analog braking and reversing using L2.

Pressure-sensitive controller input verification.

Right analog stick camera controls.

Cockpit view toggle.

Complete DualShock 3 button mapping.

Separate menu and gameplay controller mappings.

Extended gameplay and stability testing.

Planned improvements

Original soundtrack playback.

Higher internal rendering resolutions.

Performance optimization.

Memory usage optimization.

Improved controller configuration.

Removal of temporary debugging code.

Clean release build.

Public source code cleanup and documentation.

Public PS3 homebrew release.

Current development status

Component

Status

Native PS3 executable

Working

PKG installation

Working

Game startup

Working

Game data loading

Working

Main menu

Working

Menu navigation

Working

3D rendering

Working

Textures and lighting

Working

720p video output

Working

Sound effects

Working

Intro and cutscenes

Working

Cutscene audio

Working

Gameplay controls

In development

Original soundtrack

Pending

Long-term stability

Not yet fully tested

Development environment

PlayStation 3 Super Slim

Firmware 4.88 with PS3HEN

PSL1GHT SDK

PowerPC64 GCC 7.2.0

CMake

Ubuntu 24.04 / WSL2

Dethrace v0.11.0 development source

BRender

Miniaudio

Project status

The native PS3 port is operational and currently in active development.

The main focus is now completing controller support, followed by extended gameplay testing, soundtrack support and rendering improvements.

Original Carmageddon game files are required. No copyrighted game assets are intended to be distributed with this port.

Credits

Dethrace development team and contributors

PSL1GHT and PS3DEV contributors

BRender developers

Miniaudio developers

Original Carmageddon developers – Stainless Games
