# Strumprint Studio

Play your guitar and watch it become notes, tab and the circle of fifths, live in your browser.

Strumprint Studio is a free, open-source web app. Plug your guitar into an audio interface (direct cable or mic), click **Start listening**, and it shows:

- **The note you're playing**, with a tuner
- **Live tab** on the easiest string and fret, with tuning and capo settings
- **The circle of fifths**: your likely key, the chords that fit, and the path your notes take
- **A cymatic title**: sand particles that form the name, shake into fingerprint patterns and follow your notes

## Run it

1. Download or clone this repo.
2. Open `index.html` in Chrome.
3. Click **Start listening** and allow access to your input. Pick your interface and Input 1 or 2.

If Chrome blocks the input when the file is opened directly, serve the folder locally:

```
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

New here? Read [instructions.html](instructions.html) for a step-by-step guide, or [about.html](about.html) for the idea behind it.

No interface handy? Click **Try a demo**, or drop in a WAV recorded in Audacity.

## Status

v0.7: single notes, live tab, key guessing on the circle of fifths. Chords, sheet music and exports are next. See [docs/build-steps.md](docs/build-steps.md).

## Contributing

Chord shapes and chord recordings are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

- Code: public domain under the Unlicense (see `LICENSE`)
- Chord shapes and recordings: CC0 (no rights reserved)
- Third-party fonts and credits: see `NOTICE`
