# Contributing to Strumprint Studio

Two kinds of contributions build the community chord library.

## 1. Chord shapes (text)

Add one JSON file per shape in `chords/`, named like `Cmaj7__x32000.json`:

```json
{
  "name": "Cmaj7",
  "frets": ["x", 3, 2, 0, 0, 0],
  "fingers": [0, 3, 2, 0, 0, 0],
  "tuning": "standard",
  "contributor": "your-github-name"
}
```

`frets` run from the low E string to the high e string; `"x"` means the string isn't played. An automatic check will confirm the frets produce the notes of the named chord.

## 2. Chord recordings (audio)

See [recordings/README.md](recordings/README.md) for the recording method.

## Sign-off

By opening a pull request you confirm: **"I made this and release it under CC0."** (code contributions are released under the Unlicense, like the rest of the code). Recordings must be guitar only: no voices and no songs by other artists.
