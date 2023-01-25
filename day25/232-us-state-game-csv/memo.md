## **Let user actively exit the app**

![Alt Exit](pic/01.jpg)

- "break" means exit the loop.

## **Challenge: export new csv file when exit**

![Alt Challenge](pic/02.jpg)

## **My solution**

### _GuessManager_

![Alt modify GuessManager](pic/03.jpg)

- In fact there is no need to save the object for this challenge.
  - so "self.guessed_states_obj" is useless, can be removed.

### _main.py_

![Alt use it in main.py](pic/04.jpg)

### _CSV file_

![Alt result csv file](pic/05.jpg)

## **Further Optimize**

![Alt](pic/06.jpg)

- Let the GuessManager only concentrate on the logic of handling guesses.

![Alt](pic/07.jpg)
