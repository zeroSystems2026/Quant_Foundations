# Scratch Project Alpha: Conditional Logic

* **Initialization:** The 'MarketData' is set to 0 when the green flag is clicked; the Fish switches costume to Fish-a and resets to its initial position.
* **The Loop:** Forever block; wait 1 second, say "Hello!" for 2 seconds, then broadcast 'StartAction' and wait. As the Fish reacts, 'MarketData' increases by 1.
* **Logic Gates:** The Bear broadcasts 'ChangeToFish-b' if 'MarketData' is greater than 3; The Bear broadcasts 'ChangeToFish-a' if 'MarketData' is greater than 5.
* **Execution Engine:** Fish glides to new position upon receiving 'StartAction', plays 'Ocean Wave' sound, and teleports back to its original position; Fish-a switches costume to Fish-b upon receiving 'ChangeToFish-b' broadcast, Fish-b switches back to Fish-a upon receiving 'ChangeToFish-a' broadcast.