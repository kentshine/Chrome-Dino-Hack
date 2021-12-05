# Chrome-Dino-Hack 🦖

Most of us have seen the dreaded “No Internet” error message on Google Chrome. You can actually turn this screen into a fun, dino-themed endless runner game and, even better, hack it to where your dinosaur becomes invincible. Here’s how.

* To hack the game, you’ll need to be on the “No Internet” screen, so go ahead and enter `chrome://dino` in the address bar. Once there, right-click anywhere on the screen and select “Inspect” from the menu that appears.
* This opens Chrome DevTools, which appears to the right of the browser window. In DevTools, select the “Console” tab.
* Alternatively, you can press Ctrl+Shift+I and jump straight to the “Console” tab in Chrome DevTools.
* Once in the “Console” tab, paste the following command and then press the “Enter” key:

```
var original = Runner.prototype.gameOver
```
* Next, enter this command: 
 ```
Runner.prototype.gameOver = function (){}
```
* On the next line, f (){} will appear after pressing the “Enter” key.

***Enjoy Guddie Buddiesss ^^***
