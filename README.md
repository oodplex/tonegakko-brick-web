# TONEGAKKO — An Island of Sound (`0.45.1` Web)

Play **Tonegakko `0.45.1` Risograph Edition** directly in your browser — an island of musical creatures where you wake them up, mix their rhythms and moods, and discover 32 hidden styles to invite 14 new friends ashore. Includes a plain-language 6-step interactive guide, a 3-page How to Play manual, in-world comic speech bubbles, an interactive Goal Book, all 5 Risograph Print Editions, real C99 synth engine, and 14 starter sounds compiled into a single WebAssembly bundle.

**Play live:** https://oodplex.github.io/tonegakko-brick-web/

![14 Tactile 3D-to-Riso Sonari 360-degree turntable](sonari-turntable.gif)

## What's New in `0.45.1`
- **Plain-Language 6-Step Welcome Guide:** Walks total newcomers through what Tonegakko is, how progression works, and how to use every core tool in everyday English — wake a creature & press Play, add drums to invite a new friend ashore, drag a creature to change its tune & pitch, open **SOUND** to shape a voice, open **KEYS** to play along live, and open **BOOK** to pin goals (with 1-tap `SKIP` and `REPLAY GUIDE`).
- **3-Page `HOW TO PLAY` Guide (`MENU → HOW TO PLAY`):** Opens directly to a 6-card plain-English overview (*What is This?*, *Wake & Sleep*, *How to Progress*, *New Friends*, *Your Goal Book*, *Make It Yours*), alongside plain-language **Controls**, **Keyboard**, and a 1-tap **Replay Guide** button.
- **In-World Comic Speech Bubbles & Live Discovery Meter:** Cut-paper speech bubbles for both the welcome guide and live creature suggestions, plus a live top progress bar (`NEW FRIEND COMING!` / `DISCOVERING A STYLE!`) and celebratory arrival postcards.
- **Interactive Goal Book & Pinned Goal Card:** Direct `BOOK N/32` dock button with clickable **`GOALS` | `SKY MAP` | `FRIENDS`** tabs, plain-English live requirement chips (*green = ready, yellow = try next*), `UNLOCKS <NAME>` tags, `PIN GOAL` to track recipes at the top of the Island, and `HEAR AGAIN` for discovered styles.
- **Native-Feeling Phone Portrait Layout:** Edge-to-edge upright frame with a large readable Companion Strip above a clean 3×2 touch dock (`KEYS`, `BOOK`, `SOUND`, `TEMPO / FX`, `ACTIONS`, `MENU`) and tap-to-pick value sheets.

## Controls

### Touch & Mouse (Inside the Frame)
- **Tap** a creature to pick it; tap again to wake it up or put it to sleep
- **Double-tap** a creature (or tap **SOUND**) to adjust its Mood, Level, Voice, and Echo
- **Drag** a creature left/right for a new tune and up/down for pitch; tap or drag knobs, steps, mixer reeds, and FX directly
- **Tap** `KEYS` to play live notes (every key fits the island's scale!), `BOOK N/32` for Goals/Sky Map/Friends, `TEMPO / FX`, `ACTIONS`, or `MENU`
- **Right-click** anywhere on the canvas to go back or close an open panel

### Desktop Keyboard
- **`Space`** / **`Enter`**: Play / Pause
- **`↑ ↓ ← →`**: Move between creatures and controls
- **`Shift + ↑ ↓ ← →`**: Change tune, pitch, knobs, and steps
- **`D F G H J K L ;`**: Play live scale notes (hold **`'`** for higher notes)
- **`[` / `]`**: Switch editor pages
- **`Tab`** / **`S`**: Actions menu
- **`Esc`**: Back / Close panel
- **`⌘Z` / `Ctrl+Z`** and **`⇧⌘Z` / `Ctrl+Y`**: Undo / Redo

### Gamepad & Saves
- **Gamepad:** Any USB or Bluetooth controller works automatically via the browser Gamepad API
- **Saves:** Islands, Guide progress, pinned Goals, Book discoveries, and Print Edition persist automatically in browser storage (IndexedDB)
