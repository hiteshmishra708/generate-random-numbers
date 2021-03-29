# Generate Random Numbers

## Usages
```
const randomNumber = require('generate-random-numbers')
console.log(randomNumber(1000))    // random integer between 0 and 1000
console.log(randomNumber(500, 100)) // random integer between 100 and 500
```

## Create a test directory
```
mkdir test-random-number 
```
  
### Change into the directory
```
cd test-random-number
```

#### Install the package
```
npm install generate-random-numbers --save
```

#### Create a test file
```
nano test.js or vi test.js
```

Copy this simple test code and paste it in the test.js file.

```
const randomNumberGenerator = require('generate-random-numbers');

console.log(randomNumberGenerator(5, 10));
```