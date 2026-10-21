<p align="center"><img src="screenshots/banner.png" alt="FlickTune: even aim in every direction" width="100%"></p>

<h3 align="center">
  <a href="https://github.com/kicedz/flicktune-releases/releases/latest">Download FlickTune for Windows</a>
</h3>
<p align="center">Windows 10 / 11 · works with any mouse · updates itself</p>

---

Most players flick a little long in some directions and a little short in others, without knowing it.

FlickTune finds out where. You flick at targets in a 3D room at your real in-game sensitivity, and FlickTune tunes
[RawAccel](https://github.com/RawAccelOfficial/rawaccel) so your aim feels the same in every direction.
Your overall sensitivity stays yours.

<p align="center"><img src="screenshots/results.png" alt="Results: where your flicks land in every direction" width="90%"></p>

## How it works

1. **Tell it your game** and your DPI. The room turns exactly like your game.
2. **Flick.** Short rounds, targets from every angle.
3. **See your aim** in every direction, with your time to hit.
4. **FlickTune tunes RawAccel** in small steps. Every change is saved in History, and you can go back to any point.

<p align="center"><img src="screenshots/arena.png" alt="The 3D flick room" width="90%"></p>

## Questions

**Is it safe with anti-cheat?** FlickTune uses the official, signed RawAccel driver, unchanged. It does not read or touch
any game; it only changes RawAccel's settings, between flicks, inside its own 3D room. Check your game's rules if unsure.

**Does it add acceleration?** No. Your RawAccel curve stays as it is.

**I already have RawAccel.** FlickTune finds it and starts from your current settings.

**I don't have RawAccel.** FlickTune brings it. The first time, it asks to install the RawAccel driver (Windows asks for
admin rights) and you restart once.

**How do I undo everything?** Settings → *Back to where FlickTune started*, or *Stock RawAccel*. Uninstalling FlickTune
keeps RawAccel and its settings; RawAccel's own uninstaller removes the driver.

**Updates?** FlickTune checks this page on startup and offers new versions. You can turn that off in Settings, or turn
on beta versions to get new features a little earlier.

<p align="center">
  <img src="screenshots/problem.png" alt="Start screen" width="32%">
  <img src="screenshots/calib.png" alt="Calibration" width="32%">
  <img src="screenshots/history.png" alt="History" width="32%">
</p>

---

**FlickTune © 2026 Kice Djingov. All rights reserved.**

This repository holds installers and update files only. FlickTune includes the official, unchanged RawAccel runtime
(MIT, © a1xd and contributors), three.js (MIT) and the Barlow fonts (OFL); the notices are installed with the app.
