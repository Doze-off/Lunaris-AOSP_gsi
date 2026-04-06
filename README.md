# 🌙 Lunaris AOSP GSI — Balanced. Smooth. Yours. 🌙

> *A moonlit Android experience — polished performance, deep customization, and rock-solid stability.*

<a href="https://github.com/Doze-off/Lunaris-AOSP_gsi/actions/workflows/build.yml"><img src="https://github.com/Doze-off/Lunaris-AOSP_gsi/actions/workflows/build.yml/badge.svg"></a>
<a href="https://developer.android.com/about/versions"><img src="https://img.shields.io/badge/Android-15-green.svg"></a>
<a href="https://android-developers.googleblog.com/2017/05/here-comes-treble-modular-base-for.html"><img src="https://img.shields.io/badge/Project-Treble-blue.svg"></a>

---

## 🌙 About

**Lunaris AOSP GSI** is a Generic System Image based on <a href="https://github.com/Doze-off/Lunaris-AOSP_gsi">Lunaris AOSP</a>, bringing a balanced mix of performance, smoothness, and customization to any <a href="https://android-developers.googleblog.com/2017/05/here-comes-treble-modular-base-for.html">Project Treble</a> compatible device — all while keeping stability front and centre.

Lunaris AOSP draws from the best of the custom ROM world, merging features from various ROMs into a single, cohesive experience that feels both familiar and refined.

---

## ✨ Notable Features

- 🤖 **Pixel features** — Google Pixel exclusives brought to your device
- 🎨 **Advanced theming options** — Deep customization for colours, fonts, icon shapes, and more
- ⚡ **CAF changes ported** — Code Aurora Forum optimizations for improved hardware compatibility and performance
- 🔒 **Customizable lock screen** — Clocks, shortcuts, media controls, and layout tweaks at your fingertips
- 📊 **Customizable status bar** — Battery style, clock position, network indicators, and icon toggles
- 🚀 **Performance optimizations** — Tuned scheduler, smoother animations, and reduced overhead
- 🧩 **Features from various ROMs** — Handpicked additions merged from popular custom ROMs into one build

---

## 📦 Downloads

Check the <a href="https://github.com/Doze-off/Lunaris-AOSP_gsi/releases">**Releases**</a> page for the latest builds.

| Variant      | Architecture | Description                     |
|--------------|--------------|---------------------------------|
| `arm64`      | ARM64        | For most modern 64-bit devices  |
| `arm64-ab`   | ARM64 A/B    | For A/B partition devices       |

---

## 📋 Requirements

- **Project Treble** compatible device
- **Unlocked bootloader**
- A custom recovery (e.g. TWRP) or `fastboot` access
- At least **3 GB RAM** recommended
- **Android 9+** firmware on the device (for Treble support)

---

## 🔧 Installation

1. Download the latest GSI image from the <a href="https://github.com/Doze-off/Lunaris-AOSP_gsi/releases">Releases</a> page.
2. Boot into fastboot mode:
   ```bash
   adb reboot fastboot
   ```
3. Flash the GSI:
   ```bash
   fastboot flash system Lunaris-AOSP-<variant>.img
   ```
4. Reboot:
   ```bash
   fastboot reboot
   ```

> **Tip:** On some devices you may need to wipe userdata (`fastboot -w`) before flashing a GSI.

---

## ⚠️ Disclaimer

This GSI is provided **as-is** with no warranty. Always back up your data before flashing. The maintainers are not responsible for any damage to your device.

---

## 🤝 Credits

- The **Lunaris AOSP** team for the base ROM
- All upstream ROM projects whose features are merged into this build
- The **Android GSI** and **Project Treble** communities

---

<p align="center">Made with 🌙 by the Lunaris AOSP team</p>