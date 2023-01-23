## **RESET of scoreboard**

![Alt replace game_over with reset (scoreboard)](pic/01.jpg)

## **RESET of snake**

### _First try_

![Alt reset snake](pic/02.jpg)

### _Wierd result_

> Several important concepts were encountered here...

![Alt wierd result](pic/03.jpg)

![Alt reason of problem](pic/04.jpg)

- A variable name in Python exists as a tag, it does not represent a specific block of memory.
- A tag cannot hold another tag, so when we assign an object in a list to a variable, it is like adding another tag to the object.
  - This is why our list has been cleared, the variable still points to the original object.
- No values or objects in Python can be cleared manually, but are automatically erased by Python when they don't have any tags on them.

## **PAUSE Game**

![Alt pause game](pic/05.jpg)

## **HIGH SCORE can't presist after closing app**

### _close and reopen app_

![Alt close app](pic/06.jpg)

![Alt restart app](pic/07.jpg)

### _Use doc to record?_

> Shall we open another word app to record the highest score?

![Alt use outside document to record](pic/08.jpg)

- Python does the same thing, only it can be written as a script to do it more automatically.
