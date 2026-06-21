# Valdenmoor

A text-based, turn-based RPG built in Python as a learning project, following *Python Crash Course* (3rd Edition) by Eric Matthes. Every chapter adds exactly one new mechanic. Nothing is rebuilt — it only grows forward.

---

## Files

### `game.py` — Moorvran
The main game. Follows Oswin Voss, Junior Mage of An Caille Airgid (the Silver Veil), sent to clear Dún Eagla — an old fortress the Brehons believe is a routine tomb clearance. It is not.

### `brehon.py` — The Brehon Records System
A parallel data management tool representing the administrative records of Lucht na Breithiúnais (the Brehons) — the ancient hereditary jurists of Moorvran. Grows alongside game.py, one feature per chapter.

---

## How to Run

Open either file in Thonny and press **Run**. No dependencies. No installation. Pure Python.

---

## Current State

| File | Chapter | Mechanic |
|---|---|---|
| game.py | Ch. 3 complete | Character sheet + spell list |
| brehon.py | Ch. 4 in progress | Contract list generator |

---

## Chapter Build Log

| Chapter | Concept | game.py | brehon.py |
|---|---|---|---|
| Ch. 1 | Getting Started | File created ✅ | — |
| Ch. 2 | Variables & Data Types | Voss character sheet ✅ | — |
| Ch. 3 | Introducing Lists | Spell list ✅ | — |
| Ch. 4 | Working with Lists | Combat rounds (for loops) | Contract list generator |
| Ch. 5 | If Statements | Hit/miss logic | Contract danger rating |
| Ch. 6 | Dictionaries | Inventory & enemy stat blocks | Enemy stat blocks |
| Ch. 7 | User Input & While Loops | First playable floor — Sera appears | Interactive contract board |
| Ch. 8 | Functions | Combat and healing as reusable blocks | Reusable generator functions |
| Ch. 9 | Classes | Enemy and player as proper objects | Contract and Rider as objects |
| Ch. 10 | Files & Exceptions | Save system (save.json) | Persistent ledger |
| Ch. 11 | Testing | Bug-proofing | Full system validation |
| Ch. 15 | Generating Data | Eric report visualiser | Eric report charts |
| Ch. 16 | Downloading Data | Real data processing | Real data in ledger |
| Ch. 17 | Working with APIs | API data ingestion | API-fed contract board |
| Ch. 18–20 | Django | Moorvran companion site | — |

---

## Version History

Archived on GitHub after each chapter as `ch[n]_game.py` and `ch[n]_brehon.py`.

---

## The World

Moorvran — named for the great crow, *mór bran*. A kingdom where Celtic traditions survived and flourished into the middle ages. No conquest came. What grew here grew from the land itself.

**Key factions:**
- **An Caille Airgid** — The Silver Veil. A druidic order that exists to preserve itself.
- **Lucht na Breithiúnais** — The Brehons. Ancient hereditary jurists. Issue *erics* — prices assigned to problems.
- **An Comhairle Mór** — The Great Council. Governing by inertia. Nobody is steering.
- **The Fianna** — An ancient free warrior tradition. Effectively extinct.
