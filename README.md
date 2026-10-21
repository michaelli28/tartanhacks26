# ECHO

A sci-fi game built for [Tartanhacks 2026](https://tartanhacks.com/), winner for the AppLovin category. You play **Inmate 734-C**, sentenced to a "temporal recursion tether": a ghost clone that replays your movements from two seconds in the past. Use the ghost to escape the prison facility, one room at a time.

![ECHO thumbnail](echo_thumbnail.png)

## Play

You can open the game directly in a browser, or run it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Controls

| Key | Action |
|-----|--------|
| ← / → | Move |
| ↑ | Jump |
| 1 / 2 / 3 | Switch ghost mode (once unlocked) |
| S | Teleport to the ghost (ANCHOR mode) |

On mobile, an on-screen joystick and buttons appear automatically.

## Ghost modes

- **BOUNCE** – land on the ghost to launch upward.
- **SUPER-LIGHT** – the ghost lights up dark areas.
- **ANCHOR** – the ghost becomes a solid platform you can stand on or teleport to.

Modes unlock as you progress through the levels.
