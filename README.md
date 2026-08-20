# Sine Tone Composer

Free-time and tonal composition on a chromatic C2–F7 staff. Durations are literal
press lengths (millisecond precision). Fully offline after first load; no
dependencies, no build step — the entire application is one HTML file.

**Live app:** `https://<your-github-username>.github.io/<this-repo-name>/`

## Features
- Atonal (free time) and Tonal (key signature, time signature, tempo) modes
- Voices: pure sine, synthesized piano, sampled piano (import your own samples)
- Input: on-screen keys, MIDI keyboards (e.g. Roland A-49), and microphone
  pitch detection with beat quantization
- Beat Stencil Overlay: exact note-value entry, dotted values, rhythm overlays,
  harmony layering, chord building
- Editing: resize, grab, group select/move/duplicate, mute, color rules,
  precise ms timing, loops, bar map with multi-bar reorder/delete
- Desktop menu-bar interface, two themes, adjustable staff spacing
- Installable as a PWA: works offline, MIDI and mic supported (Chrome/Edge)

## Data & privacy
Everything stays on your device. Compositions live in the browser's
localStorage per device; use **File → Export all / Copy all** to move them
between devices. Imported piano samples live in IndexedDB per device.
No network calls, no analytics, no accounts.

## Updating the app
Replace `index.html` with a new version and commit. The service worker is
network-first, so open tabs pick up the new version on the next load.

## Credits
Sampled piano is designed for the **Salamander Grand Piano** by Alexander Holm
(Yamaha C5, CC BY 3.0) — https://creativecommons.org/licenses/by/3.0/

© 2026 Sine Tone Composer
