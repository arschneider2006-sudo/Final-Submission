# Final-Submission
DIG2500 Checkpoint 4
```markdown
# 👽 Cosmic Collector

## Project Overview

**Cosmic Collector** is a space-themed memory matching game built with **HTML, CSS, and JavaScript**. Players help an alien complete its mission by matching pairs of hidden space-themed cards while avoiding Human cards hidden in the deck. Every Human card revealed counts as a sighting, and after two sightings the mission fails.

The project demonstrates responsive web design, JavaScript event handling, DOM manipulation, CSS animations, and interactive game logic.

---

## Features

- Space-themed memory matching game
- 8 matching pairs of cards
- 2 hidden Human cards that act as obstacles
- Randomized card placement every game
- Match counter
- Move counter
- Human sighting tracker
- Win and lose conditions
- Restart Mission button
- Responsive layout for desktop, tablet, and mobile devices
- Animated card flip effects

---

## How to Play

1. Click two cards to flip them over.
2. Matching cards stay face-up.
3. Non-matching cards flip back over.
4. Human cards do **not** have a matching pair.
5. Each Human card revealed counts as one sighting.
6. After two sightings, the mission fails.
7. Match all eight pairs before receiving two sightings to complete the mission.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## File Structure

```

CosmicCollector/
│
├── index.html      # Main webpage
├── CC.css          # Styling and responsive layout
├── CC.js           # Game logic
└── README.md       # Project documentation

```

---

## Game Logic

The game creates an array containing:

- 8 matching pairs (16 cards)
- 2 Human cards

The array is shuffled before the game board is generated. JavaScript keeps track of:

- Player moves
- Successful matches
- Human sightings
- Win and loss conditions

Cards are dynamically created using JavaScript and displayed with CSS flip animations.

---

## Responsive Design

The game adjusts to different screen sizes using CSS media queries by:

- Reducing card size on smaller screens
- Changing the number of grid columns
- Adjusting spacing between cards
- Maintaining readable text and controls

---

## Future Improvements

Potential future features include:

- Sound effects and background music
- Difficulty settings
- Timer mode
- High score tracking
- Additional space-themed card sets
- Animated victory and defeat screens

---

## Credits

Created as a course project demonstrating responsive web design and JavaScript interactivity.

### Font

- Orbitron (Google Fonts)

### Graphics

- Unicode emoji icons supported by modern web browsers.
```
