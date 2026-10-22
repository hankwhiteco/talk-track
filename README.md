# Talk Track

A prototype of a portfolio you are talked through. The speaker sits beside or over the work, and the work changes on cue as they talk. On phones it uses Stories gestures. A contact-sheet index sits below the player.

**This is a prototype with placeholder content.** The projects, images, script and contact details are stand-ins.

Live: https://hankwhiteco.github.io/talk-track/

## Getting around

- **Phone:** tap the right of the work to go to the next beat, tap the left third to go back, and hold to pause. Swipe sideways for the next project and swipe down for the index.
- **Desktop:** click the right or left half of the work, or use the arrow keys. Shift+arrows change project. Scroll down for the index.
- **The interactive piece (Sphere Studio):** it behaves like a picture until you tap "Try it". "Back to the talk" or Done hands it back.

## Link tokens

Add tokens after `#`, joined with dots, or use them as `?` parameters.

| Token | What it does |
| --- | --- |
| `#column` (default), `#over` | Desktop layout: speaker in a column, or cut out over the work |
| `#debug` | Shows which gesture registered, plus the live piece's state |
| `#inpage` | Runs the interactive piece in the page instead of its own frame |
| `#rig`, or press `` ` `` | Opens the tools panel |
| `#A`, `#B` | Presets. A is the defaults. B is keep talking, slower cues, chunk captions and manual advance |

Variant tokens:
- `skip-cut`, `skip-keep`, `skip-browse`
- `pace-normal`, `pace-slow`
- `caps-word`, `caps-line`, `caps-chunk`
- `adv-auto`, `adv-off`
- `live-manual`, `live-auto`

Examples:
- `https://hankwhiteco.github.io/talk-track/#over.skip-keep`
- `https://hankwhiteco.github.io/talk-track/?layout=over&skip=keep&debug`

## Test runs

Each visit keeps an anonymous run on your own device: what you tapped, where you stopped, and which variant you saw. Nothing is sent anywhere. At the end, on the contact card, **Copy my test run** copies it so you can paste it into a message.
