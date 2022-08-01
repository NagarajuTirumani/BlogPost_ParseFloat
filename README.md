# ParseFloat

The **ParseFloat()** function converts the string of numbers into numbers without losing its precision.

###### Input:	
```
let value = "100.56"
let result = parseFloat(value)
console.log(result)
```

###### Output:

 ```
 100.56
 ```
 
It also has another functionality i.e, if the string contains non-numerical values after the numbers, it parses the number and it will convert those numbers. Ignores the invalid characters.

###### Input: 

```
let value = "96.496abcd"
let result = parseFloat(value)
console.log(result)
```
  
###### Output:
  
```
96.496
``` 
But in the case of value started with alphabetical or any ther special characters, it returns **NaN**.

###### Input:
```
let value = "abcd12.569"
let result = parseFloat(value)
console.log(result)
```
###### Output:
```
NaN
```

Let's see some more examples about ParseFloat.
###### Example-1:
```
let value = '    965.96   '
let result = parseFloat(value)
console.log(result)
```  
###### Output:

```
965.96
```
###### Example-2:
```
let value = '917e-2'
let result = parseFloat(value)
console.log(result)
```
  
###### OutPut:
```
9.17 
```
 	
For Read more about ParseFloat click [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat#interaction_with_bigint_values)
 	
Watch tutorial [here](https://youtu.be/OXpTBQtL4nY)
 	
