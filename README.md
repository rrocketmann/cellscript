# LuaPetri

A browser-based petri dish where microbes are programmed in Lua. Each microbe runs its own copy of your Lua "brain" every frame and can sense its surroundings (food, family, strangers) and act (move, eat, attack, reproduce).

## Play online

Visit [rrocketmann.github.io/luapetri](https://rrocketmann.github.io/luapetri).

## Run locally

Serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Quick start

- Edit the Lua code in the right panel.
- Existing microbes keep the code they were born with.
- Click anywhere on the petri dish to spawn a new microbe with the current code.
- The page follows your system's light/dark preference.

The Lua runtime is [Fengari](https://fengari.io/) (Lua 5.3 in JavaScript).
