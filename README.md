# Lab Notes

- Login to your npmjs.com profile
- The names of Github Repository, Local Folder and name and main fields in the package.json should be same
- Also, the github url should be copied from the code section of the repository!!!
- No upper case letters should be used!!!!
- Upload the module file and package.json in the github repository
- Open the folder in cmd and the enter the following commands
  *     npm pack
- Upload the zip file added from the local folder in the github repository
  *     npm adduser
- Finish the Authentication
  *     npm publish
- Verify if your package is published in your npm profile.

* Published Package - https://www.npmjs.com/package/calculator_5j5

* To test the published package :
*     npm i calculator_5j5
* Write the following `index.js` file
```
var calculator = require('calculator_5j5');
    
var x = 50, y = 10;
    
console.log("Addition of 50 and 10 is "
                + calculator.add(x, y));
    
console.log("Subtraction of 50 and 10 is "
                + calculator.sub(x, y));
    
console.log("Multiplication of 50 and 10 is "
                + calculator.mult(x, y));
    
console.log("Division of 50 and 10 is "
                + calculator.div(x, y));
```
* Run the file using the following command
*     node index.js
