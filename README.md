# Octopi

**Turn a plain-English task into a finished spreadsheet — on your own Mac.**

[**Download for macOS →**](https://useoctopi.com) &nbsp;·&nbsp; [useoctopi.com](https://useoctopi.com)

![macOS — Apple Silicon & Intel](https://img.shields.io/badge/macOS-Apple%20Silicon%20%26%20Intel-111111)
![Latest release](https://img.shields.io/github/v/release/gpignol/octopi-releases?label=latest&color=6b4fbb)
![Price — free](https://img.shields.io/badge/price-free-2e9e5b)
![Local-first](https://img.shields.io/badge/local--first-runs%20on%20your%20Mac-4a7fd6)

Octopi is a free, local-first desktop app for macOS. You describe a research or data-entry
task in ordinary language; Octopi browses the web, calls your data providers, and fills your
spreadsheet or CRM — with a clickable source on every cell. It runs on your own machine with a
local AI model, so your data never leaves your computer.

> **About the name:** Octopi (from **[useoctopi.com](https://useoctopi.com)**) is a native Mac
> research app. It is **not** OctoPrint / "OctoPi" (the Raspberry Pi 3D-printing image), and it
> is not a web service or a browser extension.

## What it does

- **Plain-English → spreadsheet.** Describe the task the way you'd describe it to an assistant;
  Octopi compiles it into a workflow and does the work, writing back only the columns your task
  asked for.
- **Real web research.** It drives an actual browser to find companies, people, and facts, and
  records where every answer came from.
- **Fills your CRM.** Create and update records in **Salesforce** and **HubSpot** with
  duplicate-safe, verified writes.
- **A source on every cell.** Results are auditable — click through to see exactly where a value
  came from.
- **Local & private.** A local AI model (via [Ollama](https://ollama.com)) runs on your Mac.
  Your spreadsheets, logins, and browsing stay on your computer.
- **Bring your own keys (optional).** Add API keys for providers like Claude, GPT, Gemini, or
  Perplexity when you want them for enrichment — entirely optional.

## Download & install

1. Get Octopi from **[useoctopi.com](https://useoctopi.com)** — a single, signed `.dmg`.
2. Open the DMG and drag **Octopi** into your Applications folder.
3. Launch it. Because the app is signed with an Apple Developer ID and notarized by Apple,
   there's no Gatekeeper warning.
4. On first run, **Set Everything Up** installs the local AI model and browser for you — a few
   clicks, no terminal required.

## Requirements

- macOS on **Apple Silicon or Intel**.
- A few GB of free disk space for the local AI model.
- An internet connection for web research. (Your data still stays on your machine — only the
  pages Octopi researches are fetched.)

## Privacy

Local-first by design. The AI model runs on your Mac, and your spreadsheets, credentials, and
browsing never leave it. Only **anonymous, opt-in** diagnostics are ever sent, and you can turn
them off any time in **Settings ▸ Privacy**. See the privacy policy on
[useoctopi.com](https://useoctopi.com).

## Updates (what this repository is)

This repo is Octopi's **update feed** — no source code lives here. It hosts:

- **`appcast.json`** — the version manifest the app checks: latest version, the signed DMG URL,
  and its SHA-256.
- **Release artifacts** — the signed `.dmg` for each version, under
  [**Releases**](https://github.com/gpignol/octopi-releases/releases).

Octopi checks here automatically (throttled to once a day), and can update itself in place. Every
download is SHA-256-verified against the manifest and checked by macOS Gatekeeper before it runs.

## Latest release

**v0.17.1** — pre-launch audit & hardening (bug fixes, no new features).
See [all releases →](https://github.com/gpignol/octopi-releases/releases).

## Credits

Octopi runs local models with [Ollama](https://ollama.com) (MIT-licensed). Everything stays on
your machine.

---

© Octopi · [useoctopi.com](https://useoctopi.com)
