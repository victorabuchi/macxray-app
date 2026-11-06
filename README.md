<p align="center"><img src="docs/assets/icon-192.webp" width="96" height="96" alt=""></p>

<h1 align="center">MacXray</h1>

<p align="center"><b>Your Mac, from the inside.</b></p>

<p align="center">
  <a href="https://github.com/victorabuchi/macxray-app/releases/latest/download/MacXray.dmg"><b>Download MacXray</b></a> ·
  <a href="https://victorabuchi.github.io/macxray-app/">Website</a> ·
  <a href="https://github.com/victorabuchi/macxray-app/releases">All versions</a>
</p>

MacXray shows what your Mac is doing right now: every app and the processes behind it, the files they change, who they talk to, each core of the chip, the memory, the battery and everything you copy. Live, and in plain English.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/assets/shots/now-dark.webp">
  <img src="docs/assets/shots/now-light.webp" alt="MacXray's Now view: the Mac drawn as an x-ray, each part lit by a live reading">
</picture>

## Install

1. Download [MacXray.dmg](https://github.com/victorabuchi/macxray-app/releases/latest/download/MacXray.dmg).
2. Open it and drag MacXray into Applications.
3. Open MacXray. The first time, macOS asks whether you're sure. Click Open.

MacXray is free. It needs macOS Sequoia 15 or later, on Apple silicon or Intel, and it's signed with a Developer ID and notarized by Apple.

## What it shows

| View | What you see |
| --- | --- |
| Now | Your Mac drawn as an x-ray, each part lit by a live reading, with one sentence that sums it all up |
| Clipboard | Everything you copy, kept in full and in every format, with images exactly as copied, ready to copy again |
| Processes | Every program, the helpers each app splits into, and what each one is |
| Files | Which app is changing which files, sorted into your files, app data, caches, settings and logs |
| Network | Every connection, from the app that opened it to the company on the other end |
| CPU cores | Each core's load second by second, the graphics, and how warm the chip is |
| Memory | What's in use, compressed or cached, and the pressure macOS feels |
| Battery | Charge, health, cycles, the cells inside and the power flowing in and out |
| System log | What macOS is writing in its diary, grouped by who's talking |

## Privacy

Everything stays on your Mac. MacXray has no account, no analytics and no tracking. It saves only your clipboard history, in a file on your Mac, and never reads or saves copies that password managers mark as sensitive. Its only use of the network is asking your DNS server for the names of the servers your apps talk to. The [privacy policy](https://victorabuchi.github.io/macxray-app/privacy/) has the details.

## Help

Something not right? [Open an issue](https://github.com/victorabuchi/macxray-app/issues/new) with what you saw, your Mac's model and its macOS version.

## This repository

It holds MacXray's website, in `docs` (served by GitHub Pages), and its downloads, in [Releases](https://github.com/victorabuchi/macxray-app/releases). MacXray's source code is private.

Apple, Mac, MacBook and macOS are trademarks of Apple Inc. MacXray isn't affiliated with or endorsed by Apple.
