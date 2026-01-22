# Fast Reader

A speed reading application that displays text one word at a time, focusing on a
central anchor letter to reduce eye movement and improve reading speed.

## Features

- **Anchor letter positioning**: Displays words centered on their middle letter
  (red highlighted)
- **Playback controls**: Play, Pause, and Reset buttons
- **Adjustable speed**: WPM control via input field and slider
- **Progress tracking**: Large slider shows current position, allows seeking
- **Word jumping**: Click any word in the text display to jump to that position
- **Dark/Light theme**: Automatically adapts to system color preference using
  CSS variables

## Usage

1. Open `src/index.html` in a web browser
2. Enter or paste your text in the left panel
3. Click "Start" to begin playback mode
4. Use Play, Pause, or Reset to control playback
5. Adjust WPM using the input field or slider
6. Click any word in the text display to jump to that position
7. Use the progress slider to navigate through the text

## Technical Details

- Vibe coded hot garbage
- Pure HTML/CSS/JavaScript (no dependencies)
- Single-file application
- CSS variables with `prefers-color-scheme` for theming
- Anchor letter positioning based on measured letter widths
- Automatic scrolling to current word in text display
