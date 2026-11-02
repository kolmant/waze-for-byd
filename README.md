# Waze for BYD Vehicles

[![Latest Release](https://img.shields.io/github/v/release/kolmant/waze-for-byd?color=blue&label=Latest%20Release)](https://github.com/kolmant/waze-for-byd/releases)

> [!TIP]
> 🇪🇸 **¿Prefieres leer en español?** Puedes ver la [versión en español aquí](README.es.md).

A modified version of Waze tailored for BYD infotainment systems. It directs voice navigation instructions through the car's dedicated navigation audio channel so guidance and music volumes stay independent.

---

## What does this project do?

On BYD infotainment screens, the standard version of Waze plays its voice directions through the main music/multimedia channel. This causes common annoyances:
* If you turn down or mute your music, navigation directions are also silenced.
* Music volume adjustments directly alter spoken route instructions.

**This project fixes that behavior:**
We adjust Waze so that voice directions are sent to your BYD vehicle's **Navigation channel**. This allows the car's system to manage navigation volume separately from Spotify, radio, or any other media source.

---

## What are "Releases"?

If you are not familiar with GitHub, you don't need to know how to code to use this:

* In software development, a **Release** is a packaged, ready-to-use version of an application.
* Whenever Waze publishes an update, our automated system generates a ready-to-install Android package file (`.apk`) and publishes it under the **[Releases](https://github.com/kolmant/waze-for-byd/releases)** page.
* You only need to visit the **Releases** tab, find the latest version, and download the `.apk` file under the **Assets** dropdown.

---

## How to Install

1. **Uninstall any existing Waze:**  
   If you have the official Google Play Store version or an older build installed, uninstall it from your car's screen first.
2. **Download the APK:**  
   Go to **[Releases](https://github.com/kolmant/waze-for-byd/releases)** and download the latest `.apk` file (e.g., `waze-navi-X.XX.X.X.apk`).
3. **Install on your car:**  
   Copy the downloaded file to a USB flash drive, plug it into your BYD vehicle, open the car's **File Manager**, and tap the APK to install.
4. **Google Play Protect notice:**  
   Because this application is re-signed with a community key, your car's system or Google Play Protect may ask for confirmation to install from an "unknown source". Simply choose to proceed.

---

## Disclaimer

This is an independent community project and is not affiliated with, endorsed by, or associated with Waze, Google, or BYD Auto.
