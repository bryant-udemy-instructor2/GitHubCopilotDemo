# Calculator Project

A simple calculator implementation with basic arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division

## Implementation

```javascript
class Calculator {
  add(a, b) {
    return a + b;
  }
  
  subtract(a, b) {
    return a - b;
  }
  
  multiply(a, b) {
    return a * b;
  }
  
  divide(a, b) {
    if (b === 0) {
      throw new Error("Division by zero is not allowed");
    }
    return a / b;
  }
}
