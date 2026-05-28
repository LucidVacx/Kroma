# Project 🇰🇭 Kroma

**Standard Khmer typing is SLOW. Kroma fixes it.**

The current standard Khmer keyboard layout is an ergonomic disaster. It forces a rich, multi-layered, three-dimensional language into a linear, 150-year-old QWERTY framework designed for English. Kroma completely throws that old paradigm away. 

Instead of hunting and pecking characters letter-by-letter, Kroma uses a **Direct Syllabic Chording Engine**. You press the entire structural DNA of a Khmer syllable at the exact same time, and the hardware instantly welds it together in perfect orthographic order.

---

## ❌ The Flaws of Standard Khmer Keyboards

*   **The Subscript Bottleneck:** Typing a basic subjoined consonant forces you to hit a dedicated modifier key (`្`) every single time before typing the actual letter. It destroys rhythm and cuts your speed in half.
*   **Insane Keystroke Counts:** Simple syllables routinely require 4 to 7 sequential keystrokes just to render on screen. 
*   **The Shift Key Trap:** High-frequency characters are scattered chaotically across multiple shift layers, forcing violent, fatiguing hand movements just to access basic vowels.
*   **Zero Ergonomics:** Your strongest digits (your thumbs) do absolutely nothing but hit a massive, wasted spacebar, while your pinkies strain to reach critical diacritics.

---

## ⚡ The Kroma Fix

Kroma maps the phonetic architecture of Khmer directly onto human hand anatomy using a split 4×11 ortholinear matrix:

*   **Left Hand:** Fires the Initial Consonants instantly.
*   **Right Hand:** Floods the screen with standalone Vowels and vertically stacked Final Consonants.
*   **Thumbs:** Execute the heavy-lifting Medial Sub-consonants.
*   **Symmetric Diacritic Injectors:** New hardware keys at `(2,3)` and `(9,3)` act as instant electrical gear-shifts. Holding them down flips the thumb row into a high-velocity injector for the essential marks: **Bantoc (`់`)**, **Muusekatoan (`៉`)**, **Triisap (`៊`)**, and **Toandakhāt (`៍`)**.
*   **True Hardware NKRO:** Every switch is isolated with a **1N4148 diode**. Smash 15+ keys for a complex syllable simultaneously—zero ghosting, zero lag.

---

## 🚀 Project Status

*   [x] **Linguistic Modeling** — Corpus parsing and phonetic role extraction.
*   [x] **Layout Optimization** — 84-token master dictionary mapping with zero spatial collisions.
*   [x] **Simulation Testing** — Immediate-mode interactive desktop sandbox testing.
*   [ ] **Hardware Prototyping** — Soldering the diode-isolated matrix grid.
*   [ ] **Bare-Metal Port** — Migrating parsing architecture to ultra-low-latency `no_std` stack memory for microsecond execution.

> **Notice:** Kroma's core compiler, lookup algorithms, and firmware source files are currently closed-source during active R&D. The technical specs and visual matrix data are published exclusively for community layout evaluation.

***
*Designed in Phnom Penh, Cambodia.*
