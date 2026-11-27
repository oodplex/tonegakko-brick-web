# TONEGAKKO — An Island of Sound (`0.45.0` Web)

Play **Tonegakko `0.45.0` Risograph Edition** directly in your browser — an island-gathering musical game with a structured 5-chapter story tutorial, in-world comic speech bubbles, an interactive Field Book with pinnable rumour quests, live stirring arrival meters, all 5 Risograph Print Editions, real C99 synth engine, and 14 starter sounds compiled into a single WebAssembly bundle.

**Play live:** https://oodplex.github.io/tonegakko-brick-web/

![14 Tactile 3D-to-Riso Sonari 360-degree turntable](sonari-turntable.gif)

## What's New in `0.45.0`
- **5-Chapter Story Tutorial ("The First Evening"):** Guided, non-modal chapters that teach waking Sonari, triggering the `HEARTH` discovery & welcoming `WORMLE`, raising tide & mood for `TIDECALL`, playing live scale notes for `HUMALONG`, and opening the Field Book to track rumours — with pulsing beacons, 1-tap `SKIP`, and `REPLAY TUTORIAL` in `MENU`.
- **In-World Comic Speech Bubbles:** Cut-paper Risograph speech bubbles with directional tails for both Story Tutorial narration and live Sonari calls.
- **Live Stirring Progress Meter & Celebration Postcard:** Watch the arrival progress bar fill as you satisfy a rumour's conditions, then greet new visitors with a live bouncing 2× portrait postcard (`OPEN BOOK` / `AWESOME!`).
- **Game-First Island Dock & Interactive Field Book:** Direct `BOOK N/32` dock button with unread indicator, clickable `TIMELINE | SKY MAP | CAST` tabs, tappable rows/stars/cast, `BRINGS <SONARI>` badges, live requirement checkmark chips, `PIN QUEST` to show a live Quest Card on the Island, and `REPLAY` for saved memories.
- **Upright Phone Companion Strip:** Edge-to-edge portrait frame with a high-legibility live Companion Strip (active Story prompt or pinned Quest card) above a clean 3×2 touch dock and tap-to-pick value sheets.

## Controls

### Mouse & Touch (Inside the Frame)
- **Click / Tap** Sonari on the island to select & wake/rest
- **Double-click / Double-tap** a Sonari (or tap **MEET**) to open its Close-Up pages (`MOOD`, `LEVEL`, `VOICE`, `ECHO`)
- **Drag** a Sonari left/right for phrase and up/down for pitch; drag knobs, parameter rails, STEPS notes, MIXER reeds, and FX cards directly
- **Tap** discrete knobs (`WANDER`, `SPACE`, `TONE`, `EDITION`, `MOOD`, `VOICE`, `SPECIES`) to open the **Value Sheet** picker
- **Tap** `KEYS` for the live on-canvas scale ribbon, `BOOK N/32` for Timeline/Sky Map/Cast & pinnable Quests, `VALUES` / `DOORS`, `ACTIONS`, `MENU`, or `EDITION`
- **Right-click** anywhere on the canvas to go Back / close overlays

### Desktop Keyboard
- **`Space`** / **`Enter`**: Play / Stop
- **`↑ ↓ ← →`**: Move cursor / select Sonari
- **`Shift + ↑ ↓ ← →`** (or **`X + ↑ ↓ ← →`**): Edit phrase, pitch, knobs, and steps
- **`D F G H J K L ;`**: Play scale notes live (hold **`2`** for upper octave)
- **`[` / `]`** (or **`Q` / `W`**): Previous / Next page
- **`Tab`** (or **`S`**): Actions panel (hold for Fold-Out Map)
- **`Esc`** (or **`Z`**): Back / Close overlay
- **`⌘Z` / `Ctrl+Z`** and **`⇧⌘Z` / `Ctrl+Y`**: Undo / Redo

### Gamepad & Saves
- **Gamepad:** Any USB or Bluetooth controller works automatically via the browser Gamepad API
- **Saves:** Islands, Story progress, pinned Quest, Book memories, and Print Edition persist automatically in browser storage (IndexedDB)
