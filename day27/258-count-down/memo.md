## **Countdown mechanism: simplest of idea**

### _simplest idea_

![Alt simply think of countdown mechanism](pic/01.jpg)

- This type of GUI program, which constantly checks for events, is called Event-driven.

### _method provide by Tkingter to include custom function_

![Alt method provide by tkinter to include our func](pic/02.jpg)

![Alt practice it with simple func](pic/03.jpg)

- Note that Unlimited positional arguments are not allowed to be written after keywords arguments, so the preceding arguments must be passed in as positional arguemtns.

![Alt practice it with simple func 2](pic/04.jpg)

- The above example is a good example of why it is important to use Unlimited positional arguments, because then the function we define can have any number of parameters.

### _Upgrade .after() to loop_

> .after() just calls our function after a certain amount of time, it's not a loop itself, so we need to do some more tricks to make the whole process a loop.

![Alt upgrade .after() to loop (by recursion inside custom func)](pic/05.jpg)

## **Set options of Canvas item**

![Alt specific method for setting canvas item's option](pic/06.jpg)

![Alt make new method of Pmodoro to set text with it](pic/07.jpg)

![Alt test it and how to bind coundown to button?](pic/08.jpg)

## **Bind countdown mechanism to Start button**

### _Move all countdown mechanism funcs into class Pomodoro_

![Alt move all countdown mechanism to class Pomodoro](pic/09.jpg)

- Since the Start button is one of the attributes in class Pomodoro, it's much easier to bind a method in the same class than to bind an external function, so I decided to move all the functions of the countdown mechanism to class Pomodoro.

### _Bind func to Start button_

![Alt bind them to button](pic/10.jpg)

- Because the method to be bound is already in the same class, so it's very simple.

## **Format countdown text**

![Alt minutes instead of seconds](pic/11.jpg)

![Alt format count time](pic/12.jpg)

![Alt test it and still wierd...](pic/13.jpg)
