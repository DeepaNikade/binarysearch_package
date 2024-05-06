# Binary Search
Binary Search is a simple npm package that provides an efficient implementation of the Binary Search algorithm in JavaScript. Binary Search is used to quickly locate a target value within a sorted array.

## Installation

You can install Binary Search via npm:

```bash
npm install binary_search_package
```

## Usage
To use Binary Search in your JavaScript code, you can require it like this:
```
const binarySearch = require('binary-search');

const arr = [1, 3, 5, 7, 9];
const target = 5;

const index = binarySearch(arr, target);

if (index !== -1) {
    console.log(`Found ${target} at index ${index}`);
} else {
    console.log(`${target} not found`);
}

```

## Contributing
Contributions are welcome! If you find a bug, have a feature request, or want to contribute improvements or new features, please open an issue or submit a pull request.