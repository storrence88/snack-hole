# Snack Hole

A 3D hole game that runs in the browser. Slide a hole around a floor covered in stuff. Anything smaller than the hole falls in. Eat enough and the hole grows, so you can swallow bigger and bigger things, ending with each level's boss.

## Controls

- **Phone or tablet:** drag anywhere on the screen.
- **Computer:** move the mouse and the hole follows it. You can also use the arrow keys or WASD.

- **Pause:** the button in the corner, or Esc / P.

## How to play

- Each level has a timer. When it runs out (or the floor is empty) you get 1 to 3 stars based on how much of the level you ate. One star unlocks the next level.
- Levels cycle through four themes: Bakery, Fruit Market, Toy Room and City Block. Each has a giant boss item; an arrow at the screen edge points to it.
- From level 2 a rival hole competes for the food, and from level 5 there are two. Get bigger than a rival and you can swallow it. Star goals are lower when rivals are around.
- Power-ups appear now and then: magnet (pulls nearby items in), speed boost, and +15 seconds.
- Eat quickly in a row to build a combo.
- Progress (unlocked levels, stars, best scores) is saved in your browser.

## How it's built

The whole game is one `index.html` file. It uses [three.js](https://threejs.org/) 0.160.0 from jsDelivr for rendering, plus a small custom physics loop for stacking and falling. There's no build step, so any static host can serve it (GitHub Pages, Vercel, Netlify).

To run it locally, serve the folder with any static server, for example `npx serve .`, and open the printed URL.
