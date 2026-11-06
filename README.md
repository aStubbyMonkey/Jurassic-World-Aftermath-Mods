# Jurassic World Aftermath — Mods

Mods for **Jurassic World Aftermath** on Meta Quest.

> **[Download the latest Mod Menu](../../releases/latest)** · **[Setup guide](#setup)**

---

## The mods

| Mod | What it does | Latest |
|---|---|---|
| **Mod Menu** | A Physical, In-Game Mod Menu attached to your wrist with Clickable Buttons and a large library of mods. | [Releases](../../releases?q=modmenu) |

More on the way. Each mod is released and versioned separately — see
[Releases](#releases) below.

---

## Mod Menu

A Physical Mod Menu Panel made from the Buttons, Textures, and Font from the game.
Press **MENU** on your left controller to open it, point with your right hand and pull the trigger to click.

---

## Setup

Ten minutes, once. You never repeat steps 1 and 2.

1. **Developer Mode on** — Meta Horizon phone app → your headset → Headset
   Settings → Developer Mode. Reboot, plug into a PC, and accept
   *"Allow USB debugging?"* **inside the headset**.
2. **Patch the game with [QuestPatcher](https://github.com/Lauriethefish/QuestPatcher/releases)**
   — pick Jurassic World Aftermath, click Patch, then launch the game once.
   ⚠️ **Patching reinstalls the game, which deletes your save.** QuestPatcher has
   a backup option; use it if you care about your progress.
3. **Run `INSTALL.bat`** from the release zip. It finds ADB, or downloads the
   official copy from Google if you do not have one. Nothing else to set up.
4. **Press MENU** on your left controller in game.

**[→ Full illustrated guide, with troubleshooting](#)**
*(replace this link with your published tutorial page)*

### Requirements

- A Meta Quest headset
- Jurassic World Aftermath, on a copy you own
- A Windows PC, for the install only
- A USB cable that carries data, not just power.

---

## Releases

Every mod is tagged with its own prefix, so versions never collide:

```
modmenu-v1.15.0          Mod Menu
speedchanger-v1.2.0      Random Speed Changer
```

Each mod also keeps a one-line version file at the repo root — `modmenu_latest.txt`
and so on. **The mods read these themselves**, which is how the Mod Menu can tell
you an update exists without you ever plugging into a PC. The filename is what
keeps each mod reading only its own version.

Do not hand-edit those files. `RELEASE.bat` generates the zip and the version
file together from the version compiled into the mod, so they cannot drift apart
and tell players two different things.

---

## `[Beta]` means

Any Mods that are tagged with "[Beta]" simply means that the mod is unstable, inconsistent, or doesn't fully work as intended.

These mods are fine to use, but aren't fully fleshed out or finished.

---

## Notes

- These mods does not share or pirate any files of Jurassic World Aftermath
- These mods are not affiliated with **Coatsink**, **Atari**, or **Universal Studios**
- These mods do not change the code of Jurassic World Aftermath, it only layers the code on top.
- These mods are unstable and can and will crash your game. Download at your own risk.
