# Memory Match

A browser-based memory match card game with a modern dark aesthetic. Single HTML file, zero dependencies (React + Babel via CDN).

## What we're building

- Classic memory match / concentration card game
- Emoji pairs as card faces
- CSS 3D flip animations (~400ms rotateY)
- Three difficulty levels:
  - Easy: 4x4 grid (8 pairs)
  - Medium: 4x5 grid (10 pairs)
  - Hard: 6x6 grid (18 pairs)
- Move counter: increments per pair attempt
- Timer: starts on first flip, stops on win
- Win screen with star rating (1-3 stars based on efficiency)
- Confetti/particle effect on win (CSS only)
- High score / best time tracking (localStorage)

## Tech

- React 18 via CDN (unpkg)
- Babel standalone via CDN (for JSX transpilation)
- Vanilla CSS (no external stylesheets)
- All code in a single index.html file

## Visual Design

- Dark background: #0f0f23
- Accent color: #6366f1 (indigo)
- Card backs: rounded rectangles with subtle gradient/pattern
- Card fronts: emoji on dark card face
- Matched cards: subtle green glow border
- Hover: slight lift/scale on unflipped cards

## Constraints

- No em dashes in comments or text
- Single HTML file with all CSS and JS inline
- Must work in Chrome, Firefox, Safari
- Mobile-friendly: cards resize based on viewport width
- Board centered on page

## Card Grid Sizes

- Easy (4x4): 16 cards, 8 pairs
- Medium (4x5): 20 cards, 10 pairs
- Hard (6x6): 36 cards, 18 pairs

## Star Rating

- 3 stars: under (pairs * 1.5) moves
- 2 stars: under (pairs * 2) moves
- 1 star: anything above
