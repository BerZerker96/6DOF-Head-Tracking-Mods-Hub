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

A hub where I release my **6DOF head-tracking mods and the NEW true Stereo3D per game mods** — they let you lean, peek, and look around in-game
using your real head movement full ( X, Y , Z axis) positional tracking and full (Yaw , Pitch , Roll ) rotational tracking. Each mod is built on the head-tracking **framework by [Loop](https://github.com/itsloopyo?tab=repositories)**, and provides Stereo3D built into one mod based on x-axis offsets ,
and ships **ready to go**: the mod is already packed with an **ASI loader**, so there's nothing extra to install.

---

<img width="800" height="450" alt="Pi7_GIF_CMP" src="https://github.com/user-attachments/assets/b42b73cd-b3b3-469c-bbf6-3e9d4186393c" />


https://www.youtube.com/watch?v=_X3-89w9E14



⚠️ ⚠️ ⚠️⚠️ ⚠️ ⚠️
> [!TIP]
> 🔧 If `dinput8.dll` doesn't work and tracking dosent start that means the injector failed to hook to game , rename it to one of these. Try them in order — top ones work in almost any game.

| Try | Rename `dinput8.dll` to | Works with |
| :-- | :-- | :-- |
| 1️⃣ | `version.dll` · `winmm.dll` | 🌐 Almost any game |
| 2️⃣ | `dxgi.dll` · `d3d11.dll` · `d3d12.dll` | 🎮 DX10/11/12 games |
| 3️⃣ | `d3d9.dll` | 🕹️ Older DX9 games |
| 4️⃣ | `xinput1_3.dll` · `wininet.dll` · `winhttp.dll` · `bink2w64.dll` | ❓ Only sometimes |

> [!IMPORTANT]
> 📄 **No `HeadTracking.log`?** The DLL isn't loading — move to the next name. Make sure it's next to the game's `.exe` and no other mod (ReShade, ENB) is using that same name.
> 
⚠️ ⚠️ ⚠️⚠️ ⚠️ ⚠️


## 🎮 Supported Games

| Game | Type | Download |
|------|:------:|:------:|
| _Assassins Creed Origins_ | 🥽 Stereo3D / 🎯 6DOF  | [⬇️ Download](../../releases/tag/1) |
| _Assassins Creed Unity_ | 🥽 Stereo3D / 🎯 6DOF  | [⬇️ Download](../../releases/tag/ACUnity) |
| _Assassins Creed Syndicate_ | 🥽 Stereo3D / 🎯 6DOF  | [⬇️ Download](../../releases/tag/s1) |
| _Alan Wake 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/AlanWake2) |
| _Alan Wake Remastered_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/AlanWakeRemastered) |
| _Batman Arkham Knight_ | 🥽 Stereo3D / 🎯 6DOF | [⬇️ Download](../../releases/tag/BatmanArkhamKnight) |
| _Crimson Desert_ | 🎯 3DOF / WIP | [⬇️ Download](../../releases/tag/CrimsonDesert) |
| _DeusEx-Human Revolution_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DeusEx-HumanRevolution) |
| _DeusEx-Mankind Divided_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DeusEx-MankindDivided) |
| _Dragon Age Inquisition_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DragonAgeInquisition) |
| _Guardians Of The Galaxy_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/GuardiansOfTheGalaxy) |
| _NieR Automata_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/NieRAutomata) |
| _NieR Replicant_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/NieRReplicant) |
| _Ni no Kuni_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/NinoKuni) |
| _Persona 4 Golden_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Persona4Golden) |
| _Shadow Of The Tomb Raider_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/ShadowOfTheTombRaider) |
| _The Witcher 3_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/TheWitcher3) |
| _Yakuza Like A Dragon_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/YakuzaLikeADragon) |
| _Batman Arkham City_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/BatmanArkhamCity) |
| _Batman Arkham Asylum_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/BatmanAA) |
| _Persona 5 Royal_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Persona5Royal) |
| _Metal Gear Rising_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/MetalGearRising) |
| _Control_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Control) |
| _Dragon Age Origins_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DragonAgeOrigins) |
| _Dragon Age 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DragonAge2) |
| _The Witcher 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/TheWitcher2) |
| _Batman Arkham Origins_ | 🥽 Stereo3D / 🎯 6DOF  | [⬇️ Download](../../releases/tag/BatmanArkhamOrigins) |
| _Rise Of The Tomb Raider_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/RiseOfTheTombRaider) |
| _Dead Space Remake_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/DeadSpaceRemake) |
| _Red Dead Redemption 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/RDR2) |
| _Crysis 3_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Crysis3) |
| _GTAIV Complete Edition_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/GTAIVComplete) |
| _Yakuza 6_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Yakuza6) |
| _Metal Gear Solid V_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/MGSV) |
| _Tomb Raider 2013_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/TombRaider2013) |
| _Yakuza Kiwami 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/YakuzaKiwami2) |
| _Resident Evil 5_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/RE5) |
| _Resident Evil 6_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/RE6) |
| _Quantum Break_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/QuantumBreak) |
| _GTA V Enhanced_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/GTAV-Enhanced) |
| _Yakuza 0_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/Yakuza0) |
| _Yakuza Kiwami_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/YakuzaKiwami) |
| _Trails in the Sky 1_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/TrailsFC) |
| _Assassins Creed 2_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/AC2) |
| _Assassins Creed Brotherhood_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/ACB) |
| _Assassins Creed Revelations_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/ACR) |
| _Granblue Fantasy_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/GranblueFantasy) |
| _Ratchet and Clank rift apart_ | 🎯 6DOF / | [⬇️ Download](../../releases/tag/RiftApart) |

want more check **Loop's Hub for more mods  by [Loop's Mods](https://github.com/itsloopyo/itsloopyo)**,

<!-- copy a row per game:
| Your Game | ✅ Released - 🎯 6DOF / | [⬇️ Download](../../releases/tag/YourTag) |
Status key: ✅ Released · 🧪 Testing · 🔜 Planned
The Download link must point at that game's own release TAG. Tags are NOT always the game name -
e.g. AC Origins = tag/1, AC Syndicate = tag/s1, GTA IV = tag/GTAIVComplete. Check the Releases page. -->


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
has **Built-In Support** for these mods no need for Opentrack — it brings the head-tracked game into VR so you can look around
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

## 🙏 Credits

- **[Loop](https://github.com/itsloopyo?tab=repositories)** — the head-tracking **framework** these mods are built on. 🔥
- **[OpenTrack](https://github.com/opentrack/opentrack)** — the head-tracking app + the **UDP** method used to send head pose.
- **Ultimate ASI Loader** — the **ASI loader** that loads the mods into the game.

---
