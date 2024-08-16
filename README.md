# null_or_empty

[![Node CI](https://github.com/Bis10/CI-CD_Test_nodejs/actions/workflows/whatever.yml/badge.svg)](https://github.com/Bis10/CI-CD_Test_nodejs/actions/workflows/whatever.yml)

A simple Node.js package that checks,if a given string is null or empty.

## Usage

First, install package using npm:

    npm install @Bis10/CI-CD_Test_nodejs --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@Bis10/CI-CD_Test_nodejs');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
