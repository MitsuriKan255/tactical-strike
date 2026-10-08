# Tactical Strike

> HTML5 tactical shooter · version-driven development · browser-based releases

![Status](https://img.shields.io/badge/status-in%20development-fbbf24)
![Version](https://img.shields.io/badge/version-v1.0%20prototype-38bdf8)
![Technology](https://img.shields.io/badge/technology-HTML5%20%7C%20CSS3%20%7C%20JavaScript-0f172a)
![License](https://img.shields.io/badge/license-MIT-34d399)

Tactical Strike is an independent top-down tactical shooter for the browser. Choose a faction, enter a compact arena, fight enemy bots, manage ammunition, buy weapons, and win rounds before the timer expires.

> This is an independent project inspired by the tactical shooter genre. It does not use code, assets, or trademarks from other games.

## Play the current build

- [![Play V1.0 Prototype](https://img.shields.io/badge/PLAY-V1.0%20PROTOTYPE-38bdf8?style=for-the-badge)](./version/tactical_strike_V1.0%20-Release.html)
- [![Download releases](https://img.shields.io/badge/DOWNLOAD-GitHub%20Releases-34d399?style=for-the-badge)](https://github.com/MitNak25/tactical-strike/releases)
- [![Latest release](https://img.shields.io/badge/LATEST-Release-fbbf24?style=for-the-badge)](https://github.com/MitNak25/tactical-strike/releases/latest)

> GitHub does not execute HTML directly in the repository viewer. Download the release ZIP, or run the file locally with a static server.

```bash
python3 -m http.server 8000
```

Then open the file at:

```text
http://localhost:8000/version/tactical_strike_V1.0%20-Release.html
```

## Controls

| Action | Control |
|---|---|
| Move | `W`, `A`, `S`, `D` or arrow keys |
| Aim | Mouse movement |
| Fire | Left mouse button |
| Reload | `R` |
| Open / close buy menu | `B` |
| Close buy menu or return to main menu | `Escape` |
| Choose a faction | Click **Counter-Terrorists** or **Terrorists** |
| Buy a weapon | Open the buy menu and click a weapon |

The game is currently designed for desktop browsers. A mouse and keyboard are recommended.

## Gameplay

- Pick a faction from the lobby.
- Defeat three enemy bots before the round timer reaches zero.
- Use walls and the central crate as cover.
- Keep track of health and ammunition in the bottom HUD.
- Use the buy menu to switch between the AK-47, M4A4, AWP, and Desert Eagle.
- Rounds restart automatically after a win, loss, or timeout.
- The scoreboard tracks Counter-Terrorist and Terrorist round wins.

## Settings

The prototype includes mouse sensitivity, bot difficulty, and volume controls in the settings screen. These controls are part of the interface prototype and are not yet connected to gameplay logic. They are planned for a future gameplay systems update.

## Repository structure

```text
Tactical Strike/
├── version/
│   ├── README.md
│   ├── v1.0.0/
│   │   └── README.md
│   └── tactical_strike_V1.0 -Release.html
├── docs/
│   └── GAMEPLAY_REVIEW.md
├── releases/
│   └── README.md
├── .github/
│   └── workflows/
├── LICENSE
└── README.md
```

## Roadmap

### v1.0 Prototype

Playable menu, faction selection, top-down combat, bots, obstacles, rounds, timer, HUD, ammunition, reloading, weapon selection, kill feed, and synthesized audio.

### v1.1 — Gameplay systems

Connect settings to the game, add credits and real weapon prices, improve collision resolution, add fire-rate balancing, and make the buy zone affect purchasing.

### v1.2 — Content update

Additional arenas, bot behaviors, objectives, sound controls, mobile-friendly input, and a clearer round result screen.

### v2.0 — Tactical Strike

Expanded game modes, persistent statistics, improved accessibility, polished visuals, and a complete release package.

## Releases and versioning

Version folders contain the playable source snapshots. GitHub Releases contain downloadable packages for public builds.

```bash
git add .
git commit -m "release: Tactical Strike v1.0.0"
git tag v1.0.0
git push origin main --tags
```

Use [Semantic Versioning](https://semver.org/) for future releases. Do not modify historical builds after publishing; create a new version folder instead.

## Development

No build tool or dependency installation is required. The game uses native HTML, CSS, Canvas 2D, and the Web Audio API. A local static server is recommended because it behaves more consistently than opening a file directly.

## Contributing

Bug reports and feature ideas are welcome. Please include your browser, operating system, reproduction steps, and the version you tested.

## License

Tactical Strike is released under the **MIT License**. See [`LICENSE`](LICENSE) for the full terms.

<p align="center"><strong>Aim. React. Survive.</strong><br><sub>Tactical Strike — every round counts.</sub></p>
