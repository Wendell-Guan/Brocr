<p align="center">
  <img src="icon/icon.png" width="180" alt="Brocr App Icon" />
</p>

<h1 align="center">Brocr</h1>

<p align="center">
  <strong>Instant screen OCR for macOS. Select, recognize, done.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS-blue?style=flat-square" alt="macOS" />
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey?style=flat-square" alt="License" />
</p>

---

> **Note** — This repository is used for **distributing releases only**. It does not contain source code.
> The source code is maintained in a separate private repository.
> Head over to [Releases](../../releases) to download the latest `.dmg`.

---

## What is Brocr?

Brocr is a lightweight, native macOS menu-bar app that lets you **extract text from anywhere on your screen** in seconds. No browser extensions, no cloud uploads, no subscriptions — just a single keyboard shortcut and instant results.

## Highlights

- **One shortcut, instant OCR** — Press `Cmd + Shift + 2`, drag a selection, and the recognized text is on your clipboard before you let go of the mouse.
- **Multilingual** — Accurately reads **English, Simplified Chinese, and Traditional Chinese**, including mixed-language content.
- **100% on-device** — Powered by Apple Vision. Your screenshots and text never leave your Mac.
- **Lives in the menu bar** — Zero windows, zero dock clutter. Brocr stays out of your way until you need it.
- **Beautiful result panel** — A minimal, dark-themed floating panel shows the recognized text with one-click copy.
- **Native & fast** — Built in Swift with ScreenCaptureKit. Tiny memory footprint, instant startup.

## Getting Started

1. Download the latest `Brocr.dmg` from [**Releases**](../../releases).
2. Open the DMG and drag **Brocr** into your Applications folder.
3. Launch Brocr — you'll see a small `[ ]` icon appear in the menu bar.
4. Press **`Cmd + Shift + 2`** and select a region to capture text.

## System Requirements

| | |
|---|---|
| **OS** | macOS 14 Sonoma or later |
| **Chip** | Apple Silicon or Intel |

## How It Works

```
  ⌘⇧2  →  Select Region  →  OCR  →  Clipboard
              ↓                        ↓
        Screen capture         Floating result panel
        (ScreenCaptureKit)     with one-click copy
```

## FAQ

**Is my data sent anywhere?**
No. All recognition happens locally on your Mac using Apple's Vision framework. Brocr makes zero network requests.

**Where is the source code?**
The source code is hosted in a separate repository and is not publicly available here. This repo exists solely for publishing releases and tracking issues.

**Can I request a feature or report a bug?**
Absolutely — open an [Issue](../../issues) and we'll take a look.

---

<p align="center">
  Made with care for people who just want the text.
</p>
