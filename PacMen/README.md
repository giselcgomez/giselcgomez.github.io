# H1 The PacMen Exercise

These files create a PacMen with the click of a button and each of them will move in the browser window at their own pace in a random way.

##*Important highlights:*##

**index.html** - produces a PacMan on the click of a button by calling several functions on a pacmen.js and styles.css files.
**pacmen.js** - works with the following functions
1. makePac() : this is the Factory function that makes a PacMan. It returns position, velocity and newimg values
2. update() : this functions updates the PacMan image with a "setTimeout" and also uses the "checkCollisions" functions to restrict the pacMan image movement inside the document
3. makeOne() : this functions add a new PacMan image to the document

**styles.css** - add styles to buttons

##*Added items:*##
- Stop Bottom refreshes the browser to stop PacMen movements
- Change direction to the PacMan (the implementation of this code is incomplete)

---
##*Where to go from here:*##

- Implement correctly the "direction" variable should change the PacMan direction as it collides with the limits
- Implement an array of PacMan so each of them change direction on its own
