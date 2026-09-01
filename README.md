# FNF FunkDot Engine

![FNF FunkDot Engine](https://img.shields.io/badge/FNF-FunkDot%20Engine-blue)
![Godot](https://img.shields.io/badge/Godot-4.x-478CBF)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)

**FNF FunkDot Engine** is a Friday Night Funkin' engine being developed in **Godot 4**.

The goal is to provide a flexible, highly customizable FNF engine while taking advantage of Godot's scene system, GDScript, shaders, and editor workflow.

> **FunkDot Engine is currently unreleased due to its W.I.P**

---

## ✨ Features

FunkDot Engine is designed around customization and giving modders as much control as possible.

### 🎵 FNF Gameplay

- 4-key rhythm gameplay
- Regular notes
- Sustain notes
- Custom note skins
- Custom note colors
- Note RGB shaders
- Note splash support
- Configurable hit windows
- Ghost tapping
- Botplay
- Practice mode
- Opponent mode
- Scroll speed customization
- Downscroll
- Middlescroll
- Note offset
- Custom ratings
- Custom hitsounds
- BPM changes
- Song timing through a Conductor system

### 🎨 Customization

FunkDot Engine uses Godot's scene system heavily.

Instead of forcing modders to create UI entirely through code, many engine components can be configured directly inside `.tscn` scenes.

For example:

```text
MainMenu
├── Background
├── MenuItems
│   ├── StoryMode
│   ├── Freeplay
│   ├── Mods
│   └── Credits
├── LeftItem
├── RightItem
└── VersionText
