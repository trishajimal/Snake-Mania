# Snake Mania

A classic arcade-style Snake game built with HTML, CSS, and JavaScript. The player controls a growing snake, collects food, avoids walls, and tries to beat the high score stored in the browser.

## Features

- Smooth keyboard controls with arrow keys
- Score tracking and persistent high score using `localStorage`
- Increasing difficulty as the snake grows
- Game-over detection and restart flow
- Retro neon/arcade-inspired UI

## How to Play

1. Open `index.html` in your browser.
2. Use the arrow keys to move the snake.
3. Eat the food to increase your score.
4. Avoid crashing into the walls or your own body.
5. Press any key after a game over to restart.

## Controls

- Up: ArrowUp
- Down: ArrowDown
- Left: ArrowLeft
- Right: ArrowRight

## Project Structure

- `index.html` — page structure and game container
- `style.css` — layout, board styling, snake, food, and UI design
- `script.js` — game logic, movement, collision detection, score updates, and sound handling

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Local browser storage for high score persistence

## Running the Game

Because this is a front-end web project, you can run it by simply opening `index.html` in a browser.

If you want to serve it locally instead, you can also use a simple static server such as:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## License

This project is open for learning and personal use.
