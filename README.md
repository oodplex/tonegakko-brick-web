# TONEGAKKO — An Island of Sound (`0.45.2` Web)

Play **Tonegakko `0.45.2` Risograph Edition** directly in your browser — an island of musical creatures where you wake them up, mix their rhythms and moods, and discover 32 hidden styles to invite 14 new friends ashore. Features tactile Risograph horizontal slide bars across every sub-menu, an elaborate 8-step interactive tutorial with animated pointers & pulsing target frames, a 3-page How to Play manual, an interactive Goal Book, all 5 Print Editions, real C99 synth engine, and 14 starter sounds compiled into a single WebAssembly bundle.

**Play live:** https://oodplex.github.io/tonegakko-brick-web/

![14 Tactile 3D-to-Riso Sonari 360-degree turntable](sonari-turntable.gif)

## What's New in `0.45.2`
- **Tactile Risograph Slide Bars Across All Sub-Menus:** Every draggable parameter (`MOOD`, `LEVEL`, `ECHO`, `PITCH`, `TEMPO`, `SPACE`, `SWING`, `CUTOFF`, `ENV`, `WOBBLE`, `PATTERN`, `STEPS HARD/HOLD/ROLL`, `FX DETAIL 1/2`, `MIXER`, `MENU VOLUME`, and Island `TEMPO / FX` top cards) now renders as a real horizontal slide bar with a chunky draggable thumb handle — click anywhere on the track to jump or slide smoothly! Discrete controls (`VOICE`, `KEY`, `SCALE`, `WAVE`, `DRIVE`, `WHEN`, `WANDER`, `TONE`) render as distinct `v` Choice Pills that open the tap-to-pick sheet.
- **Polished Console Sub-Menus:** Framed Risograph control cards along the bottom, tinted studio sidebars, mini live sliders in the left Controls column, framed page tabs, and elevated `ACTIONS` & `MENU` sheets.
- **Elaborate 8-Step Guided Tour with Animated Pointers:** Bite-sized steps with multi-line plain-English explanation cards (*Why* + *Do This*) and pulsing highlight frames + bouncing Risograph arrows pointing straight at the exact selectable creature, `PLAY` button, `SOUND` / `TEMPO / FX` / `KEYS` / `BOOK` dock button, `MOOD` slide bar, `TEMPO` slide bar, scale keys, or `PIN GOAL` button — with 1-tap `SKIP GUIDE` and `REPLAY GUIDE`.
- **3-Page `HOW TO PLAY` Manual & Interactive Goal Book:** Plain-English 6-card overview (`MENU → HOW TO PLAY`), clickable **`GOALS` | `SKY MAP` | `FRIENDS`** Book tabs, green/yellow live checklist chips, `UNLOCKS <NAME>` tags, `PIN GOAL`, and `HEAR AGAIN`.
- **Native-Feeling Phone Portrait Layout:** Edge-to-edge upright frame with a large readable Companion Strip above a clean 3×2 touch dock (`KEYS`, `BOOK`, `SOUND`, `TEMPO / FX`, `ACTIONS`, `MENU`).

## Controls

### Touch & Mouse (Inside the Frame)
- **Tap** a creature to pick it; tap again to wake it up or put it to sleep
- **Drag** a creature left/right for a new tune and up/down for pitch
- **Slide** any horizontal slide bar on `SOUND`, `SYNTH`, `ENV`, `WOBBLE`, `PATTERN`, `STEPS`, `FX`, `MIXER`, `GLOBAL`, `TEMPO / FX`, or `MENU` (Volume)
- **Tap** any `v` Choice Pill to pick from a clean grid (`VOICE`, `KEY`, `SCALE`, `WANDER`, `TONE`, `PRINT EDITION`, etc.)
- **Right-click** anywhere on the canvas to go back or close an open panel

### Desktop Keyboard
- **`Space`** / **`Enter`**: Play / Pause · **`↑ ↓ ← →`**: Move · **`Shift + ↑ ↓ ← →`**: Edit
- **`D F G H J K L ;`**: Play live scale notes (hold **`'`** for higher notes)
- **`[` / `]`**: Switch pages · **`Tab`** / **`S`**: Actions · **`Esc`**: Back · **`⌘Z` / `Ctrl+Z`**: Undo

### Gamepad & Saves
- **Gamepad:** Any USB or Bluetooth controller works automatically via the browser Gamepad API
- **Saves:** Islands, Guide progress, pinned Goals, Book discoveries, and Print Edition persist automatically in browser storage (IndexedDB)
