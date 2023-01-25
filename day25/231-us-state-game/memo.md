## **Our final goal**

![Alt goal](pic/01.jpg)

## **Start the challenge**

### _compare if answer in csv data_

![Alt check if answer in data](pic/02.jpg)

![Alt guess_manager.py](pic/03.jpg)

![Alt result is weird](pic/04.jpg)

![Alt extract string from DataFrame object](pic/05.jpg)

- Compared to getting an integer from a Series object, getting a string seems to be much more difficult.

![Alt result](pic/06.jpg)

### _build input window class_

> Because of the complexity of the prompt window, it is recommended to make it a separate class.

![Alt input window class](pic/07.jpg)

![Alt result](pic/08.jpg)

### _while loop_

![Alt while loop](pic/09.jpg)

### _further optimize: compare logic should be included by GuessManager_

![Alt further optimize: compare logic should be inside GuessManager](pic/10.jpg)

- In fact I think class GuessedStates should also be separated into a separate file, perhaps called names_drawer or something like that, so that the GuessManager can concentrate on the logic.

## **Compare to lector's**

### _String.title()_

![Alt compare to lector: .title()](pic/11.jpg)

### _Series.to_list() and operator 'in'_

![Alt compare to lector: Series.to_list() and 'in'](pic/12.jpg)

### _Series.item()_

![Alt compare to lector: Series.item()](pic/13.jpg)

### _While condition (Not infinit loop...)_

![Alt compare to lector: while condition](pic/14.jpg)
