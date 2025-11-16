# SpikeCaf-Bot
## 🔍 Overview

Valorant Stats Companion allows users to:

- Look up their **current rank**
- View **recent match history**
- Display **performance summaries** (K/D, ACS, win rate, etc.)
- Optionally integrate with **Discord** so users can pull their stats with simple commands

The goal is to make it easy for players to quickly check and share their stats with friends or teammates.

---

## ⚙️ How It Works

1. The user provides their **Riot ID** (e.g. `Name#TAG`).
2. The app sends a request to a **Valorant stats API** (using Riot-approved or third-party endpoints).
3. The API returns data such as:
   - Current rank
   - Recent matches
   - Basic performance metrics
4. The app formats this data and:
   - Displays it in a web/CLI interface, **and/or**
   - Sends an embedded message via a **Discord bot** command.

> **Note:** This project does not attempt to circumvent Riot’s rules or access restricted data. It only uses endpoints allowed by Riot’s policies (or third-party providers that comply with them).

---

## 🔐 Privacy & Data Use

- The app only uses **publicly accessible game data** tied to a user’s Riot ID.
- No passwords, tokens, or sensitive personal data are collected.
- No gameplay is affected in any way – this app is read-only and purely informational.
- Any stored data (if enabled) is used only to:
  - Cache stats for faster responses
  - Improve user experience (e.g., remember linked accounts)

If requested, users can ask to have their cached data removed.
