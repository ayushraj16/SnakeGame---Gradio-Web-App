# SnakeGame---Gradio-Web-App
A modern, interactive implementation of the classic Snake game using Python and Gradio. Play directly in your browser interface, control the snake with on-screen buttons, view stats live, and challenge yourself to beat your high score

## Features

- **Intuitive Controls**: Move the snake using directional arrow buttons or enable auto-move for continuous play.
- **Live HTML Game Board**: The snake, food, and movement are rendered using emoji and dynamic HTML for instant visual feedback.
- **Score and Stats**: View your current score, the snake’s length, and detailed game info in real-time.
- **Auto-Wrap Edges**: Snake wraps around the borders—no more walls!
- **Instant RESET**: Restart the game at any time.
- **One-File Deployment**: All major logic contained in a single Python file.

## Demo

To see a live demo, you must run the app locally as described below.

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/snakegradio.git
   cd snakegradio
   ```

2. **Install dependencies:**
   ```bash
   pip install gradio
   ```

## How to Run

Run the following command in your terminal:

```bash
python snake_game.py
```

By default, this will launch the app on `http://0.0.0.0:7860/`.

- Access the web interface via your browser.
- Use the on-screen START, arrow, and auto-move buttons to control the game.
- Compete against yourself and share your high scores!

## Game Instructions

### Controls:
- **⬆️ UP, ⬇️ DOWN, ⬅️ LEFT, ➡️ RIGHT**: Move the snake in the respective direction.
- **🚀 START GAME**: Begin a new game.
- **🎯 AUTO MOVE**: Continue moving in the current direction.

### Gameplay:
- **Goal**: Eat red apples (🍎) to grow longer.
- **Snake Head**: 🟢
- **Snake Body**: 🟩
- **Empty Space**: ⬛
- **Wrapping**: The snake wraps around at edges.
- **Game Over**: Biting yourself ends the game.

### Scoring
- Gain 10 points for every apple eaten.

## Customization

You can modify game behavior by changing the following parameters in the code:

- `width` and `height`: Board size.
- Initial snake length and starting position.
- Emoji and color themes in the `get_board_html` method.

## Example Screenshots

> Add screenshots here after running the app for visual reference.

## Dependencies

- Python 3.7+
- gradio

## License

MIT License. See `LICENSE` for details.

## Acknowledgments

- Inspired by the original Snake game and modernize for the Gradio web app framework.

## Contributing

Pull requests and issues are welcome! Please open an issue to discuss major changes.

## Author

- [Ayush Raj](https://github.com/ayushraj16)

**Enjoy the nostalgia of Snake, now ready for the web era!**
