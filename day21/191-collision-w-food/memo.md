## **Challenge: Create Food obj by inherit Turtle class**

### _instruction_

![Alt challenge: create Food object by inheriting Turtle class](pic/01.jpg)

### _My solution_

![Alt my solution](pic/02.jpg)

### _Compare to lector's_

![Alt compare to lectors](pic/03.jpg)

- There is an obvious error in my coordinates section.
- lector puts the codes for creating the Food object and the Snake object together, which is more readable and doesn't change the result much, because our snake starts moving as soon as the game starts.

## **Challenge 2: Collistion with the food**

> Here collistion means that when the snake head in the screen touches the food, the food disappears and appears in another random position.

### _hint: documents - turtle.distance_

![Alt challenge: collision - doc turtle.distance](pic/04.jpg)

### _My solution_

![Alt my solution](pic/05.jpg)

### _Problem: food not on middle of road_

![Alt problem: food not on middle of road](pic/06.jpg)

- Because snake movement relies on .forward(20), the coordinates of segments will be discrete rather than continuous, and this will result in food not appearing in the middle of the snake's path.

![Alt solve it by make coordination list with interval 20](pic/07.jpg)

- The problem can be solved by listing the coordinates of each of the snake segments, and then taking a random sample from these as the possible locations of the food.
