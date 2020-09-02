# JSX Number Format
This is a lightweight js number formatting library
##To install
 _npm install jsx-number-format_
 
 # Usage
 ```javascript
const {NumberFormat} = require('jsx-number-format');
 let formattedNumber =NumberFormat(5000,2,',');
/*5000 is the amount to format
* 2 decimal places
* , is the thousand delimiter
* result: 5,000.00
*/
let formattedNumber2 =  NumberFormat(5000.789,2,',');
/*
* gives 5,000.79
*/
let formattedNumber3 =  NumberFormat(5000.004,2,',');
/*
* gives 5,000.00
*/
```
