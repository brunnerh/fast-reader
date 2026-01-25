# Fast Reader

A [speed reading][1] application that displays text one word at a time, focusing
on a central anchor letter to reduce eye movement and improve reading speed.

[Live Application][app]

## Features

- **Anchor letter positioning**: Displays words centered on their middle letter
  (highlighted)
- **Playback controls**: Play, Pause, and Reset buttons
- **Adjustable speed**: WPM control via input field and slider
- **Variable timing**: Longer words and punctuation introduce slight pauses
- **Progress tracking**: Large slider shows current position, allows seeking
- **Word jumping**: Click any word in the text display to jump to that position
- **Dark/Light theme**: Automatically adapts to system color preference using
  CSS variables

## Usage

1. Open `src/index.html`/[application][app]
2. Enter or paste your text in the text panel
3. Click "Start" to begin playback
4. Adjust words per minute (WPM) using the input field or slider

You can also click any word in the text display to jump to that position or use
the progress slider to navigate through the text.

## Technical Details

- Vibe coded hot garbage
- Pure HTML/CSS/JavaScript (no dependencies)
- Single-file application
- CSS variables with `prefers-color-scheme` for theming
- Anchor letter positioning based on measured letter widths
- Automatic scrolling to current word in text display

[app]: https://brunnerh.github.io/fast-reader/
[1]: https://en.wikipedia.org/wiki/Speed_reading
