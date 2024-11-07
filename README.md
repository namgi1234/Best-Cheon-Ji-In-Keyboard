# FINDING-BEST-CHEON-JI-IN-KEYBOARD-LAYOUT
Considering the number of types and the distance the fingers move, we found the optimal layout of the Cheonjiin keyboard.
The fitness function is: $$\sum (f_{1} + f_{2})$$

$$f_{1}$$ is the movement distance of the finger. The distance traveled is c1 and r1 are the row and column of the current finger position before entering each character, and c2 and r2 are the row and column of the character to be entered. ($$\sqrt((c_{1} - c_{2})^2 + (r_{1} - r_{2})^2)$$)

$$f_{2}$$ is the number of characters at which typing occurs.
