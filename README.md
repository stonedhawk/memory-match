# Memory Match

![Screenshot](screenshot.png)

A browser-based memory card matching game with a dark retro aesthetic, flip animations, and three difficulty levels.

## How to Play

1. Click any card to flip it and reveal the emoji
2. Click a second card to find its match
3. If both cards show the same emoji, they stay face-up
4. If they don't match, they flip back after a short delay
5. Match all pairs as quickly and in as few moves as possible

## Features

- **3 difficulty levels** - Easy (4x4), Medium (4x5), Hard (6x6)
- **Smooth 3D flip animations** - CSS rotateY transform at 400ms
- **Move counter and timer** - track your performance per game
- **Star rating** - earn 1 to 3 stars based on move efficiency
- **Win screen with confetti** - celebrate every completed board
- **Responsive layout** - cards resize for any screen size

## How to Run

Just open `index.html` in any modern browser. No build step, no dependencies to install.

## Tech Stack

- React 18 (via CDN)
- Babel Standalone (for JSX in browser)
- Vanilla CSS (animations, 3D transforms, responsive grid)
- Single HTML file, zero build tooling

## Live Demo

[https://stonedhawk.github.io/memory-match](https://stonedhawk.github.io/memory-match)

## License

MIT - see [LICENSE](LICENSE)
