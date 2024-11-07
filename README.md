# FINDING-BEST-CHEON-JI-IN-KEYBOARD-LAYOUT

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc6f4d0f-db05-48d7-8215-3e0467d3ea35">
</p>
Considering the number of types and the distance the fingers move, we found the optimal layout of the Cheonjiin keyboard.
The fitness function is: $$\sum (f_{1} + f_{2})$$

$$f_{1}$$ is the movement distance of the finger. The distance traveled is c1 and r1 are the row and column of the current finger position before entering each character, and c2 and r2 are the row and column of the character to be entered. ( $$\sqrt((c_{1} - c_{2})^2 + (r_{1} - r_{2})^2)$$ )

$$f_{2}$$ is the number of characters at which typing occurs.

While the fitness function value (finger movement distance + number of typing) of the existing Cheonjiin keyboard was 138,007, the suitability function value of the newly created Cheonjiin keyboard using a genetic algorithm was 125,713, showing a performance improvement of about 10%.

![image](https://github.com/user-attachments/assets/5f98b712-a0b0-4ab7-bddd-22638a2e9a96)
