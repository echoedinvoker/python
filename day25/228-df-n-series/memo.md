## **Types of Datas in Pandas**

> All the features of Pandas revolve around its two data structures - DataFrame and Series.

### _DataFrame object_

![Alt DataFrame object](pic/01.jpg)

### _Series object_

![Alt Sereis object](pic/02.jpg)

### _Documents_

![Alt docs Pandas data structures](pic/03.jpg)

![Alt docs API reference data structure](pic/04.jpg)

- DataFrame and Series are the most important of all topics.

## **Dive into documents of DataFrame**

![Alt docs DataFrame](pic/05.jpg)

![Alt docs DataFrame.to_dict()](pic/06.jpg)

- The Pandas documentation explains each method even more clearly and comprehensively than the Python documentation.

### _Practice_

![Alt practice DataFrame.to_dict()](pic/07.jpg)

## **Dive into documents of Series**

![Alt docs Series](pic/08.jpg)

![Alt docs Series.to_list()](pic/09.jpg)

### _Practice_

![Alt practice Series.to_list()](pic/10.jpg)

- Until we are familiar with Pandas, we may be tempted to convert a series into a list, but then we find that Pandas itself provides much more powerful methods.

## **Challenge: calc the average temperature**

### _instruction_

![Alt Challenge: calc the avg temp](pic/11.jpg)

### _My solution_

![Alt my sol by list method](pic/12.jpg)

### _Compare to lector's_

> lector chooses to check the Pandas documents directly to see if there is a suitable method that can be used.

![Alt docs Series.mean()](pic/13.jpg)

![Alt sol by Series method](pic/14.jpg)

## **Challenge: Get maximum of temperature directly by Pandas method**

### _instruction_

![Alt Challenge: get max of temp by Pandas method](pic/15.jpg)

### _diving documents_

![Alt docs Series.max()](pic/16.jpg)

### _Codes_

![Alt sol by Series.max()](pic/17.jpg)

## **Get specific data**

### _values of specific column_

![Alt get values of column](pic/18.jpg)

- result is Series object.
  - And each Series object is stored in the attribute of the DataFrame corresponding to the header name.

### _values of specific row_

![Alt get specific row data](pic/19.jpg)

![Alt sol](pic/20.jpg)

- result is still DataFrame object.

## **Challenge: print a row of data had the highest temperature**

### _instruction_

![Alt Challenge: print row of data had the highest temp](pic/21.jpg)

### _My solution_

![Alt my sol](pic/22.jpg)

### _Compare to lector's_

![Alt compare to lector's](pic/23.jpg)

![Alt what type of row of data](pic/24.jpg)

![Alt attr of row of data](pic/25.jpg)

- Be very clear about what type of data you are getting in each of the above processes.

## **Challenge: Convert Monday's temperature to fahrenheit**

### _instruction_

![Alt Challenge: convert monday's temp to fahrenheit](pic/26.jpg)

### _My solution_

![Alt my sol (note type of attr of row data)](pic/27.jpg)

### _Compare to lector's_

![Alt compare to lector's (another way to convert type)](pic/28.jpg)

## **Create DataFrame object from scratch**

![Alt create DataFrame object from scratch](pic/29.jpg)

- Converting a dict to a DataFrame is a simple, but it is important to note the format of the dict.

## **Export CSV file from DataFrame object**

![Alt export csv from DataFrame object](pic/30.jpg)
