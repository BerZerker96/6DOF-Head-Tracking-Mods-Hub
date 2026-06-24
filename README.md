<p align="center">
<img width="1584" height="672" alt="1782281895271" src="https://github.com/user-attachments/assets/1a3d8cb9-62bf-4924-acdb-6c22fe62624c" />

</p>

<h1 align="center">🎯 6DOF Head-Tracking Mods</h1>

<p align="center">
  <i>Bring real head-tracking to your favourite single-player games.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows-0a7bbb?style=flat-square&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/input-OpenTrack%20UDP-2dd4bf?style=flat-square" alt="OpenTrack">
  <img src="https://img.shields.io/badge/loader-ASI-ff4655?style=flat-square" alt="ASI Loader">
  <img src="https://img.shields.io/badge/use-single--player%20only-808080?style=flat-square" alt="single player only">
</p>

---

## ✨ What is this?

A hub where I release my **6DOF head-tracking mods** — they let you lean, peek, and look around in-game
using your real head movement. Each mod is built on the head-tracking **framework by [Loop](https://github.com/itsloopyo?tab=repositories)**,
and ships **ready to go**: the mod is already packed with an **ASI loader**, so there's nothing extra to install.

---

## 🎮 Supported Games

> 🚧 _Placeholder — add each game as it releases. Link the download to its release._

| Game | Status | 
|------|:------:|
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released |
| _Game Name_ | ✅ Released | 
| _Game Name_ | ✅ Released | 



<!-- copy a row per game:
| Your Game | ✅ Released | [Download](../../releases) |
Status key: ✅ Released · 🧪 Testing · 🔜 Planned -->

**Status:** ✅ Released &nbsp;·&nbsp; 🧪 Testing &nbsp;·&nbsp; 🔜 Planned

---

## 📥 Install

1. **Download** the mod for your game from the [Releases](../../releases) page.
2. **Unzip** it.
3. **Copy everything** into your game's folder — the one with the game's `.exe`.
   *(Steam: right-click the game → Manage → Browse local files.)*
4. **Done.** The ASI loader is already included, so the mod loads automatically when the game starts.

> 💡 If nothing happens in-game, run the game **as Administrator** once, or make sure you copied the files
> next to the **right** `.exe` (some games have a launcher exe in a different folder).

---

## 🕹️ Set up head-tracking (OpenTrack)

These mods receive head pose over **UDP** from [OpenTrack](https://github.com/opentrack/opentrack).

1. Install **OpenTrack** and set up your tracker (webcam, IR, phone app, etc.).
2. In OpenTrack, set **Output** to **`UDP over network`**.
3. Set the destination to **`127.0.0.1`**, port **`4242`**.
4. Hit **Start** in OpenTrack, then launch your game.

---

## 🥽 Play in VR — Osiris VR Viewer

Want to play these mods in a headset? **[Osiris VR Viewer](https://github.com/BerZerker96/Osiris-Vr-Viewer/tree/main)**
has **built-in support** for these mods — it brings the head-tracked game into VR so you can look around
naturally in 3D.

👉 Grab it here: **[Osiris VR Viewer](https://github.com/BerZerker96/Osiris-Vr-Viewer/tree/main)**

---

## ⚙️ Configure

Each mod includes a **`HeadTracking.ini`** next to the game's `.exe`. Open it in any text editor to tweak:

| Setting | What it does |
|---|---|
| `UDPPort` | Must match OpenTrack's port (default **4242**) |
| Sensitivity / multipliers | How far the view moves per head movement |
| Limits | Maximum look angle / lean distance |
| Invert options | Flip an axis if it feels backwards |
| Static FOV *(where supported)* | Pin or widen the field of view |

> 🎮 **In-game hotkeys** (typical): toggle tracking on/off, and **recenter** to your current head position.
> The exact keys are listed in each mod's own README.

---

## 🎯 Tips

- Always **recenter** while looking straight ahead for the best feel.
- Start with **low sensitivity** and work up — a little head movement goes a long way.
- If an axis feels reversed, flip the matching **invert** option in the INI.

---

## ⚠️ Please read

- **Single-player / offline only.** Do **not** use these on anti-cheat or multiplayer games — you can get banned.
- Mods are provided **as-is** for personal, private use.

---

## 🙏 Credits

- **[Loop](https://github.com/itsloopyo?tab=repositories)** — the head-tracking **framework** these mods are built on. 🔥
- **[OpenTrack](https://github.com/opentrack/opentrack)** — the head-tracking app + the **UDP** method used to send head pose.
- **[Osiris VR Viewer](https://github.com/BerZerker96/Osiris-Vr-Viewer/tree/main)** — VR viewer app with **built-in support** for these mods. 🥽
- **Ultimate ASI Loader** — the **ASI loader** that loads the mods into the game.

---

<p align="center">
  <sub>Made with ❤️ for the head-tracking community · Enjoy, and fly safe ✈️</sub>
</p>
