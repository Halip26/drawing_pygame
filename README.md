# Pygame Drawing App

A simple and interactive drawing application built using Pygame. Draw on a canvas with various colors, adjust brush sizes, and use an eraser tool—all with an intuitive toolbar interface.

## Features

- **Drawing Canvas**: A large white canvas (600x400 pixels) for creating your artwork
- **Color Selection**: Draw in multiple colors:
  - Black
  - Red
  - Yellow
  - Blue
  - Green
- **Brush Size Control**: Adjust brush size from 1 to 10 pixels
  - Decrease button (-) to reduce brush size
  - Increase button (+) to enlarge brush size
- **Eraser Tool**: Switch between pen and eraser modes
- **Clear Canvas**: Clear all drawings with a single click
- **Responsive Toolbar**: Easy-to-use toolbar with all controls at the top of the window

## Requirements

- Python 3.x
- Pygame

## Installation

1. Clone or download this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the application with:

```bash
python main.py
```

### Controls

| Tool/Button            | Function                                               |
| ---------------------- | ------------------------------------------------------ |
| **Pen**                | Switch to drawing mode                                 |
| **Ers** (Eraser)       | Switch to eraser mode                                  |
| **-** (Minus)          | Decrease brush size                                    |
| **+** (Plus)           | Increase brush size                                    |
| **Clear**              | Clear the entire canvas                                |
| **Color Circles**      | Select drawing color (Black, Red, Yellow, Blue, Green) |
| **Mouse Click & Drag** | Draw on the canvas                                     |

### Tips

- Use the color buttons to select your desired drawing color before drawing
- Adjust brush size for different drawing styles
- Use the eraser to remove parts of your drawing
- Click "Clear" to start fresh with a blank canvas

## File Structure

- `main.py` - Main application code
- `requirements.txt` - Python dependencies
- `README.md` - This file
- `LICENSE` - License information

## How It Works

The application uses:

- **Pygame Surface**: Creates a canvas surface for drawing and a toolbar surface for UI controls
- **Mouse Events**: Tracks mouse button press, release, and motion to enable drawing
- **Collision Detection**: Uses rectangle and circle collision to detect button clicks
- **Event Loop**: Continuously updates the display and processes user input

## Window Specifications

- **Window Size**: 600x400 pixels
- **Toolbar Height**: 50 pixels
- **Canvas Area**: 600x350 pixels- **Window Size**: 600x400 pixels
- **Toolbar Height**: 50 pixels
- **Canvas Area**: 600x350 pixels
- **Canvas Area**: 600x350 pixels
