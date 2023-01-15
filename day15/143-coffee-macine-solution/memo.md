## **Flowchart**

### _init chart_

![Alt flowchart (init)](pic/01.jpg)

### _functionize chart_

![Alt main chart](pic/02.jpg)

![Alt coffee chart](pic/03.jpg)

![Alt transfer some block to choose](pic/04.jpg)

![Alt choose chart](pic/05.jpg)

![Alt transfer some block to resource_check](pic/06.jpg)

![Alt resource_check](pic/07.jpg)

![Alt transfer some block to coin_operator and finish rest](pic/08.jpg)

![Alt coin_operator ](pic/09.jpg)

## **Coding**

![Alt codes top level](pic/10.jpg)

![Alt codes coffee](pic/11.jpg)

![Alt codes choose, directly pass value to coffee, instead of import data](pic/12.jpg)

![Alt codes resourse_check](pic/13.jpg)

![Alt codes coin_operator, don't call through nested](pic/14.jpg)

## **Compare to lector's**

![Alt lector: use while loop to all game](pic/15.jpg)

![Alt lector: off](pic/16.jpg)

![Alt lector: return boolean is better](pic/17.jpg)

![Alt lector: parameter is acutally value](pic/18.jpg)

## **Debugging**

![Alt debug: ask question twice - nested call](pic/19.jpg)

![Alt debug: convert choose out of function](pic/20.jpg)

## **Optimize**

### _ask flavour_

![Alt optimize: ask flavour](pic/21.jpg)

### _charge_

![Alt optimize: charge](pic/22.jpg)

## **Conclusion**

- After the associated data has the correct data structure, the function often does not need to return any values, often return boolean is sufficient and can be directly as a condition.

- In addition to the return of the function, the parameter of the function should be set directly to the value that is really needed internally, because when we call the function, it is an assign operation, which can omit a lot of instructions for assignment.

- Try to use loops and avoid recursion, the latter is really prone to bugs.
  - This also means that sometimes it's better not to wrap codes in functions, but it's hard to know whether to wrap them in functions or not.
