## **Caesar Cipher statge 3: Refactor**

![Alt state 3: refactor encrypt() and decrypt() into single func caesar()](pic/01.jpg)

## **My solution**

![Alt my solution](pic/02.jpg)

- If there are too many duplicate parts in different codes blocks, you can consider combining them into one function, and use if-condition to separate the different parts.

## **Further refactor codes blocks of true/false conditions**

> If you feel that there is a lot of duplication between different codes blocks in the if-statement, and most of them are just in different sign directions, you can simplify it by adding a multiplier as follows.

![Alt true/false condition's codes block only differ from +/- sign](pic/03.jpg)

![Alt further refactor true/false condition's codes block with a multiplier variable](pic/04.jpg)
