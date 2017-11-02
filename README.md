# Base Race! (Work in Progress)

Base Race is an entry in the 2017 GitHubGameOff game jam.  Instead of building it and releasing it at the end of the jam, I have decided to build it publicly and accept pull requests/features during development.

The basis of the game: You are an aspiring mascot hoping to compete in the top Baseball Mascot Races!  Race against other mascots in 9 themed parks to be the top mascot!

## Game Settings + Development Setup

This is using Phaser.io + Webpack.  The game is an isometric racing game with multiple stages.  Game Design documents will be found in the `doc/design/` directory (when written).

To start developing, run `npm install`  to install the dependencies, then `npm start` to run the webpack-dev-server and start dynamic compiling/packing.  Any time src/index.js is changed, a new bundle will be created.
