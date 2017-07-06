## CoffeeScript Bootstrap

[![Greenkeeper badge](https://badges.greenkeeper.io/ezpn/coffeescript-bootstrap.svg)](https://greenkeeper.io/)

Basic template for easy and pleasant CoffeeScript (CS) development. It includes the
following
scripts:
- CS files watch (new, edit, remove)
- CS to JS compilation
- JS to CS mapping

### Requirements
- node.js
- npm (Node Package Manager) - should be already included with node.js

### Installation
`npm i`

I also recommend installing coffee-script package globally:

`npm i -g coffee-script`

### Development
`npm start`

### Build
`npm run build`


### How to check if it works properly
After `npm start` js directory should be created in root project dir.
Main file - index.html - should log into console "Main file loaded", which
means that coffee was properly converted to js.

**Where to go from here?**

Feel free to play with environment, add more coffee and html files. Add more
automation scripts to package.json.
