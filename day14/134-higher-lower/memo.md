## **Game Walkthrough**

![Alt play game 1](pic/01.jpg)

![Alt play game 2](pic/02.jpg)

- The blue part does not appear for the first time (before any guesses).

![Alt play game 3](pic/03.jpg)

- After each user input, the entire screen will be deleted and rendered again.

## **Files**

### _art.py_

![Alt provided file 1: art](pic/04.jpg)

- lector already provides the required ASCII art.

### _game_data.py_

![Alt provided file 2: data](pic/05.jpg)

- lector provides the required data, which we use to make the game.

### _main.py_

![Alt main.py](pic/06.jpg)

- empty, we must write the logic of the game itself from scratch.

## **Flowchart**

### _Initial_

![Alt flowchart(initial)](pic/07.jpg)

### _Functionalized_

![Alt flowchart(functionalized)](pic/08.jpg)

- It is important to clarify the input/output of each funtion.
- This can be constructed from top to bottom using abstraction, but note that the output/input of each function must be absolutely strictly defined.

## **Coding**

> Remember, try to avoid using global variables, unless they are constants

### _game_

![Alt game()](pic/09.jpg)

### _pick2_

![Alt pick2()](pic/10.jpg)

- random.sample is a useful command from stack overflow, lector works by using random.choice plus while to get two different items from the list.
- Here we use zip() to combine the two iteraters and then make a loop.
- random.sample

### _intro_

![Alt add intro() to game()](pic/11.jpg)

![Alt intro()](pic/12.jpg)

### _guess_

![Alt guess()](pic/13.jpg)

### _finish_

![Alt finish](pic/14.jpg)

- It feels like just completing each simple little function step by step, and the whole app is naturally finished.

## **Compare to lector's**

- lector and my coding method are poles apart, she is using comments to describe the method of scattering the work into small pieces and then coding directly at the top level, not like I first draw flowchart and directly plan the function and its input/output on the diagram. But still some points I learn from:
  - Do not print in the function, use return to export the data you need to print to the outside before you print.
    - `print(render())`
  - I forgot lower() the user inputs "A", "B".
