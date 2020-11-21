# Testify
## Simple JavaScript Test Framework

Testify is a feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun. Testify tests run serially, allowing for flexible and accurate reporting, while mapping uncaught exceptions to the correct test cases.

**Simple**, **Flexible**, **Fun**.

## Supportion
- Node >=12

## Installation

Install with npm globally:
```
$   npm install -g testify
```
or as a development dependency for your project:
```
$   npm install --save-dev testify
```

## Getting Started

```
$   npm install testify
$   mkdir test && cd test
```
*Optional*:
```
$   code .
```

In your editor:

```js
const assert = require('assert'); // Make sure you have assert installed
describe('Array', function() {
  describe('#indexOf()', function() {
    it('should return -1 when the value is not present', function() {
      assert.equal([1, 2, 3].indexOf(4), -1);
    });
  });
});
```

Output:

