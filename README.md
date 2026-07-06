# 🪄 Varik Emberlain - D&D Sorcerer Tracker

A lightweight, fully interactive, single-file HTML5 web application designed to track character resources, spell slots, and racial/class traits for **Varik Emberlain**, a Level 5 Wild Magic Sorcerer (and adaptable to any Level 5 D&D character).

## 🚀 LIVE DEMO

### 🔗 ACCESS THE LIVE TRACKER HERE:>

## 👉 [VIEW THE TRACKER LIVE](https://sc137.github.io/character-status-tracker/varik_emberlain_tracker.html) 👈

## ✨ Features

* **❤️ Hit Points Panel:** Dynamic current/max health tracking, dedicated Temporary HP buffer, customizable healing/damage calculators, and an interactive progress bar.
* **✨ Sorcery Points & Metamagic:** Complete tracking of Sorcery Points with quick-spend hotkeys for Metamagic features (*Empowered, Quickened, Subtle, Heightened Spells*).
* **🔮 Spell Slots Grid:** Granular tracking for Level 1, 2, and 3 Spell Slots with interactive visual slot arrays (dots) that turn on/off as you cast or recharge.
* **🌌 Innate Magic & Features:**
  * **Tides of Chaos:** Spend to gain advantage; recharges instantly on a manual trigger or a Wild Magic Surge check (which automatically rolls a d20 surge check in the log!).
  * **Hellish Rebuke:** Tracks racial/innate castings per long rest; casts with automated 3d10 damage roll calculation.
  * **Darkness:** Tracks innate 1/Long Rest casting with duration/concentration helper logs.
* **🎲 Integrated Dice Roller:** Quick-roll system for standard polyhedral dice (`d4` through `d20`) with custom quantity multipliers and static modifiers.
* **📝 Persistent Activity Log:** A running console displaying timestamps for all game mechanics, damage applications, rest functions, and dice rolls.
* **💾 LocalStorage Persistence:** Automatically saves all character states, custom trackers, and activity logs to your browser. You can safely refresh, close, or crash your browser without losing campaign progress!
* **🛌 Long Rest & Hard Reset:** Global master controls to fully restore your character attributes to baseline defaults or trigger a full 8-hour resting recovery cycle.

## 🛠️ How to Host on GitHub Pages

Hosting this interactive sheet is incredibly easy since it is built entirely inside a single standalone HTML file.

1. **Create your Repository:** Create a new repository on GitHub (e.g., `varik-tracker`).
2. **Upload the Files:** Push or upload the `index.html` file to your `main` or `master` branch.
3. **Enable GitHub Pages:**
   * Go to your repository's **Settings** tab.
   * Select **Pages** from the left-hand sidebar menu.
   * Under the **Build and deployment** section, set the **Source** to `Deploy from a branch`.
   * Select your main branch (e.g., `/root` on `main`) and click **Save**.
4. **Link the URL:** Within a minute, GitHub will give you a live deployment link. Copy that link and paste it into the **LIVE DEMO** section at the top of this `README.md` file!

## ⚙️ Technical Details

* **Tailwind CSS CDN:** Provides responsive utility-first layout styling and custom dark-theme colors out of the box.
* **Zero-Dependency JavaScript:** Built with standard web APIs to ensure fast, safe, and robust client-side execution.
* **Local Storage Sandbox:** Isolated variables protect data and prevent overlaps with other browser-stored character pages.
