## Installation

You can install this package via npm:

```
npm install 12to24-cvt
```

## Usage

```
const convert12To24 = require('12to24-cvt');

// Example 1: Convert time from 12-hour format to 24-hour format
const time12_1 = '4:30 PM';
const time24_1 = convert12To24(time12_1);
console.log(`Time in 24-hour format: ${time24_1}`);

// Example 2: Convert another time
const time12_2 = '9:45 AM';
const time24_2 = convert12To24(time12_2);
console.log(`Time in 24-hour format: ${time24_2}`);
```
