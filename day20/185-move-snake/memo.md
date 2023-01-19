## **Challenge 1: Moving the snake**

### _Instruction_

![Alt challenge: move the snake](pic/01.jpg)

### _Fist try: simply .forward() each segment_

![Alt first try](pic/02.jpg)

### _Query documents about turtle animation_

![Alt query doc about animation](pic/03.jpg)

![Alt tracer and update](pic/04.jpg)

![Alt try to use them in my codes](pic/05.jpg)

### _Second try: including animation skill_

![Alt second try](pic/06.jpg)

- Previously, .forward() had an effect similar to sleep() because the animation itself took time, but now that it is turned off, sleep() must be added.

## **Challenge 2: Moving with turning**

### _Instruction_

![Alt challenge: turn direction](pic/07.jpg)

### _First try: simply turn left 90 degree of 1st segment_

![Alt try turn 1st segment](pic/08.jpg)

- Obviously it is not working to just let the first segment change direction. But hard to image another solution...

### _Change the logic of moving_

> So the logic of moving forward may have to be replaced with a different approach.

![Alt change the logic of moving](pic/09.jpg)

![Alt test it](pic/10.jpg)

- After changing the forward logic, it is easy to change direction, just control the first segment and the following ones will follow naturally.
