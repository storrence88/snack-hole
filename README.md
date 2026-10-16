# Snack Hole

A 3D hole game that runs in the browser. Slide a hole around a wooden floor covered in snacks. Anything smaller than the hole falls in. Eat enough and the hole grows, so you can swallow cupcakes, burgers, layer cakes and a giant donut.

## Controls

- **Phone or tablet:** drag anywhere on the screen.
- **Computer:** move the mouse and the hole follows it. You can also use the arrow keys or WASD.

Clear 80% of the snacks to finish a level. Each new level has a bigger board.

## How it's built

The whole game is one `index.html` file. It uses [three.js](https://threejs.org/) 0.160.0 from jsDelivr for rendering, plus a small custom physics loop for stacking and falling. There's no build step, so any static host can serve it (GitHub Pages, Vercel, Netlify).

To run it locally, serve the folder with any static server, for example `npx serve .`, and open the printed URL.
