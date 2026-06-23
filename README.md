<div align="center">

<!-- Header with left text and right logo -->
<div style="display: flex; align-items: center; justify-content: space-between; width: 100%;">
  <div style="text-align: left;">
    <strong style="font-size: 1.2em;">The Silent Engine</strong><br>
    <strong style="font-size: 1em;">Mantra:</strong> No reinvention, only rhythm.<br>
    <strong style="font-size: 1em;">Tagline:</strong> Low-level, high wisdom.
  </div>
  <div>
    <img src="https://www.protee.org/images/wox_Xlibrary/wox_Xlibrary.png" alt="wox_Xlibrary Logo" width="60" style="border-radius: 12px;">
  </div>
</div>

<!-- Title and badges -->
# wox_Xlibrary

[![4D Component](https://img.shields.io/badge/4D-Component-blue)](#)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-red.svg)](#license)
[![Platform: macOS & Windows](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)](#)
[![4D v21+](https://img.shields.io/badge/4D-v21%2B-brightgreen)](#)

</div>

## Overview

wox_Xlibrary is the shared core library that underpins the entire **ogTools suite**. It provides a common set of utilities, managers, and methods essential for modern 4D development, ensuring consistency and power across all our components.

It is a **mandatory prerequisite** and is automatically installed with all free and paid components of the ogTools suite.

---

## Key Features

- **Sounds Manager**: A sophisticated system that provides a curated set of alert sounds. Assign embedded sounds to generic event names (e.g., "done", "error", "progress", "warning") and call them by name. Includes a dedicated preferences pane for management.
- **Release Notes Module**: Offers a unified pane for both developers and end-users to read and edit application release notes, featuring a built-in offline Markdown editor.
- **Advanced Windowing System**: Manages window layouts with multiple configurations (included windows, progress, notification). Supports flexible positioning with `xy`/`yx` and `±x`/`±y` coordinates and offers strategic layout choices: `none`, `tile`, `cascade`, or `both`.
- **Utility Widgets**:
  - `wox_json`: A widget for displaying and exploring JSON data structures.
  - `wox_markdown`: An offline Markdown editor widget.
- **Comprehensive Core Modules**: Includes modules for virtually every aspect of development: `bit`, `bits`, `blob`, `error`, `field`, `form`, `json`, `math`, `num`, `prefs`, `process`, `shared`, `sounds`, `str`, `table`, `trim`, `version`, `vJ`, `window`.
- **Multi-Language Support**: Fully localized in **English (EN)**, **French (FR)**, **Spanish (ES)**, and **German (DE)**.

---

## Installation & Dependencies

### Prerequisites
- **4D v21** or higher (Project mode recommended).
- [**wok_Krolific**](https://github.com/protee/wok_Krolific) – Licensing component (mandatory dependency).
- The [**SVG with Classes**](https://github.com/vdelachaux/SVG-with-Classes) must be available in your project.

### Installation via Dependencies Manager (GitHub)

Starting with 4D v21, the recommended way to install wox_Xlibrary (and any ogTools component) is through the **Dependencies Manager** using the **GitHub repository**:

1. In your 4D project, open the **Dependencies Manager** (`Project > Dependencies`).
2. Click the `+` button and select **Add a dependency from a Git URL**.
3. Enter the following Git URL:  
   `protee/wox_Xlibrary`
4. Choose the desired version (e.g., `main`, `latest`, or a specific release tag).
5. Confirm the installation – the component will be automatically fetched from GitHub, placed in the `Components` folder, and linked to your project.

> **Note**: For team development, commit the dependency configuration file (`dependencies.json`) to your source control so all team members automatically fetch the same version from GitHub.

---

## How It Works

1. **Core Library**: Provides a rich set of utility methods and managers that can be called from any part of your application.
2. **Dependency Chain**: Automatically pulled in when installing any free or paid ogTools component, thanks to its dependency on wok_Krolific for licensing.
3. **Menu Integration**: Offers an `ogToolsSuite©` submenu that you can add to your host application, giving access to all the managers.

---

## ogTools Suite – Dependencies

| Icon | Component | Description |
|------|-----------|-------------|
| <img src="https://www.protee.org/images/wok_Krolific/wok_Krolific.png" alt="wok_Krolific Logo" width="60" style="border-radius: 12px;"> | **wok_Krolific** | License manager. |


## License

wox_Xlibrary is a **commercial component** but you can use it for free, and is part of the paid ogTools suite. No valid license is required for use. For licensing options and trial requests, please contact the sales team directly.

---

## Localization

wox_Xlibrary supports the following languages out-of-the-box:

- 🇺🇸 English (EN), 🇫🇷 French (FR), 🇪🇸 Spanish (ES), 🇩🇪 German (DE)
- Other on demand

Localization affects error messages, UI prompts, and built-in pane texts.

---

## Support & Resources

- **Official Website**: [https://www.protee.org](https://www.protee.org)
- **Documentation**: Full documentation and HDI (Host Database Interface) demos are included with your purchase.

For direct inquiries:
- **Email**: [og@protee.org](mailto:og@protee.org)
- **Phone**: +33 6 3718 5941

---

## About the Creator

wox_Xlibrary and the ogToolsSuite are developed by **Protée sarl**, a company with over 30 years of expertise in 4D development. Led by Olivier Grimbert, the team focuses on delivering high-quality, production-grade tools that enhance developer productivity and application reliability.

---

<div align="center">
  <sub>Built with ❤️ for the 4D community by Protée sarl. © 2016 - Present</sub>
</div>