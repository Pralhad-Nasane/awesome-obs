# Awesome OBS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![OBS Studio](https://img.shields.io/badge/OBS%20Studio-Open%20Source-blue?style=flat-square)](https://obsproject.com/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgray?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

🌐 **Official Website**: [https://pralhad-nasane.github.io/awesome-obs/](https://pralhad-nasane.github.io/awesome-obs/)

> A curated collection of **open-source** plugins, scripts, tools, and themes for OBS Studio.

This repository focuses **exclusively** on high-quality, open-source software related to OBS Studio.

## Contents

- [Plugins](#plugins)
  - [Official & Core Plugins](#official--core-plugins)
  - [Streaming & Production](#streaming--production)
  - [Recording & Output](#recording--output)
  - [Visual Effects & Filters](#visual-effects--filters)
  - [AI & Machine Learning](#ai--machine-learning)
  - [Audio](#audio)
  - [Camera & Video Sources](#camera--video-sources)
  - [Input & Interaction](#input--interaction)
  - [Overlays & Browser Sources](#overlays--browser-sources)
  - [Accessibility & Monitoring](#accessibility--monitoring)
- [Scripts](#scripts)
  - [Lua Scripts](#lua-scripts)
  - [Python Scripts](#python-scripts)
  - [Scripting Resources](#scripting-resources)
- [External Tools & Utilities](#external-tools--utilities)
  - [Remote Control & Automation](#remote-control--automation)
  - [WebSocket Libraries](#websocket-libraries)
  - [Utilities](#utilities)
- [OBS Themes](#obs-themes)
- [OBS Forks](#obs-forks)

## Plugins

### Official & Core Plugins

- [OBS WebSocket (Built-in)](https://github.com/obsproject/obs-websocket) - Remote control interface for OBS v28+ essential for automation and remote control, built-in since OBS 28.0.
- [OBS Browser](https://github.com/obsproject/obs-browser) - CEF-based browser source plugin for embedding web content in OBS.

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
- [VDO.Ninja](https://github.com/steveseguin/vdo.ninja) - Bring remote video feeds into OBS via WebRTC with minimal latency for remote collaboration.
- [Project Lightspeed](https://github.com/GRVYDEV/Project-Lightspeed) - Self-contained OBS → FTL → WebRTC pipeline for sub-second latency browser streaming.

### Recording & Output

- [Source Record](https://github.com/exeldro/obs-source-record) - Record individual sources or scenes without affecting the main stream.
- [Replay Source](https://github.com/exeldro/obs-replay-source) - Instant replay playback with buffer, perfect for gaming and sports streams.
- [DistroAV (NDI)](https://github.com/DistroAV/DistroAV) - Send/receive high-quality video over IP using NDI protocol for network video transmission and dual-PC streaming setups.
- [OBS Teleport](https://github.com/fzwoch/obs-teleport) - Open-source NDI alternative for network video transmission between OBS instances.
- [RTSP Server](https://github.com/iamscottxu/obs-rtspserver) - Plugin for streaming OBS output to RTSP clients.
- [Branch Output](https://github.com/OPENSPHERE-Inc/branch-output) - Transmit individual sources via RTMP/SRT independently for multi-destination streaming.
- [Virtual Display](https://github.com/MolotovCherry/virtual-display-rs) - Create virtual displays for extended desktop, useful for VR and multi-monitor streaming setups.

### Visual Effects & Filters

- [Move Transition](https://github.com/exeldro/obs-move-transition) - Create smooth, animated scene transitions for sources.
- [StreamFX](https://github.com/Vhonowslend/StreamFX-Public) - Industry-standard effects plugin with advanced 3D, blur, shaders, and glow effects.
- [StreamFX FreeFX Fork](https://github.com/xoxfaby/obs-StreamFX) - Updated community-maintained alternative fork.
- [ShaderFilter](https://github.com/exeldro/obs-shaderfilter) - Apply custom GLSL/HLSL shader filters to any source with shader programming support.
- [ShaderFilter Plus](https://github.com/Limeth/obs-shaderfilter-plus) - Rust-based rewrite of obs-shaderfilter with performance improvements.
- [3D Effect](https://github.com/exeldro/obs-3d-effect) - Transform sources in 3D space with rotation and perspective effects.
- [Freeze Filter](https://github.com/exeldro/obs-freeze-filter) - Instant freeze frame effect for any video source on demand.
- [Composite Blur](https://github.com/FiniteSingularity/obs-composite-blur) - High-performance blur with multiple algorithms (Gaussian, Box, Bokeh) and correct alpha channel handling to prevent halos.
- [Stroke Glow Shadow](https://github.com/FiniteSingularity/obs-stroke-glow-shadow) - Efficient GPU-accelerated stroke, glow, and shadow effects for masked sources.
- [Retro Effects](https://github.com/FiniteSingularity/obs-retro-effects) - Collection of retro-style filters including CRT, VHS, and vintage effects.
- [Motion Effect](https://github.com/CatxFish/motion-effect) - Advanced source animation with keyframes and motion paths.

### AI & Machine Learning

- [Background Removal](https://github.com/royshil/obs-backgroundremoval) - AI-powered virtual green screen using neural network segmentation to remove backgrounds without physical green screen.
- [LocalVocal](https://github.com/royshil/obs-localvocal) - Fully offline Whisper-based subtitles and translation with no cloud required, supporting multiple languages.
- [OBS Captions Plugin](https://github.com/ratwithacompiler/OBS-captions-plugin) - Closed captioning using Google Speech Recognition API.
- [Face Tracker](https://github.com/norihiro/obs-face-tracker) - AI-powered face tracking that auto-crops and centers speaker using face detection for dynamic camera focus.
- [CleanStream](https://github.com/royshil/obs-cleanstream) - AI-powered profanity filter that removes unwanted words from live audio streams.

### Audio

- [Win-Capture-Audio](https://github.com/bozbez/win-capture-audio) - Capture audio from specific applications to isolate audio from individual programs instead of entire system.
- [OBS-ASIO](https://github.com/Andersama/obs-asio) - Native ASIO driver support for OBS providing low-latency audio for musicians.
- [Waveform](https://github.com/phandasm/waveform) - Real-time audio spectrum analyzer and waveform visualizer.
- [GStreamer](https://github.com/fzwoch/obs-gstreamer) - Integration for advanced audio/video processing pipelines.
- [Audio Monitor](https://github.com/exeldro/obs-audio-monitor) - Advanced audio monitoring filter for routing audio to specific output devices.
- [Spectralizer](https://github.com/univrsal/spectralizer) - Beautiful audio visualizer inside OBS (Archived - maintainer suggests "Waveform" as replacement).
- [Tuna](https://github.com/univrsal/tuna) - Real-time "Now Playing" music info from media players including Spotify, VLC, MPD, and more.

### Camera & Video Sources

- [DroidCam OBS](https://github.com/dev47apps/droidcam-obs-plugin) - Use Android/iOS phones as wireless webcam sources in OBS.
- [RemoteCam](https://github.com/Ruddle/RemoteCam) - Stream Android camera to desktop as OBS source or v4l2 webcam. Free, ad-free, and open source.
- [Spout2 Plugin](https://github.com/Off-World-Live/obs-spout2-plugin) - Spout2 integration for efficient GPU texture sharing between applications on Windows.
- [OBS Kinect](https://github.com/SirLynix/obs-kinect) - Use Kinect depth sensors for virtual green screen and advanced body detection.
- [iOS Camera Source](https://github.com/wtsnz/obs-ios-camera-source) - High-quality H.264 video streaming from iPhone cameras over USB.
- [OpenVR Input](https://github.com/baffler/OBS-OpenVR-Input-Plugin) - Capture OpenVR/SteamVR mirror in full resolution for VR streaming.

### Input & Interaction

- [Input Overlay](https://github.com/univrsal/input-overlay) - Visualize keyboard, mouse, and gamepad inputs on stream, essential for tutorials and speedrunning.
- [MIDI Control](https://github.com/nhielost/obs-midi-mg) - Control OBS with MIDI controllers and devices.

### Overlays & Browser Sources

- [Pogly Standalone](https://github.com/PoglyApp/pogly-standalone) - Real-time collaborative stream overlay editor with SpacetimeDB backend.
- [Bongobs Cat Plugin](https://github.com/a1928370421/Bongobs-Cat-Plugin) - Bongo Cat animation overlay synchronized with keyboard/mouse input.
- [Meme Box](https://github.com/negue/meme-box) - Manage and trigger media clips via browser source interface.

### Accessibility & Monitoring

- [OBS Color Monitor (Scopes)](https://github.com/norihiro/obs-color-monitor) - Professional color grading tools with waveform, vectorscope, and parade scopes.

## Scripts

OBS supports both **Lua** and **Python** scripting.

### Lua Scripts

- [Libre Macros](https://github.com/upgradeQ/OBS-Libre-Macros) - Macro engine for advanced automation.
- [Zoom to Mouse](https://github.com/BlankSourceCode/obs-zoom-to-mouse) - Automatically zooms display capture to follow mouse cursor with smooth interpolation for tutorials.
- [OBS Bounce](https://github.com/insin/obs-bounce) - Animate sources with DVD-logo style bouncing or physics throwing for fun layouts.
- [Auto Execute Commands](https://github.com/rse/obs-scripts) - Execute commands on OBS startup/shutdown, part of rse/obs-scripts collection.
- [Advanced Timer](https://github.com/cg2121/obs-advanced-timer) - Feature-rich timer script with multiple modes and formatting options.

### Python Scripts

- [Countdown Timer](https://github.com/micahmo/obs-countdown-python) - Countdown to specific date/time with customizable text and expired text (requires Python 3.6+, python-dateutil, pyperclip).
- [Countdown Timer with Sound](https://github.com/KernFerm/countdown-timer-obs) - GUI countdown timer with Pygame/Tkinter interface that imports .mp3/.wav sounds and plays them at specific times.
- [Now Playing (Linux)](https://github.com/shock59/now-playing) - Displays Spotify/media player song title, artist, and album artwork for Linux using browser source (requires PyGObject, PyYAML, Tornado, websockets, playerctl).
- [Date Time](https://github.com/deadbraindev/obs-date-time) - Real-time date and time display that updates text sources with current timestamp.
- [Random Scene Switcher](https://github.com/deadbraindev/obs-scene-switcher) - Random scene selection at intervals.
- [Random Text Generator](https://github.com/revenkroz/obs-random-text) - Display random text from lists with hotkey support, optional sound effects, and simple animations.
- [Sequence Sources](https://github.com/Prosperelucel/obs-scripts) - Cycle through sources with sequential or random source display mode.

### Scripting Resources

- [OBS Scripting Reference](https://github.com/upgradeQ/Streaming-Software-Scripting-Reference) - Comprehensive OBS Python API documentation and examples.
- [OBS Lua Reference](https://github.com/midnight-studios/obs-lua) - Lua scripting reference and examples for OBS.

## External Tools & Utilities

_(All open-source and compatible through OBS WebSocket.)_

### Remote Control & Automation

- [Bitfocus Companion](https://github.com/bitfocus/companion) - Production automation and OBS control with Stream Deck integration.
- [Kruiz Control](https://github.com/Kruiser8/Kruiz-Control) - Event-driven automation scripting for OBS with great Twitch integration.
- [OBS CLI](https://github.com/muesli/obs-cli) - Control OBS Studio from the terminal and automation scripts for command-line power users.
- [OBS Command](https://github.com/kalenmike/obs-cmd) - Rust-based CLI tool for controlling OBS instances with command-line automation.
- [OBS Blade](https://github.com/Kounex/obs_blade) - Flutter-based mobile app for controlling OBS via WebSocket from Android/iOS.
- [OBS-Web](https://github.com/Niek/obs-web) - Browser-based remote control panel with touch-friendly control from mobile devices.
- [OSC for OBS](https://github.com/jshea2/OSC-for-OBS) - Open Sound Control protocol integration for hardware controller support.

### WebSocket Libraries

#### JavaScript/TypeScript

- [obs-websocket-js](https://github.com/obs-websocket-community-projects/obs-websocket-js) - Official JavaScript/Node.js library for obs-websocket.

#### Python

- [obs-websocket-py](https://github.com/Elektordi/obs-websocket-py) - Python library for obs-websocket v4 protocol.
- [obsws-python](https://github.com/aatikturk/obsws-python) - Modern Python SDK for obs-websocket v5.

#### .NET/C#

- [obs-websocket-dotnet](https://github.com/BarRaider/obs-websocket-dotnet) - C# library for obs-websocket integration.

#### Rust

- [obws](https://github.com/dnaka91/obws) - Async Rust library for obs-websocket remote control.

### Utilities

- [NohBoard](https://github.com/ThoNohT/NohBoard) - Standalone keyboard visualization tool as an alternative to Input Overlay plugin.
- [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) - Automatically switch scenes based on stream bitrate to handle connection issues.
- [StreamerSize](https://streamersize.com) - Free calculator for streaming bitrate, video file size, upload time and storage. Supports Twitch, YouTube, Kick and OBS.
- [TikTok Stream Key Generator](https://github.com/Loukious/TikTokStreamKeyGenerator) - Direct TikTok stream key generation for OBS.

## OBS Themes

- [Catppuccin](https://github.com/catppuccin/obs) - Soothing pastel theme in Latte, Frappé, Macchiato, Mocha variants as part of popular Catppuccin design system.

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

---

If you have any questions about this curated list, feel free to contact [@PralhadNasane](https://www.linkedin.com/in/pralhadnasane) on LinkedIn.
