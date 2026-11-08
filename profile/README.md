# FerroEDA

> **Pure-Rust, memory-safe, web-ready Electronic Design Automation (EDA) for open-source silicon.**

FerroEDA is building a modern, crash-free semiconductor design suite written in 100% pure Rust. Our tools are designed for high performance, modern GPU-accelerated rendering, first-class WebAssembly support, and an AI-native command architecture.

---

## The Suite

| Tool | Focus | Status | Compatibility |
| :--- | :--- | :--- | :--- |
| **[FerroSchem](https://github.com/ferro-eda/ferroschem)** | Schematic capture & netlisting | In Active Development | xschem (`.sch` / `.sym`), SPICE, Verilog |
| **[FerroLayout](https://github.com/ferro-eda/ferrolayout)** | Physical IC layout & verification | Planned | Magic (real-time DRC) + KLayout (GDSII/OASIS) |
| **FerroWave** | Waveform viewer | Roadmap | VCD, FST, raw SPICE data |

---

## Core Principles

- 🦀 **Pure Rust (`unsafe_code = "forbid"`):** Never lose your work to a segfault. Zero memory-safety bugs in the core engine.
- 🌐 **Web & Desktop First-Class:** Runs natively on macOS, Linux, and Windows, or straight inside your browser via WebAssembly (`wasm32-unknown-unknown`) and WebGPU.
- 🤖 **AI-Native & Human-Friendly:** Every user action is an engine command (`Session::execute`). What a human can click, an AI agent or headless script can automate with full review-before-apply safety.
- 🤝 **Open Standards:** Built for open PDKs (SkyWater 130nm, GlobalFoundries 180nm, IHP SG13G2) and seamless interoperability with the broader open-source EDA ecosystem.

---

## License

All core FerroEDA tools are licensed under [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).
