# CueReader

CueReader is a mobile-friendly script cue reader by Simon Anthony (acting@torty.org.uk).

The browser edition can open TXT, PDF, DOCX and older DOC files. PDF and DOCX text is extracted locally in the browser. Legacy binary DOC extraction is best-effort; if a particular DOC cannot be read reliably, save it as DOCX or PDF.

## Controls

- Tap/click a cue to make it active.
- Up/Down arrows move through the script without speaking.
- Return/Enter plays the next computer-spoken part.
- Redo replays the previous computer-spoken cue.
- `(CONT'D)`, `(CONT’D)` and `(CONTINUED)` are treated as the same character.
- Text in brackets and ellipses are not spoken; `(pause)` and `(beat)` pause for half a second.

The web application entry point is `index.html`.
