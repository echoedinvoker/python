## **Design of new class: QuizBrain**

### _TODOs_

![Alt TODOs of quiz_brain](pic/01.jpg)

### _Attributes and method_

![Alt class QuizBrain design](pic/02.jpg)

- questions_list is indeed just to store list of objects.
- Later I found out that in fact the only demand of lector for method is to print the correct string using input.

### _Goal_

![Alt what we want to do this lecture](pic/03.jpg)

## **Challenge 1: constructor of QuizBrain**

![Alt challenge __init__ of QuizBrain](pic/04.jpg)

### _My solution_

![Alt solution](pic/05.jpg)

- The attribute "question_list" is only used to store the question_bank, i.e. the list of objects for questions.

## **Challenge 2: method of QuizBrain**

![Alt challenge method of QuizBrain](pic/06.jpg)

### _My solution_

![Alt solution](pic/07.jpg)

![Alt import to main.py and test it](pic/08.jpg)

- My approach is not only to use input to print out the questions, but also to compare the answers and return the boolean, so that it will be easy to do other features later.

### _Compare to lector's_

![Alt compare to lector's](pic/09.jpg)

- The lector really only does the method to print out the correct question using the input and that's it.
  - Maybe it's to keep the functionality of a single method focused on one simple thing?
