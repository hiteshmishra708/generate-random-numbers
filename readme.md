# Generate Random Numbers

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