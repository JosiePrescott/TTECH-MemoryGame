Each card has a front and back, the back is the logo that all the cards share when you begin the game.
When you enter the game, there is a 4x3 grid that uses flex box to accomplish this.
The cards flip when you click on them, they rotate on the Y-axis so you are able to see the front face.
If you have flipped the card, it will log that and run functions on it. One of these is checking if it matches the next card you flip. If this is the case, then those cards will lock into place.
After flipping non-matches, there is a wait time of 1500 so you are able to see the wrong cards.
If you flip non-matching cards, they will flip back over after the wait time. 
The cards will shuffle immediatly when logging into game and on every reload.
When a card is matched, the event listener is removed so you can't click it again unless you reload and restart the game.
