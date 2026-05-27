# ⚡ Vitality

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)](https://github.com/ashcabula30/Vitality)
[![SaaS](https://img.shields.io/badge/Product-Desktop%20Widget-blueviolet?style=for-the-badge)](https://github.com/ashcabula30/Vitality)
[![Tech Stack](https://img.shields.io/badge/Stack-Tauri%20%7C%20React%20%7C%20Rust-red?style=for-the-badge&logo=rust)](https://github.com/ashcabula30/Vitality)
[![Cloud Sync](https://img.shields.io/badge/Sync-Supabase%20%28Optional%29-green?style=for-the-badge&logo=supabase)](https://github.com/ashcabula30/Vitality)

> A sleek, hardware-accelerated, transparent desktop overlay widget for Windows. Seamlessly monitor your CPU, GPU, RAM, Disk, and Network metrics in real-time, rendered beautifully via a native, low-resource environment.

---

## ✨ Features Highlight

- **📊 Real-Time Metric Feeds**: Dynamic tracking of CPU (load, clock speed, temps), GPU (load, clock speed, VRAM, temps), RAM usage, Disk status, and Network throughput.
- **🎨 Frameless Glassmorphism Overlay**: Ultra-smooth borderless transparent window with fully adjustable opacity, blur backdrops, and interactive click-through behavior.
- **🔄 Dual Layout Systems**: Seamlessly toggle between a sleek vertical sidebar or a compact horizontal dashboard bar.
- **🎛️ Drag-and-Drop Widget Grid**: Configure, show/hide, and re-order individual metric monitors on-the-fly to customize your desktop view.
- **⚠️ Color-Coded Warning Levels**: Intelligent telemetry featuring customizable amber (warning) and red (critical) threshold indicators.
- **☁️ Supabase Cloud Sync**: Synchronize your widgets, layouts, and warning configurations across multiple machines securely using Google OAuth.

---

## 🛠️ The Tech Stack

Engineered using an enterprise-grade native desktop wrapper paired with next-generation frontend frameworks:

- **Desktop Framework**: [Tauri 2](https://tauri.app/) (High-performance native Rust wrapper)
- **Frontend Core**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Engineered Backend**: [Rust](https://www.rust-lang.org/) (Handles data polling, normalization, and OS bindings)
- **Styling & Fluid Motion**: [Tailwind CSS 4](https://tailwindcss.com/) & [Framer Motion](https://www.framer.com/motion/)
- **Telemetry Provider**: [LibreHardwareMonitor Web Server](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor)
- **Database / Auth**: [Supabase](https://supabase.com/) for optional settings synchronization

---

## 💼 Access & Licensing

This repository serves as a **public feature showcase** for the Vitality desktop system monitor. 

> [!IMPORTANT]
> **Source Code & Distribution Access**
> 
> The source code for this application is hosted in a private repository to protect the intellectual property, design assets, and backend configurations.
> 
> **Want to explore, build, or obtain the product?**
> - **Contact Owner**: Please reach out directly to the repository owner to request access to the active private source code repository, licensed distribution bundles, or integration workflows.
> - **Inquiries**: Open a GitHub Issue on this repository or message the repository owner via their profile.

---

<p align="center">
  Built with ❤️ using Tauri, React, and Rust
</p>
