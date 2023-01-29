## **Description the problem**

> Continuing the results of the previous lecture, we found some issues that must be solved.

![Alt desc the problem](pic/01.jpg)

## **Try to fix it & Strange feature of Python type**

### _Try to fix the problem_

![Alt 1st try & find the strange feature of Python type](pic/02.jpg)

### _Console prove: Strong type of Python_

![Alt prove strong type of Python in console](pic/03.jpg)

### _Console prove" Dynamic type of Python_

![Alt prove dynamic type of Python in console](pic/04.jpg)

## **Still not perfect about the solution...**

> Although the above approach seems to work at first glance, after getting the app running for a while, problems are found again.

### _Description of the lackiness_

![Alt still not perfect solve the problem...](pic/05.jpg)

### _Fix it with F-String and take advantages of Dynamic type_

![Alt fix it with F-String and dynamic type concept of Python](pic/06.jpg)

- We use F-String to merge strings and convert different types of data into str at the same time, and write very concise codes to achieve our goal.
- The variable that needs to be converted to a type is the same variable as the one that will be assigned, because Python is Dynamic type, which is not possible in C or Java.
