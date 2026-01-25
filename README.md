# Awesome OBS Collections [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![OBS Studio](https://img.shields.io/badge/OBS%20Studio-Open%20Source-blue?style=flat-square)](https://obsproject.com/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgray?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

🌐 **Official Website**: [https://pralhad-nasane.github.io/awesome-obs/](https://pralhad-nasane.github.io/awesome-obs/)

> A curated collection of **open-source** plugins, scripts, tools, and themes for OBS Studio.

This repository focuses **exclusively** on high-quality, open-source software related to OBS Studio.

## Contents

- [Plugins](#plugins)
- [Scripts](#scripts)
- [External Tools & Utilities](#external-tools--utilities)
- [OBS Themes](#obs-themes)
- [OBS Forks](#obs-forks)

## Plugins

### Streaming & Production

- [Multiple RTMP Outputs](https://github.com/sorayuki/obs-multi-rtmp) - Stream to multiple platforms simultaneously.
- [Aitum Vertical](https://github.com/aitum/obs-vertical-canvas) - Adds a vertical canvas (9:16) perfect for TikTok, YouTube Shorts, and Instagram Reels.
- [Aitum Multistream](https://github.com/aitum/obs-aitum-multistream) - Integrated multi-platform streaming inside OBS.
- [Advanced Scene Switcher](https://github.com/WarmUpTill/SceneSwitcher) - Powerful automation tool for rule-based automated scene switching in complex workflows.
- [Source Dock](https://github.com/exeldro/obs-source-dock) - Pop any source out into a movable dock.
- [Downstream Keyer](https://github.com/exeldro/obs-downstream-keyer) - Add persistent overlays across all scenes for consistent branding.
- [Directory Watch Media](https://github.com/exeldro/obs-dir-watch-media) - Auto-update media source based on folder contents.
- [Autostarter](https://github.com/DaviBe92/Autostarter) - Auto-launch programs like chatbots and tools when OBS starts.
- [SE.Live (StreamElements)](https://github.com/StreamElements/obs-streamelements-core) - All-in-one solution integrating Twitch/YouTube/Facebook chat, alerts, and activity feeds.

### Recording & Output

- [Source Record](https://github.com/exeldro/obs-source-record) - Record individual sources or scenes without affecting the main stream.
- [Replay Source](https://github.com/exeldro/obs-replay-source) - Instant replay playback with buffer, perfect for gaming and sports streams.
- [OBS WebSocket (Built-in)](https://github.com/obsproject/obs-websocket) - Remote control interface for OBS v28+ essential for automation and remote control, built-in since OBS 28.0.
- [DistroAV (NDI)](https://github.com/DistroAV/DistroAV) - Send/receive high-quality video over IP using NDI protocol for network video transmission and dual-PC streaming setups.
- [Win-Capture-Audio](https://github.com/bozbez/win-capture-audio) - Capture audio from specific applications to isolate audio from individual programs instead of entire system.

### Visual & Effects

- [Move Transition](https://github.com/exeldro/obs-move-transition) - Create smooth, animated scene transitions for sources.
- [StreamFX](https://github.com/Vhonowslend/StreamFX-Public) - Industry-standard effects plugin with advanced 3D, blur, shaders, and glow effects.
- [StreamFX FreeFX Fork](https://github.com/xoxfaby/obs-StreamFX) - Updated community-maintained alternative fork.
- [ShaderFilter](https://github.com/exeldro/obs-shaderfilter) - Apply custom GLSL/HLSL shader filters to any source with shader programming support.
- [3D Effect](https://github.com/exeldro/obs-3d-effect) - Transform sources in 3D space with rotation and perspective effects.
- [Freeze Filter](https://github.com/exeldro/obs-freeze-filter) - Instant freeze frame effect for any video source on demand.
- [Composite Blur](https://github.com/FiniteSingularity/obs-composite-blur) - High-performance blur with multiple algorithms (Gaussian, Box, Bokeh) and correct alpha channel handling to prevent halos.
- [Background Removal](https://github.com/royshil/obs-backgroundremoval) - AI-powered virtual green screen using neural network segmentation to remove backgrounds without physical green screen.
- [Input Overlay](https://github.com/univrsal/input-overlay) - Visualize keyboard, mouse, and gamepad inputs on stream, essential for tutorials and speedrunning.
- [Spectralizer](https://github.com/univrsal/spectralizer) - Beautiful audio visualizer inside OBS (Archived - maintainer suggests "Waveform" as replacement).
- [Tuna](https://github.com/univrsal/tuna) - Real-time "Now Playing" music info from media players including Spotify, VLC, MPD, and more.
- [Face Tracker](https://github.com/norihiro/obs-face-tracker) - AI-powered face tracking that auto-crops and centers speaker using face detection for dynamic camera focus.

### Audio

- [OBS-ASIO](https://github.com/Andersama/obs-asio) - Native ASIO driver support for OBS providing low-latency audio for musicians.

### Captioning & Accessibility

- [LocalVocal](https://github.com/royshil/obs-localvocal) - Fully offline Whisper-based subtitles and translation with no cloud required, supporting multiple languages.
- [OBS Color Monitor (Scopes)](https://github.com/norihiro/obs-color-monitor) - Professional color grading tools with waveform, vectorscope, and parade scopes.

## Scripts

OBS supports both **Lua** and **Python** scripting.

### Lua Scripts

- [Libre Macros](https://github.com/upgradeQ/OBS-Libre-Macros) - Macro engine for advanced automation.
- [Zoom to Mouse](https://github.com/BlankSourceCode/obs-zoom-to-mouse) - Automatically zooms display capture to follow mouse cursor with smooth interpolation for tutorials.
- [OBS Bounce](https://github.com/insin/obs-bounce) - Animate sources with DVD-logo style bouncing or physics throwing for fun layouts.
- [Auto Execute Commands](https://github.com/rse/obs-scripts) - Execute commands on OBS startup/shutdown, part of rse/obs-scripts collection.

### Python Scripts

- [Countdown Timer](https://github.com/micahmo/obs-countdown-python) - Countdown to specific date/time with customizable text and expired text (requires Python 3.6+, python-dateutil, pyperclip).
- [Countdown Timer with Sound](https://github.com/KernFerm/countdown-timer-obs) - GUI countdown timer with Pygame/Tkinter interface that imports .mp3/.wav sounds and plays them at specific times.
- [Now Playing (Linux)](https://github.com/shock59/now-playing) - Displays Spotify/media player song title, artist, and album artwork for Linux using browser source (requires PyGObject, PyYAML, Tornado, websockets, playerctl).
- [Date Time](https://github.com/deadbraindev/obs-date-time) - Real-time date and time display that updates text sources with current timestamp.
- [Random Scene Switcher](https://github.com/deadbraindev/obs-scene-switcher) - Random scene selection at intervals.
- [Random Text Generator](https://github.com/revenkroz/obs-random-text) - Display random text from lists with hotkey support, optional sound effects, and simple animations.
- [Sequence Sources](https://github.com/Prosperelucel/obs-scripts) - Cycle through sources with sequential or random source display mode.
- [OBS WebSocket Python Client](https://github.com/Elektordi/obs-websocket-py) - Control OBS remotely via Python to create custom automation tools (works with OBS 28.0+ built-in WebSocket).

## External Tools & Utilities

_(All open-source and compatible through OBS WebSocket.)_

- [Bitfocus Companion](https://github.com/bitfocus/companion) - Production automation and OBS control with Stream Deck integration.
- [Kruiz Control](https://github.com/Kruiser8/Kruiz-Control) - Event-driven automation scripting for OBS with great Twitch integration.
- [OBS CLI](https://github.com/muesli/obs-cli) - Control OBS Studio from the terminal and automation scripts for command-line power users.
- [NohBoard](https://github.com/ThoNohT/NohBoard) - Standalone keyboard visualization tool as an alternative to Input Overlay plugin.
- [OBS-Web](https://github.com/Niek/obs-web) - Browser-based remote control panel with touch-friendly control from mobile devices.
- [OBS Command](https://github.com/kalenmike/obs-cmd) - Rust-based CLI tool for controlling OBS instances with command-line automation.

## OBS Themes

- [Twitchy Theme](https://obsproject.com/forum/resources/twitchy-obs-theme.1192/) - Twitch-inspired interface theme with purple aesthetic for Twitch streamers.
- [Catppuccin](https://github.com/catppuccin/obs) - Soothing pastel theme in Latte, Frappé, Macchiato, Mocha variants as part of popular Catppuccin design system.
- [Ocean Blue](https://obsproject.com/forum/resources/ocean-blue.1933/) - Modern dark theme with blue accents, clean unified look, brighter blue window bar, and darker background.
- [Meloncholy](https://obsproject.com/forum/resources/meloncholy.1894/) - Vibrant light theme with custom icons as a modern alternative to standard light themes (updated March 2024).

## OBS Forks

Specialized distributions based on OBS Studio core:

- [Prism Live Studio](https://github.com/naver/prism-live-studio) - Consumer-focused feature-rich fork with beauty effects, built-in multistreaming, and simplified interface.

## Contributing

We welcome community contributions! Help us keep this list awesome.

### How to Contribute

**Found a broken link or issue?**  
 [Report a Bug](https://github.com/Pralhad-Nasane/awesome-obs/issues/new?template=bug_report.md)

**Want to add a new resource?**  
 [Suggest a Resource](https://github.com/Pralhad-Nasane/awesome-obs/issues/new?template=feature_request.md)

**Ready to submit changes?**  
 [Create a Pull Request](https://github.com/Pralhad-Nasane/awesome-obs/compare)

### Guidelines

Please ensure the resource:

- Is open-source (GitHub/GitLab)
- Is actively maintained or still useful
- Is high quality and relevant to OBS Studio
- Follows our format: `- [Name](url) - Description.`

Read our full [Contributing Guidelines](contributing.md) for more details.
