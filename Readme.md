
# to-capital-case [![Build Status](https://travis-ci.org/ianstormtaylor/to-capital-case.svg?branch=master)](https://travis-ci.org/ianstormtaylor/to-capital-case)

Convert a string to a capital case. Part of the series of [case helpers](https://github.com/ianstormtaylor/to-case).


## Installation

```
$ npm install to-capital-case
```


## Example

```js
var toCapitalCase = require('to-capital-case')

toCapitalCase('camelCase')        // "Camel Case"
toCapitalCase('space case')       // "Space Case"
toCapitalCase('snake_case')       // "Snake Case"
toCapitalCase('dot.case')         // "Dot Case"
toCapitalCase('some*weird[case')  // "Some Weird Case"
```


## API

### toCapitalCase(string)
  
Returns the `string` converted to capital case.


## License

The MIT License (MIT)

Copyright &copy; 2016, Ian Storm Taylor

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
