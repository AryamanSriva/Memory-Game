# Memory Match Game

A React-based memory card matching game where players test their memory by finding pairs of matching flower cards within a limited number of turns.


## Features

- Interactive card matching gameplay
- Limited turns (15) to find all matches
- Win/lose conditions with appropriate messages
- Responsive design for various screen sizes
- Animated card flipping effects
- Clean, modern UI

## Technologies Used

- React.js
- CSS3
- JavaScript

## Project Structure

```
memory-match-game/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── App.js          # Main application component
│   ├── App.css         # Main styles
│   ├── index.js        # Entry point
│   ├── index.css       # Base styles
│   ├── Components/     # React components
│   │   ├── Card.js     # Individual card component
│   │   ├── Grid.js     # Card grid layout component
│   │   └── Header.js   # Game header with turns and controls
│   └── Images/         # Game images
│       ├── Flower1.jpg
│       ├── Flower2.jpg
│       └── ...
└── README.md
```

## How to Play

1. Start a new game by clicking the "New Game" button
2. Click on cards to flip them over
3. Try to find all matching pairs of flowers
4. You have 15 turns to find all matches
5. Win by matching all cards within 15 turns

## Game Logic

- Cards are randomly shuffled at the start of each game
- The player can flip two cards at a time
- If the cards match, they remain face up
- If the cards don't match, they flip back face down
- Each pair of flips counts as one turn
- The game ends when all matches are found or the player runs out of turns

## Customization

You can easily customize the game by:

- Adding more card images to increase difficulty
- Changing the turn limit
- Modifying the CSS variables in `App.css` to change the color scheme

## Responsive Design

The game is fully responsive and works well on:
- Desktop computers
- Tablets
- Mobile devices

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- Flower images sourced from Pexels
- Inspired by classic memory matching card games
