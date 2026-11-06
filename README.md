# Jurassic World Aftermath — Mods

Mods for **Jurassic World Aftermath** on Meta Quest.

> **[Download the latest Mod Menu](../../releases/latest)** · **[Setup guide](#setup)**

---

## The mods

| Mod | What it does | Latest |
|---|---|---|
| **Mod Menu** | A Physical, In-Game Mod Menu attached to your wrist with Clickable Buttons with a large library of mods | [Releases](../../releases?q=modmenu) |

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

- A Meta Quest headset — built and tested on **Quest 3S**; Quest 2 and 3 should
  work but are untested
- Jurassic World Aftermath, on a copy you own
- A Windows PC, for the install only
- **A USB cable that carries data, not just power.** If your headset charges but
  the PC never sees it, the cable is the problem. This is the single most common
  thing that goes wrong.

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

Wired up and will do something, but not finished. It ships because some of it
works and it is more fun to have it than not.

**Grab Anything** is the honest example. It picks up doors, the raptor, and
anything it has already placed. Most ordinary scenery will not move, because the
game merges hundreds of props into single combined meshes when it is built — for
Quest performance — so the thing you are pointing at often is not a separate
object any more. That decision was made before the game shipped and a mod cannot
fully undo it.

---

## Notes

- These are single player, offline mods. There is no multiplayer in this game.
- Nothing is changed permanently. Everything a mod touches is restored when you
  switch it off or close the game.
- Not made by, endorsed by, or connected to **Coatsink** or **Atari**. Jurassic
  World Aftermath is their game; these are fan mods.
- Use them on a game you own.
