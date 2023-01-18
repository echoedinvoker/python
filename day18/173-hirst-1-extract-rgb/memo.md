## **PyPi: cologram**

> lector suggests using cologram to complete this lecture's challenge.

![Alt pypi colorgram](pic/01.jpg)

## **Challenge: Extract RGB tuples from hirst painting image**

![Alt challenge](pic/02.jpg)

- As shown above, our goal in this lecture is to obtain a list of RGB tuples.

## **Get JPG file & Prepare project env**

![Alt search hirst painting image](pic/03.jpg)

- Pick a favorite image to download, make sure it's a .jpg file.

![Alt prepare jpg file and colorgram module in project](pic/04.jpg)

## **My solution**

### _Check officail documents_

![Alt check official documents](pic/05.jpg)

### _Coding_

![Alt 1st try](pic/06.jpg)

![Alt 2nd try](pic/07.jpg)

- Because .rgb appears to be a single color attribute, you must use for-loop, I personally like to continue to wrap it as a function as above.
- Rgb(r=254, g=253, b=252) This format doesn't really match the RGB tuple format we need.

## **Lector's way**

### _further transfer to exact RGB tuples_

> As mentioned above, the RGB element format does not meet the requirements, so further conversions must be done.

![Alt lector: furthur transfer to pure RGB tuple](pic/08.jpg)

### _Test with w3cschool RGB calculator_

> It is best to use the RGB calculator on w3cshool to test each color, some may be background or noise.

![Alt lector: test with w3cshool RGB calculator](pic/09.jpg)

### _Get final list of RGB tuples_

![Alt lector: get final list of RGB tuples](pic/10.jpg)
