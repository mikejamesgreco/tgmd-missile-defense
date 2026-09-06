# TGMD Mafia Defender

**The Greco Mafia Defender**

A lightweight, local-first browser arcade game where three neighborhood
wiseguys defend a bank, a dive bar, and a casino from incoming Molotov
cocktails.

Each bottle carries a face on its label. TGMD includes its own cartoon
wiseguy label, or you can load local images and turn friends, foes, or
favorite faces into the incoming bottle labels.

TGMD is built as a **Single-File Local Application (SFLA)**. The game
runs directly in a modern browser with no application server, package
manager, framework, installation process, or third-party runtime
dependencies.

> **Protect the neighborhood. Save the bank, the bar, and the casino.**

![TGMD Mafia Defender screenshot](screenshot.jpeg)

## Play TGMD

**[▶ Play TGMD Mafia Defender in your browser](https://mikejamesgreco.github.io/tgmd-mafia-defender/)**

No installation is required. The GitHub Pages version runs TGMD directly
in your browser, just like opening the standalone
`tgmd-mafia-defender.html` file locally.

---

## Features

- Three defended neighborhood locations: bank, dive bar, and casino
- A little wiseguy defender stationed at each surviving location
- Click or tap the sky to fire a short machine-gun burst from the nearest defender
- Incoming Molotov cocktails with animated flames and bottle labels
- Built-in cartoon wiseguy bottle label when no image is loaded
- Load multiple local images and use them as randomized bottle labels
- Interactive crop tool for selecting the face or image area to use
- Bullet tracers, sparks, fireballs, debris, and screen shake
- Increasing waves and difficulty
- Limited ammunition each wave
- Local high score
- Mouse and touch controls
- Browser-generated sound effects
- Single-file HTML application
- No frameworks or third-party runtime dependencies

---

## Getting Started

You can either use the **[hosted TGMD game](https://mikejamesgreco.github.io/tgmd-mafia-defender/)**
or download/clone the repository and open:

```text
tgmd-mafia-defender.html
```

in a modern web browser.

Choose **Load Faces** to select one or more pictures from your computer.
Click a loaded image to crop and frame the face or object you want on the
Molotov labels, then start the game.

Click or tap anywhere in the sky. The nearest surviving neighborhood
defender turns toward that point and fires a short burst. Hit the incoming
bottles before they reach the bank, dive bar, or casino.

No installation, web server, or build process is required.

---

## Local-First

TGMD is designed to keep the game simple and your images local.

Images selected in TGMD are processed in your browser and are not
uploaded to a TGMD server. They are used for the game session and remain
under your control.

TGMD follows the same **Single-File Local Application (SFLA)**
philosophy as the other Greco browser applications: use browser-native
capabilities where practical and avoid unnecessary runtime infrastructure.

---

## Repository Structure

```text
tgmd-mafia-defender/
│
├── index.html                    # GitHub Pages launcher
├── tgmd-mafia-defender.html      # Standalone TGMD game
├── screenshot.jpeg               # Project screenshot
├── README.md
└── LICENSE
```

---

## Browser Support

TGMD is designed for modern desktop browsers. Mouse and touch controls
are supported, although exact browser behavior for generated audio can
vary.

---

## Privacy

Your selected images remain local to your browser and are used only by
the game. TGMD does not require an account, backend service, or image
upload.

---

## License

See the repository `LICENSE` file for details.

---

## Author

**Michael J. Greco**

TGMD Mafia Defender — **The Greco Mafia Defender**

© mikejamesgreco.me LLC. All rights reserved.
