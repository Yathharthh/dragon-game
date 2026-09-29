Dragon Game

A House of the Dragon-themed browser game. Claim the seats of Westeros, unlock dragons from the Targaryen family poster as you level up, and ride and breathe fire with each one.

Single HTML file, no build step, no dependencies.

Run it

Open index.html in a browser. That's it.

To serve over HTTP instead:

python -m http.server 8000
# then visit http://localhost:8000
How it works
Dragonstone is home base, opened from the map. It shows the full dragon poster; every unlocked dragon is tappable.
The Eyrie is the first seat to attack. Winterfell, the Iron Islands and Casterly Rock stay locked until the Eyrie falls.
Dragons unlock by level, starting from Shrykos and moving up the poster by size. Locked dragons show "unlocks at level N" when tapped.
Each unlocked dragon's card has Let's fly (ride) and Fire (breathe fire) buttons with a short animation.
File layout
dragon-game/
├── index.html   Game (HTML, CSS and JS in one file, images inlined)
└── README.md    This file
