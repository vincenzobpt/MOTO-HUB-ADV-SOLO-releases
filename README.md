<div align="center">

<img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/logo.png" alt="MOTO-HUB ADV-SOLO logo" width="120">

# MOTO-HUB ADV-SOLO

**One app. Everything MOTO-HUB does, with nothing else to install.**

[![Latest release](https://img.shields.io/github/v/release/vincenzobpt/MOTO-HUB-ADV-SOLO-releases?label=release&color=e10600)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/total?color=e10600)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases)
[![Standalone](https://img.shields.io/badge/standalone-no%20second%20app-2ea44f)](#installation)
[![Android 14+](https://img.shields.io/badge/Android-14%2B-3DDC84?logo=android&logoColor=white)](#installation)
[![Discord](https://img.shields.io/badge/Discord-join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/jYv7Z2chtP)

<img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/tft-ride-dashboard.png" alt="MOTO-HUB ADV-SOLO Ride Dashboard on the motorcycle TFT" width="700">

Until now, the full MOTO-HUB experience meant two apps: [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB) to connect the bike and [ADVANCED](https://github.com/vincenzobpt/MOTO-HUB-PRO-releases) for everything on top of it, kept in step at the same version number.<br>
**ADV-SOLO is both of them in one install** — pairing, the T-Box link, mirroring, handlebar buttons, the Ride Dashboard, Navigation, Trips, AI place discovery, group intercom. No companion app, no version to match.

<br>

[![Download MOTO-HUB ADV-SOLO](https://img.shields.io/badge/Download%20MOTO--HUB%20ADV--SOLO-free-e10600?style=for-the-badge&logo=android&logoColor=white)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest)

<sub>On the release page, expand **Assets** and download the file ending in `.apk`.</sub>

<br>

### 💬 Come and ride with us

**Every rider here is on Discord** — support when a dashboard misbehaves, help getting your bike working, early builds, and the place where the next features get decided.

[![Join the MOTO-HUB Discord](https://img.shields.io/badge/JOIN%20THE%20MOTO--HUB%20DISCORD-support%20·%20community%20·%20new%20builds-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/jYv7Z2chtP)

</div>

**This repository contains no source code.** MOTO-HUB ADV-SOLO is closed source. Only signed, obfuscated release APKs are published here, under the [Releases](../../releases) tab — and this is also where the app itself looks when it checks for updates.

## Which one should I install?

| | [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB) | [+ ADVANCED](https://github.com/vincenzobpt/MOTO-HUB-PRO-releases) | **ADV-SOLO** |
| --- | :---: | :---: | :---: |
| Apps to install | 1 | 2, version-matched | **1** |
| T-Box pairing, garage, connection | ✅ | ✅ | ✅ |
| Screen mirroring, handlebar buttons | ✅ | ✅ | ✅ |
| Ride Dashboard, Navigation, Trips, AI, intercom | — | ✅ | ✅ |
| Android Auto on the TFT | built in | via MOTO-HUB | [add-on module](#android-auto-comes-as-a-module) |
| Source code | open, AGPL-3.0 | closed | closed |

ADV-SOLO installs alongside MOTO-HUB and ADVANCED rather than replacing them, so you can try it without giving up what already works on your bike.

## What you get

### 🏍️ Ride Dashboard

A native, configurable riding scene rendered straight on the TFT: GPS speed, live map, trip stats, weather, phone status — every panel is a widget you choose, and panels can rotate through a carousel. The main panel is yours too: put the **live map** there, or switch it to a full **OBD gauge cluster** with live engine data and gear estimation (ELM327 Bluetooth adapter required). Turn-by-turn guidance from Waze or Google Maps shows up in the Navigation widget.

### 🗺️ Navigation, built for motorcycles

Search, motorcycle routing (including *curvy roads*), waypoints, and a route preview that is a full briefing: **where the curves are** and what the twisty line costs you against the fast one, **the shape of the ride** (ascent, turns, elevation profile), **weather along the route** (rain cells with the time you'll meet them, crosswind, ice risk), **live fuel prices** on your path in 🇮🇹 🇪🇸 🇫🇷 🇵🇹, **speed camera alerts** (off by default, disabled where the law forbids them), and **Mapillary street-level imagery** with a tap on the route line.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-1.png" alt="Route preview showing where the curves are and the Fast or Piega route choice" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-2.png" alt="Route briefing with ascent, turns, elevation profile and petrol prices on the route" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-3.png" alt="Weather along the route with temperature and crosswind at each stage" width="230">
</div>

### 📈 Trips — record, relive, improve

Full sensor telemetry on every ride: replay it on the map, in a **3D chase-cam POV**, or as a **Google Earth KMZ** flyover; analyze speed, altitude, lean angle and G-forces; get a **Riding Coach** AI evaluation; pin **audio notes** to the exact point of the trip; export GPX.

### 🤖 AI place discovery &nbsp;·&nbsp; 🎙️ Group intercom

Ask for "a scenic pass with a café at the top" and let the AI tab rank real OpenStreetMap places — bring your own OpenAI-compatible API key, stored encrypted on the phone. And when you ride with a friend, **group intercom** carries voice between two phones over the rider's own hotspot — no accounts, no servers.

### 🥚 …and one secret left to find

ADV-SOLO hides one more toy: a complete **OBD-II diagnostics suite**, tucked behind a door that appears on no menu. How to open it stays a secret — but riders who find it get **live engine data**, **fuel & air** readings, **stored trouble codes** explained by a built-in catalogue, and a **full scan** of every PID your motorcycle supports, shareable as a report.

## Android Auto comes as a module

Android Auto is not built into ADV-SOLO. The receiver that talks to the phone's Android Auto is open-source software under AGPL-3.0, and a closed app cannot carry it — so it ships as a **module the app downloads and loads when you ask for it**, from the public [MOTO-HUB-modules](https://github.com/vincenzobpt/MOTO-HUB-modules) catalogue.

Open `Settings ▸ Modules` inside the app, install the Android Auto module, and the TFT gains Android Auto. Skip it and everything else works exactly the same — the app simply never mentions a feature it cannot offer.

## Installation

1. Download the APK from [Releases](../../releases/latest).
2. Enable "Install unknown apps" for your browser or file manager when Android asks.
3. Install it, open it, and pair with your motorcycle's T-Box.
4. Optional: `Settings ▸ Modules` to add Android Auto.

Requires **Android 14 or newer**. The app checks this page for its own updates and can install them for you.

## Privacy

ADV-SOLO works without an account and records rides only on the phone. Trips, tracks and GPX exports stay on the device.

Features that need the Internet disclose only what that request needs, to the service that answers it and to no MOTO-HUB account: map tiles for the area being displayed, a typed search to the geocoder, an origin/destination pair to the routing service, destination and arrival time to the weather service. The AI tab talks to an OpenAI-compatible endpoint using **the rider's own API key**, which is stored encrypted with the Android Keystore, sent only as an authorization header, and never logged.

Official releases report **crashes and errors to Sentry** (EU region) so that failures which need a motorcycle to reproduce can be diagnosed. Sentry's default PII collection is switched off, diagnostic messages are redacted and capped per app run, and grouping tags are deliberately coarse. Screen content, T-Box passwords and recorded positions are never sent. Turning off `Settings ▸ Diagnostics ▸ Enable logging` stops the diagnostic log and the error events that come from it; crash reports are handled by the Sentry SDK itself and are not covered by that switch.

**Diagnostics reports.** After a one-time notice at first launch, ADV-SOLO also sends a diagnostics report to the developer's own collector — dashboard identity and saved motorcycle profiles (never the Wi-Fi password), phone model and Android version, app version, and the redacted diagnostic log — at most once a day, after an update, or after a crash, only over a connection with Internet access. Each report carries a **Support ID** (a one-way hash of Android's per-app installation id and the active motorcycle; shown under `Settings ▸ Diagnostics`). Quote it when asking for help. `Settings ▸ Diagnostics ▸ Send diagnostics automatically` turns it off; `Send diagnostics now` sends one on request.

## Status

**ADV-SOLO is new, and it is the newest of the three.** MOTO-HUB and ADVANCED have ridden many more kilometres. If your bike works today, keep what you have and try this one alongside it — that is exactly what it is built to allow.

MOTO-HUB is an experimental proof-of-concept, not a production-grade product. Day-to-day development happens on a CFMOTO 700MT-ADV dashboard, but the app is not CFMOTO-only: riders have confirmed it on Benelli TRK 502 / 702 / 702X, Voge DS800X and 800 Rally, Zontes 368E, QJ Motor SRT 550 and CFMOTO 800MT and 675SRR, with more models partly working or still untested. The model-by-model table lives on the MOTO-HUB page — see [Supported Motorcycles](https://github.com/vincenzobpt/MOTO-HUB#supported-motorcycles).

Behavior may differ on other motorcycles, T-Box firmware versions, or phones. Do not depend on it as your only source of critical navigation information. Plan your route before riding, and use the software at your own risk.

> [!NOTE]
> **Riding with an iPhone?** MOTO-HUB for iOS is available now — install it through AltStore Classic or sideload the IPA from [its own releases page](https://github.com/vincenzobpt/MOTO-HUB-IOS-releases). Requires iOS 17 or later.

## Community

<div align="center">

[![Discord](https://img.shields.io/badge/JOIN%20US%20ON%20DISCORD-support%20·%20community%20·%20development-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/jYv7Z2chtP)

</div>

## License

MOTO-HUB ADV-SOLO is proprietary, closed-source software. Distribution here does not grant any license to the source code. [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB) itself remains fully open source under AGPL-3.0, and the [Android Auto module](https://github.com/vincenzobpt/MOTO-HUB-modules) is AGPL-3.0.
