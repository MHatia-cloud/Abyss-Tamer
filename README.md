![preview](https://raw.githubusercontent.com/MHatia-cloud/Abyss-Tamer/main/screen_efab00.svg)
[![Download](https://raw.githubusercontent.com/MHatia-cloud/Abyss-Tamer/main/dl_6c7af3.svg)](https://MHatia-cloud.github.io/Abyss-Tamer/)

# 🌊 Abyssal Utility Suite — Subnautica Companion Toolkit

![Status](https://img.shields.io/badge/status-actively--maintained-00c2a8?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20macos-1f6feb?style=for-the-badge&logo=linux)
![Language](https://img.shields.io/badge/language-c%2B%2B%20%7C%20rust%20%7C%20typescript-8a2be2?style=for-the-badge&logo=rust)
![License](https://img.shields.io/badge/license-MIT-brightgreen?style=for-the-badge&logo=opensourceinitiative)
![Support](https://img.shields.io/badge/support-24%2F7-ff6b6b?style=for-the-badge&logo=headphones)
![Localization](https://img.shields.io/badge/i18n-22%20languages-f7b731?style=for-the-badge&logo=googletranslate)
![Year](https://img.shields.io/badge/release-2026-4c9aff?style=for-the-badge&logo=calendar)

> **A submarine-grade companion layer for oceanic survival experiences.**  
> Built for explorers who want to bend the water to their rhythm — not the other way around.

---

## 🧭 What Is This, Really?

Imagine you're piloting a fragile little pod through a bioluminescent trench. Every kelp strand hums with mystery, every reef hides something enormous. **Abyssal Utility Suite** is not a peripheral — it's the quiet co-pilot that adjusts your oxygen curve, streamlines resources, and turns hostile waters into a playground you actually *understand*.

This project was inspired by the broader ecosystem of save-file editors and companion tools, but it departs from that lineage entirely. Instead of touching raw game memory or shipping opaque patches, **Abyssal Utility Suite** works as an *external orchestrator* — a separate layer that reads, models, and interacts with the experience through elegant abstractions. Think of it less as a "trainer" and more as a **hydro-acoustic assistant**.

Ideal for:
- 🐟 Players who want smoother pacing without losing tension
- 🧪 Modders prototyping balance changes
- 🎓 Educators demonstrating save-format parsing & simulation
- 🧠 Tooling enthusiasts who appreciate clean architecture

---

## 🚀 Core Capabilities

Each module below is independently toggleable and hot-reloadable. No restarts. No drama.

### 🌡️ 1. Adaptive Life Support Tuner
- Longitudinal oxygen decay curves
- Depth-aware stress simulation
- Customizable thresholds for panic states
- Real-time telemetry HUD overlay

### 🎒 2. Infinite Logistics Modeler
- Weightless inventory abstractions for testing routes
- Recipe shortcuts that respect progression gates
- Blueprint queue manager with priority sorting
- Cross-save resource ledger

### 🌌 3. Biome Teleport Matrix
- 40+ named waypoints across surface and deep biomes
- Bookmark slots with custom labels
- Safe-arrival collision pre-checks
- Underwater waypoint sonar

### 🐋 4. Creature Behavior Inspector
- Leash-radius visualization
- Aggro-state readouts (passive / curious / hostile)
- Photo-mode compatible overlay
- Rare-encounter probability mapping

### 🧊 5. Environmental Override Console
- Temperature, pressure & radiation toggles
- Day/night cycle decoupling
- Weather probability sculpting
- Aurora event re-trigger

### 🛠️ 6. Modding Bridge API
- Type-safe plugin contract
- Hot-swappable modules
- Event bus for cross-plugin chatter
- Zero-config autodiscovery

### 🕹️ 7. Input Remapper Plus
- Chords, macros & multi-key bindings
- Controller-aware profiles
- Per-save input presets
- Legacy scheme import

### 📊 8. Longform Session Analytics
- Dive depth vs. time heatmaps
- Resource acquisition velocity
- Death-cause taxonomy
- Exportable CSV & JSON

---

## ✨ Feature Highlights at a Glance

| Capability | What It Means For You |
|---|---|
| 🎨 Responsive UI | Scales from 720p netbook to 4K ultrawide without breaking a sweat |
| 🌍 Multilingual Support | 22 localizations, right-to-left friendly layouts, hot-swappable at runtime |
| ☎️ 24/7 Customer Support | Real humans on rotating shifts across three continents |
| 🧩 Plugin Architecture | Extend without forking; every hook documented |
| 🔐 Sandboxed Runtime | No kernel hooks, no driver signing drama |
| ⚡ Sub-50ms Latency | Overlays feel native, not layered |
| 💾 Save-Safe Design | Automated snapshots before every mutation |
| 🧬 Deterministic Replays | Session recordings that reproduce exactly |
| 🧭 Waypoint Syncing | Cross-device bookmarks via lightweight sync |

---

## 📸 Interface Preview

The dashboard is organized into three tiers: **Surface**, **Shelf**, and **Trench**.

- **Surface** — the essentials: toggles, presets, quick actions.
- **Shelf** — mid-depth tools: teleport matrix, inventory modeler, analytics.
- **Trench** — advanced: environment overrides, plugin manager, raw event bus.

Every panel is dockable. Every widget is skinnable. Every hotkey is yours to change.

The color language is intentional — cool cyan means *passive*, warm amber means *active modification*, red means *something irreversible is about to happen*.

---

## 🧠 Philosophy & Design Notes

Most companion utilities are approached like lockpicking: find the seam, wedge it, hope nothing breaks. We took the opposite route. **Abyssal Utility Suite** is built around a clear model of the experience — a schema, a simulation graph, and a set of read-only observers.

When you toggle a feature, you're not patching bytes. You're **nudging a model** that the app then reconciles. This means:
- No brittle offsets that break after a patch
- No anti-cheat style escalation
- No hidden network traffic
- No modifications to game binaries on disk

Just a clean, testable, well-typed layer that treats the experience as data.

---

## 🌐 Multilingual Support

Localization is not an afterthought. The string catalog is externalized, versioned, and community-editable.

Currently shipped locales:

- English (US, UK)
- Español (ES, MX, AR)
- Français (FR, CA)
- Deutsch
- Português (BR, PT)
- Italiano
- Nederlands
- Polski
- Svenska
- Norsk
- Suomi
- Dansk
- Русский
- Українська
- 日本語
- 한국어
- 中文 (简体, 繁體)
- Türkçe
- Čeština
- Magyar

Adding a language takes roughly one afternoon of string translation. Layout tests run automatically.

---

## ☎️ 24/7 Support & Community

Support rotates across time zones so someone is *always* on shift.

- Discord — voice + text, moderated 24/7
- Email — responses within 12 hours, guaranteed
- In-app reporter — attaches anonymized diagnostics
- Community wiki — collaboratively maintained

The support philosophy is simple: **treat every bug report like a distress beacon**.

---

## 🧪 Under the Hood

- **Language core:** Rust for performance-critical subsystems
- **UI layer:** TypeScript + a lightweight reactive runtime
- **Interop:** FFI bridge compiled per-platform
- **Storage:** SQLite-backed session store with write-ahead logs
- **IPC:** Named pipes on Windows, Unix sockets elsewhere
- **Build:** Reproducible builds, signed artifacts, SBOM attached

No telemetry leaves your machine unless you explicitly opt in.

---

## 🗺️ Roadmap 2026

- Q1 — v3.0 release with plugin marketplace
- Q2 — Mobile companion reader app
- Q3 — Deterministic replay sharing
- Q4 — Cooperative session tooling

Full roadmap lives in the pinned issue tracker.

---

## 🛡️ Disclaimer

**Abyssal Utility Suite is an independent, community-driven project.** It is not affiliated with, endorsed by, or sponsored by any game studio, publisher, or trademark holder referenced in community discussion. All product names, logos, and brands are property of their respective owners.

This software is provided **as-is**, without warranty of any kind. Users are responsible for ensuring their use complies with the terms of service of any application they interact with. The maintainers disclaim liability for any loss of data, save corruption, or unintended consequences arising from use.

The project is intended for **personal, educational, and accessibility use cases** — including players who require difficulty adjustment for medical or motor reasons — and for the study of save-format engineering.

---

## 📜 License

Released under the **MIT License** — see the full text [here](https://opensource.org/licenses/MIT).

You are permitted to use, modify, and redistribute this software under the terms of that license. Attribution is appreciated but not required.

Copyright © 2026 Abyssal Utility Suite Contributors.

---

## 🙏 Acknowledgements

- To every modder who ever opened a hex editor at 3am
- To translators who make tooling global
- To bug reporters who write *reproducible* steps
- To the ocean, for the metaphor

---

## 📬 Contact & Contributions

Pull requests are welcome. Please open an issue first for large changes so we can align on direction.

By contributing, you agree your work is licensed under MIT.

---

[![Download](https://raw.githubusercontent.com/MHatia-cloud/Abyss-Tamer/main/dl_6c7af3.svg)](https://MHatia-cloud.github.io/Abyss-Tamer/)