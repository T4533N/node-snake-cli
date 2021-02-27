# 🐍 Snek.js

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![node-snake-cli on NPM](https://img.shields.io/npm/v/node-snake-cli.svg?color=green&label=node-snake-cli)](https://www.npmjs.com/package/node-snake-cli)

A command line Snake Game written in JavaScript (Node.js).

## Instructions

Use the arrow keys (`↑`, `↓`, `←`, `→`) or `W` `A` `S` `D` to navigate the snake up, down, left, or right. Eat the red dot to gain points. If the snake collides with the wall or its own tail, it's game over. Press `ENTER` to restart, and `Q`, `ESCAPE` or `CTRL` + `C` to quit the game.

## Installation

### Run without installing

The easiest way to play the game is to just run it in the terminal without installing anything!

```bash
npx node-snake-cli
```

### Clone from repository

```bash
git clone https://github.com/taniarascia/node-snake-cli
cd

# install and run via npm or yarn
npm i && npm run play
```

### npm module

Add the `node-snake-cli` module.

```bash
npm i node-snake-cli
```

Create the game.

```js
// index.js
const { UserInterface, Game } = require('node-snake-cli')
const game = new Game(new UserInterface())

// Begin game
game.start()
```

Run the game.

```bash
node index.js
```

## Author

- [Taseen Tanvir](https://www.tanvir.io)

## License

This project is open source and available under the [MIT License](LICENSE).
