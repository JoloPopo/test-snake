# Snake Game by Joty

A Python implementation of the classic Snake game with AI capabilities. Developed by Joty from iCF Cambodia.

## Game Features

The project includes several AI implementations for the Snake game:

1. **Hamilton Solver**: Achieves near-perfect performance (avg length: 63.93)
2. **Greedy Solver**: Good performance with dynamic path finding (avg length: 60.15)
3. **DQN Solver**: Experimental deep learning approach (avg length: 24.44)

## Performance Metrics

The AI performance is evaluated using:
- **Average Length**: How long the snake grows (maximum: 64)
- **Average Steps**: Number of moves made

## Installation

Requirements: Python 3.6+ with Tkinter

```bash
pip install -r requirements.txt
python run.py [-h]
```

## Running Tests

```bash
python -m pytest
```

## Controls

- **W/A/S/D**: Control snake direction
- **Space**: Pause/Resume game
- **R**: Restart game
- **ESC**: Exit game

## License

See the [LICENSE](./LICENSE) file for license rights and limitations.

---
Developed with ❤️ by Joty | iCF Cambodia
