<p align="center">
  <img src="https://raw.githubusercontent.com/Cry199/discordia-releases/main/icon.png" alt="Discordia" width="96" height="96">
</p>

<h1 align="center">Discordia</h1>

<p align="center">
  Share your screen and your PC's sound with friends, straight from PC to PC (P2P).<br>
  No server, no account.
</p>

<p align="center">
  <a href="README.pt-BR.md">🇧🇷 Leia em português</a>
</p>

<p align="center">
  <a href="https://github.com/Cry199/discordia-releases/releases/latest/download/Discordia-Setup.exe"><b>⬇️ Download Discordia for Windows</b></a><br>
  <sub>Windows 10/11, 64-bit · <a href="https://github.com/Cry199/discordia-releases/releases">All versions and release notes</a></sub>
</p>

---

## Getting started

1. **Download and run** `Discordia-Setup.exe`. It installs in a few seconds, no questions asked.
2. **Windows SmartScreen** may show "Windows protected your PC". The installer is not code-signed, so this is expected: click **More info** → **Run anyway**.
3. **Type your name** and click **Create new room**.
4. **Send the room link** (`discordia://sala/...`) or the room code to your friends. The link is fixed: the same room works again next time, and it stays under "Your rooms".
5. **Your friend opens the link** (or pastes the code and clicks **Join**) and you're in. Click **Share screen** to start streaming.

Friend doesn't have Discordia yet? Use **Copy download link**: it always points to the newest version.

## Features

- 🖥️ **Quality you choose:** 720p or 1080p, from 30 up to 144 fps.
- 🎮 **Native capture for games:** captures through the graphics card, made for games running at high fps.
- 🔊 **PC sound without Discord:** stream your whole PC's sound while leaving out the apps you pick (Discord is left out by default, so nobody hears the voice call twice), or send the sound of a single application only.
- 🪟 **Overlay over full-screen games:** see your friends' screens on top of your game, with adjustable size, opacity, layout and corner.
- 👥 **Several people sharing at once.**
- ⏸️ **You're in control:** pause someone's video (saves bandwidth), set the volume per person (remembered), and use the global shortcuts **Ctrl+Alt+M** (mute everyone) and **Ctrl+Alt+O** (toggle the overlay), which work inside games.
- 📌 **Tray and startup:** keep Discordia running next to the clock while you play; optionally start it with Windows (off by default).
- 🔄 **Automatic updates,** with a "What's new" window after each update.
- 🌎 **Languages:** Portuguese, English and Spanish.
- 🪶 **Lightweight:** while streaming, you don't see your own screen unless you click "View my screen", which saves GPU.

## Privacy and security

- **Direct, encrypted connection.** Video and sound travel straight between the PCs over WebRTC, which is always encrypted.
- **Public relays only introduce the PCs.** Discordia uses public Nostr relays so the computers can find each other. They don't see your screen or sound and can't read the connection setup: the room code works as the password for that exchange.
- **Nothing is stored on a server.** There is no Discordia server and no account.
- **Anyone with the room link can join.** Share it only with people you trust; if needed, create a new room.
- **No microphone, no camera.** Discordia never uses them. Keep using your usual voice chat.

## Requirements and limitations

- Windows 10 or 11, 64-bit.
- Because the connection is direct, it may fail on some networks, such as carrier-grade NAT (CGNAT, common on mobile internet and some ISPs) or strict corporate firewalls.
- In games using "exclusive" full screen, Windows doesn't allow anything on top: use "borderless window" mode to see the overlay.

## FAQ

**Does it update by itself?**
Yes. Discordia downloads new versions in the background and offers to restart and update. Afterwards it shows what changed.

**Where does it go when I close it?**
If you're in a room, clicking the X asks whether to close the app or keep it next to the clock (system tray), still in the room and sharing. You can change this in the settings (the gear next to your name).

**How do I uninstall it?**
Windows Settings → **Apps** → **Installed apps** (or "Add or remove programs"), find **Discordia** and click **Uninstall**.

---

<p align="center">
  Made by <a href="https://github.com/Cry199">Cry199</a> · Found a bug? <a href="https://github.com/Cry199/discordia-releases/issues">Open an issue</a>
</p>
