# 🪐 IRAM 3D: Spatial Computing & Three.js Desktop Suite

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Hyprland%20%7C%20Wayland-purple.svg)]()
[![Engine](https://img.shields.io/badge/engine-Three.js%20r128%20%7C%20WebGL2-cyan.svg)](https://github.com/mrdoob/three.js/)

**IRAM 3D** is an autonomous, hardware-accelerated 3D spatial computing suite engineered for Linux desktops (Hyprland / Wayland / Ubuntu). Built on top of [Three.js](https://github.com/mrdoob/three.js/), it replaces heavy, slow desktop toolkits with instantaneous, GPU-accelerated WebGL workspaces for CAD inspection, multi-agent AI swarm telemetry, 3D theme lighting simulation, and cinematic motion graphics.

---

## 🏛️ Integrated 3D Workspaces

```
                                  ┌────────────────────────┐
                                  │      IRAM 3D CORE      │
                                  └───────────┬────────────┘
                                              │
         ┌───────────────────┬────────────────┴────────────────┬────────────────────┐
         ▼                   ▼                                 ▼                    ▼
   [iram 3d]          [iram agent graph]              [iram theme 3d]        [iram video 3d]
   Interactive CAD    3D Force-Directed Swarm         PBR Material Shader    Cinematic Motion
   & Mesh Inspector   Topology & IPC Photon Conduits  & 18 Palette Sim       Graphics & Intros
```

### 1. `iram 3d` — 3D CAD & Mesh Inspector
* **Instant CAD Previews**: Open any local `.stl`, `.obj`, or `.gltf` file with drag-and-drop or command line:
  ```bash
  iram 3d /path/to/part.stl
  ```
* **Scientific & Procedural Models**: Out-of-the-box DNA Double Helix biomolecule, Laboratory Tube Rack (CADCraft), Torus Knot, and cyberpunk vertex clusters.
* **Telemetry**: Real-time FPS, polygon counter, wireframe toggle, and neon theme shaders (Cyan, Crimson, Emerald, Gold).

### 2. `iram agent graph` — 3D Multi-Agent Swarm Visualizer
* **Hierarchical Swarm Topology**:
  * **Tier 1 (Lead Architect)**: Core celestial sphere with planetary ring and icosahedral shell (Reasoning & Decomposition).
  * **Tier 2 (Task Coordinator)**: Intermediate orbital sphere orchestrating ticket dispatches and gate verification.
  * **Tier 3 (Grunt Workers)**: Dynamic satellite nodes (Research, TDD, CAD modeling).
  * **MCP Satellites**: Peripheral modules for Qdrant Vector Memory, PipeWire Audio, and System Bridges.
* **Animated IPC Conduits**: 3D Catmull-Rom spline curves with continuous photon streams visualizing real-time token throughput and agent messaging.
* **Interactive Node Inspector**: Inspect active LLM models, execution latencies, token burn meters, and verification gate outcomes.

### 3. `iram theme 3d` — 3D Palette Lighting Simulator
* **All 18 IRAM OS Curated Palettes**: Preview Tokyo Storm, Cyberpunk Neon, Synthwave 84, Catppuccin Mocha, Dracula, Nord Frost, Rose Pine, and more in 3D.
* **PBR Material Simulator**: Displays palette colors mapped to physical properties (glossy metallic torus, translucent glass refraction sphere, and cyberpunk floor grid).
* **Live Desktop Apply**: 1-click apply instantly updates Hyprland, Waybar, Alacritty, and Neovim without restarting.

### 4. `iram video 3d` — 3D Motion Graphics & Intro Studio
* **Kinetic Title Cards**: Procedural 3D title generation for [iram-video](https://github.com/apravint/iram-video) trailers and YouTube Shorts.
* **Camera Recipes**: Hero Reveal, Cyber Crash-Zoom, Macro Floating Drift, and Matrix Spiral Flythrough.
* **Direct WebM/MP4 Recording**: In-browser 60 FPS `MediaRecorder` capture directly exports master clips ready for FFmpeg compositing.

---

## 🚀 Installation & Standalone Usage

```bash
# Clone repository
git clone https://github.com/apravint/iram-3d.git
cd iram-3d

# Make executables available in PATH
mkdir -p ~/.local/bin
ln -sf $(pwd)/bin/* ~/.local/bin/

# Launch any studio
iram-3d                  # Launch CAD Mesh Inspector
iram-agent-graph         # Launch 3D Agent Swarm Graph
iram-theme-3d            # Launch 3D Theme Studio
iram-video-3d            # Launch 3D Motion Graphics Studio
```

---

## 📜 License
MIT License. Created by [Pravin](https://github.com/apravint) for IRAM OS.
