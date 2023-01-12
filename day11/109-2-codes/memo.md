## **Codes compare with flowchart**

![Alt codes compare to flowchart 1 (DRY func)](pic/07.jpg)

- In the later tests, it was found that the previous arg in the function can be used by the later arg.
- But the actual problem that occurs here is the problem of passing function "value" to function parameter, which will be discussed in the second half.

![Alt codes compare to flowchart 2 (recursion)](pic/08.jpg)

## **Thonny check**

> By using the Thonny app to test and observe variables step by step, I found several errors that I were not aware of, which shows the importance of using the Thonny test.

### _Indent mistake_

![Alt I thought its indent mistake... (Thonny)](pic/01.jpg)

- In fact, the logic here is completely wrong, until the final back to flowchart to solve the whole logic problem.

### _Lack of sum() after drawing_

![Alt fix indent mistake and forgot sum again after drawing (Thonny)](pic/02.jpg)

![Alt fix sum again (Thonny)](pic/03.jpg)

### _Multiple-if in the same while loop_

![Alt set while condition as a variable, because multiple if in same while (Thonny)](pic/04.jpg)

### _Pass function "value" into function_

![Alt if I just written compare operation in parameter, it is just simple value, never calc again (Thonny)](pic/05.jpg)

- I write operation directly in the parameter place, which is the same as assigning a fixed boolean to the parameter.

![Alt create two func for passing into parameters of dead_or_A func (Thonny)](pic/06.jpg)

- The contents of these two fucntions can actually return condition directly, without the need for if-statement.

![Alt adjust dead_or_A func define (Thonny)](pic/09.jpg)

![Alt call dead_or_A func and pass cond_ func "value" into it (Thonny)](pic/10.jpg)

## **Back to flowchart level to solve the logic problem**

![Alt stuck in the while loop (Thonny)](pic/11.jpg)

![Alt stick with flowchart to solve the stuck problem, don't lost in the codes (Thonny)](pic/12.jpg)

- Many of the previous mistakes are incidental disasters caused by poor logic, only by returning to flowchart can the problem be truly solved, do not get lost in codes to solve the problem.
