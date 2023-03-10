## **Re-arrange the previous Script**

![Alt regroup script for better scene](pic/01.jpg)

- It just makes the structure of the script clearer, so that the following explanation is easier to follow.
- The next three arrangements of Tkinter widgets are described.

## **.pack()**

![Alt .pack()](pic/02.jpg)

![Alt side=](pic/03.jpg)

- The disadvantage of pack() is that it is difficult to define the exact position.

## **.place()**

![Alt .place()](pic/04.jpg)

![Alt x=100, y=300](pic/05.jpg)

- The disadvantage of place() is that it can be very difficult to use when there are too many widgets.

### _mix use with pack()_

![Alt mix .pack() with .place()](pic/06.jpg)

## **.grid()**

> This is lector's favourite arrangement way.

### _concept of grid_

![Alt grid concept](pic/07.jpg)

### _.grid() is relative position_

![Alt grid() no work?](pic/08.jpg)

![Alt grid() correct use](pic/09.jpg)

### _grid() cannot mix use with pack()_

![Alt mix grid() and pack()](pic/10.jpg)

## **Challenge: Create New Button & Specific Grid Arrangement**

![Alt challenge: grid with new button](pic/11.jpg)

![Alt solution](pic/12.jpg)

## **Padding**

### _whole window_

![Alt padding for whole window](pic/13.jpg)

### _widget_

![Alt padding for widgets](pic/14.jpg)
