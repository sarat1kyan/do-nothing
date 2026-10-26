# DO NOTHING

A browser game with exactly one objective: **do absolutely nothing.**

Move the mouse, click, tap, swipe, scroll, or press a key, and you lose. The longer you resist, the higher your score — and the more desperate, insulting, and unhinged the game becomes trying to make you crack.

Live: **https://do-damn-nothing.netlify.app**

## Run it

Open `index.html` in any modern browser. That's the whole thing — one self-contained file.

- No backend, no build step, no npm, no dependencies, no API keys.
- Works offline. Nothing is fetched.

## How to lose

- **Desktop:** move the mouse, click, scroll, or type.
- **Mobile:** touch the screen, swipe, or scroll. To survive, put the phone down and walk away.

A short countdown after you press START lets you take your hands off everything, so the click that begins a run never ends it.

## Features

- Robust input state machine (`MENU → COUNTDOWN → PLAYING → FAILED → RESULTS`) using trusted events and movement deltas — no false failures from the start action, browser noise, resize, or synthetic events.
- 6 escalating phases, from polite to existential crisis.
- 150+ original lines, 19 special events (fake CAPTCHA, disappointed mom, job interview, court trial, final boss, and more), floating fake buttons, pop-up achievements, and reverse-psychology baits.
- Contextual failure verdicts and ranks based on how you failed, how long you lasted, and your history.
- Persistent personal best (`localStorage`), Web Share with clipboard fallback.
- Synthesized Web Audio (toggle in the corner), full dark theme, responsive mobile/desktop, `prefers-reduced-motion` support.
- Background tabs pause the clock — no inflated survival time.

## Deploy (Netlify)

Static site. Publish directory is the repo root; `index.html` is served automatically. `netlify.toml` is included. No build command.

## License

MIT — do nothing with it, or everything.
