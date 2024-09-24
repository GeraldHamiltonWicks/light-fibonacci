<h1 tabindex="-1" class="heading-element" dir="auto" id="docs-title">
Light Fibonacci
</h1>

Light Fibonacci is a simple JavaScript utility for calculating Fibonacci numbers. This package provides a straightforward function that can be easily integrated into your projects.

## Index

1. [Installation](#installation)
2. [Usage](#usage)
   - [Function Signature](#function-signature)
   - [Parameters](#parameters)
   - [Returns](#returns)
   - [Example](#example)
3. [Error Handling](#error-handling)
4. [License](#license)


## Installation

You can install the package via npm:

```bash
npm install light-fibonacci
```

## Usage

To use the `fibonacci` function, import it into your JavaScript file:

```javascript
import { fibonacci } from "light-fibonacci";
```

### Function Signature

```javascript
fibonacci(n)
```

### Parameters

- `n` (number): The position in the Fibonacci sequence you want to calculate (must be greater than 0).

### Returns

- The Fibonacci number at the given position `n`.

### Example

Here’s how to use the `fibonacci` function:

```javascript
console.log(fibonacci(1)); // Output: 0
console.log(fibonacci(2)); // Output: 1
console.log(fibonacci(3)); // Output: 1
console.log(fibonacci(4)); // Output: 2
console.log(fibonacci(5)); // Output: 3
console.log(fibonacci(6)); // Output: 5
console.log(fibonacci(7)); // Output: 8
```

### Error Handling

If the input is less than or equal to 0, the function will throw an error:

```javascript
try {
    console.log(fibonacci(0)); // Throws an error
} catch (e) {
    console.error(e.message); // Output: "0 should be bigger than 0."
}
```

## License

This package is licensed under the MIT License.