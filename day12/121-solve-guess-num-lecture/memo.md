## **Split whole app works**

![Alt split whole app to multiple works](pic/01.jpg)

## **Get random number & Guess**

![Alt get a random number & let player guess](pic/02.jpg)

![Alt function to check user's guess against actual answer](pic/03.jpg)

- You can see that codes are interspersed with comments, occasionally adjusting the position of comments or even adding new ones.
  - So the first division of labor is not a fixed rule, just so we have an overview, can be changed at any time.

## **Glogbal variable & Set difficulty**

![Alt global vars and make function to set difficulty](pic/04.jpg)

- Some values are better replaced with global variables, even if they are used only once, to help increase the readability of codes is good enough.

## **Initial turns**

![Alt set turns in set_difficulty()](pic/05.jpg)

![Alt use return instead of global](pic/06.jpg)

## **Middle test**

![Alt middle test](pic/07.jpg)

![Alt swap position](pic/08.jpg)

## **While loop to guess and check answer**

![Alt add while loop to guess and check answer](pic/09.jpg)

## **Why to wrap codes as a function**

![Alt wrap with function game()](pic/10.jpg)

## **Reduce turns**

![Alt turns using global to reduce](pic/11.jpg)

- The above image shows a very bad example, because changing global variables inside a function can be dangerous even if it works.

![Alt change to parameter and return](pic/12.jpg)

- Use the pass into parameter of function and return from function, so that the function is not involved in the global.

### _Use docstings for return of function_

![Alt not obvious about return of it](pic/13.jpg)

![Alt add docstring to check_answer()](pic/14.jpg)

![Alt easily use return of it to refresh turns](pic/15.jpg)

## **Final test**

![Alt middle test, non-stop when turn < 0](pic/16.jpg)

![Alt add codes to stop game() by return](pic/17.jpg)

## **Final conclusion by me**

- The lecturer divides the work into items directly using comments, but without a flowchart.
  - I think a more accurate way is to make a flow chart first, and then draw the different blocks from the chart. But still need to test by myself.
- In addition to return, there is also the addition of parameter to completely isolate the function itself from the outside variables.
  - However, this will make it difficult to use the function, but the lecturer also proposed a solution - adding docstrings.
- Use global variables to increase readability.
- Using function wrapping is reducing the global variable, this angle I hadn't thought of before.
