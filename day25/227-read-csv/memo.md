## **Use build-in functions to retrieve data from CSV**

![Alt challenge: by .readlines() to extract data from csv](pic/01.jpg)

![Alt my solution](pic/02.jpg)

- The comma is also considered part of the string, so the data in different columns are not separated and need more processing.

## **Use build-in library 'csv' to retrieve data from CSV**

![Alt csv library: got literator](pic/03.jpg)

![Alt iterate data but error](pic/04.jpg)

![Alt fix it and got data](pic/05.jpg)

- The code used is much less than the previous one, and the data for the different columns are separate, but the headers are the same as the general rows.

### _Challenge: Get all temperatures_

![Alt challenge: got all temperatures](pic/06.jpg)

![Alt my solution](pic/07.jpg)

- Because headers are no different from normal rows, it is necessary to write more code to handle headers as above.

## **Use 3rd-party library 'pandas' to retrieve data from CSV**

### _Introduce PANDAS_

![Alt image of pandas](pic/08.jpg)

![Alt pandas homepage](pic/10.jpg)

![Alt pandas documents](pic/11.jpg)

### _Use PANDAS_

![Alt install pandas](pic/12.jpg)

![Alt get table data by pandas](pic/13.jpg)

- pandas automatically distinguishes headers from normal rows, and sets an index for each rows.

![Alt get single column data by pandas](pic/14.jpg)

- In pandas, we can use the header name to retrieve data directly from a column.
