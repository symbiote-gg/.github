<br />

<p align="center">
    <img src="../.github/static/logo.svg" alt="SymbioteGG logo" width="30%" />
</p>

<br />

<p align="center">
  A free desktop app for browsing your own Heroes of the Storm replays.
</p>

<br />

<p align="center">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" alt="License: GPL v3">
    <img src="https://github.com/symbiote-gg/symbiote-app/actions/workflows/qa.yml/badge.svg" alt="QA">
</p>

---

## What is SymbioteGG?

Analyze your Heroes of the Storm replays in depth, by looking at what actually happened in each game: who did the damage, healing and soaking on both teams, which talents everyone picked, and how the match swung over time. Over many games, it shows which heroes and roles you win with, and your overall trending.

Run `SymbioteGG` while you play to get instant feedback on your games. It finds the default replay folder on its own, and every match you finish shows up as soon as the replay is saved, flagged as new, so you can check what went right or wrong before you queue again.

Everything happens **on your machine**. Nothing gets uploaded and there's no account to create.

## Get it

| Platform    | Where                                                                              |
| ----------- | ---------------------------------------------------------------------------------- |
| **Windows** | Installers on each [release](https://github.com/symbiote-gg/symbiote-app/releases) |

## Projects

- **[symbiote-app](https://github.com/symbiote-gg/symbiote-app)** - the desktop app, Tauri + React + TypeScript.
- **[replay-parser](https://github.com/symbiote-gg/replay-parser)** - offline decoder for `.StormReplay` files in Rust, a port of Blizzard's heroprotocol and mpyq.

## Blizzard content

`SymbioteGG` is a fan-made project and is not affiliated with, endorsed by, or officially connected to Blizzard Entertainment or Heroes of the Storm. Hero names, map names, artwork, icons and other game assets are the property of Blizzard Entertainment, and none of the licenses here cover them.

Heroes of the Storm™ ©2014 Blizzard Entertainment, Inc. All rights reserved. Heroes of the Storm is a trademark of Blizzard Entertainment, Inc.

## License

The app is licensed under **[GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html)**, while the parser is **[MIT](https://opensource.org/license/mit)**.
